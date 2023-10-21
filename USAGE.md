<!-- Start SDK Example Usage -->


```typescript
import { Test } from "test";

(async () => {
    const sdk = new Test();

    const res = await sdk.pets.createPets();

    if (res.statusCode == 200) {
        // handle response
    }
})();

```
<!-- End SDK Example Usage -->