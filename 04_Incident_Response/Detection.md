# Detection

Following the controlled SQL Injection activity, Apache access logs were reviewed.

Requests targeting:

`/dvwa/vulnerabilities/sqli/`

were identified.

The recorded requests originated from the local laboratory source address.

A filtered log review also identified a UNION-based SQL Injection indicator.

## Important Evidence Distinction

The Apache access log records the HTTP request.

The classification of the request as SQL Injection was established by correlating:

1. The server log
2. The DVWA application behavior
3. The vulnerable source code
