---
title: Analyzing the correlation of  countries 
layout: page
permalink: /analysis/
---
For this analysis we wanted to plot the amount of each different nutrient (carbohydrates, fats, proteins, fiber, etc) as well as the quantity of energy (kcal) consumed in neighbouring countries in order to extract some conclusions. For this reason, the different countries that appear in the Open Food Database were divided according to the continent they belong to. The number of countries per continent were: Europe (61), Africa (39), Asia (43), America(33) and Oceania (7). In the figure shown here below, we can see that despite the fact that Africa or Asia have more countries in the database than America, the quantity of nutrients and energy consumed in this continent are really remarkable.  

**Important!** Links for furder and detailed analysis below.
{: .notice}

![image-center]({{ '/images/continents_barplot.png' | absolute_url }}){: .align-center}

## Further analysis

Here there is a list of images that contain the results obtained for a detailed analysis in
each of the continents.

| Continent        |   Topic    | Comments                                                                |
|------------------|------------|-------------------------------------------------------------------------|
| [Africa]         | nutrients  | carbohydrates, fats, proteins, fiber, etc in **Africa**                 |
| [America1]       | nutrients  | carbohydrates, fats, proteins, fiber, etc in **America**                |
| [America2]       | nutrients  | carbohydrates, fats, proteins, fiber, etc in **America except of USA**. |
| [Asia]           | nutrients  | carbohydrates, fats, proteins, fiber, etc in **Asia**                   |
| [Europe1]        | nutrients  | carbohydrates, fats, proteins, fiber, etc in **Europe**                 |
| [Europe2]        | nutrients  | carbohydrates, fats, proteins, fiber, etc in **Europe except of France**|
| [Oceania]        | nutrients  | carbohydrates, fats, proteins, fiber, etc in **Oceania**                |


### Europe

The country with the most items available for any nutrient and energy consumed is France. Since the Open Food Facts Database is a French database, there might be some biased to the data collected. For this reason, we plotted again the same plot above but this time without France's data, this way the other countries' numbers can be differentiated and analyzed better.

Taking out France we can see that the countries that more consume each kind of nutrient is Republic Chec, but in the case of the alcohol is United Kingdom.


### America

In America, apart from  USA, the countries with highest values of nutrients are Mexico and Canada.


[Africa]:{{ '/images/africa_nutrients.png' | absolute_url }}
[America1]:{{ '/images/america_nutrients_withoutUSA.png' | absolute_url }}
[America2]:{{ '/images/america_nutrients.png' | absolute_url }}
[Asia]:{{ '/images/asia_nutrients.png' | absolute_url }}
[Europe1]:{{ '/images/europe_nutrients.png' | absolute_url }}
[Europe2]:{{ '/images/europe_nutrients_withoutFR.png' | absolute_url }}
[Oceania]:{{ '/images/oceania_nutrients.png' | absolute_url }}
