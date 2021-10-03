# Pandas Challenge
## Heroes of Pymoli

### Task

In this challenge we are asked to analyse a company's purchasing data relating to the Heroes of Pymoli game.

There are 9 sections to complete:

* Player Count
* Purchasing Analysis (Total)
* Gender Demographics
* Purchasing Analysis (Gender)
* Age Demographics
* Purchasing Analysis (Age)
* Top Spenders
* Most Popular Items
* Most Profitable Items

Each section has calculations that need to be done to display the results required.

After the analysis we are required to write a description of three trends we have observed from the data.

### Method

Once the data is loaded a number of different actions are taken to get the desired outcomes.
A number of different methods are used including:

* .mean() - to get the average price. 
* .count() - to count the number of entries in a colum.
* .sum() - to get the total value of a column.
* .unique() - to look at unique data.
* .nunique() - to get the number of unqiue entries in a column as a whole.
* The .groupby method is used a number of times to split the original data into different groups and enable calculations requiring more specific results.
* The data was also binned and cut to break the players up into age ranges. 

Once the calculations were done formatting was applied each data frame (where required) and each dataframe was displayed.

### Result

After completing the analyses on the purchasing data, the below observations have been made:
1. The majority of players are male (84%), however females have a slightly higher average purchase price per person. The average purchase price per male is $4.07 whereas the      average purchase price per female is $4.47.
2. Most players are in the 20 - 24 age range group (45%).
3. 77% of all purchases made are from the people aged between 15 - 29 years old.
4. Singed Scapel is one of the most profitable items but it is not one of the most popular items.

### Files

To run the file please use the HeroesOfPymoli_stater.ipynb file in Jupyter Notebook. The is found in the main branch of the repository.
The resources file contains the purchase_data the analysis is based on.

