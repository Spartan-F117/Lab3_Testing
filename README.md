# ASE Calc Microservice

[![Coverage Status](https://coveralls.io/repos/github/Spartan-F117/Lab3_Testing/badge.svg)](https://coveralls.io/github/Spartan-F117/Lab3_Testing)
[![Build Status](https://app.travis-ci.com/Spartan-F117/Lab3_Testing.svg?branch=main)](https://app.travis-ci.com/Spartan-F117/Lab3_Testing)

### Setup the environment

To setup the environment, you should follow these steps:

1. Open the project in your IDE.
2. From IDE terminal, or normal Ubuntu/MacOS terminal execute the command `virtualenv venv` inside project root.
3. Now, you have to activate it, by executing the command `source venv/bin/activate`.
4. You have to install all requirements, let's do that with `pip install -r requirements.txt`.

**Perfect!** now you can run flask application!

<span style="color:orange">WARNING:</span> each time that you open a new terminal session you have
to execute the step 3.


### Run the application

If you want to run the application, you can use the script `run.sh` by typing `bash run.sh`,
or you can set these environment variables:

```
FLASK_DEBUG=1
FLASK_ENV=development
```
