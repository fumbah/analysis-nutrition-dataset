# (General impact of macro-nutrients in the calories content of food)
## by (FUMBAH ELVIS)


## Dataset : Food Composition Database.

> This data set contains data for various types of food including the amounts of different nutrients found in the foods: like minerals, vitamins, carbohydrates, proteins, fats etc., The data set is composed of 8789 food descriptions with 77 columns (nutrients)

> source: Source: https://www.kaggle.com/datasets/trolukovich/nutritional-values-for-common-foods-and-products/download?datasetVersionNumber=1

> After  data set collection from the specified URL, the followed issues where identified and fixed below exploration:

> 1- We replaced Null values in saturated fats columns with 0

> 2- The was no category column in the data set, but we could notice that the first word of the description column was actually the category, we performed a loop and slice to produce a new column to this data set called food category

> 3- the units of the of measurements of the nutrients in the data where not the same and not suitable for our analysis, some where in g, mg., mcg UI, etc. here, there was need for conversion of those unit to one identical unit (grams) to remove this inconsistent units in the whole dataset

## Summary of Findings

> In the exploration, we found that there was a strong relationship between the calories content of food samples and their total fats, with increasing effect on the protein content and moderate with the carbohydrate content.

> The distribution of our main variable of interest looked skewed to the right but we could observer several peaks, this implies that there were few groups of food samples with quiet high calories ie above 400 calories , mean while most food samples have calories in the rage of 0 to 400 calories and some few samples went right up to 800 and 900 calories and we could show that they were oils and not Abrantes values by using the quatile ranges to filter the data set

> Tt seemed that samples of foods were divided into 2: those with low protein (between 0 to around 18g) content and very few food samples had protein content greater than 18g. we could also notice some food samples with protein content seemingly high. and this prompted more investigation at the end of which we found those high in protein are actually meat, Eggs, fish, soy, and their related. as we will see in the presentation.


> For fats the majority of samples of food are very low in total fat (between 0 to around 40g) content and very few food samples have total fat content greater than 40. and some foods are exceedingly in high total fat worth investigation which we finally found them to be oils and their related. This feature will later be presented

>There seem to be 02 kinds of sample those with carbohydrate content lesser than 20g and some with carbohydrate between and 90g but again we have quit a high number of samples with very low carbohydrate contents.

> Again the following relationships where found between our majors features and calories content:

> 1- calories level increase only seemingly with carbohydrates

> 2-calories levels increase steeply with total fats

> 3-calories level also increase seemingly with calories but not as carbohydrates


>At the end of the analysis, we could comfortable say on the bases of the reliability of the source of our data, that fats contribute to the highest percentage of the calories level of foods, and this is followed by proteins which also contribute well especially when fats are absent like in meat, well we could not neglect the contribution of carbohydrates but that is very low as compared with the others


## Key Insights for Presentation

>During our exploration, we came out to discover what we could term as high calories foods and their major calorific contributors, we will be presenting to you our top calories food and the relation with their major calorific components.

>For the presentation, we will focus on just the influence of the proteins, fats on the calories level of food samples.
we will start by introducing the calorie variable, and  to display a list of high calories foods.

> Afterwards, I introduce each of the major nutrient (those which contributes to high calories content) to display a list of food samples in which this nutrient is found in abondance.I use the bar plots of each nutrient and calorie to display counts within specific calories bins

>After which we will proceed to display the relation between these 03 features with our main feature to show the following relationships that where found between our majors features and calories content:

>1. calories level increase only seemingly with carbohydrates
2. calories levels increase steeply with total fats
3. calories level also increase seemingly with calories but not as carbohydrates

>We are  going to be presenting what we termed  high calories foods and their major calorific contributors, in essence,we  will be presenting to you our top calories food and the relationship with their major calorific components.


# analysis-nutrition-dataset
my very first exploration
