## 🚀 Quick Start

### Start Eliza with Gitpod

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/dforce-network/eliza/tree/main)

In `.env`, set

-   `EVM_PRIVATE_KEY` to your private key (TEST ONE ONLY!)
-   `OPENROUTER_API_KEY` and `OPENROUTER_MODEL` as its the default `modelProvider` in `./InteNetHelper.charactor.json`.

```
pnpm run start:debug --character="InteNetHelper.character.json"
```

Make the port 3000 public for the client in the tab `PORTS`, and copy the url

Use https://client.eliza101.xyz instead of the default local client. In the configuration, paste the public gitpod port(https://3000-XXXXX.ws-us118.gitpod.io)

For more details please refer to original documentation https://github.com/elizaOS/eliza
