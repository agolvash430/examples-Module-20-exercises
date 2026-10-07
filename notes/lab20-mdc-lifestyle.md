# Lab 20 — MDC Lifecycle

## Put
MDC.put("customerId", customerId)

## Use
Logger automatically includes the MDC key in each log line for correlation.

## Clear
MDC.clear() at the end of the request thread to avoid leakage.

## Lab 21 boundary
Controller owns MDC lifecycle; service/repo layers must not touch MDC.

## Scope
Pre-lab only.
