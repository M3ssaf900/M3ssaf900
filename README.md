<div align="center">

# Mohammad Khaled Assaf

**Senior Software Developer · Full-Stack Architect · Integration Engineer**

`Enterprise Systems` · `Multi-Tenant SaaS Platforms` · `Cross-Platform Apps` · `Clean Architecture` · `GS1 & Supply-Chain Integration`

<br/>

<img src="https://img.shields.io/badge/.NET_10-512BD4?style=for-the-badge&logo=dotnet&logoColor=white"/>
<img src="https://img.shields.io/badge/C%23_13-239120?style=for-the-badge&logo=csharp&logoColor=white"/>
<img src="https://img.shields.io/badge/ASP.NET_Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white"/>
<img src="https://img.shields.io/badge/Blazor-512BD4?style=for-the-badge&logo=blazor&logoColor=white"/>
<img src="https://img.shields.io/badge/.NET_MAUI-512BD4?style=for-the-badge&logo=dotnet&logoColor=white"/>
<img src="https://img.shields.io/badge/SQL%20Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white"/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/SignalR-512BD4?style=for-the-badge&logo=dotnet&logoColor=white"/>
<img src="https://img.shields.io/badge/EF_Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white"/>

<br/><br/>

<a href="mailto:mohammad.khaled.assaf@outlook.com">
  <img src="https://img.shields.io/badge/Email-0078D4?style=flat-square&logo=microsoftoutlook&logoColor=white"/>
</a>
<a href="https://www.linkedin.com/in/mohammad-assaf-900">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white"/>
</a>
<a href="https://github.com/M3ssaf900">
  <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white"/>
</a>

</div>

<br/>

## 🧑‍💻 About

> I design and build **enterprise-grade, multi-tenant platforms** — from backend APIs and business logic layers down to **cross-platform native & web clients** — with a strong emphasis on **scalability, security, and long-term maintainability**.

My work spans complex, regulated domains — from **pharmaceutical supply-chain compliance** (GS1 EPCIS track-and-trace, government API integration) to **emergency management platforms**, **IoT device orchestration**, and **multi-tenant SaaS products**.

I focus on solving real infrastructure problems:

- **End-to-end platform delivery** — backend APIs, admin portals, and cross-platform mobile/desktop/web clients from a single codebase
- **Multi-tenant isolation** — database-per-tenant architectures with subdomain routing, automatic provisioning, quota enforcement, and subscription lifecycle management
- **Security-first design** — JWT + refresh token flows with auto-renewal, biometric authentication, SHA-256 certificate pinning, and granular role-permission matrices
- **Compliance & integration** — standards-compliant GS1 EPCIS XML generation, OAuth2-secured third-party API integration, and full audit trails
- **Production reliability** — offline-first resilience with queued operations, health check endpoints, structured logging with correlation IDs, and feature flags for zero-downtime rollouts

<br/>

## ⚙️ Tech Stack

<table>
  <tr>
    <td><b>🔧 Backend</b></td>
    <td>C# 13 · .NET 10 · ASP.NET Core · REST APIs · SOAP · SignalR · MediatR (CQRS) · Windows Services</td>
  </tr>
  <tr>
    <td><b>🖥️ Frontend & Cross-Platform</b></td>
    <td>Blazor Server · Blazor Hybrid · .NET MAUI · Razor Components · JavaScript · HTML/CSS · Bootstrap</td>
  </tr>
  <tr>
    <td><b>🗄️ Databases & ORM</b></td>
    <td>SQL Server · PostgreSQL · EF Core 10 · Dapper · Database-per-Tenant</td>
  </tr>
  <tr>
    <td><b>🔐 Security & Identity</b></td>
    <td>Duende IdentityServer · JWT Bearer + Refresh Tokens · Biometric Auth · Certificate Pinning · Role & Permission-Based Access</td>
  </tr>
  <tr>
    <td><b>🚀 DevOps & Infra</b></td>
    <td>Docker · Docker Compose · CI/CD Pipelines · Git · IIS · Serilog · Health Checks</td>
  </tr>
  <tr>
    <td><b>🔗 Integration</b></td>
    <td>GS1 EPCIS XML · Track-and-Trace APIs · REST · SOAP · Firebase Cloud Messaging · Government & Enterprise APIs</td>
  </tr>
  <tr>
    <td><b>🛡️ Resilience</b></td>
    <td>Polly (Retry, Timeout, Circuit Breaker) · Offline Queue · Auto-Drain · Feature Flags</td>
  </tr>
</table>

<br/>

## 🔧 Key Expertise

| Domain | Description |
|:---|:---|
| **System Architecture** | Designing scalable, maintainable systems using Clean Architecture, DDD, and layered patterns |
| **Multi-Tenant SaaS** | Database-per-tenant isolation, subdomain-based routing, quota enforcement, and automatic tenant provisioning |
| **Cross-Platform Development** | Single-codebase apps shipping to Android, iOS, macOS, Windows, and Web via .NET MAUI Blazor Hybrid |
| **Enterprise Integration** | Building integration layers for GS1 EPCIS, track-and-trace APIs, REST, SOAP, and custom government protocols |
| **Security Engineering** | JWT + refresh token flows, biometric auth, certificate pinning, granular permission systems (12 × 8 matrix) |
| **Real-Time Systems** | SignalR hubs, push notifications (FCM/APNs), deep linking, and live connectivity indicators |
| **Emergency & Crisis Systems** | Siren networks, IoT device orchestration, and real-time alerting platforms |
| **API Design** | Structured, versioned, well-documented REST APIs with Swagger/OpenAPI |

<br/>

## 🏗️ Architecture & Engineering Principles

```text
✔ Clean Layered Architecture with strict top-down dependency flow
✔ Domain-Driven Design (DDD) — bounded contexts, aggregate roots, value objects
✔ Modular Monoliths & Microservices — chosen by context, not trend
✔ Database-per-Tenant isolation with automatic provisioning & migration
✔ Cross-Platform shared codebase — one Razor Class Library, every platform
✔ Centralized DI with composable registration (AddCore → AddUI → AddWeb)
✔ Repository pattern — EF Core (type-safe) + Dapper (high-performance) hybrid
✔ Integration patterns: adapters, anti-corruption layers, GS1 EPCIS XML builders
✔ Resilience-first: Polly retry/timeout/circuit-breaker, offline queues, auto-reconnect
✔ Entity inheritance chains with auditable base classes & soft-delete filters
✔ CI/CD automation with Docker Compose & predictable deployments
✔ Structured logging (Serilog) with dual sinks, correlation IDs & rolling retention
✔ Health check endpoints (liveness + readiness) for production observability
✔ Data seeding pipelines — roles, permissions, admin users, service features
```

<br/>

## 🏆 What I Build

### 🏭 Enterprise Multi-Tenant Backend Platforms

Comprehensive backend systems with **GS1 EPCIS compliance** and **third-party track-and-trace** integration, built for regulated supply chains.

<table>
<tr>
<td width="50%" valign="top">

#### Architecture & Data

- **Clean layered architecture** — Presentation (API + Admin Portal) → Business Logic → Data Access, with strict top-down dependency
- **Dual presentation layer** — REST API with JWT Bearer auth + MVC Admin Portal with cookie auth, each with independent middleware pipelines
- **EF Core dual contexts** — Master database (13 DbSets: tenants, subscriptions, permissions, templates…) and per-Tenant database (7 DbSets + Identity: operations, requests, message tracking…)
- **Dapper integration** — High-performance raw SQL queries alongside EF Core for reporting and analytics
- **Repository pattern** — Generic `IGenericRepository<T>` with specialized implementations per context (Master, Tenant, Dapper)
- **Entity inheritance chain** — `IAUDITABLE → AUDITABLE → BASE → Domain Entity` with auto-timestamping, soft deletes, and global query filters
- **MediatR (CQRS)** — Command/query separation for clean business logic orchestration

</td>
<td width="50%" valign="top">

#### Multi-Tenancy & Operations

- **Database-per-tenant isolation** — Subdomain-based tenant resolution, automatic DB provisioning, and cross-tenant EF Core migration runner
- **Quota enforcement** — Per-tenant API usage tracking, remaining quota decrement on every operation, subscription lifecycle with renewal & history audit trail
- **Warehouse operations** — Receiving, Packing, Shipping, Unpacking, Dispensing (SSCC & SGTIN) — each generating standards-compliant GS1 EPCIS XML documents
- **GS1 XML builder** — `ObjectEvent` (OBSERVE), `AggregationEvent` (ADD/DELETE) generation with EPC URI, SGLN URN, and SSCC URN conversion utilities
- **Third-party integration** — OAuth2-secured track-and-trace API calls with message status tracking and full audit logging
- **Permission system** — 12 permission categories × 8 actions, seeded at startup, with role-claim management and role-to-service feature mapping

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### Security & Identity

- **Duende IdentityServer** — OAuth2 / OIDC with in-memory clients, scopes, and API resources
- **JWT Bearer auth** (API) — Symmetric key signing, zero clock skew, event logging
- **Cookie auth** (Admin Portal) — 30-min sliding expiration, HttpOnly, SameSite
- **Refresh token store** — Persisted tokens with expiry, revocation, and token-chain tracking (`ReplacedByToken`)
- **ASP.NET Core Identity** — Custom `ApplicationUser` (FullName, Phone, IsDeleted) and `ApplicationRole` with role claims
- **Shared identity config** — Reusable extension methods for Identity, IdentityServer, JWT, and cookie setup across projects

</td>
<td width="50%" valign="top">

#### Infrastructure & Observability

- **Serilog** — Dual file sinks: error logs (14-day retention) + application logs (30-day retention), rolling daily with 10 MB size limit
- **Health checks** — `/health/live` (liveness) and `/health/ready` (readiness) endpoints
- **Data seeding** — Startup seeders for default roles (SuperAdmin, Admin, User), admin user, 12 permission categories, 8 actions per category, and 4 core service features
- **Swagger / OpenAPI** — Versioned API documentation with configurable route prefix
- **Docker & Docker Compose** — Containerized deployment with environment-based configuration
- **SignalR WebSocket hub** — Real-time in-app notification delivery
- **Firebase Cloud Messaging** — Background push via FCM (Android) / APNs (iOS) with device registration
- **Stack:** .NET 10 · C# 13 · SQL Server 2019+ · EF Core 10 · Dapper · Duende IS · Docker

</td>
</tr>
</table>

<br/>

### 📱 Cross-Platform Enterprise Clients

**One Codebase. Every Platform.** A single shared Blazor UI shipping to Android, iOS, macOS, Windows, and the Web — powered by .NET MAUI Blazor Hybrid and Blazor Server Interactive SSR.

<table>
<tr>
<td width="50%" valign="top">

#### Architecture & Shared Codebase

- **4-project solution** — `Shared` (class library: services, DTOs, core logic, DI), `UI` (Razor Class Library: pages, components, layouts), `Maui` (native host), `Web` (Blazor Server host)
- **Centralized DI** — Three composable extension methods: `AddCore()` registers HTTP clients, business services, feature flags, and validators; `AddUI()` adds auth state & sound; `AddWeb()` auto-registers web/no-op implementations for all platform services
- **Zero duplication** — Every Blazor page, component, and layout lives in the shared Razor Class Library, referenced by both MAUI and Web hosts
- **Platform abstraction** — Interfaces for secure storage, biometrics, logging, crash reporting, offline queue, deep links, push notifications — each with native (MAUI) and no-op (web) implementations
- **i18n** — Arabic / English localization with persisted language preference
- **Virtualized rendering** — `Virtualize<T>` for smooth scrolling on large data collections

</td>
<td width="50%" valign="top">

#### Security & Authentication

- **JWT + refresh tokens** — Auto-refresh with 30-second monitoring timer, triggers renewal 5 minutes before expiry
- **Biometric auth** — Fingerprint / Face ID via platform APIs, with audit logging and configurable fallback PIN
- **Secure storage** — iOS Keychain · Android Keystore · Windows DPAPI — abstracted behind `ISecureStorageService`
- **Certificate pinning** — SHA-256 thumbprint validation against pinned set, with rotation support (add new pin → deploy → rotate cert → remove old pin)
- **Inactivity lock** — Configurable idle timeout triggers biometric re-verification
- **Session management** — Singleton session with token persistence, session restore on app relaunch, and `POST /revoke` on logout

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### Resilience & Offline

- **HTTP resilience** — Polly pipelines with 3 retries, exponential backoff, and 30-second timeout
- **Offline queue** — File-persisted JSON request queue in app data directory, monitors device connectivity via platform APIs
- **Auto-drain** — Automatically replays all queued requests when connectivity is restored
- **Connectivity UI** — Real-time offline banner + pending request count badge + manual "Sync Now" button
- **`IHttpClientFactory`** — Named HTTP client with certificate pinning handler and resilience pipeline
- **Deep linking** — Custom URI scheme registered on Android (intent filter) and iOS (`CFBundleURLSchemes`), with sub-path and query string preservation

</td>
<td width="50%" valign="top">

#### Observability & Features

- **Structured logging** — Property bags with `AsyncLocal` correlation IDs, rolling file logger (MAUI) / ASP.NET Core ILogger wrapper (web)
- **Crash reporting** — File-persisted crash reports (MAUI) / in-memory (web) via `ICrashReportingService`
- **Startup health validator** — Boot-time diagnostics: API URL check, demo mode detection, local environment warning, auth status verification
- **Feature flags** — 8 runtime toggles (offline queue, deep linking, biometrics, crash reporting, structured logging, push notifications, certificate pinning, demo mode) — no redeployment required
- **Push notifications** — FCM (Android) / APNs (iOS) with server registration + local notification tray
- **SignalR real-time** — Hub connection with auto-reconnect and long-polling fallback
- **Demo mode** — Full simulated data for every operation, no backend required
- **Stack:** .NET 10 · MAUI · Blazor · SignalR · Polly · ApexCharts

</td>
</tr>
</table>

<br/>

## 🎯 Current Focus

- 🏗️ Building **cross-platform enterprise apps** with a single .NET codebase across mobile, desktop & web
- 🔄 Scaling **multi-tenant SaaS platforms** with database-per-tenant isolation
- 🔒 Hardening **security architectures** — biometrics, certificate pinning, and granular permissions
- 🧩 Refining **system design patterns** for integration-heavy, compliance-driven architectures
- 🛡️ Engineering **offline-first resilience** with queued operations and auto-synchronization
- 📡 Improving **observability and reliability** with structured logging, health checks, and feature flags

<br/>

## 📊 GitHub Activity

<div align="center">

<a href="https://github.com/M3ssaf900">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=M3ssaf900&theme=github_dark" width="70%"/>
</a>

<br/>

<a href="https://github.com/M3ssaf900">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=M3ssaf900&theme=github_dark" width="32%"/>
</a>
<a href="https://github.com/M3ssaf900">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=M3ssaf900&theme=github_dark&utcOffset=3" width="32%"/>
</a>

<br/>

<img src="https://streak-stats.demolab.com?user=M3ssaf900&theme=github-dark-blue&hide_border=true&date_format=j%20M%5B%20Y%5D" width="50%"/>

<br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=M3ssaf900&theme=github-compact&hide_border=true&area=true" width="90%"/>

</div>

<br/>

## 🤝 Open For

- 🏛️ Architecture & system design consulting
- ⚙️ Backend engineering, cross-platform development & integration projects
- 🌍 Multi-tenant SaaS platform design & implementation
- 🤝 Long-term collaboration on complex, high-impact enterprise systems

<br/>

<div align="center">

📧 **<mohammad.khaled.assaf@outlook.com>**
&nbsp;&nbsp;·&nbsp;&nbsp;
🔗 **[LinkedIn](https://linkedin.com/in/mohammad-assaf-900)**

---

<sub>Built with clarity, not noise.</sub>

</div>
