# Eradication

The underlying SQL Injection weakness was addressed using a prepared SQL statement and parameter binding.

The protected implementation separates SQL structure from user-supplied data.

The secure implementation uses:

- `prepare()`
- `bindValue()`
- `execute()`

This addresses the vulnerable pattern of directly incorporating user-controlled input into the SQL query.
