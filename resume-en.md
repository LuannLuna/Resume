# Luann Luna

**Senior iOS Software Engineer**

São Luís, Brazil (GMT-3) | Remote US/EU/LATAM overlap

+55 98 98176-4061 | [luann.marques@gmail.com](mailto:luann.marques@gmail.com) | [linkedin.com/in/luannluna](https://linkedin.com/in/luannluna) | [github.com/LuannLuna](https://github.com/LuannLuna)

---

## Professional Summary

Senior iOS Engineer (7+ yrs) leading a UIKit-to-SwiftUI migration at BeSafe and owning its networking, security, and background-execution architecture end to end. Previously cut search latency 78% (900ms → 200ms) at LTK and led war-room triage for a launch-blocking crash impacting 1.5M+ Petz users. Deep in Swift 6 strict concurrency, SwiftUI + Observation, and ADR-driven architecture, plus hands-on ownership of testing (XCTest, Swift Testing, Maestro) and CI pipelines.

**Shipped to production:** G1, GE, Dafiti, Kanui, Tricae, Next, Petz, LTK.

---

## Experience

### Senior iOS Software Engineer
**BeSafe** | Jun 2026 – Present

- Led the incremental migration of a Swift codebase from UIKit/MVVM-C to SwiftUI — NavigationStack routers, @Observable state, and async/await throughout — including a tokenized, Figma-generated design-system component library; drove architecture decisions through a formal ADR process and team-wide code reviews
- Owned the networking, session, and background-execution layers end to end — REST client with interceptors and automatic token refresh, Keychain-backed credentials, APNs/BGTask triggers, and Firebase/RevenueCat SDK integrations — then diagnosed and fixed a cross-process race with the background extension causing deterministic logouts, redesigning token storage into a single-source-of-truth model
- Built the quality and release pipeline — Swift Testing/snapshot-testing suites plus on-device Maestro end-to-end flows, wired into GitHub Actions PR validation and automated Fastlane/match TestFlight releases — and added structured, PII-redacted Firebase telemetry that turned unreproducible field bugs into queryable data, diagnosing and fixing network-recovery failures after Wi-Fi/cellular handovers

### Senior iOS Software Engineer
**Hi-Tech Talents — contracted to LikeToKnow.It (LTK)** | Oct 2025 – Apr 2026

- Consolidated 3 legacy search endpoints behind a unified async/await data layer in a Swift 6 strict-concurrency codebase, cutting search response time from 900ms to 200ms (-78%)
- Designed and shipped 3 SwiftUI components into the LTK design system, powering the rebuilt search experience end-to-end and positioned for adoption by other feature teams
- Built an end-to-end Maestro suite simulating the full user journey (login → tabbar → search → creator shop), complementing XCTest UI coverage to validate cross-screen behavior unit tests alone couldn't catch

### Senior iOS Software Engineer
**Sebratec — contracted to Petz** | Aug 2022 – Sep 2025

- Architected the loyalty program module (MVVM + Clean Architecture); shipped as Petz's first production SwiftUI flow with real business logic, driving 1,000+ organic sales in week one
- Led war-room triage for a production crash affecting all 1.5M+ users — diagnosed a misconfigured remote config value and restored service in ~3 hours; triaged 12 top-occurrence crashes via Crashlytics and Instruments, sustaining ~99% crash-free sessions
- Led UIKit-to-SwiftUI migration across 8 screens with a 2-dev team, halving feature delivery from 3 months to 1.5 and establishing SwiftUI as team standard

### iOS Engineer / Digital Solutions Architect
**Capgemini — contracted to Next** | Jul 2021 – Jun 2022

- Prototyped a redesigned authentication flow in RxSwift at NEXT, moving from upfront permission loading to on-demand privilege escalation; aligned the design with a Principal Engineer from the client and produced UML and sequence diagrams of the login lifecycle, delivered as part of the proposal
- Paired with the Chat squad on the integration of a new SDK powering Bia, NEXT's virtual assistant, contributing through code reviews and bug triage to support a seamless handoff between the bot and human support agents
- Supported a junior iOS developer's day-to-day growth through pair programming, code reviews, and technical discussions on architecture patterns, development techniques, and software design

### Mid-Level iOS Developer
**Dextra Digital — contracted to Globo and Dafiti** | Oct 2019 – Jun 2021

- Built geolocation-based news discovery (CoreLocation, MapKit, GraphQL), doubling average session time from 4.2 to 8.7 minutes
- Grew test coverage from 18% to 67% with XCTest and Quick/Nimble, preventing 25+ production bugs over 18 months
- Implemented critical security fixes in Objective-C across Dafiti Group apps (Dafiti, Kanui, Tricae) — session control and cryptographic protections required for credit card compliance

### Junior iOS Developer
**Verité Soluções** | Jul 2018 – Sep 2019

- Built 3 interconnected iOS apps for business management (Swift, UIKit), supporting 500+ daily operations
- Integrated CoreLocation for nearest-store discovery paired with push notifications (40% DAU lift), and applied Firebase Performance Monitoring optimizations for 45% faster load times

---

## Education

**Bachelor of Computer Science** | 2011 – 2016
Federal University of Maranhão (UFMA)

---

## Technical Skills

- **Languages & Runtime:** Swift (Swift 6, strict concurrency), Swift Concurrency (async/await), Combine, Objective-C (legacy interop)
- **UI & State:** SwiftUI, UIKit, Observation (@Observable), SwiftData, Accessibility (VoiceOver, Dynamic Type)
- **Architecture & Modularization:** Clean Architecture, MVVM, MVVM-C, Coordinator Pattern, SOLID, Swift Package Manager (feature modules), Design Systems (Figma-driven tokens), ADRs
- **Quality & Performance:** XCTest, Swift Testing, Snapshot Testing, Maestro (end-to-end), Instruments
- **Release & Tooling:** Fastlane, Bitrise, GitHub Actions, SwiftLint, Firebase (Crashlytics, Analytics, Firestore, Remote Config, App Check), RevenueCat
- **APIs & Platform:** REST APIs, GraphQL, CoreLocation, MapKit, APNs, Keychain, BGTask
