<div align="center">

# The AI-Powered Deployment Platform Built for Modern Developers

> **Build, deploy, scale, and manage applications with an AI-powered developer experience.**  
> Deploy containers, APIs, databases, static sites, and full-stack applications from your terminal, VS Code, GitHub, or the Deployxa Dashboard—in minutes, not hours.

<br />

[![Website](https://img.shields.io/badge/Website-deployxa.com-06b6d4?style=for-the-badge&logo=googlechrome&logoColor=white)](https://deployxa.com)
[![Documentation](https://img.shields.io/badge/Docs-docs.deployxa.com-6366f1?style=for-the-badge&logo=bookstack&logoColor=white)](https://docs.deployxa.com)
[![Dashboard](https://img.shields.io/badge/Dashboard-Deployxa%20Console-3b82f6?style=for-the-badge&logo=speedtest&logoColor=white)](https://deployxa.com/dashboard)
[![npm CLI](https://img.shields.io/badge/npm%20CLI-v1.10.4-cb3837?style=for-the-badge&logo=npm&logoColor=white)](https://www.npmjs.com/package/@deployxa/cli)
[![VS Code](https://img.shields.io/badge/VS%20Code-Extension-007acc?style=for-the-badge&logo=visualstudiocode&logoColor=white)](https://marketplace.visualstudio.com)
[![Discord](https://img.shields.io/badge/Discord-Join%20Community-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/deployxa)
[![GitHub Discussions](https://img.shields.io/badge/Discussions-Join%20Q%26A-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/deployxa/deployxa-engine/discussions)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Deployxa-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/company/deployxa)
[![Twitter](https://img.shields.io/badge/X%20%2F%20Twitter-@deployxa-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/deployxa)

---

</div>

## ⚡ Start in 60 Seconds

Your first production-ready deployment takes less than a minute with zero manual configuration.

```bash
# Step 1: Install official Deployxa CLI
npm install -g @deployxa/cli

# Step 2: Authenticate developer credentials
deployxa login

# Step 3: Deploy your repository to the edge
deployxa deploy
```

---

## 🎨 Visual Overview

<div align="center">

### Deployxa Control Console & Multi-Channel Deployment Workflow

```
+-------------------------------------------------------------------------------+
|  DEPLOYXA DASHBOARD CONSOLE                                   [v1.10.4 STABLE]|
+-------------------------------------------------------------------------------+
|  Project: my-nextjs-app           Status: ACTIVE          SSL: ENABLED (TLS)  |
|  Region: Anycast Edge CDN        Cold Start: <14ms       Rollbacks: INSTANT  |
|                                                                               |
|  [>] deployxa deploy --prod                                                   |
|  ✔ AI Framework Detection: Next.js (App Router)                               |
|  ✔ Container Bundled & Hardened (OCI Image: dep_8819a)                        |
|  ✔ Provisioned Automated Let's Encrypt TLS 1.3 Certificate                    |
|  ✅ Live Production Endpoint: https://my-nextjs-app.deployxa.app              |
+-------------------------------------------------------------------------------+
```

</div>

---

## 💡 About Deployxa

Deployxa removes infrastructure complexity so you can focus entirely on shipping product.

Developers shouldn't need to configure:
- **Kubernetes Manifests & Helm Charts**
- **Nginx Reverse Proxies & Ingress Rules**
- **Manual Let's Encrypt SSL Certbot Crons**
- **Fragile Custom Dockerfiles & CI Scripts**
- **Complex Load Balancers & Traffic Splitters**

Deployxa automates all of those tasks with an **AI-powered engine** while remaining 100% developer-first, transparent, and multi-cloud ready.

---

## 🔥 Why Developers Choose Deployxa

| Capability | Feature Highlights |
| :--- | :--- |
| **🤖 AI Deployment Assistant** | Automated framework inspection, multi-stage Dockerfile generation, and real-time build error fixes. |
| **⚡ One-Command Deployments** | Execute `deployxa deploy --prod` from any repository directory to get a live SSL URL. |
| **🔄 Instant Rollbacks** | Revert edge proxies to any previous container revision with zero downtime (`deployxa rollback`). |
| **🔒 Built-in Security** | Hardware-backed AES-256 secret vault, zero-trust container isolation, and automated Let's Encrypt SSL. |
| **🌍 Global Edge Deployments** | Low-latency Anycast CDN routing with subsecond cold starts across global edge regions. |
| **📈 Automatic Scaling** | Instant horizontal and vertical container resource scaling based on incoming HTTP traffic spikes. |
| **🛠 VS Code Integration** | Official extension integrating inline container stdout logs, secret management, and deployment triggers. |
| **🚀 GitHub CI/CD** | Automated preview deployments triggered on every pull request and git branch push. |
| **☁ Multi-Cloud Ready** | Deploy to bare metal VPS nodes, private Kubernetes clusters, or Deployxa Managed Edge Cloud. |

---

## 🛠 Supported Frameworks & Languages

Deployxa provides zero-config, single-command deployment support for every modern web stack:

| Framework / Stack | Deployment Type | Runtime Engine | Custom Ports |
| :--- | :--- | :--- | :--- |
| **Next.js (14/15)** | App Router, Standalone SSR & ISR | Node.js / OCI Container | `3000` / `PORT` |
| **React** | Vite SPA Static Asset Bundling | Anycast Edge CDN | Static / SPA |
| **Vue & Nuxt 3** | Nitro Serverless & Static Rendering | Node.js / Nitro | `3000` / `PORT` |
| **Angular** | Single Page Application | Anycast Edge CDN | Static / SPA |
| **Astro** | Hybrid SSR & Static Edge | Node.js / CDN | `4321` / `PORT` |
| **SvelteKit** | Node Adapter & Static Edge | Node.js / Adapter | `3000` / `PORT` |
| **Express.js** | Node.js REST API & WebSockets | Node.js LTS | `8080` / `PORT` |
| **NestJS** | Enterprise TypeScript API | Node.js LTS | `3000` / `PORT` |
| **FastAPI** | Asynchronous Python & Uvicorn | Python 3.11 | `8000` / `PORT` |
| **Django 5** | WSGI / ASGI Gunicorn & Postgres | Python 3.11 | `8000` / `PORT` |
| **Laravel 11** | PHP 8.3, Nginx & Artisan Queues | PHP-FPM 8.3 | `80` / `PORT` |
| **Go** | Compiled Binary Service | Native Go OCI | `8080` / `PORT` |
| **Docker OCI** | Custom Multi-Stage Dockerfiles | Native OCI Container | Custom Ports |
| **Static Sites** | HTML5, CSS3, JS & WebAssembly | Global Anycast CDN | Static Asset |

---

## 📦 Our Products

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h3>🌩 Deployxa Platform</h3>
      <p>Global cloud engine providing automated OCI container orchestration, anycast routing, Let's Encrypt TLS 1.3 SSL, health gates, and instant horizontal scaling.</p>
      <p><b>Capabilities:</b> Subsecond cold starts, anycast routing, TLS 1.3 renewals.</p>
      <p><a href="https://deployxa.com">Explore Platform →</a></p>
    </td>
    <td width="50%" valign="top">
      <h3>💻 Deployxa CLI (<code>@deployxa/cli</code>)</h3>
      <p>Developer-first terminal tool for building, deploying, monitoring, and debugging applications directly from your shell.</p>
      <p><b>Capabilities:</b> One-command deploys, secret vaulting, real-time log streaming.</p>
      <p><a href="https://www.npmjs.com/package/@deployxa/cli">Install via npm →</a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>📊 Deployxa Dashboard</h3>
      <p>Modern web console for team organization management, deployment metrics, real-time log streaming, environment secret injection, and AI Copilot assistance.</p>
      <p><b>Capabilities:</b> Organization quotas, live telemetry metrics, secret management.</p>
      <p><a href="https://deployxa.com/dashboard">Launch Console →</a></p>
    </td>
    <td width="50%" valign="top">
      <h3>🔌 Deployxa VS Code Extension</h3>
      <p>Official Visual Studio Code extension integrating real-time container stdout logs, deployment triggers, secret management, and rollback controls inside your editor.</p>
      <p><b>Capabilities:</b> Inline deployments, log streaming, secret editing.</p>
      <p><a href="https://marketplace.visualstudio.com">View on VS Code Marketplace →</a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>📖 Documentation Hub</h3>
      <p>Comprehensive developer documentation portal featuring framework blueprints, CLI specifications, API guides, and step-by-step tutorials.</p>
      <p><b>Capabilities:</b> Framework deployment guides, command palette search, tutorials.</p>
      <p><a href="https://docs.deployxa.com">Read Documentation →</a></p>
    </td>
    <td width="50%" valign="top">
      <h3>🚀 Starter Blueprints</h3>
      <p>Production-ready starter application templates for Next.js, React, Express, FastAPI, and Laravel with pre-configured Dockerfiles and secrets.</p>
      <p><b>Capabilities:</b> Copy-paste starter repositories with instant CLI initialization.</p>
      <p><a href="https://github.com/deployxa/examples">View Starter Templates →</a></p>
    </td>
  </tr>
</table>

---

## 📚 Featured Repositories

| Repository | Purpose | Technology | Current Status | Target Audience |
| :--- | :--- | :--- | :--- | :--- |
| [**`deployxa-engine`**](https://github.com/deployxa/deployxa-engine) | Core deployment control plane, container runners, and edge proxy gateways | Go / Docker / Linux | `Active` | System Engineers & Maintainers |
| [**`deployxa-dashboard`**](https://github.com/deployxa/deployxa-dashboard) | Next-gen web dashboard, marketing portal, and developer console (`deployxa.com`) | TypeScript / React / Vite | `Active` | Frontend Engineers & Developers |
| [**`deployxa-cli`**](https://github.com/deployxa/deployxa-cli) | Official command line interface (`@deployxa/cli`) published on npm | TypeScript / Node.js | `Active` | CLI Users & DevOps Automation |
| [**`deployxa-vscode`**](https://github.com/deployxa/deployxa-vscode) | Official Visual Studio Code extension for inline deployments and log streaming | TypeScript / VS Code API | `Active` | IDE Developers |
| [**`docs`**](https://github.com/deployxa/docs) | Official developer documentation portal (`docs.deployxa.com`) | React / TypeScript | `Active` | Technical Writers & Contributors |
| [**`examples`**](https://github.com/deployxa/examples) | Official starter templates for Next.js, React, Express, FastAPI, and Laravel | Multi-stack | `Active` | All Developers |

---

## 🌐 Ecosystem Architecture

```
Developer Workstation / IDE
        │
        ├──► @deployxa/cli (deployxa deploy)
        ├──► Deployxa VS Code Extension
        └──► GitHub Push / CI Webhook
                │
                ▼
   ┌─────────────────────────────────────────┐
   │    Deployxa Control Plane Engine        │
   │  - AI Framework & Runtime Inspection    │
   │  - Multi-Stage OCI Container Builder    │
   │  - AES-256 Hardware Secret Vault        │
   └─────────────────────────────────────────┘
                │
                ▼
   ┌─────────────────────────────────────────┐
   │    Global Anycast Edge Proxy            │
   │  - Let's Encrypt TLS 1.3 Certificate    │
   │  - Subsecond Cold Start Execution       │
   └─────────────────────────────────────────┘
                │
                ▼
  ✅ Production URL (https://my-app.deployxa.app)
```

---

## 🚢 What's Shipping

### 🟢 Released & Live
- **Deployxa CLI v1.10.4**: Machine-readable `--json` flag output, secret vault management, and zero-downtime rollback support.
- **VS Code Extension v1.0.0**: Inline container stdout log streaming, secret editing, and deployment triggers inside VS Code.
- **AI Deployment Copilot**: Automatic framework detection, Dockerfile generation, and health check validation.
- **Documentation Portal**: Complete framework deployment guides (Next.js, React, Express, FastAPI, Laravel, Django, Nuxt, SvelteKit, NestJS).

### 🟡 Coming Soon
- **GitHub Action (`deployxa/deploy-action@v1`)**: Zero-config GitHub marketplace action for automated PR preview deployments.
- **HashiCorp Terraform Provider**: Infrastructure-as-Code provisioner for projects, environments, and custom domains.
- **JavaScript & Go SDKs**: Programmatic deployment execution for custom backend workflows.

---

## 🔒 Trust & Reliability Signals

```
  [✅ Open Source]   [✅ TypeScript]   [✅ Docker Native]    [✅ npm Published]
  [✅ VS Code Ext]   [✅ AI Powered]   [✅ Secure Vault]     [✅ Multi-Cloud]
```

- **Open Source Transparency**: Core components licensed under open-source software licenses.
- **Enterprise Security**: Hardware-backed AES-256 secret vault and zero-trust container sandboxing.
- **SLA Reliability**: Global Anycast edge proxies backed by automated health checks and instant rollbacks.

---

## 💬 Community & Support

- 💬 **Discord Community**: Join our active developer community on [Discord](https://discord.gg/deployxa).
- 🐙 **GitHub Discussions**: Ask questions and share feedback in [Deployxa Discussions](https://github.com/deployxa/deployxa-engine/discussions).
- 📰 **Engineering Blog**: Read technical deep-dives on [Deployxa Dispatch](https://deployxa.com/dispatch).
- 🐛 **Issue Tracker**: Report bugs or submit feature requests on [GitHub Issues](https://github.com/deployxa/deployxa-engine/issues).
- 🤝 **Contributing**: Review our [Contributing Guide](https://github.com/deployxa/.github/blob/main/CONTRIBUTING.md) and [Code of Conduct](https://github.com/deployxa/.github/blob/main/CODE_OF_CONDUCT.md).

---

<div align="center">

# Ready to Deploy?

```bash
npm install -g @deployxa/cli

deployxa login

deployxa deploy
```

⭐ **Star our repositories on GitHub** • 📖 **Read the Docs** • 💬 **Join Discord** • 🚀 **Deploy your first app**

<br />

**Built with ❤️ by the Deployxa Open Source Community**  
[Website](https://deployxa.com) • [Documentation](https://docs.deployxa.com) • [Dashboard](https://deployxa.com/dashboard) • [Privacy](https://deployxa.com/privacy) • [Terms](https://deployxa.com/terms)

</div>
