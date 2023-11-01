# fifa_data_cleaning

#USE SQL, SQLITE AND PYTHON in JUPYTER NOTEBOOK

Kaggle is notorious for providing pure, clean datasets ready for analysis and model building.

So here I present to you a veeeeery messy and raw dataset of EA Sports' latest installment of their hit FIFA series - FIFA21, which I scraped from sofifa.com

Content
One of the challenges of web scraping is unclean data, and it natural, really. Different front-end developers write the HTML their own way, and that makes the incoming data unpredictable.

You'll definitely learn a lot about data cleaning with this dataset.

Acknowledgements
A huge round of applause for sofifa.com for providing this amazing data!


1. Convert the height and weight columns to numerical forms
2.Remove the unnecessary newline characters from all columns that have them.
3.Based on the 'Joined' column, check which players have been playing at a club for more than 10 years!
4.'Value', 'Wage' and "Release Clause' are string columns. Convert them to numbers. For eg, "M" in value column is Million, so multiply the row values by 1,000,000, etc.
5.Some columns have 'star' characters. Strip those columns of these stars and make the columns numerical
6.Which players are highly valuable but still underpaid (on low wages)? (hint: scatter plot between wage and value)
7. find duplicate and delete that duplicate
8. 
