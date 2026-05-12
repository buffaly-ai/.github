# Buffaly

Buffaly is a field-tested runtime for high-trust agents, developed by Matt Furnari.

Buffaly focuses on typed actions, semantic entities, prototype graphs, provider modules, tool modules, and inspectable execution. The public source is available for inspection, debugging, plugin/tool development, partner integration, and LLM-assisted understanding.

## Start here

If you are new to Buffaly:

1. Read the docs: https://buffa.ly/docs
2. Start with the runtime/source map.
3. Understand the foundations: Ontology and ProtoScript.
4. Inspect provider and tool modules to see how integrations are shaped.
5. Use the installer/runtime package for the fastest normal setup path.

## Core repositories

| Repository | What it is for |
|---|---|
| [protoscript](https://github.com/buffaly-ai/protoscript) | Executable language for prototype graphs, typed actions, ontology-native functions, parsing, interpretation, CLI validation, and workbench APIs. |
| [ontology](https://github.com/buffaly-ai/ontology) | Prototype graph runtime with typed nodes, properties, child collections, TypeOf inheritance, parsing, tests, and simulation support. |
| [buffaly-development](https://github.com/buffaly-ai/buffaly-development) | Main runtime source repository when public/available: agent host, typed tools, session services, web/worker hosts, ProtoScript integration, and embedded tool projects. |

## Provider and model integrations

| Repository | What it is for |
|---|---|
| [buffaly-providers](https://github.com/buffaly-ai/buffaly-providers) | Provider contracts and implementations for Anthropic, Gemini, xAI, plus a web harness for provider inspection. |
| [buffaly-codex-embedded](https://github.com/buffaly-ai/buffaly-codex-embedded) | Windows-first embedded/web UI around Codex-style coding sessions, with core library, CLI, web host, and tests. |

## Tool and module examples

| Repository | What it is for |
|---|---|
| [buffaly-tools-browser](https://github.com/buffaly-ai/buffaly-tools-browser) | Browser automation runtime, agent-facing browser tool, runner, skill wrapper, web harness, and tests. |
| [buffaly-openai-computeruse](https://github.com/buffaly-ai/buffaly-openai-computeruse) | OpenAI computer-use integration with core contracts, runner, smoke project, tests, and web harness. |
| [buffaly-openai-imagegeneration](https://github.com/buffaly-ai/buffaly-openai-imagegeneration) | OpenAI image generation integration with core facade, smoke project, module package, and web harness. |
| [buffaly-sms](https://github.com/buffaly-ai/buffaly-sms) | Agent-facing SMS tool and tests, with external SMS provider credentials kept outside the repo. |
| [buffaly-google-workspace](https://github.com/buffaly-ai/buffaly-google-workspace) | Google Workspace services for Gmail, Drive, Docs, Sheets, Calendar, Chat, OAuth flow, token storage boundaries, web module, and tests. |
| [buffaly-xapi](https://github.com/buffaly-ai/buffaly-xapi) | .NET X API client library, CLI, and tests for auth signing, request behavior, posting, timelines, mentions, and search. |

## Licensing

Buffaly core is GPLv3 by default. If your organization needs different terms for proprietary use, redistribution, or supported deployment, contact us for commercial licensing.

Commercial licensing inquiries can be opened as GitHub issues using the `commercial-licensing` label/template.

## What remains separate

Some domain packs, healthcare workflows, customer-specific connectors, deployment assets, implementation playbooks, sensitive demos/data, and private operational configuration remain separate from the public core. More source may be opened over time as time allows.

## Safety

Do not include PHI, credentials, secrets, OAuth tokens, customer data, private logs, or confidential information in public issues, pull requests, discussions, examples, screenshots, or attachments.

