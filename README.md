# Flowise (flowise)

Flowise is an open-source, low-code visual builder for LangChain-based LLM workflows and AI agents. Built on Node.js and TypeScript as a pnpm/Turbo monorepo, Flowise lets developers and non-developers compose chatflows, multi-agent agentflows, RAG pipelines, tools, and assistants on a drag-and-drop canvas, then expose them as REST APIs, embeddable chat widgets, or programmatic SDK calls. Flowise was acquired by Workday in 2025.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/flowise/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
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

The Flowise REST API exposes the full surface of a Flowise server, covering chatflows, agentflows, assistants, tools, variables, document stores, vector upserts, attachments, feedback, leads, chat messages, upsert history, predictions, and a ping health probe. It is documented as OpenAPI 3.0.3 from a Swagger UI shipped in the `packages/api-documentation` workspace of the FlowiseAI/Flowise monorepo and served at `/api-docs` on the Flowise server. Authentication uses an HTTP Bearer token (an API key generated in the Flowise admin UI).

**Human URL:** https://docs.flowiseai.com/api-reference

**Base URL:** http://localhost:3000/api/v1

#### Tags

- Agents, Agent Workflows, Artificial Intelligence, Large Language Models, Chatflows, Agentflows, Assistants, Tools, Variables, Document Stores, Vector, Predictions, Feedback, Leads, Chat Messages

#### Properties

- [Documentation](https://docs.flowiseai.com/api-reference)
- [OpenAPI](openapi/flowise-openapi.yml)
- [Authentication](https://docs.flowiseai.com/using-flowise/api-keys)
- [Swagger UI](https://github.com/FlowiseAI/Flowise/tree/main/packages/api-documentation)
- [Prediction](https://docs.flowiseai.com/api-reference/prediction)

## Naftiko Capabilities

- [chatflows](capabilities/chatflows.yaml)
- [prediction](capabilities/prediction.yaml)
- [document-store](capabilities/document-store.yaml)
- [assistants](capabilities/assistants.yaml)
- [tools](capabilities/tools.yaml)
- [variables](capabilities/variables.yaml)
- [vector](capabilities/vector.yaml)
- [feedback](capabilities/feedback.yaml)
- [leads](capabilities/leads.yaml)
- [chat-messages](capabilities/chat-messages.yaml)
- [attachments](capabilities/attachments.yaml)
- [upsert-history](capabilities/upsert-history.yaml)
- [ping](capabilities/ping.yaml)

## Artifacts

- **OpenAPI:** [openapi/flowise-openapi.yml](openapi/flowise-openapi.yml)
- **JSON Schema:** [chatflow](json-schema/flowise-chatflow-schema.json), [prediction](json-schema/flowise-prediction-schema.json), [assistant](json-schema/flowise-assistant-schema.json), [document-store](json-schema/flowise-document-store-schema.json), [tool](json-schema/flowise-tool-schema.json), [variable](json-schema/flowise-variable-schema.json), [chat-message](json-schema/flowise-chat-message-schema.json)
- **JSON Structure:** [chatflow](json-structure/flowise-chatflow-structure.json), [prediction](json-structure/flowise-prediction-structure.json)
- **JSON-LD:** [flowise-context.jsonld](json-ld/flowise-context.jsonld)
- **Examples:** [prediction](examples/flowise-create-prediction-example.json), [chatflow](examples/flowise-create-chatflow-example.json), [document upsert](examples/flowise-upsert-document-example.json), [vector upsert](examples/flowise-vector-upsert-example.json)
- **Vocabulary:** [flowise-vocabulary.yml](vocabulary/flowise-vocabulary.yml)
- **Spectral rules:** [flowise-rules.yml](rules/flowise-rules.yml)
- **Plans:** [flowise-plans-pricing.yml](plans/flowise-plans-pricing.yml)
- **Rate limits:** [flowise-rate-limits.yml](rate-limits/flowise-rate-limits.yml)
- **FinOps:** [flowise-finops.yml](finops/flowise-finops.yml)

## Common Properties

- [Website](https://flowiseai.com/)
- [Documentation](https://docs.flowiseai.com/)
- [GitHub](https://github.com/FlowiseAI/Flowise)
- [GitHub Organization](https://github.com/FlowiseAI)
- [Pricing](https://flowiseai.com/pricing)
- [SignUp](https://flowiseai.com/)
- [License](https://github.com/FlowiseAI/Flowise/blob/main/LICENSE.md)
- [Discord](https://discord.gg/jbaHfsRVBW)
- [X](https://twitter.com/FlowiseAI)
- [YouTube](https://www.youtube.com/@FlowiseAI)
- [Marketplace](https://flowiseai.com/marketplace)
- [TypeScript SDK](https://github.com/FlowiseAI/FlowiseSDK)
- [Python SDK](https://github.com/FlowiseAI/FlowisePy)
- [Embed Widget](https://github.com/FlowiseAI/FlowiseChatEmbed)
- [React Embed Component](https://github.com/FlowiseAI/FlowiseEmbedReact)
- [Docs Repository](https://github.com/FlowiseAI/FlowiseDocs)
- [Docker Image](https://hub.docker.com/r/flowiseai/flowise)
- [NPM Package](https://www.npmjs.com/package/flowise)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
