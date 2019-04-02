# fastapi_tutorial
This repository aims to try to use FastAPI through its tutorial.

## Setup

```
$ pip install fastapi
$ pip install uvicorn
```

## How to Run

```
$ uvicorn main:app --reload
```

Open browser at http://127.0.0.1:8000/items/5?q=somequery, and see the JSON response as:

```
{"item_id": 5, "q": "somequery"}
```

Go to http://127.0.0.1:8000/docs, and see the automatic interactive API documentation.

