# Week 4 — Postgres and RDS

I was able to complete all the required assessments. I had two issues, about which I'll tell further.

Firstly, I had an issue with PostgreSQL version:
![PSQL Error](assets/error-with-psql-version.png)

I was able to fix it with the correct version and connect to AWS RDS:
![Conncect to RDS](assets/connect-to-aws-db.png)

My security group:
![Security group](assets/security-group-rds-aws.png)

My created AWS-lambda:
![Lambda](assets/lambda.png)

Error with code from Andrew source:
![Error in lambda](assets/error-in-lambda.png)

I fixed it with determined params as in Andrews videos.

Then, I implemented creating activities with Andrew, but there is a missed error with no-passing right handle
![Message](assets/added-message.png)

![Error in handle](assets/error-in-handle.png)

I was not able to fix it yet. I guess I need to take it from jwt somehow.
