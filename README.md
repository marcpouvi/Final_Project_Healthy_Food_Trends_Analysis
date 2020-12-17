<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>


# Trend analysis: Evolution of healthy food over the last decade in western countries 
*[Marc Pou Vilarrasa]*

*[Data Analytics, Berlin & October 2020]*

## Content
- [Project Description](#project-description)
- [Hypothesis](#hypotheses-questions)
- [Dataset](#dataset)
- [Cleaning](#cleaning)
- [Analysis](#analysis)
- [Conclusion](#conclusion)
- [Future Work](#future-work)
- [Organization](#organization)
- [Links](#links)

## Project Description
The intention of this project, is analyzing the trend of healthy food over the last decade in western countries. During the last few years a movement towards a healthier lifestyle is palpable in western society. Basically, this movement is based on two fundamental pillars: 1. Exercising regularly and 2. Eating healthy. Media and social networks, such as instagram or facebook, increasingly offer this type of content. Additionally, new market leading companies are flourishing, offering healthy products to its consumers. 
Being aware of all this, it is normal to think that there is a clear positive trend and that is why people are increasingly interested in consuming this products. Well, in this project the aim is to analyze if this trend its actually real or not.

## Hypothesis
* There has been an increase in publications of healthy recipes 
* There have been more searches for keywords linked to healthy eating 
* Between the years of 2008  and 2018 the number of mentions of tofu increased significantly in the US

## Dataset
I used two different data sources:
* To gather the data related to recipes, I used a kaggle dataset from the web Food.com, one of the largest cooking recipe websites (See link in links section)
* The data related to Google trends, was obtained through pytrends, an unnofficial API for Google Trends. Allows simple interface for automating downloading of reports from Google Trends. For the first attempt, the aim was to work with recipes containing tofu as ingredient, but google trends did not return any information, so keywords such as Tofu or Kale were selected to anlyize its trends.

## Cleaning
Regarding the cleaning of the data, the recipes data contained over 180K recipes over the 2000 to 2018. The intention was analyzing the last decade and the type of recipes were not also what we were looking for. Outliers were removed, nutritional values were added in order to understand better the data set, and it was adapted for the purpose of the analysis. 
For Google trends, there was no need of cleaning

## Analysis
Visual and numerical analysis have been done during the project. The first analysis was done with the recipes data set, once the data was cleaned and ready to work with, we plot it and the graphs indicated that there has been a drop in healthy recipe posts during the recent years, this is the reason why Google trends played a main role for continuing with the analysis. Once, we obtained the data for what was consider keywords representing healthy food, we used Tableau for visualizing the tendencies. But I wanted to get further, and for the Tofu keyword, we applied inferential statistics that drove me to the final conclusions. 

## Conclusion
* Analytical Conclusions: Surprisingly, in general terms the positive trends of tofu has not been significant compared over the last decade, although it was for 2017 and 2018 
* Project Management: Learn about all the process and its different steps. Research the code, ask for help, work under pressure
* Improvise, Adapt and Overcome: During this project many blockers and problems have been faced, and the way to overcome them is to adapt to the situation and improvise when needed 
* Future steps: With further investigation on the other keywords, we would observe that words like kale are becoming more popular on our ingredients. With more time, determinign which keywords would be really representative to a healthy life-style, could help us to have a deep knowledge over this new market and a good start to implement a business plan (Heura Foods: Plant-based startup from Barcelona founded in April 2017. Heura was born to bring a solution that will leave the current food system obsolete and accelerate the shift to a world where the animals are out of the meat production equation). Also, a healthy food recommender could be a great next step.
 
## Organization
The repository is organised into 4 different files. The first, a file with all the Jupyter Notebooks with the code used. The second one, contains Tableau document visualization and the raw csv files visualized. The third, the data gathered used for the analysis, it is missing the original from Kaggle as it was too heavy. For solving this, the link to the Kaggle dataset is provided in links section. And last, the presentation stored in pdf and the photos used. 

## Links
[Repository](https://github.com/marcpouvi/Final_Project_Healthy_Food_Trends_Analysis)  
[Slides](https://docs.google.com/presentation/d/1OhBPcAHE_zIYupvJu3mVbtKwwspr_L0f4JBpOWv2bW0/edit#slide=id.gb1a88ca24d_0_174)  
[Trello](https://trello.com/b/7WeMhwv1/final-project-analysis-healthy-food-trend)  
[Kaggle with original dataset](https://www.kaggle.com/shuyangli94/food-com-recipes-and-user-interactions)
