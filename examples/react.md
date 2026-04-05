# React

```javascript
import { Eventra } from "@eventra_dev/eventra-sdk";

const eventra = new Eventra({
  apiKey: "YOUR_API_KEY"
});

export default function App() {
  return (
    <button
      onClick={() =>
        eventra.track("button_clicked", {
          userId: "user_123"
        })
      }
    >
      Click
    </button>
  );
}
```
