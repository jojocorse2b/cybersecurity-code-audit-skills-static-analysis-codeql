# codeql

Scans a codebase for security vulnerabilities using CodeQL's interprocedural data flow and taint tracking analysis. Triggers on "run codeql", "codeql scan", "build codeql database", "SAST scan", "taint analysis", "dataflow analysis", or "find vulnerabilities in this repo". Covers Python, JavaScript/TypeScript, Go, Java/Kotlin, C/C++, C#, Ruby, and Swift. Supports "run all" (security-and-quality + security-experimental) and "important only" (high-precision) scan modes, and creates data extension models for project-specific sources and sinks. For fast single-file pattern matching, or when no build is available for a compiled language, use the semgrep skill; to parse SARIF that already exists rather than produce it, use the sarif-parsing skill.

## Overview

This directory contains the operational guidance for the `codeql` skill. Start with [SKILL.md](SKILL.md), which defines when to use it and the workflow it provides.

## Usage

Install or reference this directory through your agent's skill-discovery mechanism, then invoke `codeql` when the task matches the description above. Review linked resources in `SKILL.md` only when that workflow calls for them.

## Included resources

- `agents` — supporting material for this skill.
- `assets` — supporting material for this skill.
- `references` — supporting material for this skill.
- `scripts` — supporting material for this skill.
- `workflows` — supporting material for this skill.
