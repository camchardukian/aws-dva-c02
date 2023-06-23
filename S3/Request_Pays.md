# S3 Requester Pays

_Requester Pays_ is a feature that bucket owners can configure on their buckets (it can’t be configured on individual objects).

It should also be noted that this feature doesn’t work with static website hosting or BitTorrent.

When Requester Pays is enabled, requesters pay the cost of the request and the data download from the bucket rather than the bucket owner having to pay.

Whether Requester Pays is enabled or not, the bucket owner will still always be te one to pay the cost of storing the data.

The two conditions for Requester Pays to be successfully carried out are:

1. The requesters are authenticated users.
2. Requesters must add an ‘x-amx-request-payer’ header to their requests to confirm they will be responsible for paying.
