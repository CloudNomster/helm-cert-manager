# Techdocs for cert-manager

## There are two ClusterIssuers in cluster

- For domain "*.maximillian.se
- ClusterIssuers "letsencrypt-staging" and "letsencrypt-prod"

## Staging and testing certs

For testing certifiactes annotate your gateway with:
```
cert-manager.io/cluster-issuer: letsencrypt-staging
```

## Production certs

...and for production cert annotate with:
```
cert-manager.io/cluster-issuer: letsencrypt-prod
```