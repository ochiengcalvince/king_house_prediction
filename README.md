# king_house_prediction
## Description
## Project Goal

The King County House Dataset contains a wealth of information about the price, size, location, condition and various other features of houses in Washington’s King County. In this article, I’ll disect how linear regression model in Python can help predict house prices , so that the Real Estate Agency can render constructive advices to homeowners of when they can buy or sell their houses and by what amount.There are several features or factors that should be looked into when performing this task and that what i am going to do.
## column names description
 `id` - Unique identifier for a house
* `date` - Date house was sold
* `price` - Sale price (prediction target)
* `bedrooms` - Number of bedrooms
* `bathrooms` - Number of bathrooms
* `sqft_living` - Square footage of living space in the home
* `sqft_lot` - Square footage of the lot
* `floors` - Number of floors (levels) in house
* `waterfront` - Whether the house is on a waterfront
  * Includes Duwamish, Elliott Bay, Puget Sound, Lake Union, Ship Canal, Lake Washington, Lake Sammamish, other lake, and river/slough waterfronts
* `view` - Quality of view from house
  * Includes views of Mt. Rainier, Olympics, Cascades, Territorial, Seattle Skyline, Puget Sound, Lake Washington, Lake Sammamish, small lake / river / creek, and other
* `condition` - How good the overall condition of the house is. Related to maintenance of house.
  * See the [King County Assessor Website](https://info.kingcounty.gov/assessor/esales/Glossary.aspx?type=r) for further explanation of each condition code
* `grade` - Overall grade of the house. Related to the construction and design of the house.
  * See the [King County Assessor Website](https://info.kingcounty.gov/assessor/esales/Glossary.aspx?type=r) for further explanation of each building grade code
* `sqft_above` - Square footage of house apart from basement
* `sqft_basement` - Square footage of the basement
* `yr_built` - Year when house was built
* `yr_renovated` - Year when house was renovated
* `zipcode` - ZIP Code used by the United States Postal Service
* `lat` - Latitude coordinate
* `long` - Longitude coordinate
* `sqft_living15` - The square footage of interior housing living space for the nearest 15 neighbors
* `sqft_lot15` - The square footage of the land lots of the nearest 15 neighbors



## Findings
My current preferred model is able to explain about 85% of the variance in the sale prices of homes, which shows that the model is 85% accurate .
The value of the r_squared increase as we add more predictors,with the first one being that of simple linear regression with about 24% accuracy of the model.
All the models are statistically significant having a p_value of less than 0.05
The last model would be an ideal in predicting the current and future prices of the house.


## Recommendation
I would recommend that the Agency adopt the last model since it has a higher r_squared value of 0.85 which translate to 85% accuracy of the model.
Features such as condition , bedrooms, bathrooms, and sqft_living of the house should be put into consideration because they affect prices positively .
By using this model the Agency is able to offer reasonable advices to the homeowners which will inturn help them in knowing how to maximize profits and minimize losses.




## Platforms used
Git/ Github

## Technologies used
- Python
- Pandas Library
- Seaborn
- Matplotlib Library
- statsmodels
## Author and Aknowledgement
ochiengcalvince30 Assistance was granted from the Technical Mentors of Moringa School (Nairobi, Kenya).

## License
MIT © ochiengcalvince30
