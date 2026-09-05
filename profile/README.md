# Ask2App

> **MAKE ALL SOFTWARE FREE.**
>
> Ask. Answer. App delivered — with full source code you own.

Ask2App is a proprietary AI software generator hosted at [ask2app.com](https://ask2app.com). It creates complete, deployable applications from structured inputs and guided decisions. The generator is free to use, and the source code it generates is free and customer-owned.

Revenue comes from services: custom modifications, installs, managed Azure hosting, maintenance, upgrades, training, and enterprise support.

🌐 **Website:** [ask2app.com](https://ask2app.com)
📧 **Founder:** [Don.Potts@Ask2App.com](mailto:Don.Potts@Ask2App.com)

---

## What Ask2App Ships

- **170+ named templates** across **10 client stacks**
- **20+ production reference applications**, each generated as a complete solution
- Full source-code ZIP delivery, with setup and deploy scripts in the box
- ASP.NET Core Identity, JWT auth, RBAC, multi-tenancy, audit trails, and runtime feature flags
- Stripe, Plaid, Microsoft Graph email, Docker, and cloud deployment targets
- AI integrations across OpenAI, Azure OpenAI, Anthropic, OpenRouter, and local runtimes (Ollama, LM Studio)

### The stacks

| | |
|---|---|
| **Web** | Blazor WebAssembly (MudBlazor, Radzen, Tailwind), React (Tailwind, Fluent UI), Next.js + .NET |
| **Mobile** | .NET MAUI, React Native / Expo (NativeWind, Paper, Gluestack, shadcn) |
| **Desktop** | WinForms, Delphi VCL, Delphi FireMonkey, Delphi + Skia, Godot |
| **Server** | ASP.NET Core Web API, ABP Framework, Aspire, microservices |

The **WinForms** and **Delphi VCL** desktop clients are at full parity with the web clients — foreign-key pickers, many-to-many multi-select, user and role administration, light and dark theming — and emit source with **zero third-party dependencies**. Delphi FireMonkey trades the multi-column grid for reach: one codebase for Windows, macOS, Linux, Android and iOS.

---

## From a CSV to an ABP Framework solution

[**AbpGenerator**](https://github.com/ABPGenerator) turns plain CSV files into a full [ABP Framework](https://abp.io) solution — entities, permissions, admin screens and a MudBlazor, MVC and .NET MAUI UI, generated together and switched on by flag:

cart and Stripe checkout with real orders · a signed, idempotent payment webhook · in-app mobile payment that returns to the app rather than stranding the customer in a browser · chat · CMS Kit with its Pro-equivalent features (newsletter, contact form, polls, FAQ, page feedback, URL forwarding) · privacy (export my data, close my account) · runtime-editable email templates · outbound webhooks for n8n, Zapier and Make · a 27-theme switcher · two-factor auth · SaaS editions, organisation units and impersonation.

Every feature brings its own permissions and a menu entry that is hidden from anyone who may not use it, rather than shown and then refused.

Prefer to draw it first? The **Schema Designer** at [abpgenerator.ask2app.com](https://abpgenerator.ask2app.com) lays entities and relationships out visually and exports the CSVs and the run script.

---

## Reference Applications

### Business / SaaS

- **MyExecutiveSuite** — ERP + CRM + HRM + Finance + CMS + EDI X12, with a visual workflow engine, AI digital employees, fleet management, multi-entity dimensions, project billing, an Excel Add-in and native mobile apps
- **MyEntApps** — eight business apps over one shared UI: asset, booking, helpdesk, invoice, meal, project and roster managers, plus a developer kit
- **BlazerSuite** — order, warehouse, supply-chain, service, clinic, sales-CRM, HR and SaaS-CRM apps
- **LeadFinder** — multi-tenant lead-generation CRM using the Google Places API as the primary provider, with a Playwright fallback
- **MyCRM, MyERP, MyHRM, MyCMS** — standalone business modules
- **MyAccounting** · **MyBudget** · **MySnagTime** (scheduling) · **MyInventory** · **ItemShopHub** · **ShoppingCart**

### Microservices

- **ABP Microservices** — four independently-deployable ABP services behind a YARP gateway with Keycloak single sign-on, on free modules only
- **Aspire Microservices** — a catalog API, storefront and admin front end started by one .NET Aspire AppHost, with distributed tracing across every service

### AI / Content

- **My AI Orchestrator** — chats through whichever AI provider is available, failing over automatically on rate limits and errors
- **MarkBlogger** · **MarkBlog** · **CaseySupport** — Semantic Kernel agents for blogging, CMS content and customer support

### Home / Health / Play

- **MyRecipes** · **MyDailyFitness** · **MyFamilyBlog** · **MyWheel**
- **MyArcade** · **MyPuzzel** · **MergeGame** · **FlashCards**

---

## Azure / Microsoft Stack

Ask2App is Microsoft-stack-native:

- .NET 10 / ASP.NET Core · Blazor WebAssembly · Entity Framework Core · .NET Aspire
- Azure Container Apps · Azure PostgreSQL Flexible Server · Azure Files · Azure Container Registry
- Azure OpenAI · Microsoft Graph · Excel Add-in support in MyExecutiveSuite

Live on Azure today: the generator itself at [ask2app.com](https://ask2app.com), My Executive Suite at [suite.ask2app.com](https://suite.ask2app.com) with a public sandbox at [demo.ask2app.com](https://demo.ask2app.com), and the Schema Designer at [abpgenerator.ask2app.com](https://abpgenerator.ask2app.com).

---

## How It Works

```text
┌─────────────┐ ┌─────────────┐ ┌─────────────┐
│   WE ASK    │ │ YOU ANSWER  │ │APP DELIVERED│
│  Questions  │ │  Decisions  │ │ + Source    │
└─────────────┘ └─────────────┘ └─────────────┘
```

1. **We Ask** — guided questions and structured inputs
2. **You Answer** — select features, stack, data, and deployment options
3. **App Delivered** — a working app with full customer-owned source code, emailed as a ZIP

Generation takes minutes; larger workloads can take longer.

---

## How we know it works

Generated code that compiles is not the same as an app that runs, so templates are **started**, not just built — launched, signed into, and driven through create, edit and delete. Several defects that reached customers in the past were invisible in the source and only appeared once the app was running; that is why the bar is where it is.

---

## Mission

Ask2App exists to make software creation accessible.

The generator is proprietary IP, but the generated source code belongs to the customer. The goal is to make application source code free while building a sustainable services business around customization, deployment, hosting, maintenance, training, and support.

**We ask. You answer. App delivered.**
