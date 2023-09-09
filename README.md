# REST API Project made in Flask

This project is aimed to serve as a example of a RESTful API done with flask (python)
It also contains a Dockerfile that generates a local container to test the project.

# Install:

1. Clone the repo
2. Check you are using pythong 3.10 or above (python --version)
3. Create a virtual environment (python -m venv ./venv)
4. Install dependencies (pip install -r requirements.txt)
5. Create the docker image (docker build -t rest-api-flask-python .)
6. Run the docker image (docker run -dp 5000:5000 -w /app -v "$(pwd):/app" rest-api-flask-python)

# Test:

1. Open the browser in https://localhost:5000/swagger-ui
2. Test it with any API test tool such as Postman




Enjoy!