- User-Agent is in risk of being intercepted by middle man attacks, leading to redirect all
requests in HTTP forms, pointing to HTTPS addresses due to HTTP
being the default communications between the UserAgent and the host.
- HSTS mitigates this risk by forcing HTTPS requests between
UserAgents and the host, siginificantly decreasing the chances of users
being attacked.
- `Strict-Transport-Security: max-age=31536000; includeSubDomains`
