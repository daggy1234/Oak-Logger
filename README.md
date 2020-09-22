# Oak-Logger

A simple and opinionated logging middleware for Deno oak.

## Useage
---

```ts

import logger from "https://deno.land/x/oak_logger/logger.ts";

//Register your Oak App

const app = new Application();

app.use(logger.logger)
app.use(logger.responseTime)

```

And thats it! You now have full easy and standard color coded logging. It will also add
`X-Response-Time` Headers to your code , removing boilerplate.

## Contributing and Issues

---

Please use github issues for feedback, feature-suggestions and bug reports.