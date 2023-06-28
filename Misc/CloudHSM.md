# CloudHSM

CloudHSM is a true ‘single tenant’ _hardware security module (HSM)_.

KMS is FIPS 140-2 Level 2 compliant overall and level 3 compliant in some areas while CloudHSM is 140-2 level 3 compliant overall.

CloudHSM has no native AWS integration, but it is great for offloading SSL/TLS processing from web servers.

CloudHSM can also be useful for protecting the private keys of an issuing _Certificate Authority (CA)_.
