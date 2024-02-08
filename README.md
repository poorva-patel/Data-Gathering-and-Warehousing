# Data Gathering and Warehousing
Environmental Impact if Food Production

https://www.kaggle.com/datasets/selfvivek/environment-impact-of-food-production?resource=download

  Organization: Our World in Data (https://ourworldindata.org/environmental-impacts-of-food)

  Data was downloaded from Our World in Data (OWID) in the series Environmental impacts of food production. OWID sourced this data from a study published in Science in 2018, Reducing food’s environmental impacts through producers and consumers. by J. Poore and T. Nemecek.Poore and Nemecek consolidated data on the multiple environmental impacts of ∼38,000 farms producing 40 different agricultural goods around the world. Poore and Nemecek did a meta-analysis comparing various types of food production systems.

Data was scanned for outliers and duplicates. There were missing values, however, these values were kept to avoid skewness. There were no duplicates. The data column names were changed to lowercase. No additional cleaning required. All previous and future changes and analysis for data will be done through R.

# Review of Dataset
There are 43 rows and 23 columns. Each column other than food product is a numeric variable.
  Column names include:
  + Food product: (type of food)
    - Wheat & Rye (Bread)
    - Maize (Meal)
    - Barley (Beer)
    - Oatmeal
    - Rice
    - Potatoes
    - Cassava
    - Cane Sugar
    - Beet Sugar
    - Other Pulses
    - Peas
    - Nuts
    - Groundnuts
    - Soymilk
    - Tofu
    - Soybean Oil
    - Palm Oil
    - Sunflower Oil
    - Rapeseed Oil
    - Olive Oil
    - Tomatoes
    - Onions & Leeks
    - Root Vegetables
    - Brassicas
    - Other Vegetables
    - Citrus Fruit
    - Bananas
    - Apples
    - Berries & Grapes
    - Wine
    - Other Fruit
    - Coffee
    - Dark Chocolate
    - Beef (beef herd)
    - Beef (dairy herd)
    - Lamb & Mutton
    - Pig Meat
    - Poultry Meat
    - Milk
    - Cheese
    - Eggs
    - Fish (farmed)
    - Shrimps (farmed)
  * Land use change: Greenhouse emmisions (Kg CO2 - equivalents per kg product)
  * Animal feed: Greenhouse emmisions (Kg CO2 - equivalents per kg product)
  * Farm: Greenhouse emmisions (Kg CO2 - equivalents per kg product)
  * Processing: Greenhouse emmisions (Kg CO2 - equivalents per kg product)
  * Transport: Greenhouse emmisions (Kg CO2 - equivalents per kg product)
  * Packaging: Greenhouse emmisions (Kg CO2 - equivalents per kg product)
  * Retail: Greenhouse emmisions (Kg CO2 - equivalents per kg product)
  * Total emissions: Greenhouse emmisions (Kg CO2 - equivalents per kg product)
  * Eutrophying emissions per 1000kcal
  * Eutrophying emissions per kilogram
  * Eutrophying emissions per 100g protein
  * Freshwater withdrawals per 1000kcal
  * Freshwater withdrawals per 100g protein
  * Freshwater withdrawals per kilogram
  * Greenhouse gas emissions per 1000kcal
  * Greenhouse gas emissions per 100g protein
  * Land use per 1000kcal
  * Land use per kilogram
  * Land use per 100g protein
  * Scarcity-weighted water use per kilogram
  * Scarcity-weighted water use per 100g protein
  * Scarcity-weighted water use per 1000kcal
# Sources
Ritchie, H., Rosado, P., & Roser, M. (2022, December 2). Environmental impacts of food production. Our World in Data. https://ourworldindata.org/environmental-impacts-of-food 

Vivek. (2020, August 4). Environment impact of food production. Kaggle. https://www.kaggle.com/datasets/selfvivek/environment-impact-of-food-production?resource=download 
