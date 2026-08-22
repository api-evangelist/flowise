# Flowise (flowise)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Flowise is an open-source, low-code visual builder for LangChain-based LLM workflows and AI agents. Built on Node.js and TypeScript as a pnpm/Turbo monorepo, Flowise lets developers and non-developers compose chatflows, multi-agent agentflows, RAG pipelines, tools, and assistants on a drag-and-drop canvas, then expose them as REST APIs, embeddable chat widgets, or programmatic SDK calls. The project ships a self-hostable server, a React admin UI, a third-party node component library, an auto-generated Swagger UI, official TypeScript and Python SDKs, an embed widget, and a managed Flowise Cloud offering with metered prediction quotas. Flowise was acquired by Workday in 2025.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/flowise/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/flowise/refs/heads/main/apis.yml)

## Scope

- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Agents
- Agent Workflows
- Artificial Intelligence
- Large Language Models
- Low Code
- Visual Builder
- LangChain
- RAG
- Retrieval Augmented Generation
- Chatbots
- Open Source
- Node.js
- TypeScript

## Timestamps

- **Created:** 2026-05-24
- **Modified:** 2026-05-24

## APIs

### Flowise API

The Flowise REST API exposes the full surface of a Flowise server, covering chatflows, agentflows, assistants, tools, variables, document stores, vector upserts, attachments, feedback, leads, chat messages, upsert history, predictions, and a ping health probe. It is documented as OpenAPI 3.0.3 from a Swagger UI shipped in the `packages/api-documentation` workspace of the FlowiseAI/Flowise monorepo and served at `/api-docs` on the Flowise server. Authentication uses an HTTP Bearer token (an API key generated in the Flowise admin UI). The default base URL is `http://localhost:3000/api/v1` on a self-hosted instance, or the corresponding `/api/v1` path on a Flowise Cloud workspace.

- **Human URL:** [https://docs.flowiseai.com/api-reference](https://docs.flowiseai.com/api-reference)
- **Base URL:** `http://localhost:3000/api/v1`

#### Tags

- Agents
- Agent Workflows
- Artificial Intelligence
- Large Language Models
- Chatflows
- Agentflows
- Assistants
- Tools
- Variables
- Document Stores
- Vector
- Predictions
- Feedback
- Leads
- Chat Messages

#### Properties

- [Documentation](https://docs.flowiseai.com/api-reference)
- [OpenAPI](openapi/flowise-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/flowise.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/flowise.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://docs.flowiseai.com/using-flowise/api-keys)
- [Swagger U I](https://github.com/FlowiseAI/Flowise/tree/main/packages/api-documentation)
- [Prediction](https://docs.flowiseai.com/api-reference/prediction)

## Common Properties

- [Website](https://flowiseai.com/)
- [Documentation](https://docs.flowiseai.com/)
- [Git Hub](https://github.com/FlowiseAI/Flowise)
- [GitHub Organization](https://github.com/FlowiseAI)
- [Pricing](https://flowiseai.com/pricing)
- [Sign Up](https://flowiseai.com/)
- [License](https://github.com/FlowiseAI/Flowise/blob/main/LICENSE.md)
- [Discord](https://discord.gg/jbaHfsRVBW)
- [Twitter](https://twitter.com/FlowiseAI)
- [YouTube](https://www.youtube.com/@FlowiseAI)
- [Marketplace](https://flowiseai.com/marketplace)
- [SDK](https://github.com/FlowiseAI/FlowiseSDK)
- [SDK](https://github.com/FlowiseAI/FlowisePy)
- [SDK](https://github.com/FlowiseAI/FlowiseChatEmbed)
- [SDK](https://github.com/FlowiseAI/FlowiseEmbedReact)
- [Documentation](https://github.com/FlowiseAI/FlowiseDocs)
- [Container Image](https://hub.docker.com/r/flowiseai/flowise)
- [Package](https://www.npmjs.com/package/flowise)
- [Plans](plans/flowise-plans-pricing.yml)
- [Rate Limits](rate-limits/flowise-rate-limits.yml)
- [Fin Ops](finops/flowise-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
