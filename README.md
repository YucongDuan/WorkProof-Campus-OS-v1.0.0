# DIKWP WorkProof Campus OS v1.0.0

**Open learner-rights, authentic-assessment and employer micro-apprenticeship evidence kernel**

```text
Mode: MESH95_LEARNER_AGENCY_VALUE_BOUNDARY_AUTHENTIC_ASSESSMENT_OUTCOME_CLOSURE
Protocol: WAPE-1000:2026-DRAFT
License: Apache-2.0
Automatic grading authority: 0
Automatic hiring authority: 0
Automatic payment authority: 0
Official apprenticeship-registration authority: 0
Automatic external-action authority: 0
```

WorkProof Campus helps vocational colleges, applied universities and workforce programmes turn employer briefs into protected, auditable learning experiences. It distinguishes simulation from learning-only work and production contribution; requires positive compensation and written IP/portfolio/data-use terms before production assignments; records AI-use declarations, named human review and a changed-context transfer defense; then issues portable, appealable evidence receipts and privacy-protected programme aggregates.

It is not another learning-management system, job marketplace or automated grading product. It is an open responsibility and evidence layer that can sit beside an LMS, project marketplace, credential wallet, career service or employer workflow.

## Why this exists

Open information does not prove that a learner can perform safely in a changed real-world context. Generative AI makes polished output easier while weakening the evidentiary value of an unaudited final artifact. Work-integrated learning can bridge education and employment, but it can also conceal uncompensated production work, coerced data use, opaque evaluation and unappealable reputation effects.

WorkProof therefore treats five things as inseparable:

1. the learner's informed and revocable participation;
2. the exact task mode and employer value boundary;
3. transparent AI use and evidence provenance;
4. named human review plus transfer under changed conditions;
5. correction, restitution and portable evidence after the programme.

## Core workflow

```text
institution + employer + learner purpose
  -> governed industry brief
  -> simulation / learning-only / production-contribution classification
  -> compensation + IP + portfolio + data-use terms where value is created
  -> learner assignment and support
  -> artifact + AI-use declaration
  -> named human review
  -> changed-context transfer defense
  -> portable capability receipt
  -> employer acknowledgement and value-transfer receipt
  -> privacy-threshold outcome aggregate
  -> appeal and five-receipt correction closure
```

## Production work is not free

A `PRODUCTION_CONTRIBUTION` brief cannot be activated or assigned unless it carries positive compensation and written terms. Assignment creates an auditable value commitment. Payment remains a human/authorized external process; the reference core records a receipt but never moves money automatically.

## Authentic capability, not output polish

A final artifact is insufficient. A portable receipt requires:

- a named human passing review;
- a materially changed prompt or operating condition;
- a named human-confirmed transfer defense;
- a versioned source submission and audit history.

No general intelligence, human-worth or secret employability ranking is produced.

## Run the synthetic demonstration

```bash
python -m pip install -e .
workproof demo --workspace .workproof-demo --reset
```

The demo writes:

```text
.workproof-demo/workproof-campus.db
.workproof-demo/reports/program-summary.json
.workproof-demo/reports/assurance-dossier.json
.workproof-demo/reports/assurance-dossier.md
.workproof-demo/reports/aggregate-dashboard.html
```

The bundled scenario is synthetic. It demonstrates code paths and invariants, not customer results.

## Verify the audit chain

```bash
workproof verify-ledger --workspace .workproof-demo
```

## Run tests and the bounded model check

```bash
make test
make audit
make model-check
```

## Loopback-only API

```bash
workproof serve --database .workproof-demo/workproof-campus.db --host 127.0.0.1 --port 8765
```

The reference server rejects non-loopback binding. It is not production hardened.

## Commercial deployment model

The open core can run an end-to-end pilot. Paid offerings should fund institution onboarding, SSO/SCIM, LMS/HRIS connectors, private deployment, cryptographic signing, employer/reviewer operations, industry task libraries, accessibility adaptation, evaluation design and support SLAs. Learner compensation is separate from platform revenue and may not be silently netted against service fees.

See:

- `docs/COMMERCIALIZATION.md`
- `pilot/EIGHT_WEEK_PILOT_SOW_CN_EN.md`
- `standardization/WAPE_1000_CORE_SPEC_DRAFT_CN_EN.md`

## Interoperability boundary

Reference mappings are provided for W3C Verifiable Credentials, 1EdTech Open Badges and CLR. They are unsigned exports and do not claim certification or endorsement.

## Research and legal boundary

This is a research alpha and author-side pre-standard implementation. It does not establish legal compliance, academic credit, professional licensure, registered apprenticeship status, learning impact, employment impact or product-market fit. Production use requires jurisdiction-specific labour, education, privacy, IP, accessibility, security and contract review.
