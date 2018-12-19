### the plan

Let's encrypt uses google dns, this should switch fast.

1. Set TTL of dnsrecords to 1 min (done)
2. Set maintenance deployment in new cluster on nba-maintenance.k2.k8s.naturalis.nl (done)
3. Set new redirect all to maintenance on old cluster (done)
4. Update DNS in transip (done)
5. Check google for dns change (done)
6. Update dns records in new deloyment (done)
7. Set redirects in old cluster and let is stay there for 48 hours (done)
8. Decommision old cluster

