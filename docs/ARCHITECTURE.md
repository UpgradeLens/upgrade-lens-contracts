# Contract architecture

## Responsibility

A release-review tool that compares deployed and candidate contract WASM plus interface metadata and highlights public-interface, storage, and authorization changes.

## Security boundary

Every state-changing operation must authenticate the actor that is allowed to cause
the change. Contract storage is intentionally smaller than the application database.

## Future specification

The generic development contract in this baseline must be replaced with the
project-specific state model before production deployment.
