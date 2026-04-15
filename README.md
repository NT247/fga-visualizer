# WorkOS FGA Model Visualizer

A visual tool for designing WorkOS Fine-Grained Authorization models before writing a single line of code.

## What this solves

The biggest friction in FGA adoption is the mental model gap. Developers know they need fine-grained permissions but struggle to map their product structure to a resource hierarchy before they can define it. This tool makes that step visual.

## What it does

**Model builder** - Add resource types, define parent-child hierarchy, and set relations with inheritance rules in the left panel.

**Visual canvas** - See your permission model rendered as a live tree with connections showing how access flows down the hierarchy.

**Schema output** - Generates WorkOS FGA YAML schema instantly as you build. Copy it directly into your WorkOS dashboard or API call.

**Permission tester** - Select a subject (human user or AI agent), a resource type, and an action to see whether access is granted or denied, with the full inheritance chain and evaluation steps shown.

## Why agent auth is included

WorkOS has identified agent identity as a core frontier: who are your agents and what are they allowed to do. FGA supports AI agent subjects natively, and the permission tester explicitly shows how human and agent access diverge.

## How to run

Open `index.html` in any browser. No server, no install, no dependencies beyond what loads from CDN.

## Built by

**Nivedita Thapa**: PM who has shipped auth, RBAC, and enterprise developer products from 0 to production.

niveditathapa.24@gmail.com

---

*Prototype built for the WorkOS PM role application. Not an official WorkOS product.*
