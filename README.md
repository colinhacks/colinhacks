Engineer, open-sourcer, and ride-or-die TypeScripter. I build and maintain [Zod](https://github.com/colinhacks/zod), a TypeScript schema validation library with static type inference. I also wrote the initial proof-of-concept for [tRPC](https://trpc.io), though the modern incarnation is entirely built and maintained by [@katt](https://github.com/katt).


```ts some_data.ts
import { z } from "zod";

const User = z.object({
  id: z.number(),
  name: z.string(),
  email: z.string().email(),
  createdAt: z.date(),
});
```