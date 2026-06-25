# Amazon SNS Notification Setup

## Objective

Configure Amazon Simple Notification Service (SNS) to receive email notifications whenever CloudWatch alarms are triggered.

---

## Steps

1. Open Amazon SNS.
2. Create a new SNS Topic.
3. Give the topic a name.
4. Create an Email Subscription.
5. Confirm the subscription from the received email.
6. Attach the SNS Topic to CloudWatch Alarms.

---

## Notification Flow

```
CloudWatch Alarm
        │
        ▼
Amazon SNS Topic
        │
        ▼
Email Subscription
        │
        ▼
Administrator Email
```

---

## Result

Whenever a CloudWatch alarm enters the ALARM state, an email notification is automatically sent to the subscribed email address.
