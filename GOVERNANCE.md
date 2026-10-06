# OpenLint Governance

**Status: proposed.** This is a starting point to argue with in [the discussions](https://github.com/orgs/openlint/discussions). Nothing here is final until the maintainers ratify it.

OpenLint is a community project. Governance exists so that it doesn't depend on any one person or company.

## Principles

1. **Decided in public.** Decisions happen in GitHub discussions, issues and pull requests, or at recorded [office hours](https://openlint.org/meetings/). If it was only said in a DM, it wasn't decided.
2. **Governance is data.** Who maintains what lives in [`MAINTAINERS.yaml`](MAINTAINERS.yaml) and changes through pull requests like anything else.
3. **No process before there are people to run it.** Governance grows in stages, triggered by facts rather than dates.
4. **No specification change surprises an implementer.** Changes to what a valid ruleset is get a longer review window, and known implementers are told directly.

## The three areas

| Area | Covers |
| -- | -- |
| **Specification** | The ruleset format, its normative text, and the conformance tests |
| **Toolbox** | [openlint/openlint](https://github.com/openlint/openlint), the editor extension, and the CI/CD packages |
| **Administration** | Governance, the website, funding, licensing, trademark, and the Code of Conduct |

People can maintain one area, or several.

## Roles

- **Contributor.** Anyone who takes part: code, writing, reviewing, testing, or showing up to office hours. Non-code work counts toward every role.
- **Maintainer.** Has merge rights in one or more areas, and a say in decisions there. Listed in `MAINTAINERS.yaml`.
- **Steward.** Accountable when nobody else is, and the tie-break of last resort. Kin Lane holds this role until there is a permanent home.

## How work happens

**Discussion → issue → pull request.** Ideas start as a [discussion](https://github.com/orgs/openlint/discussions). Once there are people who care about an idea, it becomes issues. The work happens in pull requests.

**Lazy consensus.** A proposal stays open for at least 7 days. Silence is agreement. Any maintainer can ask for the window to be extended once. Changes to the specification get 14 days.

**Two maintainers.** Once an area has two maintainers, no change in that area merges on one person's approval. Each repository sets its own review rules within this.

**Use of AI.** Agreed per pull request with the people involved, and stated in the pull request. AI isn't used to write issues. *(Proposed; discussion to come.)*

## Stages

- **Now.** The steward, plus maintainers added by asking in a discussion or at office hours, approved by lazy consensus.
- **At 3 or more maintainers.** At least 3 and at most 7 maintainers per area. If an area drops below 3, we say so publicly. No more than half of an area's maintainers may share an employer. Consensus comes first; if that fails, maintainers vote. Every decision is recorded in the repository.
- **With a permanent home.** OpenLint has [applied to Open Source Europe](https://opencollective.com/openlint) as its home and fiscal host. Once accepted, this document is updated to fit, and the steward role is reviewed. The specification and its reference implementation stay together, whatever the home.

## Conduct

Everyone follows the [Code of Conduct](https://github.com/openlint/.github/blob/main/CODE_OF_CONDUCT.md). Reports go to [conduct@openlint.org](mailto:conduct@openlint.org). Until the maintainers form a Code of Conduct Committee, the steward handles them.

## Changing this document

By pull request, with the 14-day window used for specification changes.

---

*Adapted from the [Spotlight governance proposal](https://github.com/api-commons/spotlight-spec/blob/main/governance.md), which draws on the governance of [OpenAPI](https://github.com/OAI/OpenAPI-Specification/blob/main/GOVERNANCE.md), [AsyncAPI](https://github.com/asyncapi/community/blob/master/docs/020-governance-and-policies/GOVERNANCE.md) and [JSON Schema](https://github.com/json-schema-org/community/blob/main/GOVERNANCE.md).*
