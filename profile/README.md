# AIMOWAY

AIMOWAY provides OpenAI-compatible AI API access for developers, AI agent users, AI coding workflows, students, and engineering teams.

Use a familiar `/v1` API endpoint with your AIMOWAY API key, base URL, and supported model names.

```text
Base URL: https://aimoway.com/v1
```

## Who AIMOWAY is for

AIMOWAY is designed for people and teams building with AI APIs, AI agents, coding agents, and OpenAI-compatible tooling.

Typical users include:

* AI agent users
* AI coding agent users
* AI agent developers
* AI application developers
* Software developers
* Backend and full-stack developers
* Indie hackers and startup teams
* Engineering teams using LLMs for software development
* Teams and organizations using AI agents
* AI/ML, platform, API, DevOps, and SRE teams
* SaaS and product teams
* Agencies, consultancies, and automation builders
* University students, learners, bootcamp learners, labs, and hackathon teams

## What AIMOWAY provides

* OpenAI-compatible `/v1` API access
* API key based authentication
* Service-credit based billing
* Usage logs
* Clear model pricing information
* Developer documentation
* Public examples for `curl`, Python, and Node.js
* Agent workflow setup notes for compatible tools

AIMOWAY provides access to selected AI models through authorized service sources and upstream infrastructure. AIMOWAY is not a scraping layer or an unofficial shortcut to AI model services.

## Start here

| Resource                | Link                                            |
| ----------------------- | ----------------------------------------------- |
| Website                 | https://aimoway.com                             |
| Quick Start             | https://aimoway.com/docs/quickstart             |
| Developer Docs          | https://aimoway.com/docs                        |
| API Reference           | https://aimoway.com/docs/api-reference          |
| Pricing                 | https://aimoway.com/pricing                     |
| FAQ                     | https://aimoway.com/faq                         |
| API Examples Repository | https://github.com/AIMOWAY/aimoway-api-examples |

## API examples

The main examples repository shows how to call AIMOWAY with:

* `curl`
* Python
* Node.js
* OpenAI-compatible SDK patterns

Repository:

https://github.com/AIMOWAY/aimoway-api-examples

## Agent and coding workflow notes

AIMOWAY can be used with AI coding tools and agent workflows when the tool supports a custom OpenAI-compatible API base URL.

In general, configure:

```text
Base URL: https://aimoway.com/v1
API key:  your AIMOWAY API key
Model:    a supported model name from the AIMOWAY Pricing page
```

See:

* OpenCode configuration: https://aimoway.com/docs/opencode
* Hermes Agent configuration: https://aimoway.com/docs/hermes-agent
* Pricing and supported models: https://aimoway.com/pricing

## Security reminder

Do not commit API keys, tokens, `.env` files, logs, or request data that may contain private information.

Use environment variables for local development:

```bash
export AIMOWAY_API_KEY="your_aimoway_api_key_here"
```

## Privacy note

AIMOWAY does not use customer prompts, outputs, uploaded files, API request content, or other customer work data to train AI models.

See:

https://aimoway.com/privacy
