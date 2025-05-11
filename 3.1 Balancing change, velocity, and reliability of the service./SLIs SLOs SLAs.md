SRE begins with the idea that availability is prerequisite for success. In SRE terms, defines whether a system is able to fulfill its intended function at a point in time.

If you’re building a system from scratch, make sure that SLIs and SLOs are part of your system requirements. If you already have a production system but don’t have them clearly defined, then that’s your highest priority work.

## SLI - Service Level Indicators

A carefully selected monitoring metrics that measure one aspect of a service's reliability.

A direct measurement of a service's behavior: frequency of successful probes in the system. 

Close linear relationship to user experience of reliability

Number of good events / Valid events
### SLI Categorization

#### [[The Four Golden Signals]]

## SLO - Service Level Objectives

Precise numerical target for system availability.

**Important:** define the lowest level of reliability that is acceptable for users of each service, then state it as SLO. Every service should have availability SLO. Without it, team and stakeholders cant make principled judgments for whether velocity or reliability is prioritize.

Combines SLI with target reliability, for example 99.9%, 99.99%, etc..., per month? per year?

SLO should be SMART
- Specific
- Measurable
- Achievable
- Relevant
- Time-bound

Should have concrete, well-documented consequences. E.g. reduce rate of change, and more engineering effort towards eliminating risks

## SLA - Service Level Agreement

Minimum level of downtime that is promised to provide to customers. If this agreement is broken, compensate consumers.

Alerting thresholds are **much** higher than minimum documented SLA.

This might be expressed in availability numbers: for instance, an availability SLO of 99.9% over one month, with an internal availability SLO of 99.95%. Alternatively, the SLA might only specify a subset of the metrics that make up the internal SLO.

---
## What should we do?

All parts of the business must agree that this is an accurate measure of *UX*! They should agree that this should be used as a **primary driver for decision making**.

![[Pasted image 20250508234212.png]]

