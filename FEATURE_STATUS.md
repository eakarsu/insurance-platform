# Feature status — Insurance policy, claims & recovery

| Capability | Status |
| --- | --- |
| Native sidebar and canonical feature registry | Built; 404 pages |
| Shared records, validation, relationships, persistence | Implemented in shared runtime |
| Clickable table rows with centered details popup | Implemented; Edit, Delete, Cancel, keyboard access and mobile layout |
| Domain field forms and source traceability | Imported from static source definitions; historical routes are labeled in mapping |
| CSV exports, attachments, audit and report totals | Implemented |
| At least 15 fictional rows per editable feature | Seeded by startup; measured in reports/seed-verification.json |
| AI question-and-answer workspace | Replaces AI feature tables; questions, context fields, formatted answers, follow-ups and saved history; live provider configuration required |
| Source calculation adapters | Available for explicitly registered calculation variants only |
| Source business-rule and state-machine parity | Incomplete beyond registered adapters and native records; verify each source journey |
| Original account/business data migration | Not performed; source data preserved |
| Provider integrations and external delivery | Not connected; request preparation only |
| Hosted authentication, independent-review roles and tenant isolation | Not migrated; local single-user boundary |

A successful build or populated table is not evidence of full source workflow parity. The source-to-feature map records every extracted definition and route, with explicit exclusions and migration warnings. Test/build reports distinguish checked behavior from remaining work.

| Canonical feature | Native mode | Source entries | Calculators | Status |
| --- | --- | ---: | ---: | --- |
| Clients & customers | records | 3 | 0 | Native records/view |
| Work items & projects | records | 0 | 0 | Native records/view |
| Contacts & parties | records | 1 | 0 | Native records/view |
| Tasks | records | 0 | 0 | Native records/view |
| Calendar | records | 0 | 0 | Native records/view |
| Deadlines & reminders | records | 0 | 0 | Native records/view |
| Notes | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Documents | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Templates | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Invoices & billing | records | 0 | 0 | Native records/view |
| Time tracking | records | 0 | 0 | Native records/view |
| Messages & communications | records | 0 | 0 | Native records/view |
| Reports & analytics | report | 23 | 0 | Native records/view |
| Activity & audit trail | audit | 19 | 0 | Native records/view |
| Provider connections | integration | 3 | 0 | Provider request records only |
| Policy endorsement and sublimit library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Covered location registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Loss-event timeline | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Physical damage evidence | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Historical revenue normalization | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Lost-sales forecasting | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Saved-expense calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Continuing-expense validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Extra-expense calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Restoration-period modeling | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Dependent-property analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Civil-authority analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Claim documentation package | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Insurer request workflow | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Advance and settlement tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Claim scenario analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fronting agreement library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Program year registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Loss run ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Case reserve validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| IBNR methodology | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Paid loss credit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Premium offset control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Collateral formula calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Instrument inventory | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Letter-of-credit fee audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Trust asset reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Release opportunity detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fronting carrier request | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Accounting close reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Program capital analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Carrier liability library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Shipment commodity registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Bill-of-lading ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Custody event timeline | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Seal and handoff tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Shortage detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Damage photo and survey evidence | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Temperature excursion analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Salvage value management | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Replacement-cost calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Liability limitation calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Claim filing deadline control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Claim packet generation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Carrier response workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Settlement reconciliation | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Carrier commodity and lane analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Catastrophe event registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Claim loss ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Occurrence definition analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Hours-clause grouping | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Ultimate loss estimate | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Retention erosion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Layer allocation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Limit exhaustion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Reinstatement premium | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cash call calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Notice deadline control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Proof-of-loss package | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Reinsurer query workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Collection reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Event tower analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Claims litigation early warning system work | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Producer agreement library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Policy premium ingestion | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Written premium calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Earned premium calculation | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Growth target validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Retention ratio calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Loss ratio calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Profitability corridor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Tier and hurdle calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Acquisition exclusion control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Commission statement audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Carrier claim package | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Payment reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Producer allocation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Carrier segment analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Value & Rollout Lab | records | 1 | 0 | Native records/view |
| Workflow Queue | records | 1 | 0 | Native records/view |
| Evidence & Documents | records | 1 | 0 | Native records/view |
| Reconciliation Engine | records | 1 | 0 | Native records/view |
| Premium Calculation & Approval | records | 1 | 0 | Native records/view |
| Dispute Correspondence | records | 1 | 0 | Native records/view |
| Farm unit acreage registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Policy endorsement library | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Acreage report reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Production history | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Harvest scale-ticket ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Yield loss calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Revenue protection calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Harvest price validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Prevented planting eligibility | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Replant payment calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Quality adjustment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Notice-of-loss deadline | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Adjuster evidence package | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Indemnity reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Crop county peril analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Incident timeline | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Notification deadline control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Forensic vendor cost ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Legal counsel costs | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Notification monitoring expense | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Data restoration expense | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Business interruption calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cyber extortion expense | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Regulatory defense costs | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Social engineering analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Consent panel vendor control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Producer contract library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| License appointment validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Commission schedule mapping | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Hierarchy split calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| New business commission | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Renewal commission | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Advance commission tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cancellation chargeback | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Free-look reversal | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Replacement policy control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Statement reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Producer dispute workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cash payment reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Carrier producer analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Carrier and producer agreement library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Policy and endorsement ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Written premium reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Base commission calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Override and bonus calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Contingent commission forecasting | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cancellation and return commission | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Producer split validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Direct-bill statement reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Agency-bill reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Missing commission detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Carrier inquiry and dispute | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cash application and aging | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Carrier and producer profitability analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Policy exposure terms | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Classification code library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Payroll exposure ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Sales exposure ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Subcontractor cost review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Certificate validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Owner officer exclusion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Experience modification control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Rate and factor calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Audit worksheet reconstruction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Dispute evidence package | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Carrier negotiation workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Return premium calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Refund reconciliation | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Policy class analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Treaties | records | 1 | 0 | Native records/view |
| Bordereaux | records | 1 | 0 | Native records/view |
| Ceded & Cash | records | 1 | 0 | Native records/view |
| Credit & Reporting | records | 1 | 0 | Native records/view |
| Treaty | records | 1 | 0 | Native records/view |
| Bordereau Record | records | 1 | 0 | Native records/view |
| Ceded Premium | records | 1 | 0 | Native records/view |
| Loss Recoverable | records | 1 | 0 | Native records/view |
| Cash Call | records | 1 | 0 | Native records/view |
| Collateral Position | records | 1 | 0 | Native records/view |
| Commutation Review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Schedule F Entry | records | 1 | 0 | Native records/view |
| Counterparty | records | 1 | 0 | Native records/view |
| Discrepancy | records | 1 | 0 | Native records/view |
| Settlement Payment | records | 1 | 0 | Native records/view |
| Treaty Term | records | 1 | 0 | Native records/view |
| Draft: Bordereau Validator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Draft: Loss Recoverable Calculator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Draft: Collateral Gap Monitor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Agreement collateral terms | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Reserve recoverable ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Paid loss recoverables | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Required collateral calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Asset eligibility review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Valuation haircut calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Credit rating adjustment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Letter-of-credit tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Trust statement reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Funds-withheld balance | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Collateral call workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Excess release calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Counterparty dispute evidence | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Accounting reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Treaty counterparty analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Bond indemnity library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Principal indemnitor registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Claim payment ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Completion cost validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Loss adjustment expense | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Collateral inventory | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Collateral drawdown | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Salvage asset tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Principal reimbursement demand | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Co-surety allocation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Subrogation opportunity | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Recovery litigation workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cash recovery ledger | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Reserve reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Bond principal analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| State title rate library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Transaction property registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Loan purchase ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Owner policy calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Lender policy calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Simultaneous issue rate | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Reissue refinance credit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Endorsement validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Search examination fee audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Recording fee reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Transfer tax calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Settlement fee audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Closing disclosure comparison | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Refund package | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Agent jurisdiction analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Insurance Policy | records | 1 | 0 | Native records/view |
| Insured Buyer | records | 1 | 0 | Native records/view |
| Policy Condition | records | 1 | 0 | Native records/view |
| Insured Shipment | records | 1 | 0 | Native records/view |
| Buyer Payment | records | 1 | 0 | Native records/view |
| Overdue Notice | records | 1 | 0 | Native records/view |
| Credit Claim | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Claim Evidence | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Insurer Decision | records | 1 | 0 | Native records/view |
| Operational Task | records | 1 | 0 | Native records/view |
| Rule Version | records | 1 | 0 | Native records/view |
| Document Requirement | records | 1 | 0 | Native records/view |
| Policy condition extraction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Buyer limit exception brief | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Shipment declaration draft | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Overdue notice preparation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Claim evidence gap analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Insurer response summary | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Evidence completeness review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Operations handoff draft | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| State account registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Taxable wage ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Rate notice extraction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Benefit charge statement | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Former employee matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Ineligible charge detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Experience rating calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Successor predecessor transfer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Joint account analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Voluntary contribution model | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Rate protest deadline | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Protest evidence package | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Amended return workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| State employer analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fraud Detection | records | 4 | 0 | AI question-and-answer workspace; records available as context |
| Damage Assessment | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Risk Assessment | records | 4 | 0 | AI question-and-answer workspace; records available as context |
| Settlement Recommendation | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Document Analysis | records | 4 | 0 | AI question-and-answer workspace; records available as context |
| Policy Coverage Analysis | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Customer Sentiment | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Claims Forecasting | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Claim Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Policy Review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Customer Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Adjuster Performance | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Payment Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Audit Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Smart Summary | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Auto-Assign Adjuster | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Claims | records | 4 | 0 | AI question-and-answer workspace; records available as context |
| Policies | records | 4 | 0 | Native records/view |
| Adjusters | records | 1 | 0 | Native records/view |
| Payments | records | 2 | 0 | Native records/view |
| Subrogation Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Reserve Estimation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Predictive Settlement Optimization | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Adjuster Workload Balancing | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Customer LTV & Retention | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Pass5 tools | records | 2 | 0 | Native records/view |
| Claim severity leakage audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| agentic claims triage auto routing by | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| computer vision damage assessment from m | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| fraud ring detection correlating claims | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| predictive settlement optimization model | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| adjuster workload balancing using capaci | records | 1 | 0 | Native records/view |
| customer ltv retention predicting post c | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| subrogation recovery optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| reserve estimation ai | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| litigation outcome predictor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| image based vehicle damage estimator | records | 1 | 0 | Native records/view |
| webhook surface for fnol ingestion | integration | 1 | 0 | Provider request records only |
| mobile push notifications for field | records | 1 | 0 | Native records/view |
| e signature for settlements | integration | 1 | 0 | Provider request records only |
| notifications module 0 references | records | 1 | 0 | Native records/view |
| websocket real time claim feed | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Missing features | records | 1 | 0 | Native records/view |
| Production readiness | records | 1 | 0 | Native records/view |
| Underwriting Rules | records | 3 | 0 | Native records/view |
| Premium Calculator | records | 2 | 0 | Native records/view |
| Compliance Monitoring | records | 3 | 0 | Native records/view |
| Reinsurance Treaties | records | 2 | 0 | Native records/view |
| Loss Ratio Analysis | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Agents & Brokers | records | 2 | 0 | Native records/view |
| Policy Renewals | records | 2 | 0 | Native records/view |
| Quote Bind Issue | records | 2 | 0 | Native records/view |
| Billing & Payments | records | 2 | 0 | Native records/view |
| Endorsements | records | 3 | 0 | Native records/view |
| Cancellations | records | 3 | 0 | Native records/view |
| E-Signature | integration | 1 | 0 | Provider request records only |
| RBAC Admin | records | 2 | 0 | Native records/view |
| Audit Exports | records | 2 | 0 | Native records/view |
| Policy Recommendation | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Customer Portal | records | 2 | 0 | Native records/view |
| Agent Portal | records | 2 | 0 | Native records/view |
| UW Workflow | records | 2 | 0 | Native records/view |
| Integration Center | integration | 2 | 0 | Provider request records only |
| Agentic Underwriting | records | 2 | 0 | Native records/view |
| Renewal Optimizer | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Appetite Drift | records | 1 | 0 | Native records/view |
| Production Controls | records | 2 | 0 | Native records/view |
| Policy Management | records | 1 | 0 | Native records/view |
| Customer Management | records | 1 | 0 | Native records/view |
| Claims Processing | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Evaluate Claim | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Analyze Risk | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| AI Suggest Optimization | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Investigate Fraud | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Optimize Premium | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Predict Trends | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Audit Trail | records | 1 | 0 | Native records/view |
| AI Recommend Renewal | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| E-Signature Packets | integration | 1 | 0 | Provider request records only |
| Appetite drift monitor | records | 1 | 0 | Native records/view |
| agentic underwriting automation handling | records | 1 | 0 | Native records/view |
| fraud syndicate detection correlating ap | records | 1 | 0 | Native records/view |
| premium dynamism recommending real time | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| renewals optimization predicting likelih | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| rule engine optimization recommending up | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| ai premium rate recommender | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| fraud probability ai | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| policy recommendation engine | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| renewal prediction model | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| rule optimization analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| live rating bureau integration still sca | integration | 1 | 0 | Provider request records only |
| webhook surface for application event | integration | 1 | 0 | Provider request records only |
| file upload for supporting documents | records | 1 | 0 | Native records/view |
| e signature for binderspolicies | integration | 1 | 0 | Provider request records only |
| Rules & Jobs | records | 2 | 0 | Native records/view |
| AI Quote Generator | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Coverage Analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Claims Assistant | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Renewal Predictor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cross-Sell Recommender | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Voice Receptionist | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Document Processor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Risk Assessor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Email Composer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Smart Search | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Client Summary | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Claim Summarizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Policy Comparison | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Chatbot | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Sentiment Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Loss Run Analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Endorsement Recommender | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Compliance Checker | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Personal Lines | records | 1 | 0 | Native records/view |
| Commercial Lines | records | 1 | 0 | Native records/view |
| Households | records | 1 | 0 | Native records/view |
| Life Events | records | 1 | 0 | Native records/view |
| Renewals | records | 1 | 0 | Native records/view |
| All Quotes | records | 1 | 0 | Native records/view |
| Comparisons | records | 1 | 0 | Native records/view |
| Proposals | records | 1 | 0 | Native records/view |
| Follow-ups | records | 1 | 0 | Native records/view |
| Settlements | records | 1 | 0 | Native records/view |
| Overview | records | 1 | 0 | Native records/view |
| Statements | records | 1 | 0 | Native records/view |
| Forecasting | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Producer Splits | records | 1 | 0 | Native records/view |
| Campaigns | records | 1 | 0 | Native records/view |
| Email Templates | records | 1 | 0 | Native records/view |
| Referrals | records | 1 | 0 | Native records/view |
| Cross-Sell | records | 1 | 0 | Native records/view |
| Results | records | 1 | 0 | Native records/view |
| Rules | records | 1 | 0 | Native records/view |
| Checks | records | 1 | 0 | Native records/view |
| Escalations | records | 1 | 0 | Native records/view |
| Complaints | records | 1 | 0 | Native records/view |
| AI Suite (NEW) | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Voice Agents | records | 1 | 0 | Native records/view |

Row popup verification passed: dashboard and feature rows, keyboard/focus, editing and persistence, delete confirmation/cancellation, centered mobile layout and full-record navigation. See `reports/row-popup-verification.json`.

## Verified local build

Build, API, browser and actual `start.sh` checks passed. All 404 feature pages were visited in the browser; 402 editable tables contain at least 15 fictional rows each. CRUD persistence and mobile layout were checked. Evidence is in `reports/verification.json`, `reports/browser-verification.json` and `reports/startup-verification.json`.

These checks cover the native local workspace. Full source-specific business rules, authentication and live provider operations remain incomplete as described above. Test servers were stopped after verification.

## AI workspace verification

All 294 AI feature routes were checked in the browser and show questions and formatted answers instead of the original record table. Existing records are retained as optional context. Questions, follow-ups, saved history across restart, Markdown tables, safe rendering, downloads, provider-failure recovery and mobile layout passed with a mocked provider. See `reports/ai-workspace-verification.json`.

Live answers require `OPENROUTER_API_KEY` and `OPENROUTER_MODEL` in this app's `.env` and an app restart. No live provider call was made during verification. Conversational answers do not execute unmigrated specialist engines, read record attachments automatically or perform external actions.


## AI word limits

Questions support up to 5,000 words with a live counter and server validation. AI responses and record drafts have a 16,000-token output budget and a default 180-second timeout to support answers up to 5,000 words; actual length depends on the request and model. Answers show their word count, and long questions can be expanded. Browser checks passed for 5,000-word questions and answers, saved history, full downloads, mobile layout and rejection of 5,001-word questions. See `reports/word-limit-verification.json` (mock-provider boundary checks).

## Merged AI assistants

294 original AI entries are now grouped into **8 assistants** in the sidebar. Choose up to 8 related capabilities and add up to 10 questions for one provider request and one saved response. Shared context is sent once; repeated questions are removed after trimming and whitespace/case normalization. The total question limit is 5,000 words and the combined answer target is up to 5,000 words.

Original feature URLs still open the appropriate assistant with that capability selected. Existing records and answers stay in place; the assistant history includes answers saved under its member features. Non-AI record tables retain their popup actions. This merges the assistant workflow and navigation; it does not implement previously missing external integrations or specialist engines. See `reports/assistant-merge-map.json` and `reports/assistant-merge-verification.json`.

## Floating Ask AI assistant

Implemented across this workspace. The bottom-right **Ask AI** button opens a persistent chat panel on every page. Use **Ask AI about item** in a row popup or record view, or **Use current item** inside the panel, to supply the selected record.

- Questions about the page, any explicitly chosen app record, and general topics.
- Formatted answers, comparison tables, follow-ups, copy and Markdown download.
- Conversation and question drafts stay intact during in-app navigation. Saved answers persist in SQLite; the last conversation restores in the same browser tab after reload. The latest 50 saved answers are listed; restoring one displays up to 20 turns. Up to four preceding turns are sent as AI context.
- Up to 5,000 input words and a response budget of up to 5,000 words. Output length remains dependent on the provider and the question.
- Page title and description are supplied automatically; record fields and notes are sent only for a selected item. Attachments and unselected records are not included. **New chat** starts without earlier conversation context.
- Existing AI provider configuration, timeout, rate limit and safe response renderer are reused. The assistant answers and drafts; it does not execute record changes or external actions.

Validation: shared backend tests, all 64 app builds/API checks, and all 64 browser checks passed with an injected test provider. Browser checks cover item context, navigation, saved history/reload, follow-ups, new-chat isolation, error recovery, word limits, keyboard controls, mobile bounds, safe Markdown rendering and attachment refresh. See [verification](reports/floating-ai-verification.json).
