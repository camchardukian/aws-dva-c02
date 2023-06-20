# Service-linked Roles

A service-linked role is a special type of IAM role that is linked directly to an AWS service.

A service-linked role can’t be deleted until it’s no longer used within that AWS service.

The ARN for a service-linked role includes a service principal, such as `SERVICE-NAME.amazonaws.com`.

We should not try to guess this service principal because it is case sensitive and the format can vary across AWS services.
