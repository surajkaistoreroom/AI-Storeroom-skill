# AI Storeroom — Product Catalog (Setup & Connections)

Each entry includes the product name and its required connections and setup logic.
Use this file to populate the "Required Connections & Setup" and product details columns.

---

## 1. AI Agents

**Intercom (Fin):** Connect help articles, product data, and support workflows. Configure resolution paths, tone, and handoff rules. Set up custom actions to trigger refunds, lookups, or escalations via API.

**Decagon:** Feed it your docs, past tickets, and product knowledge. Define escalation logic, response boundaries, and agent persona. Integrates with your CRM and ticketing stack — no model training needed.

**Sierra:** Plug in your knowledge base, policies, CRM, and APIs. Define goals, guardrails, workflows, and brand voice. Foundation models handle the AI layer — no LLM training required.

**Maven AGI:** Ingest support docs, FAQs, and historical conversations. Configure resolution workflows, tone, and escalation triggers. Plugs into your CRM, ticketing, and knowledge systems out of the box.

**Moveworks:** Connect your HRIS, ITSM, knowledge base, and enterprise apps. Define approval workflows, access policies, and conversational flows. Employees get answers and take action without ever opening a ticket.

**Aisera:** Connect your IT, HR, and customer service systems. Define automation workflows, approval chains, and resolution paths. Auto-resolves requests across channels using your existing enterprise stack.

**Harvey:** Upload your firm's precedents, templates, and matter history. Define practice area focus, jurisdiction, and output format. AI works inside your existing document and review workflows.

**Paxton AI:** Set your jurisdiction, practice areas, and preferred memo formats. Define research scope and citation standards. Surfaces relevant case law and statutory analysis tailored to your firm's work.

**Spellbook:** Connect your contract templates, playbooks, and preferred clauses. Define redline standards, fallback positions, and risk thresholds. Drafts and reviews within your negotiation parameters.

**Lawhive:** Connect your legal templates, matter types, and client intake workflows. Define scope boundaries, jurisdiction focus, and escalation paths to human solicitors.

**Leya:** Upload your firm's precedents, case law, and internal research. Define practice area scope, citation preferences, and memo format. Surfaces answers from your own knowledge base alongside external legal sources.

**Candid Health:** Connect your payer contracts, billing rules, and claims data. Define denial logic, appeal workflows, and reimbursement priorities. AI flags issues before submission and automates follow-up across payers.

**Anterior:** Feed it your clinical guidelines, payer policies, and prior auth criteria. Define decision thresholds, escalation rules, and documentation requirements. Automates auth reviews while staying aligned with your clinical standards.

**Layer Health:** Connect your EHR and define abstraction targets by condition, registry, or quality measure. Set extraction rules, confidence thresholds, and review queues. Pulls structured data from unstructured records at scale.

**SmarterDx:** Integrate with your EHR and CDI workflows. Define query triggers, documentation gaps, and physician communication preferences. AI surfaces missed diagnoses and supports accurate coding before the claim goes out.

**OpenEvidence:** Set your specialty focus, clinical context, and preferred evidence sources. Define how answers are surfaced — summaries, citations, or differential support. Trained on medical literature.

**Abridge:** Connect your EHR and configure note templates by specialty and visit type. Define documentation preferences, section structure, and sign-off workflows. Converts clinical conversations into structured notes in real time.

**Ambience Healthcare:** Connect your EHR, specialty workflows, and documentation standards. Define note structure, coding preferences, and clinician review rules. Captures and structures clinical conversations in real time.

**Mercor:** Feed it your job requirements, evaluation criteria, and hiring benchmarks. Define screening logic, skill thresholds, and role-specific assessments. AI matches and vets candidates against your standards before a human reviews.

**Paraform:** Connect your open roles, recruiter network, and sourcing preferences. Define bounty structures, candidate criteria, and submission rules. Turns your hiring pipeline into a marketplace your recruiters can work against.

**Ashby:** Integrate your ATS workflows, hiring stages, and team permissions. Define pipeline rules, interview scheduling logic, and reporting metrics. Automates coordination and surfaces hiring insights across your entire funnel.

**Clari:** Connect your CRM, rep activity data, and forecast models. Define pipeline stages, deal scoring criteria, and revenue signals. AI projects outcomes and flags risk before it shows up in your quarterly number.

**Day.ai:** Connect your email, calendar, and CRM. Define relationship tiers, follow-up rules, and meeting context preferences. AI builds and maintains customer context automatically — no manual logging required.

**MaestroQA:** Connect your support conversations, QA rubrics, and agent performance data. Define scoring criteria, coaching triggers, and escalation patterns. AI reviews every interaction against your standards.

**Hightouch:** Connect your data warehouse and define audience logic, sync destinations, and refresh cadence. Set segmentation rules, activation triggers, and identity resolution preferences. Moves your customer data into every downstream tool.

**Pendo:** Integrate your product and define in-app guide triggers, user segments, and adoption goals. Set onboarding flows, feature spotlight rules, and feedback prompts. Surfaces behavior-driven insights without touching your codebase.

**Retool:** Connect your databases, APIs, and internal systems. Define UI components, access permissions, and workflow logic. Builds internal tools around your exact data and processes — no frontend team needed.

**Gumloop:** Connect your data sources and define automation flows using a visual builder. Set triggers, transformation logic, and output destinations. Automates multi-step workflows without writing code.

**Lindy:** Connect your email, calendar, CRM, and communication tools. Define tasks, triggers, and decision logic for each workflow. AI handles recurring work end-to-end — scheduling, follow-ups, research, triage.

**CrewAI:** Define agent roles, goals, and collaboration logic. Connect your tools, APIs, and data sources each agent needs. Orchestrates multi-agent workflows where specialized agents hand off tasks to each other.

**Letta:** Define agent memory structure, persona, and task scope. Connect your knowledge bases, APIs, and long-term data stores. Builds agents that remember context across sessions and evolve with every interaction.

**Composio:** Connect your SaaS tools and define the actions each agent is allowed to take. Set permission boundaries, authentication flows, and integration scope. Gives your AI agents hands without building every integration from scratch.

**AgentOps:** Connect your agent framework, LLM providers, and deployment environment. Define tracking events, session replay rules, and alert thresholds. Monitors every agent run so you can debug, optimize, and audit at scale.

**Browser Use:** Connect your web workflows and define the tasks agents need to execute in a browser. Set allowed domains, action boundaries, and fallback logic.

**Skyvern:** Define the browser-based workflows you want automated — forms, portals, multi-step processes. Set navigation logic, data extraction targets, and error handling rules.

**Vapi:** Connect your backend, knowledge base, and telephony stack. Define conversation flows, interruption handling, latency preferences, and voice persona. Build and deploy voice agents across inbound and outbound use cases.

**Retell AI:** Connect your CRM, scripts, and call logic. Define conversation flows, transfer rules, and post-call actions. Deploys voice agents that handle real calls end-to-end — with your tone, your data, your workflows.

**Bland AI:** Upload your call scripts, objection handling, and CRM integrations. Define call goals, branching logic, and escalation triggers. Runs outbound and inbound calls at volume.

**TaxGPT:** Connect your tax documents, client data, and jurisdiction rules. Define research scope, memo format, and compliance standards.

**Basis:** Connect your GL, chart of accounts, and financial data sources. Define close workflows, reconciliation rules, and reporting preferences.

**Rillet:** Connect your ERP, billing system, and revenue data. Define recognition rules, consolidation logic, and audit trail requirements. Automates revenue accounting natively — built for SaaS financials.

**Numeric:** Connect your GL, close checklist, and accounting workflows. Define task ownership, review rules, and variance thresholds. Streamlines the month-end close.

**Campfire:** Connect your financial data, headcount plan, and operating assumptions. Define scenario logic, forecast cadence, and board reporting format.

**Truewind:** Connect your QuickBooks, Stripe, Ramp, and other financial sources. Define categorization rules, entity structure, and reporting preferences.

**Finaloop:** Connect your ecommerce stack — Shopify, Amazon, payment processors, and ad platforms. Define P&L structure, COGS logic, and reconciliation rules. Real-time books for ecommerce businesses.

**Zeni:** Connect your bank accounts, payroll, expenses, and billing systems. Define approval workflows, burn tracking preferences, and reporting cadence. Full-stack finance ops for startups.

**Levelpath:** Connect your ERP, vendor data, and procurement policies. Define approval workflows, spend categories, and compliance rules.

**Zip:** Connect your ERP, legal, security, and finance systems. Define intake forms, approval chains, and vendor onboarding requirements. Orchestrates the entire procure-to-pay process.

**Tropic:** Connect your vendor contracts, renewal calendar, and software spend data. Define negotiation playbooks, approval workflows, and savings targets.

**Tacto:** Connect your supplier database, RFQ workflows, and procurement specs. Define sourcing criteria, risk thresholds, and cost benchmarks. Built for industrial and manufacturing procurement.

**Prewave:** Connect your supplier list, tier structure, and risk tolerance parameters. Define monitoring categories — ESG, financial, geopolitical — and alert thresholds.

**Altana:** Connect your supplier network, trade data, and compliance requirements. Define mapping depth, risk categories, and regulatory scope. Builds a live AI-powered map of your entire supply chain.

**EliseAI:** Connect your property listings, leasing workflows, and resident communication channels. Define response logic, qualification criteria, and follow-up rules.

**Doorstead:** Connect your property data, pricing models, and maintenance workflows. Define rent optimization rules, tenant screening criteria, and operational thresholds.

**Jones:** Connect your vendor roster, insurance requirements, and compliance standards. Define certificate criteria, coverage minimums, and renewal tracking rules.

**Stake:** Connect your property management system and resident data. Define reward structures, cash back triggers, and retention incentives.

**VTS:** Connect your portfolio data, leasing pipeline, and tenant activity signals. Define deal stages, market comps, and asset performance benchmarks.

**Rogo:** Connect your internal research, filings, pitch decks, and financial databases. Define role-based permissions and query scope. Pull answers from your own deal data alongside public market intelligence.

**Clay:** Connect your data sources, enrichment providers, and outreach tools. Define table logic, enrichment waterfalls, and personalization variables. Set workflow triggers, CRM sync rules, and campaign sequencing logic.

**Apollo.io:** Connect your CRM and outreach stack. Define ICP criteria, sequence logic, and contact scoring rules. Set enrichment preferences, intent signal thresholds, and territory assignments.

**Unify:** Connect your product data, CRM, and intent signals. Define warm outbound triggers, account scoring logic, and personalization rules. Turns product usage and intent data into outbound motion.

**Common Room:** Connect your community platforms, product data, and CRM. Define member scoring rules, signal categories, and engagement thresholds. Turns community and product signals into revenue motion.

**Profound:** Connect your brand content, product data, and knowledge sources. Define AI search optimization targets, citation preferences, and monitoring scope. Optimizes your brand for how AI systems find and cite information.

**AthenaHQ:** Connect your GTM data sources. Define buyer intelligence scope, account research rules, and signal categories. Automates the account research layer.

**Qualtrics:** Connect your customer, employee, and product data sources. Define survey logic, experience metrics, and response workflows. Set alert thresholds, closed-loop action rules, and cross-program analytics.

---

## 2. Generative AI & Foundation Models

**OpenAI (ChatGPT/API):** Access foundation models via API. Build on top with fine-tuning, Assistants, and custom instructions. Define tool use, retrieval logic, and memory configuration.

**Anthropic (Claude):** Access Claude via API with system prompts, tool use, and document grounding. Define model behavior, safety boundaries, and output format at the system level.

**Cohere:** Connect your enterprise data and fine-tune on your domain-specific content. Define retrieval pipelines, embedding logic, and deployment environment.

**Mistral:** Deploy open or API-based models with full control over fine-tuning, hosting, and inference. Define model size, task specialization, and data residency requirements.

**Notion AI:** Connect to your existing Notion workspace — docs, databases, and projects. Define autofill logic, summary preferences, and writing assist rules.

**Coda:** Connect your data tables, external APIs, and team workflows. Define AI column logic, automation triggers, and doc-level instructions.

**Granola:** Connect your calendar and meeting stack. Define note structure, summary format, and follow-up templates by meeting type.

**Superhuman:** Connect your Gmail or Outlook. Define triage rules, follow-up preferences, and writing style. Set AI reply defaults, priority signals, and keyboard-driven workflows.

**Fireflies AI:** Connect your meeting stack — Zoom, Meet, Teams. Define note templates, topic trackers, and speaker labels. Set summary format, action item extraction rules, and CRM sync preferences.

**Cursor:** Connect your codebase. Define project context, coding conventions, and AI behavior rules via a cursor rules file. Set model preferences, autocomplete aggressiveness, and codebase indexing scope.

**Claude Code:** Connect your terminal. Define task scope, file permissions, and tool access. Set coding style preferences, test requirements, and iteration rules via conversation.

**Cognition (Devin):** Define the engineering task, repo access, and acceptance criteria upfront. Set review checkpoints, tool permissions, and escalation rules.

**Windsurf:** Connect your codebase. Define Cascade rules, project conventions, and context depth. Set autocomplete behavior, multi-file edit scope, and memory preferences.

**Perplexity:** Define your search scope, source preferences, and output format. Set citation standards, follow-up depth, and domain focus.

**Glean:** Connect your company apps — Drive, Slack, Notion, Jira, Confluence. Define access permissions, content indexing scope, and search ranking preferences. Set assistant personas, knowledge boundaries, and team-specific contexts.

**Hebbia:** Upload your documents — filings, contracts, research, reports. Define extraction schemas, query scope, and output structure. Set confidence thresholds, citation requirements, and workflow templates.

**Exa:** Connect your search pipeline. Define query types, content freshness, and source filters. Set embedding-based retrieval logic, crawl scope, and result format.

**Consensus:** Define your research question, study filters, and evidence quality thresholds. Set citation format, population scope, and outcome focus.

**Elicit:** Upload your literature set or define search scope across research databases. Set extraction schemas, inclusion criteria, and synthesis format.

**Guru:** Connect your existing knowledge sources — Slack, Notion, Confluence, support docs. Define card structure, verification cadence, and team-level permissions.

**Sana AI:** Connect your company knowledge base, communication tools, and people data. Define learning paths, knowledge retrieval logic, and assistant behavior by team or role.

**ElevenLabs:** Connect your text sources, content pipeline, and audio output destinations. Define voice persona, tone, pacing, and language preferences.

**Deepgram:** Connect your audio pipeline. Define model preferences, language targets, and domain-specific vocabulary. Set accuracy thresholds, speaker diarization rules, and latency requirements.

**Cartesia:** Connect your text pipeline. Define voice persona, prosody preferences, and output format. Set latency targets, language scope, and streaming configuration.

**Runway:** Connect your creative assets. Define generation style, motion preferences, and output resolution.

**Synthesia:** Upload your scripts. Define your AI avatar, language targets, and brand visual standards. Set scene templates, tone, and update cadence.

**Tavus:** Connect your data sources. Define personalization variables, avatar likeness, and delivery format. Set video triggers, CRM sync rules, and audience segmentation.

**OpusClip:** Connect your long-form video library. Define clip criteria, hook preferences, and platform targets. Set brand voice, caption style, and repurposing cadence.

**Captions:** Connect your video content. Define subtitle style, translation targets, and editing preferences. Set auto-cut rules and caption animation format.

**Gamma:** Connect your brand kit, data sources, and content library. Define slide structure, design language, and tone preferences.

**Tome:** Connect your brand assets and data sources. Define narrative structure and design rules.

**Pitch AI:** Connect your brand kit, data sources, and collaboration workflows. Define deck structure, design language, and version control rules.

**Jenni AI:** Connect your research sources and citation manager. Define academic style, citation format, and output structure.

**Mem:** Connect your notes, documents, and knowledge sources. Define tagging logic, retrieval preferences, and writing assist rules.

**Rewind:** Run on your device. Define capture scope, privacy exclusions, and search preferences.

**Limitless:** Connect your meetings, conversations, and daily context. Define what gets captured, summarized, and surfaced.

---

## 3. AI Infrastructure & Observability

**Groq:** Connect your inference pipeline. Define model targets, throughput requirements, and latency thresholds.

**CoreWeave:** Connect your training and inference workloads. Define compute allocation, cluster configuration, and scaling rules.

**Lambda:** Connect your ML workflows. Define instance types, storage configuration, and team access permissions.

**Scale AI:** Connect your model pipeline. Define data types, labeling schemas, and quality thresholds.

**Weights & Biases:** Connect your training pipeline. Define experiment tracking rules, metric logging preferences, and team collaboration settings.

**Langfuse:** Connect your LLM application. Define tracing scope, evaluation criteria, and prompt versioning rules.

**Arize AI:** Connect your models. Define performance monitors, drift detection rules, and evaluation datasets.

**WhyLabs:** Connect your ML pipelines and data streams. Define monitoring profiles, anomaly thresholds, and data quality rules.

**Lakera:** Connect your LLM application. Define prompt injection detection rules, content policies, and risk thresholds.

**Protect AI:** Connect your ML pipeline. Define vulnerability scanning scope, model risk policies, and compliance requirements.

**HiddenLayer:** Connect your model pipeline. Define threat detection rules, adversarial attack policies, and monitoring scope.

**Reality Defender:** Connect your content ingestion pipeline. Define detection scope, media types, and risk thresholds.

**Braintrust:** Connect your LLM application. Define evaluation datasets, scoring criteria, and prompt versioning rules.

**Humanloop:** Connect your LLM pipeline. Define prompt templates, model routing logic, and evaluation criteria.

**Patronus AI:** Connect your LLM application. Define evaluation suites, failure mode criteria, and compliance requirements.

**Galileo:** Connect your LLM pipeline. Define data quality rules, evaluation metrics, and error analysis scope.

**Arthur AI:** Connect your deployed models. Define performance monitors, fairness metrics, and drift detection rules.

**Vanta AI:** Connect your infrastructure, code repos, and compliance frameworks. Define control scope, evidence collection rules, and audit workflows.

**Drata AI:** Connect your cloud environment, identity systems, and compliance frameworks. Define control mapping rules, evidence automation scope, and audit readiness workflows.

---

## 4. Data, Analytics & Governance

**Atlan:** Connect your data sources, pipelines, and team workflows. Define metadata standards, lineage tracking rules, and access policies.

**Alation:** Connect your databases, BI tools, and data pipelines. Define catalog structure, curation rules, and stewardship workflows.

**Collibra:** Connect your enterprise data landscape. Define governance policies, data quality rules, and regulatory compliance requirements.

**MotherDuck:** Connect your DuckDB workflows, data sources, and cloud storage. Define query preferences, compute scaling rules, and collaboration permissions.

**Hex:** Connect your data warehouse, databases, and APIs. Define notebook templates, team permissions, and publishing rules.

**Omni:** Connect your data warehouse. Define semantic model structure, metric definitions, and access permissions.

**ThoughtSpot:** Connect your cloud data warehouse. Define search scope, pinboard templates, and access permissions.

**Cyera:** Connect your cloud environment. Define data classification rules, sensitivity policies, and compliance scope.

**Dataminr:** Connect your information feeds. Define signal categories, risk topics, and geographic scope.

**Endor Labs:** Connect your code repositories. Define dependency scope, vulnerability policies, and reachability analysis rules.

**Pangea:** Connect your application. Define security service scope — audit logging, embargo checks, redaction, and threat intel.

**People Data Labs:** Connect your data pipeline. Define enrichment targets, match criteria, and dataset scope.

**Hightouch:** Connect your data warehouse. Define audience logic, sync destinations, and refresh cadence.

---

## 5. Research, Knowledge & Enterprise Extras

**WisdomAI:** Connect your enterprise knowledge sources, documents, and expert content. Define retrieval logic, access permissions, and response boundaries.

**Persia:** Connect your data sources. Define personalization logic, audience segments, and content targeting rules.

**Stratify AI:** Connect your business data. Define segmentation logic, analysis scope, and reporting preferences.

**Dovetail:** Connect your research data — interviews, surveys, support tickets, and feedback. Define tagging schemas, insight templates, and team permissions.

**Sprig:** Connect your product. Define study triggers, participant targeting, and survey logic.

**Listen Labs:** Connect your research workflows. Define interview guides, participant criteria, and synthesis templates.

**Particl:** Connect your product catalog, pricing data, and competitive landscape. Define market tracking scope, category benchmarks, and alert thresholds.

**Lily AI:** Connect your product catalog. Define attribute taxonomy, enrichment rules, and search optimization logic.

**Motive:** Connect your fleet, driver data, and operations systems. Define safety thresholds, compliance rules, and maintenance triggers.

**Warp:** Connect your terminal workflows. Define AI command preferences, team sharing rules, and environment configuration.

**Veho:** Connect your logistics data, carrier systems, and customer communication stack. Define delivery routing rules, exception handling logic, and notification preferences.

**Buildots:** Connect your construction project data, BIM models, and site capture workflows. Define progress tracking rules, deviation thresholds, and reporting cadence.

**Trunk Tools:** Connect your construction documents, RFIs, submittals, and project data. Define query scope, document hierarchy, and response boundaries.

**Qure.ai:** Connect your radiology workflows, imaging systems, and EHR. Define detection scope, priority routing rules, and reporting preferences.

**PathAI:** Connect your pathology lab workflows, slide scanning systems, and clinical data. Define analysis scope, biomarker targets, and reporting templates.

**Tennr:** Connect your referral intake, EHR, and payer systems. Define document classification rules, data extraction schemas, and workflow routing logic.

**Onyx:** Connect your company knowledge sources — Confluence, Notion, Drive, Slack, and internal docs. Define retrieval logic, access permissions, and assistant behavior by team.

**Mem0:** Connect your AI application. Define memory types, retention rules, and retrieval logic.

**Graphiti:** Connect your data sources. Define entity types, relationship schemas, and graph update logic.

**Happenstance:** Connect your team data, collaboration tools, and organizational context. Define relationship mapping rules, connection triggers, and serendipity logic.

**Delve:** Connect your research content. Define synthesis scope, knowledge structure, and team access rules.

---

## Known ROI Calculators (Official)
- Intercom Fin: https://fin.ai/roi-calculator
- Vanta: https://www.vanta.com/roi
