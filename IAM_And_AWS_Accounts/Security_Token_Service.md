# AWS Security Token Service (STS)

STS generates temporary credentials whenever the `sts:AssumeRole` operation is used.

These credentials DO expire, and they don’t belong to the identity.

`sts:AssumeRole` calls are made by an existing identity. The two types of existing identities are:

- **Internal identities** — Users or roles that were created within our AWS account.
- **External identities** — Users or roles that were created outside of our AWS account. Federation for example allows external users to authenticate with a trusted third-party service (such as Google or Facebook) to gain temporary access to AWS resources using `sts:AssumeRole`.
