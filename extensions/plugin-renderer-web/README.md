# @stackflow/plugin-renderer-web

Render active activity only using the stack state. this plugins can be used for web application to be served on the web browser

- [Documentation](https://stackflow.so)

## Usage

```typescript
import { stackflow } from "@stackflow/react";
import { webRendererPlugin } from "@stackflow/plugin-renderer-web";

const { Stack, useFlow } = stackflow({
  activities: {
    // ...
  },
  plugins: [webRendererPlugin()],
});
```
