Simple TODO website created with Flask as a beginner.



To run the website install python in your computer from [here](https://www.python.org/downloads/). 

Then open cmd(command prompt) and type the following commands:
```
pip install Flask
```
Then
```
pip install Flask-SQLAlchemy
```

Now clone this project:
```
git clone https://github.com/Saswata28/simple_todo_with_flask.git
```

Then go to the directory:
```
cd simple_todo_with_flask
```

Then run the todo.py
```
python todo.py
```

then on your brower(any) go to:
```
http://127.0.0.1:8888
```

**If you are running this locally(which is what this project was intended to), then you can run it with the above commands without a problem, but If you want to make it public with a specific domain then remove the `Debugger=True` or make it `Debugger=Flase` in the last line of todo.py. So the last line should be `app.run(port=8888)` or `app.run(debug=Flase, port=8888)`.**

