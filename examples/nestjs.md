# NestJS

```typescript
import { Injectable } from "@nestjs/common";
import { Eventra } from "@eventra_dev/eventra-sdk";

@Injectable()
export class EventraService {
  private eventra = new Eventra({
    apiKey: process.env.EVENTRA_API_KEY
  });
}
```
