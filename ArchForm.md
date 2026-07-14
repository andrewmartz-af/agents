# ArchForm Context for AI Agents

This file gives future AI agents enough context to help with ArchForm work without needing to rediscover the business from scratch. It combines public context from archform.com with project chat/thread summaries and local ArchFormAI artifacts. It is not a source of truth for current pricing, clinical instructions, legal commitments, or customer-specific facts; verify those from current systems before acting externally.

## Short Summary

ArchForm is a digital orthodontics company. It provides orthodontic treatment-planning software and related production workflows for clear aligners, in-office aligners, direct-print aligners, indirect bonding trays, robotic aligner trimming, and outsourced aligner manufacturing.

The core value proposition is giving doctors more control, speed, flexibility, and margin than traditional outsourced aligner workflows. ArchForm helps practices move from scans to treatment setup, STL export, printing/manufacturing, packaging, and patient delivery with less back-and-forth.

## What ArchForm Does

ArchForm is best understood as an orthodontic production platform rather than just a design tool. Its surface area includes:

- Orthodontic design software for treatment planning from intraoral scan files.
- Automated segmentation, tooth labeling, trimming, hollowing, supports, staging, attachments, bite stops, IPR, pontics, bite shifts, arch shape control, and print preparation.
- In-office thermoforming workflows where practices print models and make aligners themselves.
- Factory-made aligners manufactured and shipped by ArchForm, including practice-branded packaging in supported markets.
- Direct-print aligner workflows using validated printers, resin, curing, centrifuge, and post-processing steps.
- Indirect bonding workflows for digital bracket placement, bracket libraries, transfer tray generation, and optional design/manufacturing service.
- ArchMill, a desktop 5-axis aligner trimming machine with cloud trim paths and automated model detection.
- Dashboard/order workflows for patient/order tracking, design services, manufacturing, and production status.

Public positioning emphasizes same-day starts, higher profitability, reduced lab bills, better clinical control, in-office production, and the ability to move between braces and aligners in one ecosystem.

## Customers and Buyers

ArchForm serves orthodontists, general dentists doing ortho, practices with in-office labs, DSOs, dental labs, and manufacturing partners. Buyer motivation varies:

- Some want lower aligner cost.
- Some want clinical control over staging, attachments, IPR, and exports.
- Some want faster starts and refinements.
- Some want to bring aligners or indirect bonding in-house.
- Some want turnkey outsourced manufacturing while keeping case planning flexible.
- Some are evaluating direct-print aligners or robotic trimming as production technologies.

When helping with sales or onboarding, start with discovery. Ask what brought the person to ArchForm, what workflow they use now, what they want to see, and whether they care most about control, speed, cost, manufacturing, or clinical capability.

## Product and Workflow Pillars

### Design Software

The software is the center of the system. Public pages describe it as simple orthodontic design software that can go from scan to finalized treatment plan in minutes. Notable capabilities include automatic segmentation, automatic tooth labeling, adjustable attachments, staging control, IPR adjustment, bite stops, bite shifts, pontics, model trim tools, auto-orientation, automatic aligner count, and print-ready exports.

### In-Office Aligners

For in-office thermoforming, the workflow is scan, import, design, export print-ready models, 3D print, thermoform, trim/polish, and package. Local follow-up notes frame this as a good path for practices that already own printers or want maximum cost savings and same-day starts.

### Factory-Made Aligners

ArchForm can manufacture aligners in its California robotic factory and ship them to practices. The public site emphasizes high precision, low cost, quick turnaround, scalloped trimlines, high-resolution printing, Zendura FLX material, robotic trimming, polishing, and optional custom packaging where available.

### Direct Print Aligners

Direct print is a software plus hardware plus resin workflow. Public materials describe ShapeForm shape-memory polymer, print-ready aligner shell and support generation, validated printers, nitrogen UV curing, centrifuge post-processing, and hot-water washing. Treat direct print claims carefully: verify current regulatory, material, printer, and availability details before giving advice or making commitments.

### Indirect Bonding

The IDB workflow supports digital bracket placement, bracket/wire/tube library selection, arch-form presets, occlusal clearance checks, collision warnings, transfer tray generation, and custom groupings. ArchForm can support DIY design, design service, or manufactured trays depending on the customer's needs and geography.

### ArchMill

ArchMill is presented publicly as a 5-axis desktop aligner trimming machine. It uses ArchForm-generated cloud trim paths, model detection via vision/code reading, and can trim aligners quickly with a consistent edge. Verify availability, support status, and customer fit before positioning it externally.

## Pricing and Commercial Context

Do not treat pricing in this file as current. Pricing has appeared in project chats and customer follow-ups as operational context, including:

- Free starter/export credit, often described as $200.
- Self-setup/export pricing discussed as per-patient or per-STL in some contexts.
- Design service options, including technician-led and orthodontist-led setup/refinement routes.
- Manufacturing and shipping availability that can vary by geography.
- Special partnership, DSO, lab, reseller, or volume arrangements that need explicit confirmation.

Before writing to a customer or vendor, verify current pricing, credits, billing rules, manufacturing geography, and what product/service is actually live.

## Internal Operating Model

Project chats and local ArchFormAI artifacts show Andrew operating across product, clinical workflows, manufacturing, shipping, support, sales, partnerships, finance, and legal/vendor coordination. The general operating pattern is:

1. Identify the real blocker.
2. Decide the smallest useful action that unblocks it.
3. State what is known, what is uncertain, and who owns the next step.
4. Use concrete artifacts: patient/case files, STL exports, software versions, screenshots, package dimensions, shipping labels, invoices, contracts, or meeting notes.
5. Preserve trust with customers, employees, vendors, and partners.
6. Avoid overcommitting when a feature, release, integration, material, or commercial term is not confirmed.

The work is cross-functional. A request may involve clinical behavior, software behavior, manufacturing details, shipping/account integrations, payments, contracts, onboarding, and customer communication all at once.

## Common AI-Agent Tasks

AI agents are likely to be useful for:

- Drafting customer follow-up emails after demos or support calls.
- Creating concise meeting briefs from calendar, Gmail, HubSpot, Zoom, and Slack context.
- Summarizing Slack/Gmail/Zoom activity without exposing unnecessary sensitive detail.
- Producing sales follow-up decks or PDFs tailored to a prospect's exact workflow.
- Preparing onboarding instructions for doctors testing their first case.
- Reconciling orders, invoices, shipping logs, tracking numbers, and outstanding balances.
- Drafting internal specs for product/engineering issues using observed behavior and example files.
- Distilling clinical/product reasoning into testable rules without inventing clinical facts.
- Helping with partnership evaluation, pilot structure, and customer segment selection.
- Creating durable Notion notes and task records from conversations.

## Communication Defaults

For sales calls and demos, lead with discovery and workflow. Do not launch into a generic feature list. Ask what the prospect is trying to do, then show the part of ArchForm that maps to their workflow.

For external emails, be plain, compact, and concrete. Use a greeting, answer/context, next action, and signoff. Preserve a useful paper trail when money, contracts, shipment, customer commitments, or support outcomes are involved.

For Slack/internal messages, be direct and action-oriented. Short messages are normal unless exact specs, links, facts, or decisions are needed.

For support, acknowledge the issue first, clarify what is true today, and give the next step. If ArchForm caused harm or delay, own it quickly and repair it.

## Guardrails for Future Agents

Do not invent or infer:

- Clinical instructions or treatment recommendations.
- Patient/customer identities or case-specific facts.
- Pricing, credits, discounts, or payment status.
- Bank details, payroll details, vendor payment details, or legal terms.
- Product availability, release dates, regulatory status, validated hardware/materials, or manufacturing geographies.
- Shipping addresses, package specs, tracking numbers, or account billing ownership.

Always verify exact facts from current source systems before external use. If a claim is based on a project artifact rather than a live system, say so.

For clinical/product reasoning, translate observations into testable hypotheses. Use real cases and artifacts, distinguish cosmetic issues from functional blockers, and avoid turning a single case observation into a universal rule.

For manufacturing/logistics, use exact specs. Separate manual workarounds from automated MES/dashboard behavior. If label generation or shipping-account automation is not working, identify the owning system and the practical workaround.

For partnerships, evaluate whether the opportunity can become a repeatable operating framework. Use pilots, customer-segment fit, measurable success criteria, and clear ownership.

## Useful Local Context in This Project

This repo appears to be an AI workspace for ArchForm research, automations, summaries, and generated artifacts, not the core ArchForm application repository.

High-signal local artifacts include:

- `style_algorithm_eval_2026-06-14/algorithm.md`: operating model for Andrew's cross-functional decision-making and communication patterns.
- `style_algorithm_eval_2026-06-14/report.md`: methodology and caveats for the Slack/Gmail/Zoom operating-model extraction.
- `outputs/zoom-meeting/ahmad-shalata-followup/`: sales follow-up PDF/HTML for orthodontist-led aligner planning, STL exports, Formlabs printing, and refinements.
- `outputs/zoom-meeting/terence-followup/`: IDB follow-up materials for in-house indirect bonding and self-printing.
- `outputs/zoom-meeting/presentations/adit-partnership-followup/`: partnership follow-up deck around patient communications and aligner adoption.
- `3dna_mike_order_shipping_summary.md`: example of order, invoice, and shipping reconciliation across Gmail, attachments, and tracking logs.
- `outputs/rfl_shipping_reconciliation/`: shipping reconciliation spreadsheets.
- `outputs/archform_circle_calculator/`: calculator artifact related to in-office aligner savings.

The project thread list also shows recurring automations for meeting briefs, Slack unread summaries, Zoom meeting follow-ups, top-customer outreach, and connector-driven Notion/Gmail/Slack workflows. Treat those as operational patterns: ArchForm uses agents to keep customer, meeting, sales, and internal follow-up loops moving.

## External Public Sources

Useful public pages:

- https://www.archform.com/
- https://www.archform.com/software
- https://www.archform.com/in-office
- https://www.archform.com/form-aligners
- https://www.archform.com/direct-print
- https://www.archform.com/idb
- https://www.archform.com/archmill

When public site copy conflicts with current internal knowledge, verify before acting. Some public pages contain placeholder-like wording in lower-priority sections, so rely on the strong product/feature claims but avoid quoting unsupported filler.
