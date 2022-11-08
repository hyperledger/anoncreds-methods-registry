## Governance

This registry is managed by the [AnonCreds Specification Working
Group](https://github.com/hyperledger). The contents of the registry is
maintained in a [GitHub
repository](https://github.com/hyperledger/anoncreds-methods-registry)
and managed through a pull request submission, review and approval process. The
details of how pull requests are managed is outlined in this Governance section
of the registry.

### Roles

- The **[AnonCreds Specification Working
Group](https://github.com/hyperledger)** is the governing authority over this
repository. Its members collaborate to approve and merge pull requests that
result in changes to the Registry and the repository.

- **Editors** are individuals delegated by the [AnonCreds Specification Working
Group](https://github.com/hyperledger) to process issues and pull requests
according to the rules defined in the [Pull Request
Handling](#pull-request-handling) section of this document. Editors are given
[GitHub Maintain and Admin
roles](https://docs.github.com/en/organizations/managing-access-to-your-organizations-repositories/repository-roles-for-an-organization#repository-roles-for-organizations)
in the repository to manage their work.

- **Implementers** are individuals or organizations that add their AnonCreds
  method to the registry. Implementers MUST follow the guidelines in the
  [Adding a Registry Entry](#adding-a-registry-entry) documentation in
  submitting pull requests to add or update their method.

- **Contributors** are individuals that submit pull requests that propose
changes to the registry or any part of the repository that is the source of the
registry. Anyone with a GitHub account can be a contributor.

- **Readers** are individuals that read the registry and use the information
there in to move forward their use of AnonCreds.

### Types of Content

There are two types of content in the source repository for the registry:

- The entries in the [AnonCreds Methods Registry](#registry).
  - The content of the entries are managed by the implementers of specific
    AnonCreds methods.
  - The format of the entries MUST adhere to the guidelines defined in the
    [Method
    Template](https://github.com/hyperledger/anoncreds-methods-registry/blob/main/registry/method_template.md),
as defined by the [AnonCreds Specification Working
Group](https://wiki.hyperledger.org/display/ANONCREDS/AnonCreds+Specification+Working+Group).

- All other content in the registry and [registry
  repository](https://github.com/hyperledger/anoncreds-methods-registry)
  - Such content is governed by the [AnonCreds Specification Working
Group](https://wiki.hyperledger.org/display/ANONCREDS/AnonCreds+Specification+Working+Group), and
    includes things like this Governance section of the registry, the format of
    the method entries, how the registry is published, and so on.
    - Anything about the management of the registry may be changed through an
      update to this type of content.

### Pull Request Handling

The [AnonCreds Specification Working
Group](https://wiki.hyperledger.org/display/ANONCREDS/AnonCreds+Specification+Working+Group) MUST approve all changes to be merged
into the registry (additions, updates and deletions) and to the rules for the
management (governance) of the registry.

The [AnonCreds Specification Working Group](https://wiki.hyperledger.org/display/ANONCREDS/AnonCreds+Specification+Working+Group) has
delegated to the Editors the authority to merge pull requests of any [type of
content](#types-of-content) as follows:

- Based on an explicit vote of the [AnonCreds Specification Working
Group](https://wiki.hyperledger.org/display/ANONCREDS/AnonCreds+Specification+Working+Group) to merge the pull request; or
- When, in the judgement of the Editors, the change is simple editorial update
  that improves the content of any type; or
- When the pull request is to add or update a Registry method entry, and, in the
  judgement of the Editors,
  - the entry adheres to the registry entry guidelines, and
  - the links in the registry entries resolve to relevant content (e.g. the
    specification of the method), and
  - there is some evidence that the submitter is related or sufficiently
    familiar with the work being done on the method.

The [AnonCreds Specification Working Group](https://wiki.hyperledger.org/display/ANONCREDS/AnonCreds+Specification+Working+Group) has
delegated to the Editors the authority to cancel pull requests of either type of
content as follows:

- Based on an explicit vote of the [AnonCreds Specification Working
Group](https://wiki.hyperledger.org/display/ANONCREDS/AnonCreds+Specification+Working+Group) to cancel the pull request; or
- When, in the judgement of the Editors, the change is spam or a mistake, or
- When, in the judgement of the Editors, the change is a simple editorial update
  that is either incorrect or does not improve the content

The [AnonCreds Specification Working Group](https://wiki.hyperledger.org/display/ANONCREDS/AnonCreds+Specification+Working+Group) has
delegated to the Editors the authority to raise (for discussion or vote) to the
[AnonCreds Specification Working Group](https://wiki.hyperledger.org/display/ANONCREDS/AnonCreds+Specification+Working+Group) any
other pull requests. Prior to the raising of a pull request to the [AnonCreds
Specification Working Group](https://wiki.hyperledger.org/display/ANONCREDS/AnonCreds+Specification+Working+Group) for processing,
the Editors (and any other contributor) may work with the submitter of the pull
request to clarify and/or improve the pull request such that it fits in the
categories above for merging or cancellation.
