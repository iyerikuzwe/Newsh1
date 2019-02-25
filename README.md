# Author
        Iyerikuzwe Regine

# News-Highlights
        This is a Python-Flask application for displaying News Highlights from various News sources using a [News API](https://newsapi.org/).
### Prerequisites
        To use this application, visit the live application link at:
        https://regine7.herokuapp.com/

## User Stories
        These are the behaviours/features that the application implements for use by a user.

        As a user I would like to:
                * See various news sources 
                * Select the ones they prefer
                * See the top news articles from that news source
                * See the image, description and time the news article was created
                * Click on an article and read it fully from the news source

## Specifications
| Behaviour | Input | Output |
| :---------------- | :---------------: | ------------------: |
| Display news sources | On page load | List of various news sources is displayed per category |
| Display articles from a news source | Click a news source | Redirected to a page with a list of articles from the source |
| Display the preview of an article | On page load | Each article displays an image, title, description and publication date |
| Read an entire article | Click an article | Redirected to the news source's site to read the entire article |

## SetUp & Installation Requirements
### Prerequisites
* [![Python 3.6](https://img.shields.io/badge/python-3.6-blue.svg)](https://www.python.org/downloads/release/python-360/)
* [![Pip](https://img.shields.io/badge/pypi-v18.1-blue.svg)](https://pypi.org/project/pip/)
* [![Virtualenv](https://img.shields.io/badge/virtualenv-16.1.0-brightgreen.svg)](https://virtualenv.pypa.io/en/latest/installation/)

### Cloning
*In your terminal:
        
*$ git clone https://github.com/iyerikuzwe/Newsh1

*$ cd Newsh

## Running the Application
* Creating the virtual environment

        $ python3.6 -m venv --without-pip virtual
        $ source virtual/bin/env
        $ curl https://bootstrap.pypa.io/get-pip.py | python 
        
* Installing Flask and other Modules

        $ python3.6 -m pip install Flask
        $ python3.6 -m pip install Flask-Bootstrap
        $ python3.6 -m pip install Flask-Script
        
* Setting up the API Key
        
        To be able to gather article info from the News API you will need an API Key.
        
        * Visit https://newsapi.org/ and register for an API key.
        * In the root directory of the project folder create a file: run.py
        * Insert the following info into it: 
        
                export NEWS_API_KEY='<Your-Api-Key>'
                python3.6 manage.py server
                
        * Insert the API Key you received from News Api where <Your-Api-Key> is.
        
* To run the application, in your terminal:

        $ python3.6 run.py
        
## Testing the Application
* To run the tests for the class files:

        $ python3.6 run.py tests
        
## Technologies
    Flask
    Flask-Bootstrap
    python3.6 
    html
## Contact & Support_lines
        E-mail:iyerikuzweregine19@gmail.com
        phone_number:0789140216
## License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/iyerikuzwe/Newsh1/blob/master/LICENSE)
