# Common Knowledge Project

## What is it?

The Common Knowledge Project (CKP):

- supports the sharing of information on the internet for human and programmatic access.
- designed for humans and machines to be able to interpret
  - machines and particularly LLMs and agentic AI systems are first class users
  - present information in a way optimized for them
- as websites are optimized for human users, the common knowledge aims to support AI users while still being human interpretable
- as language models and agentic systems become interfaces between humans and information, we aim to facilitate that experience. examples of this include:
  - information retrieval for retrieval-augmented generation
  - tool calling

### Why?

- let AI systems interface with information
- let AI systems interface with each other
- TODO: what else...?

### Common Knowledge API Specification

- to support this, the Common Knowledge Project is developing the **Common Knowledge API Specification**.
  - The Common Knowledge API Specification provides a shared definition for accessing information in an AI-first way
  - aims to be t AI systems what the websites are for humans
  - builds on existing standards, specifically:
    - TCP/IP: Network communication.
    - HTTP(S): Application-level protocol for information distribution.
    - OpenAPI Specification: Specification for describing schema of API.
  - It also encourages using common standards for representing knowledge
  - for full definition of Common Knowledge API, refer to the [[Common Knowledge API Specification]].

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
