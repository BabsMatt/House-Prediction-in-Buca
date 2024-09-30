About Dataset
Title: House Rent Price Prediction Dataset for Buca

Sources:

Origin: This dataset was collected from www.hepsiemlak.com

Date: November 16, 2022

Relevant Information:

Buca is the most populous district of Izmir, Turkey. This dataset includes the rents of the houses in Buca and the
independent variables that may be related to these prices.

# Column Dtype Description
--- ------ ---------- -------------------
0 location category districts of Buca

1 num_rooms uint8 number of rooms

2 gross uint8 unit: square meter

3 building_age uint8 unit: year

4 floor_type category location of flat in the building

5 furnishing_status int64

6 price uint16 rental price of a house

The model used are LinearRegression and RandomForestRegressor. Both models were trained with and without both Normalized data
RandomForestRegressor without normalized data gives the highest accuracy