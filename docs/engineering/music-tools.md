# 🔭 Connecting music tools to explicit requests

**Development project · public design note · AI-assisted implementation**

Project: **spotify-mcp**. Its implementation is not released through this note.

## The practical problem

A useful integration needs to turn a human request into a specific action whose result can be inspected.

## What the project explores

The staged Spotify integration exposes playback, search, queue, playlist, and library operations through Model Context Protocol. Its design distinguishes ordinary requests from destructive changes requiring confirmation.

## A synthetic example

A fictional user asks for a short playlist. The system resolves candidate tracks, presents the intended changes, and records the tool result after the user chooses what to do.

## Evidence and limits

Playback depends on account capabilities and an active device. API availability and platform rules can change. This note describes the project; it does not connect a reader's account or claim every operation is currently available.

## Why it belongs in this showcase

Clearer interfaces, explicit context, and observable results are building blocks for tools that people can understand and direct. Their value for the broader mission still needs to be evaluated.

[Engineering index](README.md) · [Our purpose](../mission.md) · [Sharing principles](../sharing.md)
