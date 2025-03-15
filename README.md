# M.I.T.O. Treaties
This repository contains all present and past treaties, agreements, and rules.

## Repository structure
Files under the `de-jure/` directory represent documents that are currently valid.

Files under the `repealed/` directory represent documents that were valid in the past and that have been repealed.

Files under the `discussed/` directory represent documents that never came into effect.

Files in the root directory and under the `.github/` directory are used for repository administration and are not subject to MITO legislation.

## Management
MITO documents in this repository are created, updated, and removed mainly through _Trade Enhancement Proposals_ (TEPs). Trade Enhancement Proposals are not required to alter ordinary operations (i.e., altering the root directory, altering the `./github` directory, altering the `discussed/` directory, or altering the configuration of this repository).

### Submiting Trade Enhancement Proposals
TEPs can be submitted via a Pull Request to this repository.

#### Title
The title of said PUll Request shall start with "TEP: " followed by one of the proposal types listed below:
- Propose (For new documents)
- Ammend (To ammend an existing document)
- Repeal (To repeal an existing document or ammendment)
The title of the Pull Request hsall also detail what document is being altered:
- Propose TEPs shall include the name of the new document (not the file name) using the format `"<Name>"`
- Ammend TEPs shall include the number of the TEP to be ammended using the format `TEP-<Number>`
- Repeal TEPs shall include the number of the TEP to be repealed using the format `TEP-<Number>`

##### Examples
- TEP: Propose "Minecraft Agreement on Tariffs and Trade"
- TEP: Ammend TEP-1
- TEP: Repeal TEP-1

#### Body
The body of the Pull Request may include the number of a previous TEP on which the current one depends. This number, if present, shall be placed following the `Depends on: ` prefix using the format `TEP-<Number>`.

#### Example
- TEP-3:
```
TEP: Repeal TEP-1
Depends on: TEP-2
```
- TEP-2:
```
TEP: Propose "New Minecraft Agreement on Tariffs and Trade"
```

### Evaluation of Trade Enhancement Proposals
The process of evaluation of Trade Enhancement Proposals is regulated by the MITO. The maintainers of this repository may only unilaterally reject TEPs that depend on other TEPs that have been rejected by the MITO or TEPs that violate these contribution guidelines.

## Document structure
See [TEMPLATE.md](TEMPLATE.md).
