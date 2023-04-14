# Haikus

Haiku generation using feedforward and recurrent neural networks.
## Setting up the project

installing Python should come with pip3, so in your terminal you can do:

1. `pip3 install venv` <-- (only do if you haven't installed venv already)
2. `virtualenv venv` <-- (only do if the venv folder doesn't exist already)
3. `source venv/bin/activate`
4. `pip3 install -r requirements.txt`

## Running the project

1. `source venv/bin/activate` <-- (if not already done in the current terminal)
2. `jupyter-notebook haikus.ipynb`

## Installing New Dependencies

1. `source venv/bin/activate`
2. `pip3 install NEW_DEPENDENCY`
3. `pip3 freeze > requirements.txt`

Then commit the new requirements.txt which should have added lines for the new package you're installing and any of its dependencies.

## Data Sources

https://kaggle.com/datasets/bfbarry/haiku-dataset

https://www.kaggle.com/datasets/schwartstack/english-phonetic-and-syllable-count-dictionary

https://github.com/docmarionum1/haikurnn/blob/master/input/poems/haikus.csv

