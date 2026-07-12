# Vapor
A secure, RAM-only ephemeral messaging app.

## Security Architecture
- **Ephemeral Storage:** Data is hosted in a volatile Valkey relay.
- **E2EE:** Messages are encrypted client-side using [Library Name].
- **Zero-Knowledge:** No persistent user accounts; sessions are managed via temporary IDs.