
Task Description: Deploying and Stress Testing a GPT Model on an API
  

Objective:
The objective of this task is to deploy a heavy GPT (Generative Pre-trained Transformer) model of the size of 3-4 GB on an API, create basic tasks for the GPT as API calls, and then stress test the deployed model by simulating 10 concurrent users making requests to the API.

  

Tasks:

1. Deploy GPT Model on API:
    

	- Set up an API endpoint to receive requests and interact with the GPT model.
	    
	- Deploy the GPT model on the API platform (e.g., AWS Lambda, Azure Functions).
	    
	- Ensure that the API endpoint is secure and accessible.
	    

2. Implement Basic Tasks for GPT:
    

	- Define basic tasks for the GPT model, such as generating text based on prompts, summarizing text, or answering questions.
	    
	- Create API endpoints to handle these tasks (e.g., /generate-text, /summarize-text, /answer-question).
    

4. Stress Test with Concurrent Users:
    

	- Write a script to simulate 10 concurrent users making requests to the API.
	    
	- Each user should send a request to the API with different inputs (prompts, questions, etc.).
	    
	- Ensure that the requests are asynchronous and run concurrently.
	    

6. Monitoring Resource Consumption:
    

	- Monitor RAM consumption during the stress test to ensure it stays within acceptable limits.
	    
	- Implement logging to record the RAM consumption for each request.
    

8. Documentation:
    

	- Document the setup and configuration of the API endpoint and GPT model deployment.
	    
	- Record the details of the stress test, including the number of concurrent users, types of requests, and response times.
	    
	- Document the RAM consumption for each request and overall system performance during the stress test.
	    
	- Summarize the findings and provide recommendations for optimizing resource utilization.


Deliverables

1. Deployed GPT model on API with documentation.
    
2. Brownie points for more concurrent users than 10
    
3. Script for simulating 10 concurrent users.
    
4. Log file containing response times and RAM consumption for each user request.
    
5. Documentation summarizing the stress test results and recommendations for optimization.

Additional Points


	- Ensure that the API endpoint and GPT model are properly secured to prevent unauthorized access.
	    
	- Optimize the code for efficient resource utilization to minimize RAM consumption.
	    
	- Test the API endpoints thoroughly to ensure correct functionality and error handling.
	    
	- Collaborate with team members for assistance and guidance throughout the task.
    

Deadline : 07-05-2024 10:00 pm

  

Once finished with the task upload the code details on github and ping Aditya Goel  on 9950866260 with the Github Repo and output.txt file for further discussion



To complete this task, we'll need to develop several components: the GPT model deployment, the API server, and the stress testing script. Here's a breakdown of the steps and the structure of the project:

1. **Deploy GPT Model on API**:
   - **Set up an API endpoint using a web framework like Flask or FastAPI.**
   - **Load and deploy the GPT model on the API server.**
   - **Create an endpoint to receive requests and interact with the GPT model.**
   - **Deploy the API server on a cloud platform like AWS Lambda, Azure Functions, or a virtual server.**
   - **Configure security settings (e.g., API keys, rate limiting) for the API endpoint.**

2. **Implement Basic Tasks for GPT**:
   - **Define functions for the basic tasks (e.g., `generate_text`, `summarize_text`, `answer_question`).**
   - **Create API endpoints for each task (e.g., `/generate-text`, `/summarize-text`, `/answer-question`).**
   - **Implement the logic to handle incoming requests and pass the data to the GPT model.**
   - **Return the generated output from the GPT model as the API response.**

3. **Stress Test with Concurrent Users**:
   - **Write a script using a library like `requests` or `aiohttp` (for asynchronous requests).**
   - **Define a list of sample inputs (prompts, questions, etc.) for the stress test.**
   - **Implement a function to send a request to the API with a random input from the list.**
   - **Use a library like `asyncio` or `threading` to create and run multiple concurrent tasks.**
   - **Each task should send a request to the API and print or log the response.**
   - **Run the stress test script and observe the performance of the API and the GPT model.**

Here's a high-level structure of the project:

```
project/
│
├── api/
│   ├── __init__.py
│   ├── app.py          # API server code
│   ├── tasks.py        # GPT model tasks (e.g., generate_text, summarize_text)
│   └── model/          # GPT model files
│
├── stress_test/
│   ├── __init__.py
│   └── stress_test.py  # Stress testing script
│
├── requirements.txt    # Project dependencies
├── README.md           # Project documentation
└── ...
```

The `api` folder will contain the code for the API server and the GPT model tasks. The `stress_test` folder will contain the script to simulate concurrent users and stress test the API.

To proceed, you'll need to:

1. **Set up the project structure and install the required dependencies (e.g., web framework, GPT model library, async libraries).**
2. **Implement the API server code and the GPT model tasks.**
3. **Deploy the API server on your chosen cloud platform.**
4. **Write the stress testing script.**
5. **Run the stress test and analyze the results.**

Note: This is a high-level overview of the project structure and the steps involved. Depending on the specific technologies and libraries you choose to use, the implementation details may vary.