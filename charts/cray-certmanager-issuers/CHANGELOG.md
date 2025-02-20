# Change Log

Changes to the `cray-certmanager-issuers` chart, indexed by semantic versions.

## v0.8.0

- Upgrade cert-manager to v1.17.0

## v0.7.2

- Update cray-certmanager-issuers by removing docker-kubectl image from values.yaml.
This is no longer needed because the patch script to set issuer secretRef is no longer used with cert-manager v1.12.9.

## v0.7.1

- Upgrade cray-certmanager-issuers to authenticate with kubernetes service accounts for k8s 1.24

## v0.7.0

- Upgrade cert-manager to v1.12.9

## v0.4.0 

- Add common issuer to ceph-rgw namespace (CASMSEC-206)

## v0.2.1

- Add common issuer to sma and spire namespaces (CASMSEC-168)

## v0.2.0

- Refactored issuers to add istio-system common issuer and update vault PKI role mappings (CASMSEC-123)
- Bumped to version 0.2.0 after shasta master/1.3 branch event

## v0.1.0:

- Initial release
- Setup ```services``` namespace, cert-manager issuer for cert-manager 0.14.1 (v1alpha3)
