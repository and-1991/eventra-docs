# Express

```javascript
import express from "express";
import { Eventra } from "@eventra_dev/eventra-sdk";

const app = express();

const eventra = new Eventra({
  apiKey: process.env.EVENTRA_API_KEY
});
```
