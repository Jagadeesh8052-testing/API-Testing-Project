# GET API Test Cases – E-commerce REST APIs

## GET /products

1. Verify GET /products returns status code 200.
2. Verify response time is less than 2000 ms.
3. Verify response header Content-Type is application/json.
4. Verify response body contains list of products.
5. Verify each product has id, title, price, description, category, image.
6. Verify product id is integer.
7. Verify product price is numeric.
8. Verify products list is not empty.

## GET /products/{id}

9. Verify GET product by valid ID returns status code 200.
10. Verify correct product details are returned for given ID.
11. Verify response contains correct product id.
12. Verify GET product by invalid ID returns status code 404.
13. Verify proper error message is returned for invalid product ID.
