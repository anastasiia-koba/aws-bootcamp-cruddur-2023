# Week 6 — Deploying Containers

I was able to complete the required assessments. But after setting everything in AWS I found that my budget had grown extremely because of usage of VPC (more than $2 for 2 days). Also, Rout 53 is very expensive and I could not create a public domain for service. So I was forced to delete my VPC and Route 53  and therefore I will maybe watch for the next weeks and try to do it without a real implementation in AWS.

My backend image in AWS:

![Image](assets/week-6/backend-image.png)

Created log group in Cloud Watch

![Created Log group](assets/week-6/created-log-group.png)

Created custom roles:

![Created roles](assets/week-6/created-roles.png)

Set up load balancer:
![Load balancer](assets/week-6/load-balancer.png)

Created cluster:

![Created ESC](assets/week-6/created-esc.png)

Services:

![Ecs service](assets/week-6/ecs-service.png)

Created ECR:

![Created ECR](assets/week-6/created-ecr.png)

Fargate task:

![Backend task](assets/week-6/created-backend-task.png)

And finally, I waited for a long time but my certificates were still pending:

![Created ESC](assets/week-6/certificate-pending.png)

