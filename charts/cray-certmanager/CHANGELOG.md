# Change Log

Changes to the `cray-certmanager` chart, indexed by semantic versions.

##v0.8.1

- Enable PodSecurityPolicy so that chart can be upgraded during CSM 1.5 to CSM 1.6 upgrade.

##v0.8.0

- Upgrade cert-manager to v1.12.9

##v0.7.0

- Removed cray-certmanager-init
- Upgrade cert-manager to v1.5.5

##v0.5.0

- Modify wait-jobs.yaml to wait for webhook service to respond to connect requests (CASMSEC-256)

##v0.4.0

- Modifications for Loftsman v1

##v0.3.0

- Bumped to version 0.3.0 after shasta master/1.3 branch event, no change to chart

##v0.2.0:

- Upgrade cert-manager to v0.14.1.
- Remove setup of self-signed ClusterIssuer. See the ``cray-certmanager-issuers`` chart for issuer deployment.
- Updated non-legacy cert-manager CRD due to use of custom webhook service name (see values.yaml)

##v0.1.0:

- Initial release
- Install cert-manager v0.9.1.
- Setup self-signed ClusterIssuer.
