# Engineering Case Studies

**Real problems. Evidence-based diagnosis. Clear technical decisions.**

A public, bilingual collection of engineering case studies by **Juan Herbozo**. The focus is not just *what* was implemented, but **how the problem was understood, investigated, resolved, and validated** across enterprise systems, ERP, AI, cloud integrations, and data.

**Español:** [Leer este README en español](README.es.md)

## Case studies

| ID | Area | Case | Status | Languages |
|---|---|---|---|---|
| ECS-001 | Cloud & integrations | [When SMTP works but a serverless form returns HTTP 502](cloud-architecture/cloudflare-workers-smtp/README.md) | Resolved · validated | [EN](cloud-architecture/cloudflare-workers-smtp/README.md) · [ES](cloud-architecture/cloudflare-workers-smtp/README.es.md) |

## Areas

- **[Business Central & ERP](business-central/README.md)** — functional analysis, finance, warehouse, sales, integrations, upgrades, and migrations. Future cases will be generalized and rebuilt with synthetic data.
- **[AI & Intelligent Systems](ai-intelligent-systems/README.md)** — generative AI, AI in ERP, agents, retrieval, evaluation, and system design.
- **[Cloud & Integrations](cloud-architecture/README.md)** — runtime compatibility, deployment, APIs, messaging, and reliability.
- **[Data & Analytics](data-analytics/README.md)** — data modeling, quality, reporting, and operational dashboards.

## Templates

Use the [English](templates/case-study-template.md) or [Spanish](templates/case-study-template.es.md) documentation template.

## How each case is documented

1. **Context and observed behavior** — distinguish symptoms from assumptions.
2. **Impact and boundaries** — what failed, and what continued to work.
3. **Hypotheses and tests** — evidence supporting or rejecting each explanation.
4. **Decision and trade-offs** — what was changed and what was deliberately left untouched.
5. **Validation** — measurable success criteria and their results.
6. **Lessons and limitations** — what can be generalized and what remains unproven.

## Publication and confidentiality policy

These are **sanitized, educational reconstructions**, not exports of customer tickets or private production repositories. They never intentionally include customer identities, contracts, credentials, tokens, internal endpoints, production logs, proprietary source code, or real business records. Illustrative architectures and examples are generalized; any future executable examples must use synthetic information and pass a separate review before publication.

A successful outcome is described as **observed** only where a real validation exists. Hypotheses remain labeled as hypotheses; unresolved cases are not presented as resolved. Confidentiality and intellectual-property obligations take precedence over publication.

## Related writing

- Personal site: [juanherbozo.com](https://juanherbozo.com/)
- Technical article (English): [When an SMTP Integration Fails in Serverless](https://juanherbozo.com/en/blog/cloudflare-smtp-integration/)
- Artículo técnico (español): [Cuando una integración SMTP falla en Serverless](https://juanherbozo.com/es/blog/cloudflare-smtp-integration/)

*Linked article URLs should be checked after publication; the GitHub case study remains self-contained.*

## Scope and license

Documentation is provided for professional learning and discussion. **No open-source license is granted at this stage.** A future license will be selected explicitly if reusable code or diagrams are published.
