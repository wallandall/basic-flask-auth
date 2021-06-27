# Basic Flask Auth 
In this project we will setup basic Flask authentication using [Auth0](https://auth0.com/docs)

## Getting Started

### Installing Dependencies

#### Python 3.7

Follow instructions to install the latest version of python for your platform in the [python docs](https://docs.python.org/3/using/unix.html#getting-and-installing-the-latest-version-of-python)

#### Virtual Enviornment
From your project directory initialize and activate a virtualenv using:

``` python -m virtualenv venv ```

```source env/bin/activate ```
>**Note** - In Windows, the `env` does not have a `bin` directory. Therefore, you'd use the analogous command shown below:
    ``` source env/Scripts/activate ```

Instructions for setting up a virual enviornment for your platform can be found in the [python docs](https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/)

#### PIP Dependencies

Once you have your virtual environment setup and running, install dependencies by running:

```
pip install -r requirements.txt

```

This will install all of the required packages we selected within the `requirements.txt` file.

##### Key Dependencies

- [Flask](http://flask.pocoo.org/)  is a lightweight backend microservices framework. Flask is required to handle requests and responses.

- [jose](https://python-jose.readthedocs.io/en/latest/) JavaScript Object Signing and Encryption for JWTs. Useful for encoding, decoding, and verifying JWTS.

## Running the server

From within this directory first ensure you are working using your created virtual environment.

Each time you open a new terminal session, run:

```bash
export FLASK_APP=app.py;
```

To run the server, execute:
Run the development server from the backend folder:
   
   ``` export FLASK_APP=flaskr ``` 

   ``` export FLASK_ENV=development ```

   ``` flask run --reload```
   
   >**Note** - for Windows CMD:

    ``` set FLASK_APP=flaskr ``` 

   ``` set FLASK_ENV=development ```
   
   ``` flask run --reload```

    >**Note** - for Windows PowerShell:

    ``` $env:FLASK_APP = "flaskr" ```  

   ``` $env:FLASK_ENV = "development" ```
   
   ``` flask run --reload ```

## Tasks

### Setup Auth0