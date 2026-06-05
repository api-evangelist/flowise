# Flowise (flowise)

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
