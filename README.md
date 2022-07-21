# Description:

A repository to store the codes that I will write during my studies to learn how to work with Flask.

## Example: Flask Hello World

```python
from flask import Flask

app = Flask(__name__)

@app.route("/")
def hello_world():

    return "Hello World!"

if __name__ == "__main__":

    app.run(debug = True)
```