# AWS Monitoring and Alerting using CloudWatch

## Project Overview

This project demonstrates how to configure monitoring and alerting for Amazon EC2 instances and an Elastic Load Balancer (ELB) using Amazon CloudWatch and Amazon SNS.

The objective is to monitor important performance metrics, create alarms for critical events, and receive email notifications whenever thresholds are exceeded.

---

## AWS Services Used

- Amazon EC2
- Elastic Load Balancer (ELB)
- Amazon CloudWatch
- Amazon SNS

---

## Features

- CloudWatch Dashboard with EC2 and ELB metrics
- CloudWatch Alarms for critical events
- Email notifications using Amazon SNS
- Real-time monitoring of application performance

---

## Project Architecture

```
User
   │
   ▼
Elastic Load Balancer
   │
   ▼
EC2 Instance(s)
   │
   ▼
CloudWatch Metrics
   │
   ▼
CloudWatch Alarms
   │
   ▼
Amazon SNS
   │
   ▼
Email Notification
```

---

## Repository Structure

```
AWS-Monitoring-and-Alerting/
│
├── README.md
├── cloudwatch-dashboard.md
├── cloudwatch-alarms.md
├── sns-notification.md
└── LICENSE
```

---

## Outcome

Successfully configured monitoring and alerting for AWS infrastructure using CloudWatch dashboards, CloudWatch alarms, and Amazon SNS notifications.
