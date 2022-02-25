# GraphQLIntrospectionScanner
It is obvious... A GraphQL Introspection Query Scanner. If it returns code 200 with the queries, it means the server has improper access control.
# Impact
With this queries an attacker can perform malicious queries, that can read and write data to the server.
If you get creative, you might find a query that can trigger XSS, SQL injection or even an RCE!
