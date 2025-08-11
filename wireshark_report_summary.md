# Wireshark Report Summary

## Protocols Observed
- **DNS**: Domain name resolution queries and responses.
- **TCP**: Three-way handshake and HTTP communication.
- **HTTP**: GET requests to websites.

## Observations
- DNS queries resolved domain names successfully.
- TCP handshake completed without issues.
- HTTP traffic included standard GET requests.

## Possible Risks
- If unencrypted HTTP is used, sensitive data could be intercepted.
- Open ports visible from capture could be exploited.

## Recommendations
- Prefer HTTPS over HTTP.
- Restrict unnecessary open ports.
- Monitor DNS queries for unusual activity.
