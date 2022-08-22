# Adding a Registry Entry

To add a new AnonCreds Objects Methods Registry entry please:

- Review the [Contributions policy](Contributing.md) for this repository.
- Add a new registry entry by following these steps:
  - Fork this repository.
  - Copy the [`registry/method_template.md`](registry/method_template.md) file
    to a new file in the `registry` folder, named as appropriate for the new
    registry entry.
  - Update the new file as appropriate for the AnonCreds Objects Methods
    Registry entry you are adding.
  - Update the [`specs.json`](./specs.json) file to include your entry in the
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

## Repository Issues and Updates

If you have any questions, concerns or comments, please submit an Issue to this
repository. If you see anything else in this repository that you think should be
changed please submit a pull request.

See the [Governance](./Governance.md) document for information on how issues in,
and pull requests to, this repository, are processed Registry entries are
processed.

## Testing your Edits Locally

Full guidance for using Spec-Up is in its
[repository](https://github.com/decentralized-identity/spec-up). The short
version of the instructions to render this specification locally while you are
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
