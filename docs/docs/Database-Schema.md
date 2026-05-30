# Database Schema

Users

- user_id
- name
- email
- password

Expenses

- expense_id
- user_id
- amount
- category
- payment_method
- description
- date

Budgets

- budget_id
- user_id
- category
- monthly_limit

Goals

- goal_id
- user_id
- target_amount
- current_amount

Subscriptions

- subscription_id
- user_id
- service_name
- monthly_cost
