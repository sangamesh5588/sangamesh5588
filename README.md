<div align="center">

# SANGAMESH K
### **Principal Full-Stack, Mobile & Cloud Systems Architect**
*Engineering resilient cross-platform mobile architectures (React Native & Flutter for Android/iOS), cloud-native edge infrastructure, and AI-accelerated product ecosystems.*

<br/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=20&duration=2600&pause=1100&color=00F2FE&center=true&vCenter=true&width=740&lines=React+Native+%26+Flutter+Mobile+Architect+(Android+%26+iOS);ParkDady+%7C+Real-Time+Geospatial+Parking+Ecosystem;SyloNow+%7C+Customer+%26+Vendor+Mobile+Platform;Turborepo+Monorepo+%26+NestJS+Microservices;Multi-Factor+Mobile+Identity+%26+OAuth2+%2F+PKCE+Security" alt="Technical Competency Header" />
</a>

<br/><br/>

[![Status](https://img.shields.io/badge/Status-Available_for_High--Impact_Roles-00F2FE?style=for-the-badge&logo=statuspage&logoColor=black)](mailto:sangamesh.sylonow@gmail.com)
[![Mobile Stack](https://img.shields.io/badge/Mobile-React_Native_%7C_Flutter-61DAFB?style=for-the-badge&logo=react)](https://github.com/sangamesh5588?tab=repositories)
[![Cloud Stack](https://img.shields.io/badge/Cloud-AWS_%7C_Cloudflare-F58220?style=for-the-badge&logo=cloudflare)](https://github.com/sangamesh5588?tab=repositories)
[![Monorepo](https://img.shields.io/badge/Architecture-Turborepo_Monorepo-EF4444?style=for-the-badge&logo=turborepo)](https://github.com/sangamesh5588/human-platform)

</div>

---

## 🏛️ Executive Summary

I am a **product-minded systems architect and full-stack engineer** with a proven track record of designing, building, and deploying mission-critical applications across **Mobile (React Native & Flutter for Android and iOS)**, **Web (React 19, Next.js)**, and **Cloud Edge Infrastructure (AWS, Cloudflare, Supabase)**.

- **Dual-Engine Mobile Expertise:** Deep architectural proficiency across both **React Native (TypeScript, Bare Workflow & Expo SDK)** and **Flutter (Dart)**. Expert in native bridging (JSI, TurboModules, Native C++/Java/Swift), 60fps gesture-driven animations (Reanimated 3), and device OS APIs across Android and iOS.
- **Enterprise Monorepos & Microservices:** Engineered full-scale monorepo architectures using **Turborepo** and **pnpm**, uniting cross-platform mobile apps, client web portals, and **NestJS + Prisma** microservice backends.
- **System Reliability & Performance:** Specialized in offline-first mobile databases, sub-second geospatial querying, real-time WebSocket state synchronization, and hardware-accelerated media rendering.
- **Enterprise-Grade Security:** Deep practical experience implementing multi-factor authentication (Biometrics, Apple/Google SSO, SMS OTP via MSG91/Fast2SMS, OAuth 2.0 with PKCE), database Row-Level Security (RLS), and cryptographic keystore management.
- **AI-Augmented Engineering:** Leverage state-of-the-art AI infrastructure (Claude Code, Cursor, Antigravity, MCP, LLM APIs) to achieve 10x shipping velocity without sacrificing architectural rigor, type safety, or test coverage.

---

## 🏆 The 6 Major Production Platforms

```
┌────────────────────────────────────────────────────────────────────────────────────────┐
│                              SYSTEM TOPOLOGY OVERVIEW                                  │
├────────────────────────────────────────────────────────────────────────────────────────┤
│  [Human Platform (RN)]  [ParkDady (Driver & Host)]   [SyloNow (Customer & Vendor)]     │
│             │                        │                             │                   │
│             └────────────────────────┼─────────────────────────────┘                   │
│                                      ▼                                                 │
│                  [Cloudflare Global Edge: CDN / DDoS / SSL]                            │
│                                      │                                                 │
│              ┌───────────────────────┴───────────────────────┐                         │
│              ▼                                               ▼                         │
│      [NestJS Microservices]                          [Supabase PostgreSQL + RLS]       │
│      • Prisma ORM / PostgreSQL                       • Realtime WebSocket Channels     │
│      • AI Agent Workflows                            • Edge Functions (MSG91 Telecom)  │
│      • KYC / DigiLocker APIs                         • Razorpay Payment Gateway        │
└────────────────────────────────────────────────────────────────────────────────────────┘
```

### 1. 🌐 [Human Platform — Enterprise AI Collaboration Monorepo](https://github.com/sangamesh5588/human-platform)
> **Stack:** React Native (iOS & Android) • Turborepo • pnpm • NestJS • Prisma ORM • PostgreSQL • Docker
* **Architectural Scope:** Enterprise monorepo coordinating cross-platform mobile apps, multiple portal web apps (Admin, Expert, Organization, Docs), and backend microservices.
* **Core Engineering Feats:**
  * **React Native Client (`apps/mobile`):** Powered by Reanimated 3, Gesture Handler, Native Google Sign-In, and Zustand state management.
  * **NestJS Microservice Engine (`services/api`):** AI guide services, Razorpay booking integrations, DigiLocker/Aadhaar identity verification, and Prisma database migrations.
  * **Shared Monorepo Packages:** Centralized design tokens, type-safe API SDKs, and Zod validation schemas.

### 2. 🅿️ [ParkDady (Driver App) — Real-Time Geospatial Parking Engine](https://github.com/sangamesh5588/parkdady_user)
> **Stack:** Flutter (Dart) • Riverpod • Supabase PostgreSQL • Google Maps SDK • Razorpay • QR Code Engine
* **Architectural Scope:** Multi-sided marketplace mobile application serving urban drivers to discover, navigate to, reserve, and pay for parking spots in real-time.
* **Core Engineering Feats:**
  * Real-time GPS distance radius filtering and dynamic map viewport clustering.
  * Native OS Speech-to-Text integration for hands-free voice-assisted destination search.
  * Cryptographic QR ticket boarding pass generation with camera scanning at barriers.
  * Full Razorpay checkout pipeline with webhook signature verification.

### 3. 🅿️ [ParkDady (Host App) — Spot & Host Management Mobile Engine](https://github.com/sangamesh5588/park-dady-host-)
> **Stack:** Flutter (Dart) • Supabase PostgreSQL • Google Maps SDK • Dual-Role RBAC
* **Architectural Scope:** Dedicated host/space-owner application for onboarding private parking spaces, configuring hourly/monthly rates, and monitoring real-time occupancy.
* **Core Engineering Feats:**
  * Dual-role state machine enabling seamless switching between host and renter privileges.
  * Earnings analytics, automated payout tracking, and space availability schedulers.

### 4. 🎉 [SyloNow (Customer App) — On-Demand Event & Decor Mobile Client](https://github.com/sangamesh5588/sylonow_user_app_main)
> **Stack:** Flutter (Dart) • Supabase • Cross-Platform Mobile
* **Architectural Scope:** Core customer-facing mobile application for browsing curated event themes, customized on-demand decor packages, and booking verified specialists.
* **Core Engineering Feats:**
  * Rich visual catalogs, date/time scheduling slots, and real-time order tracking.
  * Integrated multi-factor authentication and transactional status updates.

### 5. 🛠️ [SyloNow (Vendor App) — Partner & Service Fulfillment Mobile App](https://github.com/sangamesh5588/sylonow_vendor_app)
> **Stack:** Flutter (Dart) • Supabase • OneSignal Push Notifications
* **Architectural Scope:** B2B partner application empowering decor teams and event vendors to receive instant job dispatches, accept orders, and update job progress.
* **Core Engineering Feats:**
  * Real-time push notification pipelines via OneSignal and Supabase database triggers.
  * Live status transitions (Assigned ➔ In-Transit ➔ In-Progress ➔ Completed) with photo verification uploads.

### 6. ⚡ [SyloNow (Web Platform) — Full-Stack On-Demand Management Suite](https://github.com/sangamesh5588/sylonow-new-web-app)
> **Stack:** Next.js 16 • React 19.2 • Tailwind CSS v4 • Supabase SSR • MSG91 SMS Gateway
* **Architectural Scope:** Modern responsive customer portal and operational management platform.
* **Core Engineering Feats:**
  * Powered by Next.js 16 App Router, React 19 Server Components, and zero-runtime Tailwind CSS v4.
  * Automated SMS alert workflows dispatched via MSG91 telecom gateway and Supabase Edge Functions.
* **Companion Service:** [`sylonow_web_app`](https://github.com/sangamesh5588/sylonow_web_app) & [`Sylonow_admin_panel`](https://github.com/sangamesh5588/Sylonow_admin_panel).

---

## 🛠️ Technical Competency Matrix

### 📱 1. Mobile Engineering (React Native & Flutter — Android & iOS)
* **Mobile Frameworks:** **React Native** (Bare Workflow & Expo SDK), **Flutter** (Dart), Android (Java/Kotlin), iOS (Swift).
* **React Native Ecosystem:** Reanimated 3, Gesture Handler, React Navigation (Native Stack), FlashList, MMKV (C++ ultra-fast encrypted storage), Hermes Engine optimization.
* **Architecture & State Management:** Riverpod, BLoC, Clean Architecture, Redux Toolkit, Zustand, React Context, Repository Pattern.
* **Hardware & Device OS APIs:** Background GPS tracking, Google Maps SDK, camera access, QR scanning (`mobile_scanner`), Speech-to-Text voice recognition, Biometrics (Face ID / Fingerprint).

### ☁️ 2. Cloud Infrastructure, Edge & DevOps
* **Amazon Web Services (AWS):** S3 (Secure object storage, presigned URLs), AWS Lambda (Serverless execution), CloudFront (Global CDN), Route53.
* **Cloudflare Global Edge:** Cloudflare Workers (Edge compute), Cloudflare Pages, DNS management, SSL/TLS termination, DDoS mitigation, and edge caching.
* **BaaS & Realtime Backends:** Supabase (PostgreSQL, Realtime WebSockets, Database Triggers, Edge Functions), Firebase (Firestore, Cloud Messaging FCM, Analytics).
* **CI/CD & Tooling:** Docker, Docker Compose, GitHub Actions CI/CD automation, Bun runtime, Playwright, Vitest.

### 🔐 3. Identity, Cryptography & Multi-Role Authentication
* **Protocols & Standards:** OAuth 2.0, PKCE, OpenID Connect, JWT signing & refresh token rotation, Bearer auth handshakes.
* **Multi-Factor & Social SSO:** Google Sign-In, Sign in with Apple (strict nonce validation), Biometric Auth, SMS OTP Gateways (MSG91 / Fast2SMS), KYC (DigiLocker / Aadhaar API).
* **Access Control:** Role-Based Access Control (RBAC) with multi-role state machines, PostgreSQL Row-Level Security (RLS) enforcement.

### 🤖 4. AI-Augmented Engineering & Autonomous Tooling
* **Engineering Accelerators:** Claude Code, Cursor IDE, Antigravity, GitHub Copilot, Trae.
* **Agentic Architectures:** Model Context Protocol (MCP), LLM APIs (Anthropic Claude, OpenAI), automated multi-step code refactoring, context-injected autonomous subagents.

---

## 📊 Live GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=sangamesh5588&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&title_color=00F2FE&icon_color=00F2FE&text_color=94A3B8&bg_color=0D1117" height="175" alt="GitHub Stats" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sangamesh5588&layout=compact&theme=tokyonight&hide_border=true&title_color=00F2FE&text_color=94A3B8&bg_color=0D1117" height="175" alt="Top Languages" />

<br/><br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=sangamesh5588&theme=tokyonight&hide_border=true&stroke=00F2FE&ring=00F2FE&fire=00F2FE&currStreakLabel=00F2FE&background=0D1117" alt="GitHub Streak" />

</div>

---

## 📬 Contact & Engineering Inquiries

<div align="center">

I am actively open to discussing **Senior Full-Stack / Mobile Architect roles (React Native & Flutter), technical leadership opportunities, and high-impact software engineering projects**.

<br/>

[![Email](https://img.shields.io/badge/Email-sangamesh.sylonow%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sangamesh.sylonow@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Profile-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sangamesh5588)
[![Portfolio](https://img.shields.io/badge/Portfolio-Live_Showcase-00F2FE?style=for-the-badge&logo=googlechrome&logoColor=black)](https://github.com/sangamesh5588/sangamesh-glow-portfolio)

<br/>

<sub>Crafted with engineering precision • Designed for scale</sub>

</div>