# Luann Luna

**Senior iOS Software Engineer**

São Luís, Brazil (GMT-3) | Remote US/EU/LATAM overlap

+55 98 98176-4061 | [luann.marques@gmail.com](mailto:luann.marques@gmail.com) | [linkedin.com/in/luannluna](https://linkedin.com/in/luannluna) | [github.com/LuannLuna](https://github.com/LuannLuna) | [luannluna.github.io/portfolio](https://luannluna.github.io/portfolio/)

---

## Professional Summary

Senior iOS Engineer (8+ yrs) who led BeSafe's incremental UIKit→SwiftUI migration — 200+ SwiftUI views, 25 Swift Packages, and the networking, session, and background-execution layers behind them — and shipped it to the App Store on the contractual deadline. Cut search latency 78% (900ms → 200ms) at LTK and led war-room triage for a launch-blocking crash affecting 1.5M+ Petz users. Strong in Swift 6 strict concurrency, SwiftUI + Observation, and ADR-driven architecture, with hands-on ownership of testing (Swift Testing, XCTest, Maestro) and CI/CD.

**Shipped to production:** G1, GE, Dafiti, Kanui, Tricae, Next, Petz, LTK, BeSafe.

**Public project:** [BudgetLens](https://github.com/LuannLuna/BudgetLens) — SwiftUI app for exploring a bundled budget snapshot and discussing it with any LLM via a user-supplied API key; layered Swift package, Keychain-isolated credentials, Swift Testing + XCUITest.

---

## Experience

### Senior iOS Software Engineer
**BeSafe — contract (first release + App Store approval)** | Jun 2026 – Nov 2026

- Led the incremental UIKit/MVC → SwiftUI + Clean Architecture migration — NavigationStack routers, @Observable state, async/await — ending with 200+ SwiftUI views and only 5 UIKit controllers; all SwiftUI views shipped with VoiceOver and Dynamic Type support
- Modularized the app into 25 local Swift Packages with CI-enforced boundaries, including a tokenized, Figma-generated design system and localization-ready strings; set architecture direction through ADRs and team-wide code reviews
- Owned networking, session, and background execution end to end: REST client with interceptors and automatic token refresh, Keychain-backed credentials, APNs/BGTask triggers, and Firebase/RevenueCat integration
- Diagnosed a cross-process race between the app and its background extension that caused deterministic logouts; redesigned token storage into a single source of truth
- Built the quality and release pipeline: 3,000+ Swift Testing cases, 270 snapshot baselines, 45+ on-device Maestro end-to-end flows, GitHub Actions PR validation, and nightly Fastlane/match TestFlight releases
- Instrumented structured Firebase telemetry with PII stripped, turning unreproducible field bugs into queryable data — used to diagnose Wi-Fi/cellular network-recovery failures

### Senior iOS Software Engineer
**Hi-Tech Talents — contracted to LikeToKnow.It (LTK)** | Oct 2025 – Apr 2026

- Consolidated 3 legacy search endpoints behind a unified async/await data layer in a Swift 6 strict-concurrency codebase, cutting search response time 78% (900ms → 200ms)
- Designed and shipped 3 SwiftUI components as Swift Packages in the LTK design system, powering the rebuilt search experience end to end in a mixed UIKit/SwiftUI codebase
- Built an end-to-end Maestro suite covering login → tab bar → search → creator shop, complementing XCUITest coverage and catching cross-screen regressions that unit tests could not

### Senior iOS Software Engineer
**Sebratec — contracted to Petz** | Aug 2022 – Sep 2025

- Architected the loyalty program module (MVVM + Clean Architecture) with Combine in a few reactive flows; shipped it as Petz's first production SwiftUI flow with real business logic, driving 1,000+ organic sales in week one
- Led war-room triage for a production crash affecting the full 1.5M+ user base — traced it to a misconfigured remote config value and restored service in ~3 hours; triaged 12 top-occurrence crashes via Crashlytics and Instruments, sustaining ~99% crash-free sessions
- Led a UIKit→SwiftUI migration across 8 screens with a two-developer team, cutting feature delivery time from 3 months to 1.5 and establishing SwiftUI as the team standard

### iOS Engineer / Digital Solutions Architect
**Capgemini — contracted to Next** | Jul 2021 – Jun 2022

- Prototyped a redesigned RxSwift authentication flow at NEXT, replacing upfront permission loading with on-demand privilege escalation and cutting login time from 4.2s to 1.5s in the validation environment. Aligned the design with the client's Principal Engineer and documented the login lifecycle in UML and sequence diagrams
- Partnered with the Chat squad to integrate the SDK behind Bia, NEXT's virtual assistant, contributing code review and bug triage for the bot-to-human handoff
- Mentored a junior iOS developer through pair programming, code reviews, and architecture discussions

### Mid-Level iOS Developer
**Dextra Digital — contracted to Globo and Dafiti** | Oct 2019 – Jun 2021

- Built geolocation-based news discovery with UIKit, CoreLocation, MapKit, and GraphQL, doubling average session time from 4.2 to 8.7 minutes
- Raised test coverage from 18% to 67% with XCTest and Quick/Nimble, preventing 25+ production bugs over 18 months
- Implemented security fixes in Objective-C across Dafiti, Kanui, and Tricae — session control and cryptographic protections required for credit-card compliance

### Junior iOS Developer
**Verité Soluções** | Jul 2018 – Sep 2019

- Built 3 interconnected iOS apps for business management (Swift, UIKit, Storyboards), supporting 500+ daily operations
- Integrated CoreLocation for nearest-store discovery and push notifications (40% DAU lift); cut load times 45% with Firebase Performance Monitoring

---

## Technical Skills

- **Languages & Runtime:** Swift (Swift 6, strict concurrency), Swift Concurrency (async/await), Combine, RxSwift, Objective-C (legacy interop)
- **UI & State:** SwiftUI, UIKit, Observation (@Observable), Accessibility (VoiceOver, Dynamic Type), Localization (i18n)
- **Architecture & Modularization:** Clean Architecture, MVVM, MVVM-C, Coordinator Pattern, Dependency Injection, SOLID, Swift Package Manager (feature modules), Design Systems (Figma-driven tokens), ADRs
- **Quality & Performance:** XCTest, XCUITest, Swift Testing, Snapshot Testing, Maestro (end-to-end), Instruments
- **Release & Tooling:** Git, Fastlane (match), GitHub Actions (CI/CD), SwiftLint, Firebase (Crashlytics, Analytics, Firestore, Remote Config), RevenueCat, AI-assisted development (Claude Code, Codex, GitHub Copilot)
- **APIs & Platform:** REST APIs, GraphQL, CoreLocation, MapKit, APNs, Keychain, BGTask

---

## Education

**Bachelor of Computer Science** | 2011 – 2016
Federal University of Maranhão (UFMA)

---

## Languages

Portuguese (native) | English (professional working proficiency)
