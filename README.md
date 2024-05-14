# Common Knowledge Project

The Common Knowledge Project is a project to support the sharing of information on the internet for human, AI, and programmatic access.

## Goals

The Common Knowledge Project (CKP):

- supports the sharing of information on the internet for human and programmatic access.
- designed for humans and machines to be able to interpret
  - machines and particularly LLMs and agentic AI systems are first class users
  - present information in a way optimized for them
- as websites are optimized for human users, the common knowledge aims to support AI users while still being human interpretable
- as language models and agentic systems become interfaces between humans and information, we aim to facilitate that experience. examples of this include:
  - information retrieval for retrieval-augmented generation
  - tool calling

## Common Knowledge API Specification

To support the goals of the CKP, the Common Knowledge Project is developing the **Common Knowledge API Specification**. This is a base API specification defining how to access information in a way that supports these goals.

For the full definition of the specification, refer to the [Common Knowledge API Specification](./common-knowledge-openapi.yaml).

- The Common Knowledge API Specification provides a shared definition for accessing information in an AI-first way
- aims to be t AI systems what the websites are for humans

The specification builds on the following existing standards:

- TCP/IP: Network communication.
- HTTP(S): Application-level protocol for information distribution.
- OpenAPI Specification: Specification for describing schema of API.

It also encourages using common standards for representing knowledge,
such as using Markdown to represent text and JSON to represent structured data.

### Use Cases

The Common Knowledge API specification is designed to support the following use cases:

- Let AI systems interface with information using retrieval-augmented generation (RAG)
- Exporting data in a way that is easy to use for AI systems. This includes for training purposes and building other AI systems.
- Building generative AI chatbots and other AI systems to be consumed by human and AI users.

### Example Specification

TODO: create mongodb specification

## Future Work

- create clients in popular programming languages for using Common Knowledge APIs
- Establishing a set of supplementary standard usage patterns
  - think like how cookies not necessary part of web but widely used common standard
  - standard relationship between website resources and common knowledge api resources
  - standards for authentication
  - standard tools for common things like information retrieval and using APIs defined with OpenAPI specifications
- Tooling to easily create and host Common Knowledge APIs
- Integration with popular AI systems and frameworks

```ccard
type: folder_brief_live
```
