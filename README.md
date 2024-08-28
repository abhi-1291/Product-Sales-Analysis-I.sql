SELECT product_name, year, price
<br>
FROM Sales
<br>
LEFT JOIN Product
<br>
ON Sales.product_id = Product.product_id;
