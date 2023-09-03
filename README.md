## Overview
This repository contains some exploratory analysis of the real estate market.  
  
[The dataset](https://www.kaggle.com/datasets/ahmedshahriarsakib/usa-real-estate-dataset) was provided on Kaggle by **ahmedshahriarsakib**.

---

### Quick Start
Run the setup script in the terminal:
```shell
. ./setup/init.sh
```

---

### Repository Structure
`models/` - Contains all the analytical models used for parsing, fitting, and prediction.

`data/` - Contains the data used by the analytical models.  
   
`data/us_real_estate.csv` 
- `status` - (moot) All houses are for-sale
- `bed` - number of bedrooms
- `bath` - number of bathrooms
- `acre_lot` - number of acres for property
- `city` - Name of the city
- `state` - Name of the state
- `zip_code` - Zipcode of the house
- `house_size` - Square feet of the house
- `prev_sold_date` - last time house was sold
- `price` - Current listing price or recently sold price (if the house is sold recently) 

