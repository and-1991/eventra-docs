# Browser

```html
<script type="module">
import { Eventra } from "https://esm.sh/@eventra_dev/eventra-sdk";

const eventra = new Eventra({
  apiKey: "YOUR_API_KEY"
});

eventra.track("page_view", {
  userId: "user_123"
});
</script>
```
