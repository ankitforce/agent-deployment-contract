# Runtime-change review

- [ ] Record runtime/platform version and image digest.
- [ ] Record startup hooks and data reachable during warmup.
- [ ] Confirm snapshot, volume, and session-state treatment.
- [ ] Confirm approved Regions, residency requirement, VPC/network boundary, and rollback path.
- [ ] Map every remote tool or MCP server to an execution identity, bounded policy, owner, and allowed operations.
- [ ] State which consequential actions require a human approval.
- [ ] State the stop condition and escalation owner.
- [ ] Record tool calls, approvals, outputs, failures, retention period, and evidence owner.
- [ ] Test a rollback and a denied-access path before expanding production use.
