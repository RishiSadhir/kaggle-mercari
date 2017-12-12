# kaggle-mercari
Build an algorithm that automatically suggests the right product prices using user-inputted text descriptions of their products, including details like product category name, brand name, and item condition. Our scores are evaluated via root mean squared logarithmic error.

## Data

 1. Train and test data are split between train.tsv, test.tsv. The files consist of a list of product listings. These files are tab-delimited.
 2. train_id or test_id - the id of the listing
 3. name - the title of the listing. Note that we have cleaned the data to remove text that look like prices (e.g. $20) to avoid leakage. These removed prices are represented as [rm]
 4. item_condition_id - the condition of the items provided by the seller
 5. category_name - category of the listing
 6. brand_name
 7. price - the price that the item was sold for. This is the target variable that you will predict. The unit is USD. This column doesn't exist in test.tsv since that is what you will predict.
 8. shipping - 1 if shipping fee is paid by seller and 0 by buyer
 9. item_description - the full description of the item. Note that we have cleaned the data to remo
 
 

