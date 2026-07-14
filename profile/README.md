# Buffaly

Buffaly is a field-tested runtime for high-trust agents, developed by Matt Furnari.

Buffaly focuses on typed actions, semantic entities, prototype graphs, provider modules, tool modules, and inspectable execution. The public source is available for inspection, debugging, plugin/tool development, partner integration, and LLM-assisted understanding.

## Start here

If you are new to Buffaly:

1. Read the docs: https://buffa.ly/docs
2. Start with the [Agent Kit](https://github.com/buffaly-ai/agentkit) — the public reference implementation for embedding agent/tool loops in .NET applications.
3. Understand the foundations: [Ontology](https://github.com/buffaly-ai/ontology) and [ProtoScript](https://github.com/buffaly-ai/protoscript).
4. Use the [installer](https://github.com/buffaly-ai/buffaly-installer) for the fastest normal setup path.
5. Browse [skills](https://github.com/buffaly-ai/buffaly-skills) for community and bundled skill packages.

## Public repositories

| Repository | What it is for |
|---|---|
| [agentkit](https://github.com/buffaly-ai/agentkit) | Buffaly Agent Kit 1.0 — a small headless .NET SDK for agent/tool loops with ProtoScript tool support and an optional ASP.NET inspector. This is the public reference implementation. |
| [protoscript](https://github.com/buffaly-ai/protoscript) | Executable language for prototype graphs, typed actions, ontology-native functions, parsing, interpretation, CLI validation, and workbench APIs. |
| [ontology](https://github.com/buffaly-ai/ontology) | Prototype graph runtime with typed nodes, properties, child collections, TypeOf inheritance, parsing, tests, and simulation support. |
| [buffaly-installer](https://github.com/buffaly-ai/buffaly-installer) | Public installer releases for Buffaly runtime packages. |
| [buffaly-skills](https://github.com/buffaly-ai/buffaly-skills) | Community and bundled skill packages for Buffaly agents. |

## Agent Kit

The [Buffaly Agent Kit](https://github.com/buffaly-ai/agentkit) is a frozen, one-time reference release that provides:

- A headless agent/tool loop (`AgentKitRuntime`) that accepts any `IChatClient` provider
- ProtoScript tool loading via explicit export manifests
- An optional ASP.NET package with DI registration, JSONL persistence, and a static inspector
- Three domain-specific samples (medical administration, commerce returns, DevOps incident investigation)
- No production Buffaly dependencies, no SQL, no worker infrastructure

It is designed to be installed via `dotnet add package` into any .NET application.

## Licensing

Buffaly core is GPLv3 by default. If your organization needs different terms for proprietary use, redistribution, or supported deployment, contact us for commercial licensing.

Commercial licensing inquiries can be opened as GitHub issues using the `commercial-licensing` label.

## What remains separate

Some domain packs, healthcare workflows, customer-specific connectors, deployment assets, implementation playbooks, sensitive demos/data, and private operational configuration remain separate from the public core. Additional source repositories (providers, integrations, tools, and internal modules) are maintained privately.

## Safety

Do not include PHI, credentials, secrets, OAuth tokens, customer data, private logs, or confidential information in public issues, pull requests, discussions, examples, screenshots, or attachments.
