The tool SRE uses to balance service reliability with the pace of innovation. 

The error budget is  - SLO. 1 - 99.9% = 0.1%

If our service receives 1,000,000 requests in four weeks, a 99.9% availability SLO gives us a budget of 1,000 errors over that period.

### Types of Failures

Shape of failure for a service is also important consideration. How resilient is business to downtime? Which is worse: constant low rate of fails or occasional full-site outage? Same number of errors but may have vastly different impacts on business.

> Consider a contact management application, and the difference between intermittent failures that cause profile pictures to fail to render, versus a failure case that results in a user’s private contacts being shown to another user. The first case is clearly a poor user experience, and SREs would work to remediate the problem quickly. In the second case, however, the risk of exposing private data could easily undermine basic user trust in a significant way. As a result, taking down the service entirely would be appropriate during the debugging and potential clean-up phase for the second case.



---
## Note

Error budgets are useful if you can detect the trend **TOWARDS** it, not after it. Once error budget has exceeded, then reactive measures are done, instead of proactive. Alerts should be on the trend, not the actual budget running out.


## See also

https://sre.google/workbook/error-budget-policy/