# 🔭 Consistent instructions across tools

**Development project · public design note · AI-assisted implementation**

Project: **cross-harness-canon**. Its implementation is not released through this note.

## The practical problem

Agent instructions can drift when each coding tool has its own independently maintained file.

## What the project explores

The staged project generates several harness entry files from shared configuration and checks whether the output still matches that source. It separates the common instruction body from a small set of tool-specific entry details.

## A synthetic example

A fictional research assistant uses two coding tools. A revised instruction reaches both generated entry files. A later hand-edit is detected as drift.

## Evidence and limits

On October 6, 2026, a local run of the staged package passed 33 tests covering rendering, drift, setup errors, and command-line behavior. This documentation does not publish that implementation or establish universal enforcement.

## Why it belongs in this showcase

Clearer interfaces, explicit context, and observable results are building blocks for tools that people can understand and direct. Their value for the broader mission still needs to be evaluated.

[Engineering index](README.md) · [Our purpose](../mission.md) · [Sharing principles](../sharing.md)
