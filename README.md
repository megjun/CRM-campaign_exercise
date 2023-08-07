 # Exercise: CRM campaign

 ## Notebooks

 In this system, we have 4 notebooks to fully understand the context of our system. 

* First Notebook: `Explore Sample Data` - path: 'Explore_sample-data.ipynb' - the main goal of this notebook is to explore the sample that was provided, and try to contextualize the data & features we are working with. 

* Second Notebook: `Generate_Data` - path: 'Generate_Data.ipynb' - the main goal with this notebook was to generate data, based on the sample required, for 7 following days, so then we could test our system. The Data Generated of saved in the path: 'data'. 

* Third Notebook: `Exercise_CRM-campaign_Teste` - path: 'Exercise_CRM-campaign_Teste.ipynb' - in this notebook, we did the first design of our system/code, we tested it in the data we just generated. In this notebook, we could check that the system was working.

* Fourth Notebook: `Exercise_CRM-campaign_Final` - path: 'Exercise_CRM-campaign_Final.ipynb', our final product, final system. Ready to be used. 

## How to use

* First: After receiving the files with the daily streams, in the format of 'listen-YYYYMMDD.txt', you should save it in the path 'data'. 

* Second: You need to run the code every day, the code on the notebook: `Exercise_CRM-campaign_Final` (path: 'Exercise_CRM-campaign_Final.ipynb')

* Third: Your script with the top 50 songs per country, on the last 7 days, will be saved in the path 'output_top-50-songs'. 

## Final notes

We used this format in our code 'listen-YYYYMMDD.txt' because it was the one used on the sample provided, and not 'listen-YYYYMMDD.log', but in case the files are '.log', you just need to change it in the code and it will work just fine. 
