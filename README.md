# Instacart Market Basket Analysis

## Abstract

Instacart has emerged as a leading grocery delivery platform in North America and it's growth is fast accelerating due to COVID-19. Given the increase in online grocery shopping and as avid food enthusiasts, we wanted to understand what people are ordering and how their behaviour differs. After exploring the dataset and the different data points it contains, we identified the opportunity to focus on user and order behaviour when buying produce (fruits, vegetables, etc.).

## Research Questions

*1. What is the breakdown of customers that <ins>buy organic</ins> versus ones that <ins>never buy
organic</ins> when given the option?*

*2. Does purchasing behavior differ between organic and never organic users?*

*3. Does user purchasing behavior change as they make more orders on Instacart? And is
buying “organic” a stable or dynamic behavior?*

## Project Outcomes

In conclusion, given the analysis of our three research questions, we believe that the following
insights can help us understand the purchasing behavior of produce among Instacart users:

- **Organic customers make up a large portion** of users (>50% of purchased produce is
organic)
- Users that **never buy organic produce (i.e., Never Organics) seem to shop
differently** than users that buy organic; they order less, more sporadically and when
they do order, they buy less produce than organic buyers
	 - Super Organic users also order less produce per order, we hypothesize that they
might be “pickier” buyers
- As users make more orders, they **seem to include produce items more often** and to
**shift towards organic produce** as well
- Users in the **Super Organic and Never Organic segments appear less stable** than
those in the Moderate Organic and Organic Taster segments. Super Organics migrate
towards Moderate while Never Organics migrate towards Tasters

## Tools Used

Languages:
- Python

Libraries:
- numpy
- pandas
- matplotlib

## Research Dataset

The source dataset leveraged was from a machine-learning based Instacart Kaggle
competition that contained a relational set of files describing Instacart customers' orders over
time. For the purpose of the competition, the ordered products were split into the prior, train and
test datasets, of which the test dataset was not publicly available.
Source datasets: Instacart Market Basket Analysis (available on [Kaggle](https://www.kaggle.com/c/instacart-market-basket-analysis/data))

- Datasets leveraged for this analysis - `aisles.csv`, `departments.csv`,
`order_products__prior.csv`, `order_products__train.csv`, `orders.csv`, `products.csv`

Note that the `orders.csv` contains information pertaining to each order as a whole, while
each `order_products__*.csv` contains information about the basket of products within each
order (one order can have multiple products).

## Division of Labor
For the purposes of refraining from taking credit for my other dedicated group members work, each notebook is labelled by last name to denote contribution to the overall research project. Additionally, the work contributed by the other members of the research team has been seperately stored within the `Other_analysis` directory. The following notebooks have been labelled as my own contributions to the project:

- `Data_cleaning_Temlock.ipynb`
- `Preprocressing_organic_segmentation_Temlock.ipynb`
- `Question3_Temlock.ipynb`

Credit for this project also goes to Greg Tully and Faris Haddad of the UC Berkeley Masters of Information and Data Science program.
