# 🔭 Seeing what the system actually used

**Development project · public design note · AI-assisted implementation**

Project: **llm-cost-meter**. Its implementation is not released through this note.

## The practical problem

Usage can be difficult to understand when logs come from different tools and attribution is incomplete.

## What the project explores

The staged meter reads existing usage records and summarizes tokens, latency, model and agent attribution, and appropriately labeled cost estimates. Missing evidence remains missing.

## A synthetic example

A synthetic report separates measured token fields, unavailable latency, unknown attribution, and estimated API-equivalent cost.

## Evidence and limits

An API-equivalent estimate is not an invoice or a subscription charge. A report cannot reconstruct fields the source never recorded. Real usage logs and identifiers are excluded from this showcase.

## Why it belongs in this showcase

Clearer interfaces, explicit context, and observable results are building blocks for tools that people can understand and direct. Their value for the broader mission still needs to be evaluated.

[Engineering index](README.md) · [Our purpose](../mission.md) · [Sharing principles](../sharing.md)
