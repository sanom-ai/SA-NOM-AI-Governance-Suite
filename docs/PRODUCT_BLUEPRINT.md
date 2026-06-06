# Product Blueprint

SA-NOM is a private-first governed AI operating system for real roles, real work, and real oversight.

This blueprint is the product-level source of truth for what SA-NOM is, what it is not, how the system is structured, how work is supposed to move, and how later versions should evolve without drifting away from the core doctrine.

It is written against the repository state as of `2026-06-06` and should be maintained as a living document.

Read this together with:

- [Product Scope](PRODUCT_SCOPE.md)
- [SA-NOM Operating Model](SA_NOM_OPERATING_MODEL.md)
- [Control Room Information Architecture](CONTROL_ROOM_INFORMATION_ARCHITECTURE.md)
- [SA-NOM Command Surface Doctrine](SA_NOM_COMMAND_SURFACE_DOCTRINE.md)
- [Feature Matrix](FEATURE_MATRIX.md)
- [System Architecture](SYSTEM_ARCHITECTURE.md)

## 1. One-Line Mission

Turn AI from a loose assistant into a governed operating workforce that can do real organizational work inside explicit authority, escalation, evidence, and recovery boundaries.

## 2. Product Identity

SA-NOM is not primarily a chatbot wrapper.

SA-NOM is not primarily a workflow ticketing tool.

SA-NOM is not primarily a compliance document library.

SA-NOM is a governed AI operating system.

That means the product exists to do five things together:

1. define AI roles as real operating actors
2. route work through governed boundaries
3. allow AI to proceed inside approved authority
4. stop or escalate work when trust boundaries are reached
5. retain evidence so every important move remains explainable

## 3. Core Promise

The system promise is simple:

- AI should be able to work
- humans should remain in control
- governance should not require turning AI into a passive drafting toy
- private deployment and operational confidence should be first-class, not optional

In practice, SA-NOM should help an organization move from:

- "AI answers questions"

to:

- "AI performs bounded organizational work and humans govern the meaningful control boundaries"

## 4. Non-Negotiable Product Doctrine

The following rules are foundational and should not be weakened by later feature work.

### 4.1 Private-First

The product must remain understandable and deployable as a private or self-managed runtime.

Cloud convenience may exist later, but the conceptual center of the product is still organization-controlled deployment, private data handling, and explicit infrastructure posture.

### 4.2 AI Does The Work

AI is not only a narrator or suggester.

The product should always prefer a model where AI performs routine operational work inside allowed boundaries and humans step in where accountability, risk, or authority requires it.

### 4.3 Humans Govern

The human role is not to redo every AI step manually.

The human role is to:

- approve
- escalate
- override
- recover
- publish
- release
- accept or reject exceptions
- redesign structure when trust breaks

### 4.4 Governance Must Be Operational

Governance is not a decorative report layer.

It must visibly change whether the system can:

- act
- route
- publish
- release
- recover
- export evidence
- trust a role

### 4.5 Action-First UX

Every serious governance screen should answer:

- what state are we in
- what should happen next
- what is blocked
- where is the fix

before it shows long descriptive text.

### 4.6 Evidence Must Travel With Decisions

The product should not rely on operator memory.

Important actions need explicit evidence, traceability, and continuity through audit, workflow proof, trusted registry state, and exportable artifacts.

## 5. Product Boundaries

### 5.1 In Scope

The product is in scope for:

- governed AI role definition
- authority-aware task routing
- AI execution inside policy boundaries
- human checkpoints where needed
- escalation and override handling
- trusted publication of roles
- audit and evidence continuity
- runtime health, recovery, and backup posture
- master data and routing governance
- outbound integrations and model-provider lanes
- private-first deployment and operator diagnostics

### 5.2 Out Of Scope

The product is not trying to be:

- a generic social chatbot
- a normal office intranet
- a general CRM or ERP replacement
- a manual service desk where SA-NOM staff run customer work for them by default
- a fake "fully autonomous AI company" with no human accountability

### 5.3 Product Responsibility Boundary

At the highest level:

- the customer owns policy, authority, and organizational decisions
- the platform owns runtime behavior, governance enforcement, and product posture

Commercial packaging may add rollout or advisory layers, but the product core should not blur this responsibility model.

## 6. Product Pillars

The product should stay coherent around the following pillars.

### 6.1 Governed AI Workforce

AI operates through roles, not vague prompts.

The system should express:

- who the role is
- what the role can do
- where the role reports
- what the role must escalate
- what the role must never do alone

### 6.2 Governed Work Movement

Work should move through:

- cases
- documents
- AI actions
- Human Ask
- routing and assignment
- trust and evidence checkpoints

This movement should be visible as a governed flow, not as disconnected feature islands.

### 6.3 Structural Trust

Even if a role looks correct on paper, the surrounding structure may still be unsafe.

The product therefore needs structural review through PT-OSS and related posture layers before calling a role or workflow trustworthy.

### 6.4 Operator Confidence

The platform must give founder, admin, and IT operators one understandable place to:

- set up
- verify
- diagnose
- recover
- publish
- export evidence

without forcing them to read raw infrastructure internals all day.

### 6.5 Command Surface Clarity

Normal users should be able to operate from a cleaner command surface.

Advanced operators should have a protected control surface.

This split is essential.

## 7. Surface Model

SA-NOM uses a split-surface architecture.

### 7.1 Command Surface

The command surface is the normal working interface.

Its job is to support business operation, not deep system setup.

Primary surfaces:

- `Home`
- `Work Inbox`
- `Cases`
- `Documents`
- `AI Actions`
- `Human Ask`
- directory and quick access patterns

The command surface should feel like:

- AI is already working
- work is already moving
- the user only intervenes where useful

### 7.2 Control Surface

The control surface is `Governance > Control Room`.

Its job is to support:

- setup
- trust
- publication
- diagnostics
- recovery
- provider and integration posture
- role governance
- advanced routing and master data posture

The control surface should feel like:

- mission control
- compact but high-confidence
- action-first, not prose-first

## 8. System Map

This section defines the intended job of each major surface.

### 8.1 Home

Purpose:

- show overall posture
- show next human action
- show what AI is already doing

Home is not for deep setup.

Home is the daily command dashboard.

### 8.2 Work Inbox

Purpose:

- show queued, active, escalated, or waiting governed work
- clarify who owns the next move

This is the operational intake and movement lane.

### 8.3 Cases

Purpose:

- anchor governed work items into durable operational stories
- preserve continuity across requests, documents, actions, and human review

Cases are not only tickets.

They are the continuity spine for governed work.

### 8.4 Documents

Purpose:

- create, classify, route, approve, publish, retain, and review governed documents

This is the operating document lane, not a passive file cabinet.

### 8.5 AI Actions

Purpose:

- observe AI work in motion
- see action outcomes
- follow escalation and continuity

This is where normal monitoring lives, not deep provider configuration.

### 8.6 Human Ask

Purpose:

- let humans call into the governed system for reports, meetings, summaries, and status review

Human Ask is an intentional governance entry point, not a bypass around the system.

### 8.7 Governance > Control Room

Purpose:

- configure
- verify
- publish
- trust
- recover

This is the advanced protected surface.

## 9. Control Room Structure

Control Room should remain grouped into clear operator houses.

### 9.1 Control Room Overview

The overview should behave like mission control.

It should show:

- runtime state
- first-run or pilot blockers
- trust posture
- publication readiness
- recovery attention
- the next advanced action

### 9.2 Setup & Onboarding

Purpose:

- bootstrap a real governed runtime quickly and correctly

Core capabilities:

- Setup Assistant
- First-Run Action Center
- Quick-Start Doctor
- owner bootstrap posture
- deployment readiness

### 9.3 AI Workforce & Roles

Purpose:

- create, review, refine, approve, and publish governed AI roles

Core capability:

- `Role Private Studio`

This lane should let operators:

- input normal JD-style role intent
- convert that into PTAG-backed structure
- review publish readiness
- inspect PT-OSS signals
- compare revisions
- publish into trusted posture

### 9.4 Trust & Evidence

Purpose:

- preserve trust continuity and exportable proof

Core capabilities:

- Audit Chain
- Evidence Export
- workflow proof posture
- Trusted Registry posture
- mismatch and signature visibility

### 9.5 Runtime & Recovery

Purpose:

- keep the governed runtime healthy and recoverable

Core capabilities:

- runtime health
- conflicts and locks
- sessions posture
- backup and restore
- smoke and diagnostics posture

### 9.6 Integrations & Providers

Purpose:

- manage external lanes safely

Core capabilities:

- Integrations
- outbound channels
- Model Providers
- fallback and readiness posture

### 9.7 Master Data & Routing

Purpose:

- keep organization structure and routing continuity trustworthy

Core capabilities:

- people
- seats
- teams
- assignment pressure
- search readiness
- searchable ownership continuity

### 9.8 Structural Risk & Alignment

Purpose:

- assess structural fragility and alignment risk

Core capabilities:

- PT-OSS Structural Intelligence
- structural readiness
- fragility posture
- Global Harmony or alignment governance when data is ready

### 9.9 Access & Security

Purpose:

- govern privileged access, session behavior, and advanced safety posture

Core capabilities:

- access profile posture
- owner-only controls
- session revocation
- Authority Guard
- Resource Lock

### 9.10 Admin Settings

Purpose:

- hold advanced product and runtime configuration that does not belong on daily work surfaces

## 10. Core Capability Model

The platform should be understood as several capability families that work together.

### 10.1 Role Definition

Includes:

- Role Private Studio
- PTAG-backed policy and authority structure
- review and publication workflow
- trusted publication posture

### 10.2 Work Execution

Includes:

- requests and work inbox
- AI actions
- governed case continuity
- document movement

### 10.3 Human Governance

Includes:

- approval
- escalation
- override
- Human Ask reporting and meeting entry points
- owner and privileged actions

### 10.4 Trust Continuity

Includes:

- audit chain
- evidence exports
- trusted registry
- workflow proof
- readiness and mismatch signals

### 10.5 Runtime Confidence

Includes:

- health
- sessions
- conflicts
- recovery
- backup and restore
- startup and smoke diagnostics

### 10.6 Structural Intelligence

Includes:

- PT-OSS assessment
- structural score
- fragility posture
- publish blockers
- guarded versus blocked distinctions

### 10.7 Routing Infrastructure

Includes:

- master data
- directory/search
- assignment ownership
- fallback routing
- organizational continuity

## 11. End-To-End Operating Flow

This is the intended top-level workflow shape.

### 11.1 Phase 1: Setup

An advanced operator:

- initializes the runtime
- completes owner registration
- validates environment readiness
- confirms trusted baseline files
- checks provider and integration posture

### 11.2 Phase 2: Workforce Definition

The organization:

- defines or uploads role intent
- refines role boundaries through Role Private Studio
- validates, simulates, and structurally reviews the role
- publishes the role into trusted posture

### 11.3 Phase 3: Work Intake

A request, case, document event, or AI action trigger enters the system.

The system:

- identifies the relevant context
- routes the work to the correct governed lane
- evaluates what AI role should act

### 11.4 Phase 4: Governed AI Work

AI:

- performs classification
- drafting
- routing
- synthesis
- document movement
- structured preparation

as long as authority and policy allow it.

### 11.5 Phase 5: Human Boundary

If the work reaches a boundary such as:

- approval
- release
- exception
- escalation
- irreversible action
- trust-sensitive publication

the system prepares the decision surface for a human.

### 11.6 Phase 6: Evidence And Continuity

During and after movement, the system records:

- audit events
- workflow proof continuity
- evidence artifacts
- trusted-state references

### 11.7 Phase 7: Recovery And Review

If something degrades, the system should support:

- blocked-state diagnosis
- lock review
- session review
- backup and restore
- structural redesign

## 12. Human And AI Role Model

The system should remain consistent about how human and AI responsibilities are divided.

### 12.1 AI Role

AI should:

- do the operational load
- move routine work forward
- prepare decision-ready outputs
- stop when authority is insufficient

### 12.2 Human Role

Humans should:

- govern
- approve
- override
- escalate
- recover
- redesign unsafe structures

### 12.3 Wrong Pattern To Avoid

Do not let the product drift into:

- AI writes drafts, humans do everything important

That would reduce SA-NOM into a safer assistant instead of a governed operating system.

## 13. UX Blueprint

This is the expected UX rule set for serious product surfaces.

### 13.1 Action-First Screen Model

Every advanced screen should follow this order:

1. `Status strip`
2. `Primary actions`
3. `Blockers`
4. `Details and diagnostics`
5. `Evidence and logs`

### 13.2 Status Strip

The status strip should summarize posture in one line using a small set of states:

- `Ready`
- `Attention`
- `Blocked`

### 13.3 Primary Actions

The screen should show one to three high-value actions first.

The user should not need to read several paragraphs before knowing what to click.

### 13.4 Blockers

Only real blockers should appear in the blocker area.

Each blocker should have:

- a short label
- a short explanation
- a direct fix action

### 13.5 Details

Longer analysis, deep posture, compare views, and technical context should remain available but secondary.

### 13.6 Evidence

Logs and proof should support the decision, not steal first attention from it.

### 13.7 Cross-Surface Consistency

Home, Control Room, Studio, and advanced governance tools should feel like one product family, not unrelated dashboards.

## 14. State Model

The product should use a small, comprehensible state language.

### 14.1 Ready

Meaning:

- the relevant conditions are satisfied
- the operator may proceed

### 14.2 Attention

Meaning:

- the system can still function
- but a meaningful operator review or improvement is needed

### 14.3 Blocked

Meaning:

- do not treat this path as safely operational until the blocker is resolved

### 14.4 Published

Meaning:

- the role, artifact, or trust object is already promoted into trusted posture

### 14.5 Guarded

Meaning:

- a path may still move, but the structural or governance posture is warning-level and should be treated carefully

## 15. Role Private Studio Blueprint

Role Private Studio is one of the defining capabilities of the product.

Its intended shape is:

- user inputs role intent in a normal document-like or JD-like way
- the system translates that intent into governed structure
- the operator reviews policy, hierarchy, simulation, and PT-OSS posture
- the operator publishes the role into trusted posture

This lane should not require normal users to understand PTAG syntax to benefit from governed role creation.

PTAG is a system layer.

The user-facing experience should feel natural and document-like wherever possible.

## 16. Trusted State Blueprint

SA-NOM needs an explicit trust chain.

That trust chain should include:

- trusted role publication
- trusted registry posture
- evidence continuity
- workflow proof continuity
- signature or mismatch visibility

The system should make it hard to confuse:

- draft state
- active reviewed state
- trusted published state

## 17. Runtime Blueprint

The runtime should be understood as governed execution infrastructure.

It is not only a server process.

It must provide:

- policy enforcement
- dispatch discipline
- session continuity
- recovery capability
- traceability

The runtime is the place where product doctrine becomes real behavior.

## 18. Document And Records Blueprint

Documents are not side content.

In SA-NOM they are governed operational artifacts.

The document system should support:

- structured creation
- classification
- approval routing
- release control
- retention
- record custody
- Human Ask reporting

This keeps document work inside the same governed operating model as actions and cases.

## 19. Search, Assignment, And Routing Blueprint

Search, routing, and assignment are governance infrastructure, not only convenience features.

The system should always be able to answer:

- who owns this next
- why it was routed there
- what fallback applies
- whether searchable continuity still works

If ownership and search continuity are weak, governance confidence is weak.

## 20. PT-OSS Blueprint

PT-OSS exists to answer a different question from PTAG.

PTAG asks:

- what is allowed

PT-OSS asks:

- is the surrounding structure safe enough to trust

This distinction should remain explicit in product design, documentation, and commercial positioning.

## 21. Commercial Alignment Rule

The product blueprint should stay compatible with both:

- open-core public baseline
- founder-led commercial delivery

But the blueprint should never depend on service-heavy behavior to make the product concept work.

The product must still make sense as a product.

Commercial support may accelerate rollout, hardening, or advisory judgment, but should not be the only reason the system functions conceptually.

## 22. What Must Not Drift

The following drifts should be treated as product mistakes.

### 22.1 Chatbot Drift

If the product starts behaving like a general-purpose assistant with weak operating boundaries, it has drifted.

### 22.2 Dashboard Dump Drift

If major screens become text-heavy status reports with no obvious next move, they have drifted.

### 22.3 Manual Work Drift

If humans must do most real work while AI only drafts, the product has drifted.

### 22.4 Governance Theater Drift

If governance exists only as labels and documentation but does not influence real execution, trust, or publication movement, the product has drifted.

### 22.5 Surface Mixing Drift

If normal business work and deep setup/admin posture are mixed together until the product becomes confusing, the product has drifted.

## 23. Roadmap Spine

This is the single-axis product direction that later work should follow.

### 23.1 Current Maturity Direction

The current system already contains:

- command surface
- Control Room baseline
- Role Private Studio baseline
- governed cases, documents, and AI actions
- trust and evidence posture
- routing and master data posture
- recovery and diagnostics posture

### 23.2 Immediate Next Direction

The next major quality objective should be:

- make every serious screen equally action-first and operationally smooth on tablet and PC

This means:

- less prose before action
- stronger state clarity
- cleaner blocker handling
- more direct fix buttons
- smoother dropdown, popover, and mission-control behavior

### 23.3 Medium Direction

The next structural direction after UX polish is:

- deepen runtime confidence
- strengthen self-serve setup
- tighten provider and dispatch boundaries
- make role publication and trust continuity even more robust

### 23.4 Long-Term Direction

Long-term, SA-NOM should become increasingly credible as:

- a governed AI operating system
- a private-first control architecture
- a policy-and-structure-aware execution runtime

not merely a dashboard over AI tools.

## 24. Blueprint Maintenance Rules

This file should be updated when:

- the command surface model changes
- Control Room grouping changes
- role governance model changes
- trust chain model changes
- product boundary changes
- the meaning of human versus AI work changes

This file should not be updated for:

- minor styling tweaks
- small implementation details
- narrow internal refactors that do not alter product meaning

## 25. Summary

SA-NOM is a private-first governed AI operating system.

Its defining idea is not "AI can help."

Its defining idea is:

- AI can work
- work can move
- humans can govern
- trust can remain explicit
- evidence can remain attached
- the whole system can still be operated from a clean, high-confidence surface

That is the product.
