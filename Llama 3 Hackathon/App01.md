1. Run

```conda create -n groq python=3.11 -y```

* _This way we are creating a virtual environment which doesn't distract or disturb other projects

2. Now we are going to activate Groq virtual environment
   
```conda activate groq```

3. We are going to create API using flask (Flask is a python package used to create microservice in our case API)

```pip install groq gradio requests flask```

4. Let's create a file called ```API.py```
