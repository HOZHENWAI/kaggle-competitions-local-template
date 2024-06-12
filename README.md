# A template for kaggle based project

By itself, this template does not do much, it just has a simple requirements.txt preconfigured.
Because, I do not like to store credentials hidden somewhere in my computer, I prefer to use dotenv cli command to setup
the project.

## Usage
- git clone this project
- ``pip install -r ./requirements.txt``
- complete the `.env` file
- ``dotenv run -- kaggle competitions download -p data -c ${competitions-name} ``


Good machine learning!
