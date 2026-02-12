## Component: AI Agent Architecture

### Objective
Define agent-based execution model for TodoGPT.

### Agents
- IntentAgent → understands user intent
- TaskAgent → performs task operations
- ResponseAgent → formats replies

### Rules
- Agents must be deterministic
- No agent may bypass MCP permissions
