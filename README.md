# Test

## Teleportation Secrets

This website contains secrets for Teleportation


# **Test for test**

# Fusion

## Introduction

***Concept:*** A Tool to analyze Financial Assets for an Individual or a Business and suggest best practices for financial wellbeing with Fusion Assistant (Built on Google's Gemini)

>[!WARNING]
>This web application contains multiple security vulnerabilities. Read security section.

&nbsp;The is our first Hackathon project as Freshers. Made just to demonstrate the idea of financial analysis tool.

&nbsp;


### Security
As this application is just for a demo purpose in hackathon we didn't intend take any security measures
- Prone to SQL injection.
- No measures were taken to prevent database poisoning.

---

## How to deploy on local server (127.0.0.1:5000)

1. Clone the project
	```
	git clone https://github.com/mvsprabash/fusion.git
	```

2. Activate the envirnoment
    ```
	cd Fusion
	```

    - Linux:<br>
        > venv config already exists in the source directory. Just activate and go directly to step 3 Creating Gemini API key<br>
        
        ```
		source Fusion_env/bin/activate
		```
    - Windows:<br>
        ```
        python -m venv venv
        .\venv\Scripts\activate.bat
        ```


3. Install dependencies
    - Flask
    ```
	pip install flask werkzeug
	```
    - Gemini API
    ```
	pip install google-generativeai
	```
    <br> Create your API following this video on *[YouTube](https://www.youtube.com/watch?v=pTcunloZ-_o)*.
    <br> Export the API KEY to the environment: `export GEMINI_API_KEY=<your-key>`

4. Start the server
    ```
	python app.py
	```
    The Web application will be running at **[Localhost](http://127.0.0.1:5000/)** IP address



