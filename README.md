Hello, I am Shaon Rahman, Here's Some of my recent works.

# [Freezenet: Neural Network watermarking System](https://github.com/Wizdore/FreezeNET)
This system allows an user to train a neural network with a digital signature. The neural network model can later be licensed and distributed with the signature. Redistributed neural network can be identified with this system to prevent illegal copying of the model. The embedded signature can also be used as a proof of work in neural network training based crypto currency mining.
* [Project Report](https://github.com/Wizdore/open_projects/blob/main/reports/FreezeNet.pdf)
![](/images/freezenet.png)

# [FinnScraper: Housing Data Collection from finn.no](https://github.com/Wizdore/finn_scraper)
This project is aimed at collecting used home-for-sale ads data from finn. The program collects AD ID's from all the newly listed houses and scraps the details of the houses from each ad id. It can be run everyday with a cronjob to periodically collect newly listed house ads. The bash script to run the cron is included in the project. The collected houses are stored in a local `TinyDB`  database. It also sends a notification to discord with a webhook informing the user how many new ads data has been collected and whats the total size of the dataset everytime the program is run.
![](/images/finnscraper.jpg){:width="200px"}
