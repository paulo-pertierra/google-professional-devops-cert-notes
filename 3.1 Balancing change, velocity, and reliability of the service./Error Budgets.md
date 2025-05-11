The tool SRE uses to balance service reliability with the pace of innovation. 

The error budget is  - SLO. 1 - 99.9% = 0.1%

If our service receives 1,000,000 requests in four weeks, a 99.9% availability SLO gives us a budget of 1,000 errors over that period.

### Types of Failures

Shape of failure for a service is also important consideration. How resilient is business to downtime? Which is worse: constant low rate of fails or occasional full-site outage? Same number of errors but may have vastly different impacts on business.

> Consider a contact management application, and the difference between intermittent failures that cause profile pictures to fail to render, versus a failure case that results in a user’s private contacts being shown to another user. The first case is clearly a poor user experience, and SREs would work to remediate the problem quickly. In the second case, however, the risk of exposing private data could easily undermine basic user trust in a significant way. As a result, taking down the service entirely would be appropriate during the debugging and potential clean-up phase for the second case.

### Motivation for Error Budgets

There might be an increasing tension between product development and SRE because one wants features the other wants reliability, so there are informally agreed upon actions for the below, but we need a factual, measurable metric instead of hope or politics or fear. 

***Data-driven decision making*** is very important in SRE.

#### Software fault tolerance

How hardened do we make the software to unexpected events? Too little, and we have a brittle, unusable product. Too much, and we have a product no one wants to use (but that runs very stably).

#### Testing

Again, not enough testing and you have embarrassing outages, privacy data leaks, or a number of other press-worthy events. Too much testing, and you might lose your market.

#### Push frequency

Every push is risky. How much should we work on reducing that risk, versus doing other work?

#### Canary duration and size

It’s a best practice to test a new release on some small subset of a typical workload, a practice often called _canarying_. How long do we wait, and how big is the canary?

Usually, preexisting teams have worked out some kind of informal balance between them as to where the risk/effort boundary lies. Unfortunately, one can rarely prove that this balance is optimal, rather than just a function of the negotiating skills of the engineers involved. Nor should such decisions be driven by politics, fear, or hope. (Indeed, Google SRE’s unofficial motto is "Hope is not a strategy.") Instead, our goal is to define an objective metric, agreed upon by both sides, that can be used to guide the negotiations in a reproducible way. The more data-based the decision can be, the better.

---
## Note

Error budgets are useful if you can detect the trend **TOWARDS** it, not after it. Once error budget has exceeded, then reactive measures are done, instead of proactive. Alerts should be on the trend, not the actual budget running out.


## See also

https://sre.google/workbook/error-budget-policy/