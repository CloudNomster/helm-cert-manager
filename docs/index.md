# Techdocs for cert-manager

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