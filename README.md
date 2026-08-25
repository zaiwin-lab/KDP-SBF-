# Programme Management PULSE — Digital PMO Demonstrator

**Maturity:** Interactive concept prototype  
**Portfolio category:** Programme operations, governance and public-sector service design  
**Production status:** Not commissioned, endorsed or production-ready

Programme Management PULSE explores how a complex, multi-provider funding or training programme could be coordinated through a shared digital operating view. It turns governance, delivery, evidence, certification, claims and reporting requirements into an inspectable front-end experience.

> This repository demonstrates product and workflow thinking. It is not an official platform of Sarawak Business Federation, MINTRED, the Sarawak Premier's Office or any other external organisation.

## Business problem

Large programmes are frequently managed through disconnected spreadsheets, messages, schedules and evidence files. That makes it difficult for decision-makers to answer basic operational questions:

- Which cohorts and providers are on schedule?
- Is attendance or delivery evidence complete?
- Which certificates and claims are ready for review?
- Where are exceptions, delays or governance risks emerging?
- Can management see one current view without manually consolidating reports?

PULSE provides a concrete interface concept for discussing those questions before investing in a production system.

## Intended users

- programme owners, sponsors and executive evaluators;
- programme secretariat and PMO teams;
- training or delivery providers;
- finance, claims and governance reviewers;
- participants seeking programme and cohort information.

These are intended personas, not evidence of current users or adoption.

## Demonstrated capabilities

The repository contains two self-contained interactive HTML experiences:

- executive portfolio and programme dashboards;
- programme lifecycle, schedule and status views;
- provider, participant, attendance and certificate concepts;
- evidence-completeness and claim-readiness views;
- governance, accountability and management-reporting flows;
- provider and participant journey demonstrations;
- English, Bahasa Malaysia, Chinese and Iban interface content;
- responsive layouts and reduced-motion support.

The experiences are useful for workflow discovery, stakeholder workshops and proposal evaluation. They do not establish that an operational PMO system exists.

## What the implementation actually does

- Both variants are static HTML, CSS and client-side JavaScript applications.
- Dashboard figures and named entities are demonstration content.
- Some indicators and interface interactions are calculated or updated in the browser.
- Browser storage is used only for small interface preferences such as language selection.
- The visible contact or registration forms do not transmit data to a server.
- There is no API integration, shared database, authentication, role enforcement, audit log, payment rail, certificate service or claims-processing backend.
- “AI” panels are interface demonstrations; this repository contains no model call or AI inference service.

This distinction is important: the prototype makes a future operating model visible, but it does not execute that operating model.

## Strategic value

PULSE demonstrates how KOBIS can convert a long-form programme proposal into an interactive operating blueprint. Its value is in:

1. aligning stakeholders around roles and process stages;
2. exposing data, approval and evidence requirements early;
3. making governance and exception-management needs tangible;
4. providing a testable basis for a properly scoped pilot;
5. reducing ambiguity before backend, security and integration work begins.

## Technology

| Layer | Evidence in this repository |
|---|---|
| Interface | Semantic HTML, responsive CSS and vanilla JavaScript |
| Visualisation | Client-side dashboard, chart and progress components |
| Local state | Browser state and limited localStorage preferences |
| Internationalisation | In-page English, Bahasa Malaysia, Chinese and Iban content |
| Backend | Not implemented |
| AI service | Not implemented |
| Data source | Illustrative datasets embedded in the pages |

## Demonstration links

Two matching Netlify projects were confirmed in a ready state on **25 August 2026**:

- [BizFund2 Digital PMO](https://bizfund2-digital-pmo.netlify.app)
- [SBF BizFund2 / PULSE](https://sbfbizfund2.netlify.app)

Both are manual hosted demonstrations. The repository does not record a Git-linked deployment provenance, so validate the deployed build against the repository before using either as canonical evidence.

## Delivery role

**Ts. Zaiwin Kassim** led the product strategy, workflow architecture, executive narrative and solution direction with the **KOBIS AI Prodigy Team**, using supervised AI-assisted development.

This is a delivery and prototyping role statement. It does not imply appointment by, partnership with or endorsement from any organisation shown in the concept.

## Responsible use

Before any external pilot or production use:

- obtain written approval for programme names, logos, partners and institutional references;
- replace all illustrative budgets, participant counts, programme statistics and timelines with validated sources;
- implement consent, privacy notices, retention rules and PDPA-aligned data handling;
- introduce authentication, least-privilege roles, audit trails and security testing;
- validate eligibility, claims, payments, certificates and reporting rules with authorised owners;
- establish accessibility, language and content review with qualified stakeholders;
- retain human authority over approvals, funding, provider selection and participant decisions.

## Limitations

- No operational adoption, user count, revenue, impact or programme outcome is evidenced.
- No external institution is represented as a verified client, partner or sponsor.
- Displayed numbers and success indicators must not be cited as real performance.
- The prototype cannot accept valid registrations, process claims or make funding decisions.
- It should not be used to imply that the proposed programme, budget or governance model has been approved.

## Run locally

Open either `index.html` or `sbf-bizfund2/index.html` in a modern browser. No build step is required.

## Evidence needed for the next maturity stage

A credible pilot should demonstrate one authenticated, auditable workflow end to end:

**provider submission → evidence review → authorised decision → status notification → management report**

That vertical slice should use synthetic data first, documented roles, tested permissions and an approved programme taxonomy.
