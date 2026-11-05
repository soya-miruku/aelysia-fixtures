# aelysia-fixtures

Synthetic test data for Aelysia acceptance tests. Every value here is made up; nothing
describes a real warehouse, person or account.

- `inventory/synthetic-wh-1.json`: fake stock for items A, B and C. The test operator replaces
  it with a second version partway through a test run to check stale-data handling.
