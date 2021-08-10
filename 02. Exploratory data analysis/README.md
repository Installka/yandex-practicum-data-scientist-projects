# Exploratory data analysis

__Analysis of apartment advertisements__

__Input data__ - Yandex.Nedvizhimost service data: archive of ads for the sale of apartments in St. Petersburg and neighboring settlements for several years.

__Target__ - determine the parameters for determining the market value of real estate.

__What's done__:
- data preprocessing:
    - detection, correction and removal of missing values and anomalies;
    - data types correction;
    - settlements names lemmatization and categorization of settlement types.
- calculation of new features:
    - price per square meter;
    - day of the week, month and year of publication of the ad;
    - apartment floor;
    - ratio of residential area to total;
    - ratio of kitchen area to total.
- EDA performed:
    - analysis of area, price, number of rooms and ceiling heights - areas and height of the ceilings heights affect price mostly. With an increase in the area of an apartment, the price for it increases, but not in direct proportion. Maximum price depends on the number of rooms in apartment and its distance from the center, directly and inversely, respectively;
    - analysis of the time of sale of an apartment - on average, apartments are sold in 3-4 months;
    - removed rare values and outliers;
    - determination of the city center - about 10 km radius;
    - analysis of apartments in the city center - in the city center apartment prices increase sharply. The nature of price dependence on various parameters for apartments in the center and for all apartments does not differ.

__Tools used__ - pandas, pymystem3.