# fifa_data_cleaning

Kaggle is notorious for providing pure, clean datasets ready for analysis and model building.

So here I present to you a veeeeery messy and raw dataset of EA Sports' latest installment of their hit FIFA series - FIFA21, which I scraped from sofifa.com

Content
One of the challenges of web scraping is unclean data, and it natural, really. Different front-end developers write the HTML their own way, and that makes the incoming data unpredictable.

You'll definitely learn a lot about data cleaning with this dataset.

Acknowledgements
A huge round of applause for sofifa.com for providing this amazing data!

Inspiration
Convert the height and weight columns to numerical forms
Remove the unnecessary newline characters from all columns that have them.
Based on the 'Joined' column, check which players have been playing at a club for more than 10 years!
'Value', 'Wage' and "Release Clause' are string columns. Convert them to numbers. For eg, "M" in value column is Million, so multiply the row values by 1,000,000, etc.
Some columns have 'star' characters. Strip those columns of these stars and make the columns numerical
Which players are highly valuable but still underpaid (on low wages)? (hint: scatter plot between wage and value)
