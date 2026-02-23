---
name: "Labs Project Contribution and Onboarding"
about: To contribute an experimental/exploratory project to FINOS Labs.
title: "[insert project name here] Labs Contribution and Onboarding"
labels: contribution, labs
assignees: maoo, TheJuanAndOnly99
---

# Prerequisites

## Membership Requirement
Please note that only FINOS members can propose new projects. If you're interested in membership, see [here](https://www.finos.org/membership-benefits#become-a-member).
- [ ] I confirm I am contributing on behalf of a **FINOS member organization** (`add organization name`) or I will seek a maintainer from a FINOS member during socialization.

## Understanding the Labs Stage
Projects in FINOS Labs are in an experimental phase and are hosted in the [FINOS Labs GitHub org](https://github.com/finos-labs/).
- [ ] I have reviewed the [Labs Stage Definition](https://community.finos.org/docs/governance/lifecycle-stages/labs).
- [ ] I confirm I have reviewed the [FINOS Software Projects Governance](https://community.finos.org/docs/governance/#open-source-software-projects).
- [ ] I understand that the project must maintain development activity and pass health reviews every six months to avoid archival in accordance to the [Labs ongoing maintenance requirements documentation](/docs/governance/lifecycle-stages/labs#labs-ongoing-maintenance-requirements).

## Legal Compliance
- [ ] I understand that if the project has an existing name and/or logo that has been used in the public domain I will need to review and sign the [Project Contribution Agreement](https://community.finos.org/governance-docs/The.Linux.Foundation.--.Form.of.Trademark.Assignment.20221202.pdf) in order to transfer the IP ownership to the foundation (even if it has not been trademarked).
- [ ] I confirm that any existing material **does not** include any patent or copyright that conflicts with FINOS Governance and bylaws.
- [ ] I understand that project contributions will be checked for [Developer Certificate of Origin (DCO) signatures](https://github.com/finos-labs/project-blueprint/blob/main/CONTRIBUTING.md#developer-certificate-of-origin-dco) and all contributions to the project must be properly signed.

# 1. Describing The Contribution

### Proposed Project Metadata
- **Name:** `enter here proposed project name`
- **Slug:** `enter here proposed project slug (should follow kebab-case naming convention)`
- **Description:** `enter here 1-2 sentence description`

### Business Problem
> Describe the business or technical problem this contribution solves for the financial services industry.

### Proposed Solution
> Describe how this project solves the problem and what the goals are.

### Tentative Roadmap
> Describe the short-term goals. What does success look like for this project?

### Current State
> Summarize the history and current state of the project

### Existing Materials
- [ ] **GitHub/GitLab URL:** `add link if it exists`
- [ ] **Documentation:** `URL or N/A`
- [ ] **Logo:** `Yes/No (Link if yes)`

### Maintainers
| Name | Affiliation | Email Address | Github Username |
| :--- | :--- | :--- | :--- |
| John Example | Example LTD | john@example.com | @johnexample |
| Jane Example | Example LTD | jane@example.com | @janeexample |

### Socialization (Optional)
- [ ] Contribution has been socialized via `community@finos.org`. (Linking to this issue)
- [ ] Open questions from the community have been answered and intrest from the community has been demonstrated.

# 2. Acceptance Review

### Labs Acceptance Requirements
> *To be completed by FINOS staff*
- [ ] Project has a clear use case for the financial services industry and has potential to bring valuae to the FINOS community.
- [ ] Project name/logo comply with [FINOS Trademark Requirements](https://community.finos.org/docs/governance/Software-Projects/contribution#trademark).
- [ ] Project license complies with [FINOS IP Policy](https://community.finos.org/governance-docs/IP-policy.pdf).
- [ ] ** FINOS Staff Approval:** `Approved | Rejected`

# 3. Infrastructure & Onboarding

### Code Transfer
- [ ] Invite `finos-admin` as Admin to the existing repository.
- [ ] Transfer repository to `github.com/finos-labs`.
- [ ] Enable **DCO App**.

### Labs Compliance
- [ ] Project conforms to the [Labs Project Blueprint](https://github.com/finos-labs/project-blueprint)
  - [ ] Add the **FINOS Labs Badge** to the top of the README:
  - [ ] LICENSE, LICENSE.spdx, NOTICE, CONTRIBUTING.md, CODE_OF_CONDUCT.md, and README.md files conform to FINOS requirements (see blueprint).
- [ ] Enable branch protection (Require a pull request before merging).
- [ ] Enable automated dependency updates (e.g., Renovate).

# 4. Announcement
- [ ] Lead maintainer worked with FINOS marketing to send announcement to announce@finos.org once the onboarding has been completed.
