## AWS RDS

#### This cloudformation stack provisions the following resources:

1. RDS MySQL instance
2. RDS subnet group
3. security group with TCP protocol ingress from port 3306 to port 3306

#### Includes parameters for:

1. VPC to deploy RDS instance
2. database name
3. database user
4. database password
5. subnets for subnet group
