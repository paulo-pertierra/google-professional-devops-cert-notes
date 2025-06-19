## What it is

Alerting policy has:
- a name - use something descriptive
- one or more conditions
- notifications
- documentation
can be created via CLI, API, or TF. JSON or YAML format.

**Types of alerting policies:**

![[Pasted image 20250619101654.png]]
E.g. alert metrics if latency is long
Log based alerting if specific message occurs in a log. E.g. when human user accesses sec key of service account.

![[Pasted image 20250619102824.png]]
## Related

SLO is heading towards not being met, or service is down, or something needs to be changed.

This is maths.

![[Pasted image 20250619100753.png]]

![[Pasted image 20250619100847.png]]

![[Pasted image 20250619100919.png]]

Imagine 99.9% SLO over 30 days.

![[Pasted image 20250619101057.png]]

Precision inverted correlation to recall

Good strat to increase precision AND recall

![[Pasted image 20250619101128.png]]

Prioritize alerts based on customer impact and SLA!!!
- Involve humans for critical alerts
- Use severity level to assess the priority
- Configure how to triage low and high prio alerts

High prio = Slack, Pub/Sub, PagerDuty, GChat webhook
Low prio = email, ticket management, logged

