# Serverless

```javascript
import { Eventra } from "@eventra_dev/eventra-sdk";

export default async function handler(req, res) {
  const eventra = new Eventra({
    apiKey: process.env.EVENTRA_API_KEY
  });
}
```
