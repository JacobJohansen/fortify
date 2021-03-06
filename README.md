# Fortify Desktop Application
Fortify enables web applications to use smart cards, local certificate stores and do certificate enrollment. This repository contains everything you need to build the desktop application and installers for the Fortify application.

## Install dependencies

```
npm install
```

> NOTE: `.npmrc` has `opessl_dir` param. Update it to your local path before `install` script run


## Build

```
npm run build
```

> NOTE: Put compiled `pvpkcs11.dylib` to project folder

> NOTE: PKIjs has [issuer](https://github.com/PeculiarVentures/PKI.js/issues/113). Use [instruction](https://github.com/PeculiarVentures/webcrypto-local#build--server) to fix it

## Thanks
Thanks to the [CA Security Council](https://casecurity.org/) for their support of this project and the many individuals from [Twitter](https://twitter.com/rmhrisk) who provided feedback and testing.
