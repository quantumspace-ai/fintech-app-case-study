# Portfolio evidence matrix

| Competency | Evidence available in the private implementation | Public boundary |
| --- | --- | --- |
| API design | Wallet API and tenant-scoped Connect contracts | Architecture only |
| PostgreSQL | Transactional ledger and reservation lifecycle | No schema or migration files |
| Authentication | Authenticated sessions and role gates | No auth implementation |
| Payments | Successful BLIK pay-in through Tpay sandbox, including signed notification validation and exactly-once ledger settlement; Stripe sandbox flows | No provider adapter code |
| Webhooks | Signature checks and idempotent settlement | No endpoints or secrets |
| MCP | Tenant-scoped tool catalogue and proposed actions | Contract description only |
| Testing | Unit, integration, authorization, and build gates | Verified summary only |
| CI/CD | Repository-wide quality workflow and controlled deployment branch | No deployment configuration |
| Security | Minor units, encryption boundaries, least privilege, fail-closed readiness | Non-exploitable overview |

Claims in this repository are limited to evidence verified in the private
source repository on 28 July 2026. External provider sandbox verification is
not equivalent to production or regulatory readiness.
