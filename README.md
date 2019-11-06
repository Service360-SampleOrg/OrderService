# OrderService

Source of truth for Order data. Provides API to access and manipulate 
customers orders data.

Owner|Tier|Status|Landscape|Contexts
---|---|---|---|---
CheckoutTeam|Tier1|Prod|Web|Payments, Orders, Customers, Catalog

##### Environments

Production:

- URL: https://...
- AWS account: 1234567890
- Logs: https://...
- Dashboard: https://...

Staging:

- URL: https://...
- AWS account: 1234567890
- Logs: https://...
- Dashboard: https://...

##### Tech

- Golang 13.x: implementation
- AWS ECS: execution env
- AWS ALB: request routing
- AWS SNS: domain events transport
