[![smithery badge](https://smithery.ai/badge/@FerryZhaoHui/linear-test-mcp)](https://smithery.ai/server/@FerryZhaoHui/linear-test-mcp)

### Installing via Smithery

To install Linear Issue Tracker Integration for Claude Desktop automatically via [Smithery](https://smithery.ai/server/@FerryZhaoHui/linear-test-mcp):

```bash
npx -y @smithery/cli install @FerryZhaoHui/linear-test-mcp --client claude
```

### Setup

- Create Linear API Key
  - https://linear.app/dispatch-io/settings/account/security
- Create a `.env` file in the root directory based on `.env.example` with your Linear API key:
  ```
  LINEAR_API_KEY=your_linear_api_key_here
  ```
- run `npm install`
- run `npm run build`
- setup mcp
  - Exmaple https://modelcontextprotocol.io/quickstart/user
