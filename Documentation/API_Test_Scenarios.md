# API Test Scenarios

## GET /users
- Validate status 200
- Extract user_id dynamically

## GET /products
- Validate status 200
- Extract product_id dynamically

## POST /carts (Positive)
- Validate cart creation
- Validate SLA
- Store cart_id

## POST /carts (Negative)
- Invalid quantity
- Missing fields
