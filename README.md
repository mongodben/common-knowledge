# Common Knowledge Project

The Common Knowledge Project (CKP) supports sharing information for use by humans and artificial intelligence (AI) through programmatic access.

## Motivation

> Knowledge refers to information that has been processed, organized, and understood in a way that makes it useful for decision making, problem solving, or enabling intelligent action. It goes beyond raw data to include meaning, context and applicability.
>
> _Claude 3 Opus_

Since the invention of writing, humans have been the primary creators and consumers of "knowledge".
However, with the rise of Large Language Models (LLMs), AI is increasingly capable of understanding and creating knowledge. Coming agentic AI systems will also be increasingly capable of acting on knowledge.

Humans are increasingly using AI systems to interface with knowledge. This takes the form of querying language models directly and with retrieval-augmented generation (RAG). We increasingly see AI systems as an interface for human consumption of knowledge.

As the world wide web has made information more accessible to humans, the Common Knowledge Project aims to make knowledge more accessible to AI systems. While AI systems are capable of consuming information on the web, the information is not optimized for them.

The Common Knowledge Project aims to provide a way to share information that is optimized for both humans and AI systems.

## Common Knowledge API Specification

To support these goals, the Common Knowledge Project is developing the **Common Knowledge API Specification**. This is a base API specification defining how to access information in a way that supports these goals.

For the full definition of the specification, refer to the [Common Knowledge API Specification](./common-knowledge-openapi.yaml).

The Common Knowledge API Specification provides a shared definition for accessing information in an AI-first way.

The specification builds on the following existing standards:

- TCP/IP: Network communication.
- HTTPS: Application-level protocol for information distribution.
- OpenAPI Specification: Specification for describing schema of API.

It also encourages using common standards for representing knowledge,
such as using Markdown to represent text and JSON to represent structured data.

### Components

A Common Knowledge API has the following components:

- Conversations API: For interacting with information in a conversational way with back and forth using retrieval-augmented generation.
- Answers API: For interacting with information in a query-answer way with one-off queries using retrieval-augmented generation.
- Content API: For consuming information in a read-only way.

### Use Cases

The Common Knowledge API specification is designed to support the following use cases:

- Human users converse with Conversations and Answers APIs through UIs. This includes for chatbots and product features.
- Human users consume information from Content APIs through UIs. This includes for reading and searching.
- AI systems converse with Conversations and Answers APIs through APIs. This includes for AI agents.
- AI systems consume information from Content APIs through APIs. This includes for AI agents and plugins to external systems.
- Pulling clean knowledge data from Content API. This includes for training AI models and building other knowledge bases.

### Example Specification

An example Common Knowledge API specification for MongoDB can be found here: [MongoDB Common Knowledge API Specification](./examples/mongodb-common-knowledge-openapi.yaml).

## Future Work

- Create clients in popular programming languages for using Common Knowledge APIs
- Establishing a set of supplementary standard usage patterns
  - Think like how cookies not necessary part of web but widely used common standard
  - Standard relationship between website resources and common knowledge api resources
  - Standards for authentication
  - Standard conversation and answer types for common things like information retrieval and using APIs defined with OpenAPI specifications.
- Tooling to easily create and host Common Knowledge APIs.
- Integration with popular AI systems and frameworks.
