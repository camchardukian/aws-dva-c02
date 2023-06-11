# Identity and Access Management (IAM)

IAM is a globally resilient service.

IAM allows us to create 3 different types of identity objects:

- **Users** -- Identities which represent humans or applications that need access to our account.
- **Groups** -- Collection of related users e.g. development team, finance, or HR.
- **Roles** -- Can be used by AWS services, or for granting external access to our account.

IAM policies can be used to ALLOW or DENY access to AWS services, but they have no effect until they are attached to one of the 3 above identity objects.

## Access Keys

An IAM User has 1 username and 1 password. On the other hand, an IAM user can have up to 2 access keys.

Access keys can be created, deleted, or be made active/inactive.

Access keys are made up of two parts:

**Access Key ID** -- This is kind of like a username.

**Secret Access Key** -- This is kind of like a password and is only provided to us by AWS one time.

IAM Users are the only identity that use access keys.
