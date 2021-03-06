# Trump Tweets Analysis
> Statistical and sentiment analysis of Trump tweets from 01/01/2018 to 26/04/2019.

Assignment 2 of the *Data Analytics* course for the MSc in Computer Science at University of Milano-Bicocca.

<!--![](header.png) -->

## Authors

- **Matteo Basso** - [mbasso](https://github.com/mbasso)
- **Nassim Habbash** - [dodicin](https://github.com/dodicin)

# Brief

Donald Trump uses Twitter a lot. *A lot*. The President of the USA is very vocal of his likes and dislikes on the platform, specially when he's talking about politics, making his account a good educational resource for data analytics.

The repository contains the sentiment analysis work we've conducted on his tweets from roughly the last year and a half to see if we could find any interesting facts about them.

## Requirements
* Python 3
* Python virtual environment of your choice
* Jupyter Notebook

Or:
* Google account (Colaboratory)

## Installation

```sh
$ git clone https://github.com/Dodicin/trump-tweet-analysis 
```

## Usage

```sh
$ cd trump-tweet-analysis
#Setup your virtual environment for the project, I'm using virtualenv
$ virtualenv .venv
$ source .venv/bin/activate
#Installing Python kernel in the virtual environment
(.venv) $ pip install ipykernel
(.venv) $ ipython kernel install --user --name=.ven
(.venv) $ jupyter notebook

#When you're finished
(.venv) $ deactivate
```

Or:

* Upload `analysis.ipynb` on Google Drive
* Open it with Colaboratory

## Feedback
* Add community detection (Stylometric analysis, profiling) to analysis
* Might be useful to check timezone distributions differences
* Add more visual markers in the presentations
* Actual sentiment dynamics (sentiment changing in time)

# 
## Acknowledgements

* Word Affect Intensities. Saif M. Mohammad. In Proceedings of the 11th edition of the Language Resources and Evaluation Conference, May 2018, Miyazaki, Japan. (NRC Affect Intensity Lexicon)