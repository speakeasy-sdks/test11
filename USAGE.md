<!-- Start SDK Example Usage [usage] -->
```typescript
import { Test } from "test";

async function run() {
    const sdk = new Test();

    const res = await sdk.pets.createPets({
        id: 596804,
        name: "string",
    });

    if (res.statusCode == 200) {
        // handle response
    }
}

run();

```
<!-- End SDK Example Usage [usage] -->