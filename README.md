# Agent Deployment Contract

A small, vendor-neutral record for reviewing an AI-agent runtime change before it changes state, placement, identity, tool reach, or human control.

Canonical article: [The Deployment Contract Is Now Part of the Agent Contract](https://ankitkumar3514.substack.com/p/agent-deployment-contract)

## Start here

1. Read [the review checklist](checklists/runtime-change-review.md).
2. Copy [the example record](templates/agent-deployment-contract.example.json).
3. Validate it with [the JSON Schema](schemas/agent-deployment-contract.schema.json).

## What a human can use

Use the checklist when a runtime version, region, VPC setting, snapshot behavior, MCP connection, or approval workflow changes.

## What an agent can do

Read `AGENTS.md`, then validate a supplied deployment record against the schema and report missing ownership, access, review, or evidence fields. Do not infer access permissions or execute any deployment.

## Intentionally excluded

This repository does not prescribe a cloud vendor, grant IAM permissions, store credentials, or replace a threat model, incident process, or legal review.
