# Zerops + Nitro

![Header Image](https://storage-prg1.zerops.io/4gn35-objectstorage0/upload-dir/nitro-zerops.png)

A Nitro example for Zerops that you can deploy in 2 steps on zerops.

**Features**

- Nitro - [Next-gen Server toolkit by unjs](https://nitro.unjs.io)

## Instructions to Deploy on Zerops

1. Navigate to the Zerops Dashboard and locate the import project button on the sidebar.

2. Paste the Project Yaml

```yaml
project:
  name: zerops-nitro

services:
  - hostname: nitrojs
    type: nodejs@20
    buildFromGit: https://github.com/fxck/zerops-nitrojs
    ports:
      - port: 3000
        httpSupport: true
    enableSubdomainAccess: true
    minContainers: 1
```

If you still find yourself stuck in the process join our [Discord community](https://discord.gg/5ptAqtpyvh).
