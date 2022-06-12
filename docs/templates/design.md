---
title: Design
---

Sample block of text.

> Special Text
> Written
> Here

Here is some shell code:

```sh
yarn add express              # add express as a dependency
yarn add -D @types/express    # add types for express as a dev dependency
```

This is a block of text that references some file `file.txt` and contains a link 
to [google](https://www.google.ca) if we want to redirect somewhere.

## First Header Title

Here are some options that can be set in a tsconfig.json with the block of code labelled appropriately for the file being referenced:
```json title="./tsconfig.json"
"noUnusedLocals": true,
"noUnusedParameters": true,
"noImplicitReturns": true,
```

## Second Header title

Heres how we can make some bullet points:

- its pretty easy to do
- you just add a dash and space before each line

Here is some typescript code that sets up an express server:

```ts
import express from 'express';

const main = async () => {
  const app = express();
  app.listen(4000, () => {
    console.log(`server started on localhost:4000`);
  })
}

main();
```