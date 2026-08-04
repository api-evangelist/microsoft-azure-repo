# Azure Repos (microsoft-azure-repo)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Azure Repos is a set of version control tools that you can use to manage your code. Whether your software project is large or small, using version control as soon as possible is a good idea.

**APIs.json:** [https://azure.microsoft.com/en-us/services/devops/repos/](https://azure.microsoft.com/en-us/services/devops/repos/)

## Tags

- DevOps
- Git
- Repositories
- Source Control
- TFVC
- Version Control

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-19

## APIs

### Azure DevOps Services REST API - Git

REST API for Git repositories in Azure Repos, including repositories, commits, pull requests, branches, and more.

- **Human URL:** [https://docs.microsoft.com/en-us/rest/api/azure/devops/git/](https://docs.microsoft.com/en-us/rest/api/azure/devops/git/)
- **Base URL:** `https://dev.azure.com/{organization}/{project}/_apis/git`

#### Tags

- Branches
- Commits
- Git
- Pull Requests
- Repositories

#### Properties

- [Documentation](https://docs.microsoft.com/en-us/rest/api/azure/devops/git/)
- [OpenAPI](https://github.com/MicrosoftDocs/vsts-rest-api-specs/blob/master/specification/git/7.1/git.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://docs.microsoft.com/en-us/azure/devops/integrate/get-started/authentication/authentication-guidance)
- [Rate Limits](https://docs.microsoft.com/en-us/azure/devops/integrate/concepts/rate-limits)
- [Reference](https://learn.microsoft.com/en-us/rest/api/azure/devops/git/?view=azure-devops-rest-7.1)
- [Quickstart](https://learn.microsoft.com/en-us/azure/devops/repos/git/gitquickstart?view=azure-devops)
- [Client  Libraries](https://learn.microsoft.com/en-us/azure/devops/integrate/concepts/dotnet-client-libraries?view=azure-devops)
- [Postman Collection](collections/azure-repo-git-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-repo-git-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure DevOps Services REST API - TFVC

REST API for Team Foundation Version Control (TFVC) repositories in Azure Repos.

- **Human URL:** [https://docs.microsoft.com/en-us/rest/api/azure/devops/tfvc/](https://docs.microsoft.com/en-us/rest/api/azure/devops/tfvc/)
- **Base URL:** `https://dev.azure.com/{organization}/{project}/_apis/tfvc`

#### Tags

- Changesets
- Shelvesets
- TFVC
- Version Control

#### Properties

- [Documentation](https://docs.microsoft.com/en-us/rest/api/azure/devops/tfvc/)
- [OpenAPI](https://github.com/MicrosoftDocs/vsts-rest-api-specs/blob/master/specification/tfvc/7.1/tfvc.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://docs.microsoft.com/en-us/azure/devops/integrate/get-started/authentication/authentication-guidance)
- [Reference](https://learn.microsoft.com/en-us/rest/api/azure/devops/tfvc/?view=azure-devops-rest-7.1)
- [Rate Limits](https://learn.microsoft.com/en-us/azure/devops/integrate/concepts/rate-limits)
- [Client  Libraries](https://learn.microsoft.com/en-us/azure/devops/integrate/concepts/dotnet-client-libraries?view=azure-devops)
- [Postman Collection](collections/azure-repo-git-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-repo-git-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure DevOps Services REST API - Policy

REST API for managing repository policies including branch policies, required reviewers, and build validation.

- **Human URL:** [https://docs.microsoft.com/en-us/rest/api/azure/devops/policy/](https://docs.microsoft.com/en-us/rest/api/azure/devops/policy/)
- **Base URL:** `https://dev.azure.com/{organization}/{project}/_apis/policy`

#### Tags

- Branch Policy
- Build Validation
- Code Review
- Policy

#### Properties

- [Documentation](https://docs.microsoft.com/en-us/rest/api/azure/devops/policy/)
- [OpenAPI](https://github.com/MicrosoftDocs/vsts-rest-api-specs/blob/master/specification/policy/7.1/policy.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Reference](https://learn.microsoft.com/en-us/rest/api/azure/devops/policy/?view=azure-devops-rest-7.1)
- [Authentication](https://learn.microsoft.com/en-us/azure/devops/integrate/get-started/authentication/authentication-guidance?view=azure-devops)
- [Rate Limits](https://learn.microsoft.com/en-us/azure/devops/integrate/concepts/rate-limits)
- [Postman Collection](collections/azure-repo-git-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-repo-git-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://learn.microsoft.com/en-us/azure/devops/repos/?view=azure-devops)
- [Getting Started](https://docs.microsoft.com/en-us/azure/devops/repos/get-started/)
- [Documentation](https://learn.microsoft.com/en-us/azure/devops/repos/git/?view=azure-devops)
- [Authentication](https://learn.microsoft.com/en-us/azure/devops/integrate/get-started/authentication/authentication-guidance?view=azure-devops)
- [Pricing](https://azure.microsoft.com/en-us/pricing/details/devops/azure-devops-services/)
- [Rate Limits](https://learn.microsoft.com/en-us/azure/devops/integrate/concepts/rate-limits)
- [Status Page](https://status.dev.azure.com/)
- [Terms of Service](https://azure.microsoft.com/en-us/support/legal/)
- [Privacy Policy](https://privacy.microsoft.com/en-us/privacystatement)
- [Changelog](https://learn.microsoft.com/en-us/azure/devops/release-notes/features-timeline-released)
- [Blog](https://devblogs.microsoft.com/devops/)
- [Support](https://azure.microsoft.com/en-us/support/devops/)
- [Console](https://dev.azure.com)
- [Sign Up](https://learn.microsoft.com/en-us/azure/devops/repos/get-started/sign-up-invite-teammates?view=azure-devops)
- [Website](https://azure.microsoft.com/en-us/services/devops/repos/)
- [S D Ks](https://learn.microsoft.com/en-us/azure/devops/integrate/concepts/dotnet-client-libraries?view=azure-devops)
- [Community](https://developercommunity.visualstudio.com/AzureDevOps)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/azure-devops)
- [GitHub Organization](https://github.com/MicrosoftDocs/vsts-rest-api-specs)
- [YouTube](https://www.youtube.com/@AzureDevOps)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
