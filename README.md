## [Norwegian house ads data dashboard](https://housing-market-norway.herokuapp.com/)
{: #house-dashboard }
This is a dashboard of general statistics of housing market. The data is mined using the [FinnScrapper](https://github.com/Wizdore/finn_scraper) deployed on a `Raspberry Pi` that collect new house ads posted in finn.no and stores the data locally. The dashboard aims to provide an overview of price, location, facilities etc. one can expect given their preference of house price, area and other factors. The data cleaning, preparation and the dashboard is all done with Python. Its currently deployed on [Heroku](https://housing-market-norway.herokuapp.com/).

{:refdef: style="text-align: center;"}
![](/images/housingdashboard.png)
{: refdef}



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



## [Freezenet: neural network watermarking system](https://github.com/Wizdore/FreezeNET)
This system allows an user to train a neural network with a digital signature. The neural network model can later be licensed and distributed with the signature. Redistributed neural network can be identified with this system to prevent illegal copying of the model. The embedded signature can also be used as a proof of work in neural network training based crypto currency mining.

#### [Project Report](https://github.com/Wizdore/open_projects/blob/main/reports/FreezeNet.pdf)
![](/images/freezenet.png)



## [AR Object Placement and Interaction](https://github.com/Wizdore/AR_Project)
It was developed for "Project in Computer Science" course using C# and Unity Engine. It contains an asset library, user can choose any image or text from the asset library and place it in the augmented reality environment. The objects in the environment can also be moved, deleted or transformed through a dynamic UI system which changes based on the context. The codebase is easily extendable, 3D objects can also be included in the asset library and Buttons will be generated at runtime. 

#### [Project Report](https://github.com/Wizdore/AR_Project/raw/main/AR_ProjectReport.pdf)
{:refdef: style="text-align: center;"}
<iframe width="700" height="480" src="https://www.youtube.com/embed/JjdaOWXR9-M" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
{: refdef}



## [Genetic Algorithm to solve dynamic control problem](https://github.com/Wizdore/Evolutionary_Ann)
We wrote genetic algorithm to train neural network to balance a pole on a moving cart. The neural network and the genetic algorithm both is written from the scratch. We have also tweaked the genetic algorithm's fitness scoring so that the pole that moves the most without falling get a hgher score, It resulted into more interesting neural networks which try to keep the pole from falling but also keep moving on the environment. The same algorithm can be used to solve other dynamic control problems in `openai gym`. We use multithreading to show the performance metrics and cart simulation at the same time.

{:refdef: style="text-align: center;"}
<p align="middle" float="center">
  <img src="https://github.com/Wizdore/portfolio/raw/main/images/evolution2.gif" width="300" />
  <img src="https://github.com/Wizdore/portfolio/raw/main/images/evolution.png" width="500" />
</p>
{: refdef}

