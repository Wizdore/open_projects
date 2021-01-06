## [Freezenet: neural network watermarking system](https://github.com/Wizdore/FreezeNET)
This system allows an user to train a neural network with a digital signature. The neural network model can later be licensed and distributed with the signature. Redistributed neural network can be identified with this system to prevent illegal copying of the model. The embedded signature can also be used as a proof of work in neural network training based crypto currency mining.

#### [Project Report](https://github.com/Wizdore/open_projects/blob/main/reports/FreezeNet.pdf)
![](/images/freezenet.png)

## [FinnScraper: house ads mining from finn.no](https://github.com/Wizdore/finn_scraper)
This project is aimed at collecting used home-for-sale ads data from finn. The program collects AD ID's from all the newly listed houses and scraps the details of the houses from each ad id. It can be run everyday with a cronjob to periodically collect newly listed house ads. The bash script to run the cron is included in the project. The collected houses are stored in a local `TinyDB`  database. It also sends a notification to discord with a webhook informing the user how many new ads data has been collected and whats the total size of the dataset everytime the program is run.

{:refdef: style="text-align: center;"}
![](/images/finnscraper.png)
{: refdef}


## [Norway 1910 census data analysis](https://github.com/Wizdore/portfolio/raw/main/reports/Census_data_analysis.pdf)
This project was done as a course work for data intensive systems. In the final project of the course we proposed a project where we had to process a large amount of semi-structured data. We mailed [Digitalarkivet](https://www.digitalarkivet.no/) for historical census data. They provided us with 6GB of proprietary data in seperated files. We have deployed `Hadoop` in the university provided server space to clean and process the data and make visualizations. We cleaned the semi structured xml data to a flat format, mapped 1910 municipality names to current day municipalities using wikipedia as a reference. We visualized distributions of gender, religion and population density on the present day map of Norway.

{:refdef: style="text-align: center;"}
![](/images/census.png)
{: refdef}


## [Genetic Algorithm to solve dynamic control problem](https://github.com/Wizdore/Evolutionary_Ann)
We wrote genetic algorithm to train neural network to balance a pole on a moving cart. The neural network and the genetic algorithm both is written from the scratch. We have also tweaked the genetic algorithm's fitness scoring so that the pole that moves the most without falling get a hgher score, It resulted into more interesting neural networks which try to keep the pole from falling but also keep moving on the environment. The same algorithm can be used to solve other dynamic control problems in `openai gym`. We use multithreading to show the performance metrics and cart simulation at the same time.

{:refdef: style="text-align: center;"}
![](/images/evolution.png){: style="max-height: 500px; width: auto;"}
{: refdef}


