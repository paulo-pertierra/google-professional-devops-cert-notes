The tool SRE uses to balance service reliability with the pace of innovation. 

The error budget is  - SLO. 1 - 99.9% = 0.1%

If our service receives 1,000,000 requests in four weeks, a 99.9% availability SLO gives us a budget of 1,000 errors over that period.

---
## Note

Error budgets are useful if you can detect the trend **TOWARDS** it, not after it. Once error budget has exceeded, then reactive measures are done, instead of proactive. Alerts should be on the trend, not the actual budget running out.

## See also

https://sre.google/workbook/error-budget-policy/