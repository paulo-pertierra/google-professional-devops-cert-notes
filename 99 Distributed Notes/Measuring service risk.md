Identify an objective metric.

Sometimes, time-based availability isn't very good, since we may be exposing our service distributed, so fault isolation is harder to do. Instead, we measure in terms of request success rate. **Aggregate availability** shows how yield-based metric is calculated over a rolling window.

availability = successful requests / total requests.
