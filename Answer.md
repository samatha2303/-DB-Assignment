### Answers


### 1. Explain the relationship between the "Product" and "Product_Category" entities from the above diagram. ###

Answer:

The "Product" and "Product_Category" entities are related through the "category_id" column in the "Product" table. This "category_id" is a foreign key referencing the "id" column in the "Product_Category" table. This relationship indicates that a product is associated with one product category.

-------

### 2. How could you ensure that each product in the "Product" table has a valid category assigned to it? ###

Answer:
To ensure that each product in the "Product" table has a valid category assigned to it, we can implement referential integrity constraints in the database schema. We can enforce a foreign key constraint on the "category_id" column in the "Product" table, referencing the "id" column in the "Product_Category" table. This constraint would prevent insertion or update operations that would create an invalid category assignment

