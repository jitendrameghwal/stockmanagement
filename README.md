Context

You need to create a simple live inventory management system that allows storing a list of
products, a list of warehouses, count and minimum stock thresholds of all products at all
warehouses.

● Product has an 8 character unique sku_code, a name and a price.

● A warehouse has a 4 to 16 character unique wh_code, a name, a pincode and
max_capacity.

● For every product at every warehouse, we wish to maintain an item_count and a
low_item_threshold.

Assignment

You need to create a angular.js/node.js/mysql app that does the following -

● On the root url, show the current list of products and their counts in all warehouses in a
table with the following structure -

○ The first column contains product sku codes.

○ The second column contains the product names

○ Every warehouse is represented as a column after this showing the count of the
product at the warehouse. If a count is below threshold then it is shown with a red
background.

○ Clicking on a product code allows us to go to the product edit page.

● Going to a product edit page allows us to change the counts and thresholds of that
product at all warehouses.

● Going to create warehouse displays a form that allows creating a warehouse and on
creating the warehouse automatically sets a threshold of 10 and a count of 0 for all
existing products for that warehouse.

