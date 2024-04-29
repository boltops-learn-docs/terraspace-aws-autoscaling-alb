<!-- note marker start -->
NOTE: This repo contains only the documentation for the private BoltsOps repo code.
Original file: https://github.com/boltops-learn/terraspace-aws-autoscaling-alb/blob/master/README.md
The docs are publish so they are available for interested subscribers.
For access to the source code, you can become a BoltOps subscriber.
See: https://learn.boltops.com

<!-- note marker end -->

# Terraspace AutoScaling Application Load Balancer ALB Example

[![BoltOps Badge](https://img.boltops.com/boltops/badges/boltops-badge.png)](https://www.boltops.com)

This contains example code to deploy:

* AutoScaling Group
* Applcation Load Balancer

It uses modules from the Terraform Registry via the [Terrafile](Terrafile):

* [terraform-aws-modules/alb](https://registry.terraform.io/modules/terraform-aws-modules/alb/aws/latest)
* [terraform-aws-modules/autoscaling](https://registry.terraform.io/modules/terraform-aws-modules/autoscaling/aws/latest)

## Env Vars

You should configure these env vars:

* AWS_REGION

## Deploy

To deploy:

    terraspace up autoscaling-alb

## Video

[![Watch the video](https://uploads-learn.boltops.com/ggd4pc0710t9p1wueshucafakhtl)](https://learn.boltops.com/courses/terraspace-aws/lessons/terraspace-aws-autoscaling-with-application-load-balancer-alb)

Note: Premium video content requires a subscription.