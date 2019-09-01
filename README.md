# ml-with-flask
Machine Learning Web App using Flask web framework.

Working on Windows machine

Step 1.1:
Create a Virtual Environment using commands py -3 -m venv venv.
Activate Virtual Environment using venv\Scripts\activate

Step 1.2:
Install Flask using 'pip install flask'

Step 2.1:
Create hello.py file and copy paste below lines of code,

```python
from flask import Flask
app = Flask(__name__)


@app.route('/')
def hello_world():
    return 'Hello, World!'
```

Step 2.2:
Set FLASK_APP environment variable using below command 'set FLASK_APP=hello.py'

Step 2.3:
Running the flask web app using command 'flask run'.