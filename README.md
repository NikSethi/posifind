# posifind
This is an application to look for tweets with a positive sentiment towards the search term. It was built using Python (2.7) and Flask, using [python-twitter](https://python-twitter.readthedocs.org/en/latest/) to interact with the Twitter API and using [the Text-Processing API](http://text-processing.com/) in order to measure sentiment. 

## Running the application
To run the application, you must have Flask installed, which you can do by following [these instructions](http://flask.pocoo.org/docs/0.10/installation/#installation) and then navigating to the directory, running `source venv/bin/activate` and then `python run.py`. The application should appear on http://127.0.0.1:5000/. 

## Todo
* Search needs to be improved - maybe due to the python wrapper for twitter or due to rate limiting by the actual Twitter API, results of searches are extremely limited, and queries invovling any additional information such as language or result type.
