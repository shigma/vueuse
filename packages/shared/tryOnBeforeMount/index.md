---
category: Component
---

# tryOnBeforeMount

Safe `onBeforeMount`. Call `onBeforeMount()` if it's inside a component lifecycle, if not, just call the function

## Usage

```ts
import { tryOnBeforeMount } from '@vueuse/core'

tryOnBeforeMount(() => {

})
```
