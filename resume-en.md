# Luann Luna

**Senior iOS Software Engineer**

São Luís, Brazil (GMT-3) | Remote US/EU/LATAM overlap

+55 98 98176-4061 | [luann.marques@gmail.com](mailto:luann.marques@gmail.com) | [linkedin.com/in/luannluna](https://linkedin.com/in/luannluna) | [github.com/LuannLuna](https://github.com/LuannLuna) | [luannluna.github.io/portfolio](https://luannluna.github.io/portfolio/)

---

## Professional Summary

Senior iOS Engineer (8+ yrs) who led a UIKit-to-SwiftUI migration at BeSafe and owned its networking, security, and background-execution architecture end to end. Also cut search latency 78% (900ms → 200ms) at LTK and led war-room triage for a launch-blocking crash impacting 1.5M+ Petz users. Deep in Swift 6 strict concurrency, SwiftUI + Observation, and ADR-driven architecture, plus hands-on ownership of testing (XCTest, Swift Testing, Maestro) and CI pipelines.

**Shipped to production:** G1, GE, Dafiti, Kanui, Tricae, Next, Petz, LTK, BeSafe.

---

## Experience

### Senior iOS Software Engineer
**BeSafe — contract (App Store launch)** | Jun 2026 – Nov 2026

- Shipped the app to the App Store by the contractually agreed launch deadline
- Led the incremental migration of a Swift codebase from UIKit/MVC to SwiftUI with Clean Architecture — NavigationStack routers, @Observable state, and async/await throughout — reaching 200+ SwiftUI views with only 5 UIKit controllers remaining
- Modularized the app into 25 local Swift Packages with CI-enforced module boundaries, including a tokenized, Figma-generated design-system library; drove architecture decisions through a formal Architecture Decision Record (ADR) process and team-wide code reviews
- Owned the networking, session, and background-execution layers end to end — REST client with interceptors and automatic token refresh, Keychain-backed credentials, APNs/BGTask triggers, and Firebase/RevenueCat SDK integrations
- Diagnosed and fixed a cross-process race between the app and its background extension that caused deterministic logouts, redesigning token storage into a single-source-of-truth model
- Built the quality and release pipeline — 3,000+ Swift Testing cases, 270 snapshot baselines, 45+ on-device Maestro end-to-end flows, GitHub Actions PR validation, and automated nightly Fastlane/match TestFlight releases
- Added structured Firebase telemetry with personal data stripped out, turning unreproducible field bugs into queryable data used to diagnose Wi-Fi/cellular network-recovery failures

### Senior iOS Software Engineer
**Hi-Tech Talents — contracted to LikeToKnow.It (LTK)** | Oct 2025 – Apr 2026

- Consolidated 3 legacy search endpoints behind a unified async/await data layer in a Swift 6 strict-concurrency codebase, cutting search response time from 900ms to 200ms (-78%)
- Designed and shipped 3 SwiftUI components into the LTK design system as Swift Packages, powering the rebuilt search experience end-to-end in a mixed UIKit/SwiftUI codebase and positioned for adoption by other feature teams
- Built an end-to-end Maestro suite simulating the full user journey (login → tabbar → search → creator shop), complementing XCTest UI coverage to validate cross-screen behavior unit tests alone couldn't catch

### Senior iOS Software Engineer
**Sebratec — contracted to Petz** | Aug 2022 – Sep 2025

- Architected the loyalty program module (MVVM + Clean Architecture); shipped as Petz's first production SwiftUI flow with real business logic, driving 1,000+ organic sales in week one
- Led war-room triage for a production crash affecting all 1.5M+ users — diagnosed a misconfigured remote config value and restored service in ~3 hours; triaged 12 top-occurrence crashes via Crashlytics and Instruments, sustaining ~99% crash-free sessions
- Led UIKit-to-SwiftUI migration across 8 screens with a 2-dev team, halving feature delivery from 3 months to 1.5 and establishing SwiftUI as team standard

### iOS Engineer / Digital Solutions Architect
**Capgemini — contracted to Next** | Jul 2021 – Jun 2022

- Prototyped a redesigned authentication flow in RxSwift at NEXT, moving from upfront permission loading to on-demand privilege escalation and cutting login time from 4.2s to 1.5s in the validation environment; aligned the design with a client Principal Engineer and delivered UML and sequence diagrams of the login lifecycle as part of the proposal
- Partnered with the Chat squad to integrate a new SDK powering Bia, NEXT's virtual assistant, contributing code reviews and bug triage that supported a seamless handoff between the bot and human support agents
- Mentored a junior iOS developer through pair programming, code reviews, and technical discussions on architecture patterns, development techniques, and software design

### Mid-Level iOS Developer
**Dextra Digital — contracted to Globo and Dafiti** | Oct 2019 – Jun 2021

- Built geolocation-based news discovery in Xcode using UIKit and Storyboards (CoreLocation, MapKit, GraphQL), doubling average session time from 4.2 to 8.7 minutes
- Grew test coverage from 18% to 67% with XCTest and Quick/Nimble, preventing 25+ production bugs over 18 months
- Implemented critical security fixes in Objective-C across Dafiti Group apps (Dafiti, Kanui, Tricae) — session control and cryptographic protections required for credit card compliance

### Junior iOS Developer
**Verité Soluções** | Jul 2018 – Sep 2019

- Built 3 interconnected iOS apps for business management (Swift, UIKit, Storyboard), supporting 500+ daily operations
- Integrated CoreLocation for nearest-store discovery paired with push notifications (40% DAU lift), and applied Firebase Performance Monitoring optimizations for 45% faster load times

---

## Technical Skills

- **Languages & Runtime:** Swift (Swift 6, strict concurrency), Swift Concurrency (async/await), Combine, RxSwift, Objective-C (legacy interop)
- **UI & State:** SwiftUI, UIKit, Observation (@Observable), Accessibility (VoiceOver, Dynamic Type)
- **Architecture & Modularization:** Clean Architecture, MVVM, MVVM-C, Coordinator Pattern, SOLID, Swift Package Manager (feature modules), Design Systems (Figma-driven tokens), ADRs
- **Quality & Performance:** XCTest, Swift Testing, Snapshot Testing, Maestro (end-to-end), Instruments
- **Release & Tooling:** Fastlane, GitHub Actions, SwiftLint, Firebase (Crashlytics, Analytics, Firestore, Remote Config), RevenueCat
- **APIs & Platform:** REST APIs, GraphQL, CoreLocation, MapKit, APNs, Keychain, BGTask

---

## Education

**Bachelor of Computer Science** | 2011 – 2016
Federal University of Maranhão (UFMA)

---

## Languages

Portuguese (native) | English (professional working proficiency)
