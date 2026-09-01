# Overview

[简体中文](overview.zh-CN.md) | [Docs Index](README.md)

## Purpose

In-process local paired-channel transport for Gnalloy tests and embedded deployments.

This module owns an I/O boundary. It creates or adapts Gnalloy Channels for a concrete transport while protocol parsing, business handlers, TLS policy, and observability remain in other modules.

## Repository Identity

- Module path: `gnalloy.org/transport-local`
- GitHub repository: `github.com/gnalloy/transport-local`
- Default branch: `dev`
- License: Apache-2.0

## Package Map
- `gnalloy.org/transport-local` (`local`)

## Direct Gnalloy Dependencies
- `gnalloy.org/gnalloy`

## Direct Dependents in the Current Module Plan
- No repository in the current module plan depends on this module directly.

## Architecture Position

Gnalloy keeps the core small and dependency-light. This repository is a replaceable module around one responsibility, connected through explicit Go packages instead of runtime discovery.

## Compatibility

The public import path is `gnalloy.org/transport-local`. Until the first stable tag is published, use `@dev` or an explicit pseudo-version selected by your dependency policy.
