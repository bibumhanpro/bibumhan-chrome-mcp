# chrome-mcp-bibumhan-shared

Internal shared types, constants, and message contracts used by the [mcp-chrome-bibumhan](https://github.com/bibumhanpro/bibumhan-chrome-mcp) Chrome extension and the [`mcp-chrome-bibumhan-bridge`](https://www.npmjs.com/package/mcp-chrome-bibumhan-bridge) Node.js Native Messaging host.

**Not intended for direct end-user consumption.** Public APIs are not guaranteed stable across minor versions — pin a specific version if you depend on it.

## Install

```bash
npm install chrome-mcp-bibumhan-shared
```

## Usage

```ts
import { TOOL_NAMES, NativeMessageType } from 'chrome-mcp-bibumhan-shared';
```

Subpath exports: `constants`, `types`, `tools`, `rr-graph`, `step-types`, `labels`, `node-spec`, `node-spec-registry`, `node-specs-builtin`, `agent-types`.

## Links

- Source & issues: <https://github.com/bibumhanpro/bibumhan-chrome-mcp>
- Bridge package: <https://github.com/bibumhanpro/bibumhan-chrome-mcp/releases>

## License

MIT
