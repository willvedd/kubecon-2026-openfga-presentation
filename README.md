
![](./images/kccnc-na-2026-white.png)

# OpenFGA: Fine-Grained Authorization for Apps, APIs, and Agents

Presentation I gave at KubeCon + CloudNativeCon NA 2026 about OpenFGA, starting from the fundamnetal challenges with authroization today, a basic overview of how OpenFGA works and how OpenFGA can be used to authorize agentic workloads through Dynamic Conditions. 

**Note:** I was not the original submitter of this talk but very happy to be the final presenter.

[Session Link](https://events.linuxfoundation.org/kubecon-cloudnativecon-north-america/program/schedule/?id=1289672)


## Slides

Written in markdown in the `presentation.md` file, to be used with the DeckSet presentation software.

Also exported `presentation.pdf` for easier review.


## Original Abstract

OpenFGA helps teams move beyond role checks to relationship-based authorization for cloud native apps, APIs, and AI agents. Prior OpenFGA talks have introduced the project, shown SaaS and gateway adoption, and sketched the agent delegation model. This session goes one layer deeper.

We will walk through OpenFGA as a working project: authorization models, tuples, checks, local testing, CLI/SDK workflows, and production concerns. Then we will show a concrete agent-tool authorization flow: a user delegates a scoped task to an agent, a gateway extracts user/agent/task/tool/resource context, OpenFGA decides before the tool runs, and an audit trace records the request, decision, and result.

Attendees will leave knowing when OpenFGA fits, how to try it, and where to contribute across server, CLI, SDKs, docs, tests, and agent authorization examples.


## Continued Reading

- [Playground](https://play.fga.dev)
- [Docs](https://openfga.dev/docs)
- [Sample implementations](https://github.com/openfga/sample-stores)  (incl. MCP Gateway examples)
- [Dynamic Conditions Announcements](https://openfga.dev/blog/dynamic-abac-expressions-announcement)
- [Community](https://openfga.dev/community)