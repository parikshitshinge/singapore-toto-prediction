Singapore TOTO Prediction
==============================

Toto (est. in 1968 and stylised as TOTO) is a legalised form of lottery sold in Singapore, known by different names elsewhere. It is held by Singapore Pools, the only legal lottery operator in Singapore.[2] As of April 2015, it was the second most popular type of gambling activity after 4-Digits.[3] Toto can be purchased from any of the Singapore Pools outlets across Singapore. Draws are conducted every Monday and Thursday at 6:30 pm (SG time). In case of the cascade draw, the draw time will change to 9.30 pm.[4] The "live" Toto draw can be viewed at the Singapore Pools Main Branch at 210 Middle Road. The profits from Toto go to the Singapore Totaliser Board (the owner of Singapore Pools) which uses the money for charity and other worthy causes.

In this TOTO Game, an intending Participant has to purchase a set of six (6) numbers selected from 1 to 49 for the Relevant Draw. The correct matching of the set of six (6) numbers selected with any three (3) or more of the winning numbers drawn under the Rules shall qualify the Participant for a Prize or Prizes as provided in these TOTO Game Rules (General).


Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    |
    ├── data
    │   ├── source         <- The source data sets in case the source files are downloaded from source systems.
    │   ├── raw            <- The original, immutable data dump.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── external       <- Data from third party sources.
    |
    ├── logs               <- Logs generated when program is running
    │
    ├── models             <- Trained and serialized models, model predictions, model summaries, or vectorizers
    │
    ├── notebooks          <- Jupyter notebooks. 
    |
    └── src                <- Source code for use in this project.
        ├── __init__.py    <- Makes src a Python module
        ├── app.py         <- Initiator for flask app
        ├── exception.py   <- Custom exception handler
        ├── logger.py      <- Custom logger
        ├── utils.py       <- Set of custom utilities functions
        │
        ├── data           <- Scripts to extract data and transform data
        │   ├── data_ingestion.py
        │   └── data_transformation.py
        │
        ├── pipelines      <- Scripts to train models and then use trained models to make
        │   │                 predictions
        │   ├── train_pipeline.py
        │   └── predict_pipeline.py
        │
        └── templates      <- Web pages to host to take real time inputs and provide predictions
            ├── index.html
            └── home.html
