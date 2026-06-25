# CloudWatch Alarms

## Objective

Configure alarms to detect abnormal resource usage and notify administrators immediately.

---

## Configured Alarms

### High CPU Utilization

- Metric: CPUUtilization
- Threshold: Greater than 80%
- Evaluation Period: 5 Minutes
- Action: Send SNS Notification

---

### High ELB Latency

- Metric: Target Response Time
- Threshold: Greater than 1 Second
- Evaluation Period: 5 Minutes
- Action: Send SNS Notification

---

### High Network Traffic

- Metric: Network In
- Threshold: Custom Threshold
- Evaluation Period: 5 Minutes
- Action: Send SNS Notification

---

### Unhealthy Hosts

- Metric: UnHealthy Host Count
- Threshold: Greater than 0
- Evaluation Period: 5 Minutes
- Action: Send SNS Notification

---

## Result

CloudWatch alarms were successfully configured to detect performance issues and trigger alerts automatically.
