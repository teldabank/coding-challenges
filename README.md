# ~ coding challenges

## README
Solutions should provide a README including the following items:

- Breif description of the solution.
- Reasoning behind your technical decisions.
- Trade-offs made, if any.
- Example usage snippet(s).
- Possible future improvements.

## Cron scheduler
Implement an in-process cron scheduler that accepts a job spec to be executed periodically. Clients should be able to specify:

- A single run expected interval, e.g. `30m`.
- Scheduling frequency, e.g. `1hr` for a job that should run every one hour.
- The job implementation, e.g. a function.

Solutions must:
- Be able to execute multiple jobs concurrently.
- Include tests.
- Be in one of the following langauges:
  - Go
  - Java
  - Python
  - C++
  - Ruby
  - JavaScript
