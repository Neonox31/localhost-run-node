# Localhost.run

Open a tunnel with localhost.run and expose the url

```ts
import { createExternalUrl } from "localhost-run";

const result = await createExternalUrl({ port: 3000 });

console.log(result);

// Prints
// {
//   domain: '1234.lhrtunnel.link',
//   secure: 'https://1234.lhrtunnel.link',
//   insecure: 'http://1234.lhrtunnel.link',
// }
```

NOTE: this is a little personal project, it's not affiliated with localhost.run.  
This software currently rely on the presenc of `ssh` binary in your environment
