# Issue contract — Cluster Energy Admission

## Problem
Large AI clusters admit jobs without energy envelope feasibility.

## Desired outcome
A bounded, open, testable implementation of **Cluster Energy Admission** that demonstrates Admit jobs only under measured energy/power envelopes with explicit reject receipts.

## Non-goals
- Nebius affiliation or proprietary integration
- Portfolio-wide scale/performance claims
- UI marketing site

## Acceptance
1. Mechanism module implements allow + refuse with structured receipts
2. pytest behavioral suite green
3. operate.py cold-start produces JSON receipt
4. Non-affiliation disclaimer preserved
