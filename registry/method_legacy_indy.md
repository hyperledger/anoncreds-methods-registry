### Hyperledger Indy Legacy AnonCreds Method

The Hyperledger Indy Legacy AnonCreds method is the mechanism implemented in
early Hyperledger Indy instances, prior to the implementation of `did:indy`
support. It is unique in this registry in that its identifiers are **not** URIs,
but instead are as defined by the original open source developers of Indy. This
method is deprecated and issuers using Hyperledger Indy ledgers are recommended
to use the [`did:indy` AnonCreds
method](#didindy-anoncreds-method) wherever possible.

- Status: Deployed
- Verifiable Data Registry: Hyperledger Indy instances
- Contact Name: Stephen Curran
- Contact Email: stephen.curran@sovrin.org
- Contact Website: [Hyperledger Indy documentation](https://hyperledger-indy.readthedocs.io)
- Specification: Details can be found in [Hyperledger Indy documentation on
  registering/retrieving AnonCreds
  objects](https://hyperledger-indy.readthedocs.io/projects/node/en/latest/requests.html#requests)
