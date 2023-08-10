
# Exploring Linear Regression with Python

This repository hosts a Google Colab notebook aimed at providing a hands-on introduction to fundamental statistical concepts using Python. Through a real dataset and clear explanations, it'll guide you through key measures like linear regression and the dummy variable trap.

## Table of Contents

1. [Dataset Description](#dataset-description)
2. [Exploring Statistical Concepts](#exploring-statistical-concepts)
3. [How to Use the Notebook](#how-to-use-the-notebook)

## Dataset Description

The dataset is from Chu, Singfat (2001) “Pricing the C's of Diamond Stones”, Journal of Statistics Education, 9(2).

The variables are as follows :

    1. carat
        weight of diamond stones in carat unit
    2. colour
        a factor with levels (D,E,F,G,H,I)
    3. clarity
        a factor with levels (IF,VVS1,VVS2,VS1,VS2)
    4. certification
        certification body, a factor with levels ( GIA, IGI, HRD)
    5. price
        price in Singapore $

## Exploring Statistical Concepts

### Linear Regression:
**Linear Regression** is a statistical method that helps us study the relationship between a dependent variable and at least one or more independent variables.

The dataset that we'll be using to understand the method is a Diamond dataset, wherein we'll try to study the relationship between the carat and the price of a diamond.

In this case, the carat will be an independent variable as it does not depend on the price, whereas the price will be a dependent variable as it relies on the amount of the carat.

The equation of a simple linear regression model can be represented as:

    y=mx+b

Where:

    y is the dependent variable (**target**).

    x is the independent variable (**feature**).

    m is the slope of the line.

    b is the y-intercept.

### Dummy variable Trap:

The Dummy Variable Trap is a multicollinearity issue that occurs when the dummy variables are highly correlated, making it difficult to distinguish their individual effects on the dependent variable.

This can lead to highly unreliable and unstable results while estimating regression coefficients.

In Layman's terms, a dummy variable trap is a situation where you have too much redundant information.

## How to Use the Notebook

Follow these steps to start exploring the statistical concepts using the provided Google Colab notebook:

1. **Clone or Download:** Clone this repository to your local machine using Git or download the repository as a ZIP file.

2. **Open in Google Colab:** If you're using Google Colab, you can directly open the notebook by clicking on the "Open in Colab" button at the top of the notebook file.

3. **Upload to Google Colab:** If you prefer to use Google Colab via your browser, upload the downloaded notebook (`notebook.ipynb`) to your Google Drive. Then, open it with Google Colab by right-clicking the file and selecting "Open with" > "Google Colaboratory".

4. **Interact with the Notebook:** Once the notebook is open, you can follow along with the code cells. Execute the code cells by clicking the "Run" button or using the keyboard shortcut (Shift + Enter).

5. **Explore and Learn:** Engage with the interactive exercises and explanations to grasp the concepts of mean, median, mode, correlation, and standard deviation.

Feel free to experiment, modify the code, and further explore statistical measures on your own!

