
# List of Categories
> http://localhost:9500/categories

# List of Products
> http://localhost:9500/products

# List the number of products on the basis of category
> http://localhost:9500/product?category=Organic+Fruits

# List the products on the basis of category and rating
> http://localhost:9500/productss?rating=4.5+stars&category=Diary+products

# List the products on the basis of product name and price
> http://localhost:9500/productss?Product_name=Fresh+Garlic&price=$5 

# List of products on the basis of category and discount
> http://localhost:9500/productss?category=Fresh+meat&discount=25%+off

# list of products by each names and pricing 
> http://localhost:9500/product?productName=Organic+Butter&price=$0.48

# List of product details on the basis of product name
> http://localhost:9500/product/Fresh Tomato

# List of the customer's who had placed Order (POST method)
> http://localhost:9500/placeOrder

# List of Orders (GET method)
> http://localhost:9500/viewOrder

# List of the customers on the basis of the email
> http://localhost:9500/viewCustomer?email=rahul@gmail.com

# Update the Order(PUT method)
> http://localhost:9500/updateOrder/63b66289e900acabab3f4a13
 
# Delete the Order on the basis of customer name (Delete method)
> http://localhost:9500/deleteOrder/Rohit

