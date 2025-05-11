100% reliability is extremely unrealistic. Stability limits innovation, and how quickly products are delivered to users. 

There are factors beyond our control that might even down our 100% reliability, like cell service for customers.

By balancing reliability and rapid innovation, there is more overall user happiness with features, service, and performance.

2 dimensions of cost.
- The cost of redundant machine/compute resources - self explanatory
- The opportunity cost - engineering resources, devs, engineers, etc. etc.

In SRE, we maintain reliability by: **managing risk**. We are in control. We conceptualize risk as a continuum. We also give equal importance between higher reliability, and identifying appropriate level of tolerance.

### Thoughtful Risk Taking

We seek the reliability as a min and a max. If we are not using the error budget, then we are not innovating. If we are falling behind the error budget, we need to divert our decisions to reliability.


## Cost

Cost is often the key factor in determining the appropriate availability target for a service. Ads is in a particularly good position to make this trade-off because request successes and failures can be directly translated into revenue gained or lost. In determining the availability target for each service, we ask questions such as:

- If we were to build and operate these systems at one more nine of availability, what would our incremental increase in revenue be?
- Does this additional revenue offset the cost of reaching that level of reliability?

To make this trade-off equation more concrete, consider the following cost/benefit for an example service where each request has equal value:

- Proposed improvement in availability target: 99.9% → 99.99%
- Proposed increase in availability: 0.09%
- Service revenue: $1M
- Value of improved availability: $1M * 0.0009 = $900

In this case, if the cost of improving availability by one nine is less than $900, it is worth the investment. If the cost is greater than $900, the costs will exceed the projected increase in revenue.

It may be harder to set these targets when we do not have a simple translation function between reliability and revenue. One useful strategy may be to consider the background error rate of ISPs on the Internet. If failures are being measured from the end-user perspective and it is possible to drive the error rate for the service below the background error rate, those errors will fall within the noise for a given user’s Internet connection. While there are significant differences between ISPs and protocols (e.g., TCP versus UDP, IPv4 versus IPv6), we’ve measured the typical background error rate for ISPs as falling between 0.01% and 1%.

---
## See also

[[Measuring service risk]]

[[Error Budgets]]

