# Data Dictionary

## Customers

| Column | Description |
|----------|----------|
| customer_id | Unique customer identifier |
| customer_unique_id | Unique customer reference |
| customer_city | Customer city |
| customer_state | Customer state |

## Orders

| Column | Description |
|----------|----------|
| order_id | Order identifier |
| customer_id | Customer identifier |
| order_status | Order status |
| order_purchase_timestamp | Purchase date |

## Payments

| Column | Description |
|----------|----------|
| order_id | Order identifier |
| payment_type | Payment method |
| payment_value | Payment amount |
