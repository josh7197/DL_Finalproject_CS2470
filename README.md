# CS 2470 Final Project: Predicting NYT Bestseller using Natural Language Processing

## Step 1: Web Scraping

- Our group started out by scraping data from the web, leveraging the GoodReads, NYT API along with Amazon Books, to fetch meta information for each book. Navigate to the following notebook for the technical implementation: Amazon_Web_Scrapper_Code.ipynb, scraper.ipynb. 

#### Note: We referenced krbarounis kickstarter code to get a working data set before running EDA to match our problem scope.

## Step 2: EDA

- The next step was to gain a deeper understanding of our dataset and to remove any features that we did not believe to be advantageous in predicting whether a book will be a bestseller or not. Refer to the following notebook for a technical implementation: EDA_Part1.ipynb.  

## Step 3: Modelling

- The last step was to implement 4 models which yielded a higher test accuracy with each consecutive model. The following four models were implemented: GRU, CNN + GRU, Single-Headed Attention, Multi-Headed Attention. For a technical implementation, please refer to the following notebooks: Model_GRU_GRUCNN.ipynb and Model_Attention.ipynb.
