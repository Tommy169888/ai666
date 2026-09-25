---
name: asset-promotion-material
description: Generate owner-direct real estate asset promotion materials from user-provided source facts, with Chinese, English, and Khmer outputs and a mandatory verification checklist.
---

# Asset Promotion Material

Use this skill when the user asks to draft, package, translate, or standardize promotional material for land or property assets held for owner-direct sale.

## Core Boundary

Only use facts supplied by the user or by clearly identified source files. Never invent asset location, area, land/property nature, certificate status, price, ownership status, or transaction terms. If any required fact is missing, write `占位示例，数据待核` or `待确认` visibly in the output.

Do not publish, send, upload, or message external platforms. Prepare drafts only. Final factual review and external use require human approval.

## Required Inputs

For each land or property asset, request or extract these fields when available:

- Asset type: land or property
- Location
- Area: land area or building area
- Nature: land nature, property use, zoning, or permitted use
- Certificate status
- Asking price and currency
- Source material reference
- Contact method or contact placeholder

If the user has not provided real source material, produce a placeholder sample and label it `占位示例，数据待核`.

## Generation Structure

For each asset, generate the same structure:

1. Title
2. Overview
3. Key Metrics
4. Advantages
5. Contact Placeholder
6. Verification Checklist

## Output Languages

Provide three versions:

- Chinese
- English
- Khmer

Keep the English version suitable for international investors and LinkedIn-style business communication, but avoid exaggerated claims and unsupported superlatives.

## Verification Checklist

Every deliverable must include a checklist requiring human review before external use:

- Location verified against source material
- Area verified against certificate, survey, or owner file
- Nature/use verified against official or owner-provided source
- Certificate status verified
- Price and currency verified
- Contact information approved
- No unsupported investment return, legal, zoning, or guarantee claims

## Style

Use clear, direct, businesslike language. Mention `Direct Owner Sale` only when the user confirms it applies or when the broader task context already establishes owner-direct sale. Keep uncertain items as `待确认`.
