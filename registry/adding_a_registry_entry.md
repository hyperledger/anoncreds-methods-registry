## Adding a Registry Entry

To add a new AnonCreds Objects Methods Registry entry please:

- Review the [Governance](#governance) section of this document that describes
  who can add/update registry entries, how such updates get approved and
  applied.
- Create a pull request in the GitHub repository ([https://github.com/AnonCreds-WG/anoncreds-objects-methods-registry](https://github.com/AnonCreds-WG/anoncreds-objects-methods-registry)) that is the source for generating this webpage, by following these steps:
  - Fork [the repository](https://github.com/AnonCreds-WG/anoncreds-objects-methods-registry).
  - In your local fork, copy the [`registry/method_template.md`](https://github.com/AnonCreds-WG/anoncreds-objects-methods-registry/blob/main/registry/method_template.md) file
    to a new file in the same `registry` folder, named as appropriate for the new
    registry entry, prefix `method_`, and `.md` extension.
  - Update the new file for the AnonCreds Objects Methods
    Registry entry you are adding.
  - Update the [`specs.json`](./specs.json) file to include your entry within the
    list of methods, in alphabetical order.
  - Test your updates as outlined below.
  - Submit a pull request with your changes.

The registry source consists of the markdown files listed in
[specs.json](/specs.json) and found in the [`/registry`](/registry) folder. The
registry is automatically rendered as a webpage (using
[Spec-Up](https://github.com/decentralized-identity/spec-up)) to the `/docs`
folder of the `gh-pages` branch of this repository on each pull request merge
(using a GitHub Action), and then published (using GitHub Pages).

See the [Governance](./Governance.md) document for information on how
additions and updates to the Registry entries are processed.

### Testing your Edits Locally

Full guidance for using Spec-Up is in its
[repository](https://github.com/decentralized-identity/spec-up). The short
version of the instructions to render the registry webpage locally while you are
editing is:

- Install the prerequisites: `node` and `npm`
- Run `npm install` from the root of the repository
- Run `npm run edit` from the root of the repository to render the document with
  live updates to the `docs/index.html` as
  you edit the source files.
  - You can also run `npm run render` to just generate the specification file once.
- Open the rendered file in a browser and refresh to see your updates as you work.
- When you are done, hit `Ctrl-c` to exit the live rendering.

Please test your edits locally before you submit a pull request!
