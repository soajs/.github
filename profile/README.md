<p align="center">
  <a href="https://www.soajs.org"><img src="https://www.soajs.org/images/soajs-logo.png" alt="SOAJS" height="48"></a>
</p>

<h3 align="center">Turn your microservices into multi-tenant products.</h3>

<p align="center">
  <a href="https://www.soajs.org">Website</a> ·
  <a href="https://www.soajs.org/docs/getting-started/quickstart/">Quickstart</a> ·
  <a href="https://www.soajs.org/docs/">Docs</a> ·
  <a href="https://www.soajs.org/releases/">Releases</a>
</p>

---

SOAJS is an open-source multi-tenant API gateway and microservices platform. Before your code runs, the gateway knows which customer is calling, what their package allows and who the user is: **tenant keys, per-API ACL and OAuth work together**, with rate limiting, caching and idempotency. Your services contain business logic only.

**MCP for AI agents.** Agents connect to one gateway endpoint, `/soajs/mcp`, and see your APIs as tools, filtered by each tenant's package and each user's ACL. Every tool call goes through the gateway like any API call. [Read more](https://www.soajs.org/docs/concepts/mcp/)

**In production:** seven platforms, 126 microservices. [Built on SOAJS](https://www.soajs.org/built-on-soajs/)

## Repositories

| | |
|---|---|
| **Gateway** | [soajs.controller](https://github.com/soajs/soajs.controller) (Node.js) · [soajs.controller.go](https://github.com/soajs/soajs.controller.go) (Go, preview) |
| **Framework** | [soajs](https://github.com/soajs/soajs): build Node.js services with input validation and gateway registration |
| **Core services** | [soajs.oauth](https://github.com/soajs/soajs.oauth) · [soajs.urac](https://github.com/soajs/soajs.urac) · [soajs.multitenant](https://github.com/soajs/soajs.multitenant) · [soajs.marketplace](https://github.com/soajs/soajs.marketplace) · [soajs.repositories](https://github.com/soajs/soajs.repositories) · [soajs.infra](https://github.com/soajs/soajs.infra) · [soajs.console](https://github.com/soajs/soajs.console) |
| **SDKs** | [soajs.nodejs](https://github.com/soajs/soajs.nodejs) (Express, Hapi) · [soajs.python](https://github.com/soajs/soajs.python) (FastAPI, Flask, Django) · [soajs.golang](https://github.com/soajs/soajs.golang) (net/http, Gin) |
| **Deploy** | [soajs.helm](https://github.com/soajs/soajs.helm) · [soajs.deployer](https://github.com/soajs/soajs.deployer) · [soajs.installer.versions](https://github.com/soajs/soajs.installer.versions) |
| **Libraries** | [soajs.core.modules](https://github.com/soajs/soajs.core.modules) · [soajs.core.libs](https://github.com/soajs/soajs.core.libs) · [soajs.urac.driver](https://github.com/soajs/soajs.urac.driver) |

## Security

Report a vulnerability privately, not in a public issue: open the affected repository's **Security** tab and choose "Report a vulnerability". Published advisories are listed on each repository's Security page.

Apache 2.0
