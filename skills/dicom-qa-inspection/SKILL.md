---
name: dicom-qa-inspection
description: Specialized capability for Inspects medical imaging DICOM metadata and pixel arrays to verify slice thickness consistency, contrast phase, and patient de-identification.
license: MIT
allowed-tools: ""
metadata:
  author: "Rucha Salpure"
  version: "1.0.0"
  category: healthcare
---

# Radiology DICOM QA Agent — Dicom Qa Inspection Skill

## Purpose
The `dicom-qa-inspection` capability provides high-assurance execution routines for `Radiology DICOM QA Agent`.

## Execution Workflow
1. Validate input parameters against typed schemas and invariant constraints.
2. Ingest contextual metrics and establish a deterministic baseline.
3. Formulate candidate recommendations with explicit confidence intervals.
4. Submit draft plans to the independent checker agent for verification.

## Boundary Conditions
- **Input validation:** Reject non-conforming or malformed payloads before evaluation.
- **Fail-safe:** Escalate immediately if telemetry indicators exhibit critical anomalies.
