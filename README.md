# AI Red Team Report Template

A professional Word document template for AI/LLM red team engagement reports — built for practitioners who need a structured, polished deliverable that communicates findings clearly to both technical and executive audiences.

**Built by:** [CyberGemChick](https://github.com/cybergemchick) | AI Red Team

---

## What's Included

**AI_RedTeam_Report_Template.docx** — A complete report template covering:

| Section | Contents |
|---------|----------|
| Cover Page | Engagement title, date, version, TLP classification, practitioner info |
| Executive Summary | BLUF statement, risk summary matrix, top 3 priority actions |
| Engagement Overview | Scope, authorization, timeline, methodology |
| Attack Surface Summary | 5-layer AI attack surface table (Input/Model/Context/Output/Agentic) |
| Findings | Pre-formatted finding cards with severity, OWASP LLM, ATLAS mapping, evidence, remediation |
| Recommendations | Tiered by immediacy: 0–7 days, 30 days, 90 days |
| Appendix A | MITRE ATLAS technique coverage matrix |

## Who This Is For

- AI red team practitioners writing client deliverables
- Security teams documenting internal AI security assessments
- Researchers communicating AI vulnerability findings
- Students building out an AI security portfolio

## How to Use

1. Open `AI_RedTeam_Report_Template.docx` in Microsoft Word
2. Replace all `[BRACKETED PLACEHOLDERS]` with your engagement-specific content
3. Duplicate the `F-001` / `F-002` finding cards for each additional finding
4. Delete the `F-003` placeholder once your real findings are documented
5. Update the ATLAS coverage appendix with actual tested/untested technique status

## Finding Severity Definitions

| Severity | CVSS Range | SLA |
|----------|-----------|-----|
| CRITICAL | 9.0–10.0 | Remediate within 24 hours |
| HIGH | 7.0–8.9 | Remediate within 7 days |
| MEDIUM | 4.0–6.9 | Remediate within 30 days |
| LOW | 0.1–3.9 | Remediate within 90 days |

## TLP Classification Guidance

This template uses **TLP:RED** (Traffic Light Protocol). Adjust based on your engagement:

- **TLP:RED** — Not for distribution; named recipients only
- **TLP:AMBER** — Limited distribution; need-to-know within the organization
- **TLP:GREEN** — Community-shareable; not for public posting
- **TLP:CLEAR** — Unrestricted

## References

- [OWASP LLM Top 10](https://owasp.org/www-project-top-10-for-large-language-model-applications/)
- [MITRE ATLAS](https://atlas.mitre.org/)
- [NIST AI Risk Management Framework](https://www.nist.gov/artificial-intelligence/risk-management)
- [Traffic Light Protocol (TLP)](https://www.cisa.gov/tlp)
