### `did:indy` AnonCreds Objects Method

The `did:indy` AnonCreds objects method uses registration and resolution methods
implemented in later Hyperledger Indy clients (such as those based on [Indy
VDR](https://github.com/hyperledger/indy-vdr)). The `did:indy` AnonCreds objects
identifiers are URIs (to be precise DID URLs with path elements to identify the
specific AnonCreds object), evolved from the identifiers used initially in
Hyperledger Indy. The objects are registered and resolved using the same tools
as the [Hyperledger Indy AnonCreds objects
method](#hyperledger-indy-anoncreds-object-method), with the primary difference
being the AnonCreds objects identifiers within the objects themselves.

- Status: Not deployed
- Verifiable Data Registry: Hyperledger Indy instances
- Contact Name: Stephen Curran
- Contact Email: swcurran@cloudcompass.ca
- Contact Website: [https://github.com/hyperledger/indy-did-method](https://github.com/hyperledger/indy-did-method)
- Specification: [https://hyperledger.github.io/indy-did-method/#other-indy-ledger-object-identifiers](https://hyperledger.github.io/indy-did-method/#other-indy-ledger-object-identifiers)
