## Advancing DeepFake Detection


Based on the documents provided, here is a draft for the updated submission:

Title: Advancing DeepFake Detection for Robust Identity Verification

**Introduction:**
The rapid advancement of deepfake technology, which generates highly realistic synthetic media using deep learning techniques, has raised significant concerns regarding identity theft, fraud, and the spread of disinformation. While deepfakes were initially limited to face swaps and manipulated celebrity content, recent research has shown their ability to bypass face authentication systems with a 96% fool rate. This exponential improvement, combined with the accessibility of open-source deepfake tools, highlights the urgent need for robust detection methods, particularly focusing on forensic identity verification use cases.

**Literature Review:**

Prior research in deepfake detection has primarily focused on analyzing facial cues and artifacts in images and videos. However, recent advancements in generative models can synthesize realistic faces that bypass traditional biometric approaches. Some recent works have explored supplementary modalities like audio, speech patterns, and micro-expressions to improve detection accuracy. 

Face Warping Artifacts used the approach to detect artifacts by com- paring the generated face areas and their surrounding regions with a dedicated Convolutional Neural Network model. In this work there were two-fold of Face Artifacts.

Their method is based on the observations that current deepfake algorithm can only generate images of limited resolutions, which are then needed to be fur- ther transformed to match the faces to be replaced in the source video. Their method has not considered the temporal analysis of the frames.

Detection by Eye Blinking describes a new method for detecting the deep- fakes by the eye blinking as a crucial parameter leading to classification of the videos as deepfake or pristine. The Long-term Recurrent Convolution Network (LRCN) was used for temporal analysis of the cropped frames of eye blinking. As today the deepfake generation algorithms have become so powerful that lack of eye blinking can not be the only clue for detection of the deepfakes. There must be certain other parameters must be considered for the detection of deep- fakes like teeth enchantment, wrinkles on faces, wrong placement of eyebrows etc.

Capsule networks to detect forged images and videos  uses a method that uses a capsule network to detect forged, manipulated images and videos in different scenarios, like replay attack detection and computer-generated video detection.

In their method, they have used random noise in the training phase which is not a good option. Still the model performed beneficial in their dataset but may fail on real time data due to noise in training. Our method is proposed to be trained on noiseless and real time datasets.

Recurrent Neural Network (RNN) for deepfake detection used the ap- proach of using RNN for sequential processing of the frames along with Ima- geNet pre-trained model. Their process used the HOHO  dataset consisting of just 600 videos.

Synthetic Portrait Videos using Biological Signals approach extract bio- logical signals from facial regions on pristine and deepfake portrait video pairs. Applied transformations to compute the spatial coherence and temporal consis- tency, capture the signal characteristics in feature vector and photoplethysmog- raphy (PPG) maps, and further train a probabilistic Support Vector Machine (SVM) and a Convolutional Neural Network (CNN). Then, the average of au- thenticity probabilities is used to classify whether the video is a deepfake or a pristine.

Fake Catcher detects fake content with high accuracy, independent of the generator, content, resolution, and quality of the video. Due to lack of discriminator leading to the loss in their findings to preserve biological signals, formulating a differentiable loss function that follows the proposed signal processing steps is not straight forward process.

Techniques and Algorithms:
1. Forensic Analysis:
   - Compression Artefacts: Analyse video frames for compression artefacts, as deepfake generation may introduce different compression patterns compared to genuine videos.
   - Noise Patterns: Examine noise patterns in the image, as deepfake algorithms may produce unnatural noise that differs from real-world video recording.

2. Temporal Analysis:
   - Frame Consistency: Analyse the temporal consistency of facial features, shadows, and other elements throughout the video, as deepfake videos may exhibit inconsistencies between frames.
   - Lip Sync Analysis: Evaluate lip sync accuracy by comparing lip movements with corresponding audio, as deepfake lip syncing may not perfectly match the spoken content.

Problem Statement:
As deepfake generation becomes increasingly accessible, instances of identity theft and fraud through the usage of deepfakes are likely to rise. Cybercriminals may leverage deepfakes to impersonate individuals and gain unauthorised access to sensitive personal or financial data. Furthermore, deepfakes threaten to undermine public trust and exacerbate the disinformation crisis, with potential societal impacts that necessitate the development of reliable deepfake detection techniques, particularly in the context of identity verification.


Proposed Solution:
We propose a novel multi-modal framework that leverages image, frame, and video cues for detecting deepfake identity theft attempts. Unlike previous works, our method uniquely integrates signed biometric modalities found in forensic systems to enable matching against enrolled identities. The fusion of explicit biometric signals with learned deepfake artefacts provides a robust identity verification approach. We would be using LSTM based artificial neural network.
We would develop a User client based Web application where the user can upload the file and get the confidence score.

Identified parameters include:
	1. Blinking of eyes  
    2. Teeth enchantment  
    3. Bigger distance for eyes  
    4. Moustaches  
    5. Double edges, eyes, ears, nose
    6. Iris segmentation  
    7. Wrinkles on face  
    8. Inconsistent head pose  
    9. Face angle
    10. Skin tone  
    11. Facial Expressions
    12. Lighting  
    13. Different Pose  
    14. Double chins  
    15. Hairstyle  
    16. Higher cheek bones


Baseline Results:

Use Case View:


<Yha pr Images daal dio jo maine bnai h>



Tools for Deep Fake Creation :
	FaceSwap
	Faceit
	Deep Face Lab
	Deepfake Capsule GAN
	Large Resolution face masked



Potential Contributions:
- Development of a novel deepfake detection model integrating advanced neural network architectures.
- Enhancement of detection accuracy by capturing intricate patterns and temporal dependencies in manipulated media content.
- Robustness against evolving deepfake generation techniques, providing a more sustainable solution.
- Empirical validation through extensive experimentation on diverse datasets, demonstrating the practical utility of the proposed method.
- Contribution to the ongoing efforts to mitigate the potential harms associated with manipulated media content by providing infrastructure and deployable defense mechanisms against credential compromise attempts using AI-generated media.

Project Plan:
(Provide a detailed project plan, including tasks, timelines, milestones, and risk management strategies.)

Conclusion:
This research endeavors to address the escalating challenges posed by deepfake technology through the development of an innovative detection method. By introducing a hybrid neural network architecture, our approach aims to push the boundaries of current deepfake detection capabilities, contributing to the ongoing efforts to mitigate the potential harms associated with manipulated media content.

Note: This draft covers the key components of an updated submission, including the problem statement, literature review, proposed solution, evaluation methodology, baseline results, potential contributions, and a project plan. Feel free to expand upon each section with more details and refine the content based on your specific requirements.


**References**

Yuezun Li, Siwei Lyu, “ExposingDF Videos By Detecting Face Warping Arti- facts,” in arXiv:1811.00656v3.  

Yuezun Li, Ming-Ching Chang and Siwei Lyu “Exposing AI Created Fake Videos by Detecting Eye Blinking” in arXiv:1806.02877v2.  

Huy H. Nguyen , Junichi Yamagishi, and Isao Echizen “ Using capsule net- works to detect forged images and videos ” in arXiv:1810.11215.  

D. Güera and E. J. Delp, "Deepfake Video Detection Using Recurrent Neural Networks," 2018 15th IEEE International Conference on Advanced Video and Sig- nal Based Surveillance (AVSS), Auckland, New Zealand, 2018, pp. 1-6.  

I. Laptev, M. Marszalek, C. Schmid, and B. Rozenfeld. Learning realistic hu- man actions from movies. Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition, pages 1–8, June 2008. Anchorage, AK  

Umur Aybars Ciftci, ̇Ilke Demir, Lijun Yin “Detection of Synthetic Portrait Videos using Biological Signals” in arXiv:1901.02212v2