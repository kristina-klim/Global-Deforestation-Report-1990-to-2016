# Global-Deforestation-Report-1990-to-2016
Project: Global Deforestation Report 1990 to 2016

[Link to Tableau](https://public.tableau.com/app/profile/kristina.klimenchuk/viz/GlobalDeforestation1990vs2016/GlobalDeforestation1990vs2016)

## **Intro**

The project aims to analyze data on deforestation worldwide and increase awareness of the issues. Data was sourced from the World Bank and included the following data sets: forest (forest_area.csv) and land area (land_area.csv) by country and year from 1990 to 2016, and a table of countries and their corresponding regions (regions.csv)

For analyzing the data sets, I used SQL to get tables together and query them to find answers. 

I have also created a visualization of this data using Tableau. [Please take a look](https://public.tableau.com/app/profile/kristina.klimenchuk/viz/GlobalDeforestation1990vs2016/GlobalDeforestation1990vs2016)

### To accomplish this goal, I will answer the following questions:

- Q1: What was the total forest area (in sq km) of the world in 1990?
- Q2: What was the total forest area (in sq km) of the world in 2016?
- Q3: What was the change (in sq km) in the forest area of the world from 1990 to 2016?
- Q4: If we compare the amount of forest area lost between 1990 and 2016, which country's total area in 2016 is it closest to?
- Q5: What was the percent forest of the entire world in 1990? Which region had the HIGHEST percent forest in 1990, and which had the LOWEST?
- Q6: What was the percent forest of the entire world in 2016? Which region had the HIGHEST percent forest in 2016, and which had the LOWEST?
- Q7: Which regions of the world DECREASED in forest area from 1990 to 2016?
- Q8: Which 5 countries saw the largest amount decrease in forest area from 1990 to 2016?
- Q9: Which 5 countries saw the largest percent decrease in forest area from 1990 to 2016?
- Q10: If countries were grouped by percent forestation in quartiles, which group had the most countries in it in 2016?

## **Summary**

As we can see from The World Bank data sets, the global forest area decreased from 41,282,694.9 sq km **(Q1)** in 1990 to 39,958,245.9 sq km **(Q2)** in 2016, a loss of 1,324,449 sq km **(Q3)**. This is slightly larger than the land area of Peru in 2016, which is 1,279,999.98 sq km **(Q4).**

In 1990, the global percentage of land designated as the forest was 32.42%. Latin America & Caribbean had the highest percentage at 51.03%, and the Middle East & North Africa had the lowest at 1.78%. **(Q5)**

In 2016, 31.38% of the world's total land area was designated as forest. Latin America & Caribbean had the highest percentage of forestation at 46.16%, while the Middle East & North Africa had the lowest at 2.07%. **(Q6)**

Sub-Saharan Africa and Latin America & Caribbean were the only regions that saw a decrease in the percentage of forest area from 1990 to 2016. Sub-Saharan Africa dropped from 32.19% to 27.56%, and Latin America & Caribbean dropped from 51.03% to 46.16%. All other regions experienced an increase in forest area during this period. Despite this, the overall percentage of forest area in the world decreased from 32.42% to 31.38% due to the significant decreases in these two regions. **(Q7)**

<img width="702" alt="image" src="https://user-images.githubusercontent.com/84743536/212173509-5624a7c5-fd2f-49f3-8b7d-1f8d7898088d.png">

*Pic1: Percent Forest Area by Region, 1990 & 2016*



As we can observe in Pic3, the countries that experienced the most significant decrease in forest area percentage between 1990 and 2016 are Togo, Nigeria, Uganda, and Mauritania, all of which are located in the region of Sub-Saharan Africa. Notably, Nigeria ranks in the top 5 for the absolute square kilometer decrease in forest area and the percent decrease in forest area from 1990 to 2016. The fifth country on the list is Honduras, in Latin America & Caribbean region.**(Q8,9)**

<img width="707" alt="image" src="https://user-images.githubusercontent.com/84743536/212173786-f30cc3f7-9f1d-4245-aa53-f3422dbad9dd.png">

*Pic2: Top 5 Countries of decreasing forest area in sq km*

<img width="709" alt="image" src="https://user-images.githubusercontent.com/84743536/212173847-7cae073f-b193-487c-b340-607d2633157a.png">

*Pic3: Top 5 Countries of decreasing forest area in percentage*

The largest number of countries in 2016 were found in the first quartile.**(Q10)**
| Quartile  | Number of Countries |
| --- | --- |
| 0-25% | 85 |
| 25-50% | 73 |
| 50-75% | 38 |
| 75-100% | 9 |

To further save the forest, we must investigate what the countries with the highest growth percentage over the period
have done right. And on the other side, learn from the country with the decreasing forest area what not to do.

**References**
The original project report was created for Udacity Nanodegree Program.
