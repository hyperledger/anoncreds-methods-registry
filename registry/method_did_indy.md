### `did:indy` AnonCreds Method

The `did:indy` AnonCreds method uses registration and resolution methods
implemented in later Hyperledger Indy clients (such as those based on [Indy
VDR](https://github.com/hyperledger/indy-vdr)). The `did:indy` AnonCreds
identifiers are URIs (to be precise DID URLs with path elements to identify the
specific AnonCreds object type), evolved from the identifiers used in the initial
Hyperledger Indy AnonCreds implementatation. The objects are registered and resolved using the same tools
as the [Hyperledger Indy AnonCreds
method](#hyperledger-indy-legacy-anoncreds-method), with the primary difference
being the AnonCreds identifiers within the objects themselves.

- Status: Not deployed
- Verifiable Data Registry: Hyperledger Indy instances
- Contact Name: Stephen Curran
- Contact Email: swcurran@cloudcompass.ca
- Contact Website: [https://github.com/hyperledger/indy-did-method](https://github.com/hyperledger/indy-did-method)
- Specification: [https://hyperledger.github.io/indy-did-method/#other-indy-ledger-object-identifiers](https://hyperledger.github.io/indy-did-method/#other-indy-ledger-object-identifiers)
