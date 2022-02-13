# FlaskIntroduction

This repo has been updated to work with `Python v3.8` and up.

### How To Run
1. Install `virtualenv`:
```
$ pip install virtualenv
```

2. Open a terminal in the project root directory and run:
```
$ virtualenv env
```

3. Then run the command:
```
$ .\env\Scripts\activate
```

4. Then install the dependencies:
```
$ (env) pip install -r requirements.txt
```

5. Finally start the web server:
```
$ (env) python app.py
```

This server will start on port 5000 by default. You can change this in `app.py` by changing the following line to this:

```python
if __name__ == "__main__":
    app.run(debug=True, port=<desired port>)
```

# Images 
![Screenshot (39)](https://user-images.githubusercontent.com/77200703/153746696-29aba72b-bc8a-4f2b-8aa4-e93d4e15a0ba.png)
![Screenshot (40)](https://user-images.githubusercontent.com/77200703/153746698-0564b93d-8e81-4dc9-bfe1-3760b16cf093.png)
![Screenshot (41)](https://user-images.githubusercontent.com/77200703/153746702-6db4d2d2-0c7f-41bb-a976-edaedf7a649c.png)


