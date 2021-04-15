# Analysis of correspondence between real-world football players' statistics and FIFA players' values and rating

### Description:
In this project I will collect the statistical data from the 5 biggest Europoean football league - namely Premier League, La Liga, Serie A, Bundesliga and Ligue 1 as well as the data from the game FIFA. The statistics will be for the season 2016/2017 and the equivalent FIFA 18.

Then, I will calculate the correspondence of the real performance of the player on the field with the FIFA value and overall rating of the player. The results could be used to gauge to which extend the developers of the game take into account the players' real performance or the fame of the players is more important when determining the value and rating for the game. I will use my own scoring weights for various statistics.

At the end I will list the worst judged players in the FIFA game.

### Opeartion guide:

#### Input:
The input data-sets are stored in the repository in the directory **data** and are named according to the convention
 - data for Premier League has prefix (league shortcut) PL
 - data for La Lila has prefix LL
 - data for Serie A has prefix SA
 - data for Bundesliga has prefix BL
 - data for Ligue One has prefix L1

and the real-world statistics has suffixes

 - STD for overall standard statistics, such as minutes played, goals scored, etc.
 - MISC some special stats, such as number of crosses, fouls, etc.
 - GK statistics of goalkeepers such as goals allowed, clean sheets, etc.

Next input is the source code of my experiment. This source code is in a form of an Jupyter Notebook **experiment.ipynb** that is stored in the directory **code** in this repository as well.

#### Output:
The output file are stored in the directory **data/output** and the naming convention is similar as with the input files, that means for each league there is a statistics output file with the calculated statistics based on my chosen weights named **statistics[league shortcut]**.
The histogram, which shows the comparison of the distribution of players' values for each league, is at the end of the output of the run of iPython notebook. 

#### Run:
To run my experiment, all that is necessary is to run the iPython notebook in any Jupyter Notebook application. All the input files are already linked to this GitHub repo to the corresponding directory. The output files, that are the same as stored here in the repo in directory **data/output**, are after the running the experiment stored on your local machine in the directory where the notebook is stored.

### Acknowledgements:
The real-world data were collected by team from the webpage https://fbref.com/en/comps/ and provided for the download and reuse.

The FIFA data-set was created by Kevin Heavey and contributors and is available also here on GitHub in the repo https://github.com/kevinheavey/fifa18-even-more-player-data/tree/master/data/final/current.
