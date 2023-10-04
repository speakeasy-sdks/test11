<!-- Start SDK Example Usage -->


```typescript
import { Test } from "test";
import { CreatePetsResponse } from "test/dist/sdk/models/operations";

const sdk = new Test();

sdk.pets.createPets().then((res: CreatePetsResponse) => {
  if (res.statusCode == 200) {
    // handle response
  }
});
```
<!-- End SDK Example Usage -->