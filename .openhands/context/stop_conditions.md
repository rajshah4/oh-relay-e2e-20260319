# Stop Conditions

- Stop if `workflow_state.json.status` is `complete`.
- Stop if the next step is ambiguous.
- Stop if required context files are missing.
- Stop if the API call to create the next conversation fails.
- Stop after a successful handoff. Do not monitor the child conversation.
