# Data Dictionary

## Customers

| Column | Description |
|----------|----------|
| customer_id | Unique customer identifier |
| customer_unique_id | Unique customer reference across purchases |
| customer_city | Customer city |
| customer_state | Customer state |

## Orders

| Column | Description |
|----------|----------|
| order_id | Unique order identifier |
| customer_id | Customer identifier linked to Customers dataset |
| order_status | Current order status |
| order_purchase_timestamp | Date and time of purchase |

## Payments

| Column | Description |
|----------|----------|
| order_id | Order identifier linked to Orders dataset |
| payment_type | Payment method used |
| payment_value | Total payment amount |

## Relationships

Customers.customer_id → Orders.customer_id

Orders.order_id → Payments.order_id
