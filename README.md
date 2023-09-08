# HERM Karma Proposals

This repository contains all of people's contributions, whether via Code or via Proof of Generosity.

There is still no defined standard, which, I anticipate, needs to be stipulated so that we can standardize the proposals when Karma-API starts its respective voting blocks.

Therefore, if you open a new proposal to be validated when the system is on the Main Network, you must always consider that a lot can change and you will probably have to update your proposals to follow the pattern of the finalized version.

## Creating a proposal

The first step is actually to have already done your good deed before creating a proposal.

The second step is to open a new Merge Request for this repository with just one file in Markdown.

It must have the following name: {{dd-mm-yyyy/hhmm}} + the title of the proposal in kebab-case, for example: `08-09-2023/1904-page-translation.md`

> You must create a folder if there isn't one, or just include your file there.

And it must follow a template, which follows as an example:

```
### Page Translation

As per the suggestion at the bottom of the [page](https://hermetic.surge) I contributed to the translation of all possible things.

#### Proof of Action:

{{ proof_of_action }}

But I'm not a developer, so I couldn't implement it.

#### Bonus Intention: `0.0000500`
#### Wallet: `0x000000000000000000000000`
```

> Or consider using two Wallets as well, where appropriate.

```
### Page Translation

As per the suggestion at the bottom of the [page](https://hermetic.surge) I contributed to the translation of all possible things.

#### Proof of Action:

{{ proof_of_action }}
{{ url_commit or url_merge_request }}

But I'm not a developer, but in partnership with another user we implemented a flag on the Website capable of changing, therefore translating all available text, with the exception of extenas urls.

#### Bonus Intention: `0.0000500`
#### Wallet: `[0x000000000000000000000000000000000000000, 0x0000000000000000000000000000000000000001]`
```

> The amount will be divided among all accounts on the list.

---

## Expectation

The idea is that after the Karma-API is functional people can vote so they can choose options like:

- Valid
- Invalid
- Valid but Underpriced
- Valid but Overpriced

And Karma will be responsible for stipulating a Bonus based on the answers.