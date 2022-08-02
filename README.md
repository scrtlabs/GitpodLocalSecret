# GitpodLocalSecret

[![Gitpod ready-to-code](https://img.shields.io/badge/Gitpod-ready--to--code-blue?logo=gitpod)](https://gitpod.io/#https://github.com/scrtlabs/GitpodDevEnv)

### LocalSecret as a Service

Can't run your local secret environment because you're on M1, or too lazy to install docker? We got your back!

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/scrtlabs/GitpodDevEnv)

This will create an environment that automatically starts localsecret, and exposes the ports for application development. To connect,
prepend the port number with the gitpod url. e.g. if my workspace is at `https://scrtlabs-gitpoddevenv-shqyv12iyrv.ws-eu54.gitpod.io` then I would be able
to connect to the LCD service at `https://1317-scrtlabs-gitpoddevenv-shqyv12iyrv.ws-eu54.gitpod.io`.

This repo also comes with all the dependencies you need to develop Secret Contracts, and SecretCLI. 

### How is this different from Secret IDE?

[Secret IDE](https://github.com/digiline-io/Secret-IDE-Plugin) is an awesome tool, that sets up a Jetbrains IDE in the browser for you, with amazing templates to start from. However, it does not include the LocalSecret environment. This is mainly where this Gitpod container comes in handy, mainly for users that either:

* Are on M1, and cannot run LocalSecret locally
* Cannot, or don't want to install docker just to play with a contract
* Simply prefer the interface of VSCode to that of Jetbrains
