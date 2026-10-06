## Hi there 👋

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/kagent-dev/kagent/main/img/icon-dark.svg" alt="kagent" width="400">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/kagent-dev/kagent/main/img/icon-light.svg" alt="kagent" width="400">
    <img alt="kagent" src="https://raw.githubusercontent.com/kagent-dev/kagent/main/img/icon-light.svg">
  </picture>
  <div>
    <a href="https://github.com/kagent-dev/kagent/releases">
      <img src="https://img.shields.io/github/v/release/kagent-dev/kagent?style=flat&label=Latest%20version" alt="Release">
    </a>
    <a href="https://opensource.org/licenses/Apache-2.0">
      <img src="https://img.shields.io/badge/License-Apache2.0-brightgreen.svg?style=flat" alt="License: Apache 2.0">
    </a>
    <a href="https://github.com/kagent-dev/kagent">
      <img src="https://img.shields.io/github/stars/kagent-dev/kagent.svg?style=flat&logo=github&label=Stars" alt="Stars">
    </a>
    <a href="https://discord.gg/Fu3k65f2k3">
      <img src="https://img.shields.io/discord/1346225185166065826?style=flat&label=Join%20Discord&color=6D28D9" alt="Discord">
    </a>
    <a href="https://www.bestpractices.dev/projects/10723">
      <img src="https://www.bestpractices.dev/projects/10723/badge" alt="OpenSSF Best Practices">
    </a>
  </div>
</div>

---

**kagent** is a Kubernetes native framework for building AI agents. You declare an agent as a Kubernetes custom resource, and kagent runs it on a sandboxed runtime, connects it to your models and tools, and keeps its conversation history across restarts. Because every part of an agent is an API object, you manage agents with the same `kubectl`, GitOps, and observability workflows you already run.

<div align="center">
  <img src="https://raw.githubusercontent.com/kagent-dev/kagent/main/img/kagent-agents-ui.gif" alt="The kagent dashboard" width="800">
</div>

---

## Get started

The kagent documentation is at [kagent.dev/docs](https://kagent.dev/docs/).

- [Install kagent](https://kagent.dev/docs/kagent/1.x/setup/installation/)
- [Build your first agent](https://kagent.dev/docs/kagent/1.x/get-started/your-first-agent/)
- [Architecture](https://kagent.dev/docs/kagent/1.x/about/architecture/)
- [Examples](https://kagent.dev/docs/kagent/1.x/examples/)

## Projects in this organization

Beyond the kagent framework itself, this organization maintains the tools that agents call, the servers that publish those tools, and the site that documents them.

| Repository | What it does |
| --- | --- |
| [kagent](https://github.com/kagent-dev/kagent) | The agent framework: controller, dashboard, CLI, and runtimes. |
| [kmcp](https://github.com/kagent-dev/kmcp) | A CLI and Kubernetes controller for building, testing, and deploying MCP servers. |
| [tools](https://github.com/kagent-dev/tools) | The MCP tools that kagent agents call, including the Kubernetes, Istio, and Helm tools. |
| [khook](https://github.com/kagent-dev/khook) | A controller that triggers kagent agents in response to Kubernetes events. |
| [a2a-slack-template](https://github.com/kagent-dev/a2a-slack-template) | A template for reaching a kagent agent from Slack over A2A. |
| [doc2vec](https://github.com/kagent-dev/doc2vec) | A tool that turns documentation sites into vector database files. |
| [website](https://github.com/kagent-dev/website) | The kagent.dev site and the documentation for kagent and kmcp. |
| [community](https://github.com/kagent-dev/community) | Governance, the code of conduct, and community meetings. |

## Get involved

Contributors are expected to [respect the kagent Code of Conduct](https://github.com/kagent-dev/community/blob/main/CODE-OF-CONDUCT.md). There are many ways to take part.

- 🐛 [Report bugs and issues](https://github.com/kagent-dev/kagent/issues/)
- 💡 [Suggest new features](https://github.com/kagent-dev/kagent/issues/)
- 📖 [Improve the documentation](https://github.com/kagent-dev/website/)
- 🔧 [Submit pull requests](https://github.com/kagent-dev/kagent/blob/main/CONTRIBUTING.md)
- 🗺️ [Follow the roadmap](https://github.com/orgs/kagent-dev/projects/3)
- 💬 [Help others in Discord](https://discord.gg/Fu3k65f2k3)
- 🤝 [Share tips in the CNCF #kagent Slack channel](https://cloud-native.slack.com/archives/C08ETST0076)
- 💬 [Join the kagent community meetings](https://calendar.google.com/calendar/u/0?cid=Y183OTI0OTdhNGU1N2NiNzVhNzE0Mjg0NWFkMzVkNTVmMTkxYTAwOWVhN2ZiN2E3ZTc5NDA5Yjk5NGJhOTRhMmVhQGdyb3VwLmNhbGVuZGFyLmdvb2dsZS5jb20)

## Contributors

Thanks to all contributors who are helping to make kagent better.

<a href="https://github.com/kagent-dev/kagent/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=kagent-dev/kagent" />
</a>

## Star history

<a href="https://www.star-history.com/#kagent-dev/kagent&Date">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=kagent-dev/kagent&type=Date&theme=dark" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=kagent-dev/kagent&type=Date" />
   <img alt="Star history of kagent-dev/kagent over time" src="https://api.star-history.com/svg?repos=kagent-dev/kagent&type=Date" />
 </picture>
</a>

---

<div align="center">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/cncf/artwork/refs/heads/main/other/cncf/horizontal/color-whitetext/cncf-color-whitetext.svg">
      <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/cncf/artwork/refs/heads/main/other/cncf/horizontal/color/cncf-color.svg">
      <img width="300" alt="Cloud Native Computing Foundation logo" src="https://raw.githubusercontent.com/cncf/artwork/refs/heads/main/other/cncf/horizontal/color-whitetext/cncf-color-whitetext.svg">
    </picture>
    <p>kagent is a <a href="https://cncf.io">Cloud Native Computing Foundation</a> project.</p>
</div>
