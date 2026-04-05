# Node.js

```javascript
import { Eventra } from "@eventra_dev/eventra-sdk";

const eventra = new Eventra({
  apiKey: process.env.EVENTRA_API_KEY
});

eventra.track("server_event", {
  userId: "user_123"
});
```
