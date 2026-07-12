# Vapor
A secure, RAM-only ephemeral messaging app.

## Security Architecture
- **Ephemeral Storage:** Data is hosted in a volatile Valkey relay in RAM.
- **E2EE:** Messages should be encrypted client-side.
- **Zero-Knowledge:** No persistent user accounts; sessions are managed via temporary IDs until I add full user accounts.
