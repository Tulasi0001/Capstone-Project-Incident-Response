# Incident Analysis

The incident was analyzed using three evidence sources.

## Application Evidence

The DVWA application demonstrated unauthorized database output during the vulnerable-state SQL Injection test.

## Server Log Evidence

Apache recorded requests targeting the SQL Injection endpoint.

## Source-Code Evidence

The vulnerable implementation directly incorporated user-controlled input into the SQL query.

## Correlation

Suspicious Request
↓
Vulnerable Application Behavior
↓
SQL Injection
↓
Unauthorized Database Output

This correlation established the nature and root cause of the simulated incident.
