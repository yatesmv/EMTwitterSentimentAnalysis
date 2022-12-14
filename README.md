# Sentiment Analysis of Elon's Twitter Takeover Using VADER

Information travels extremely quickly nowadays and one of the easiest places to see that happen is the social network service Twitter. Twitter allows people from all over the globe to communicate in a way that was never seen before, called tweets. For the past decade and a half, Twitter has been a hotbed of activity including but not limited to social justice, journalism, connecting with friends and family, and rapid reporting of disasters both natural and otherwise. Within the past two months, Twitter has very publicly been turned upside down by its new CEO with the removal of 2FA, high employee turnover, scaring advertisers off by releasing controversial statements, and reinstating previously banned figures. A tumultuous event such as this is ripe for analysis as anyone and everyone has opinions on the subject.
Despite Twitter natural language processing analyses being fairly easy to find online, it is no simple feat. Using a computer to analyze human language is quite complex because computers do not think the same way humans do and teaching one how to analyze the context behind certain words or phrases has been the subject of research for decades. In addition, analyzing text from social media is often much more complicated due to how different people express themselves. Our goal is to analyze the English language reactions on Twitter to Elon Musk’s recent ascension to CEO by focusing on tweets with specific hashtags relating to his takeover.


## Getting Started

Each of the five scripts used in this analysis can we run standalone as long as the data is saved in the same folder.  

### Prerequisites

All of these scripts were made in Python, using either Jupyter Lab or Jupyter Notebook. 

The script to scrape Twitter requires only:
* Snscrape 
* pandas

The following packages are required for the analysis files:
* csv
* SpaCy
* NLTK
* pandas
* string
* re

And the sentiment comparison script also requires a few other packages for visuals:
* matplotlib
* math
* statistics
* numpy

In additon to the above, having access to the "en_core_web_sm" model in SpaCy is a must for the Baseline Sentiment Analysis and the Comparison script.


### Installing

A step by step series of examples that tell you how to get a development env running

Say what the step will be

If you don't have Jupyter Notebook or Jupyter Lab (they're interchangeable for this particular project), then it can be downloaded and installed in a python terminal

```
pip install jupyterlab
```

or for JUpyter Notebook:

```
pip install notebook
```

And to use, just call either in the temrinal like:

```
jupyter-lab
```

or 

```
jupyter notebook
```

Once either Jupyter Notebook or Jupyter Lab are installed, then install the packages either in the same terminal or inside either of those IDEs.

Example:

```
pip install nltk
```


## Authors

* **Jaeho Shin** 
* **Meris Yates** - [yatesmv](https://github.com/yatesmv)
* **Mostafa Omidi** 

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hutto, C. J., & Gilbert, E. E. (2014). VADER: A Parsimonious Rule-Based Model for Sentiment Analysis of Social Media Text. Eighth International Conference on Weblogs and Social Media (ICWSM-14). https://ojs.aaai.org/index.php/ICWSM/article/view/14550/14399, https://github.com/cjhutto/vaderSentiment 
* JustAnotherArchivist. Snscrape. (2022). GitHub. Retrieved November 30, 2022, from https://github.com/JustAnotherArchivist/snscrape  

