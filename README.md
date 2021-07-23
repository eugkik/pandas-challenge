# pandas-challenge

The 'Pandas Homework' Jupyter Notebook will read the 'purchase_data.csv' file and create a dataframe.

The number of unique values in the 'SN' column will be counted and used to create a new dataframe  to display the Total Players.

The number of unique items will be counted from 'Item Name'.  The average price, total count of purchases, and sum of all purchases will be found from 'Price'  A new dataframe will be created and displayed with these values with currency formatting.

A new dataframe of unique players will be created by removing duplicate values from the 'SN' column.  A count of values for each gender category will be found.  The percentage of each gender category will be found and all values will be displayed.

The original dataframe will be grouped by 'Gender'.  The number of unique values will be found from the grouped dataframe.  The number of purchases, average purchase price, total purchase amount, and average per person will be found and displayed as a new dataframe.

The highest age will be found from the unique players dataframe.  Bins will be created for different age ranges, with the upper limit set as the highest age found.  The unique players dataframe will be placed in the bins and new column will be added for the age ranges.  A new dataframe will be created, sorted by age ranges, and displayed.

The binned age ranges column will be added to the original dataframe and grouped by age ranges.  The number of unique players will be found, along with the purchase count, average purchase price, total purchase amount, and average purchase per player.  A new dataframe with these values will be created and displayed.

A new column called 'Purchase Count', with a value of 1, will be added to the original dataframe and grouped by 'SN'.  The total purchase, purchase count , and average purchase price will be found for each player from the grouped dataframe.  A new dataframe will be created with these values, sorted by total purchase price.

The original dataframe will be group by item ID and item name.  The sum of purchase count and item price will be found and used to find the average item price.  A new dataframe will be created with these values, sorted by the purchase count.

A copy of the previous dataframe will be made.  The formatted '$' will be removed from the Total Purchase Value column and sorted.  The column will be reformatted with the '$' and displayed.