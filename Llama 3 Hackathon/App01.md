1. Run

```conda create -n groq python=3.11 -y```

* _This way we are creating a virtual environment which doesn't distract or disturb other projects

2. Now we are going to activate Groq virtual environment
   
```conda activate groq```

3. We are going to create API using flask (Flask is a python package used to create microservice in our case API)

```pip install groq gradio requests flask```

4. Let's create a file called ```API.py```

5.Inside the file

```from flask import Flask, request, jsonify```

```import json```

6. Now we are initializing the flask application 

```app = Flask(__name__)```

7. next we're going to create a function called get game score

```def get_game_score(team_name):```



![image](https://github.com/zulfiqaralimir/Hackathons/assets/68346772/74722067-8573-4aae-aa80-80aaf2773835)
