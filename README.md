# kody-clientsdk-js

Publishes the [kp-protocols-clientsdk](https://github.com/KodyPay/kp-protocols-clientsdk)
gRPC protos as an npm package (`@kodypay/kody-clientsdk-js`) on GitHub Packages, for
JS/TS consumers (e.g. KodyUniverse) that generate their own gRPC clients from the raw `.proto`.

## Release
Run the **JS SDK Build & Publish** workflow (`workflow_dispatch`), optionally passing the
`kp_tag` of kp-protocols-clientsdk to publish. The proto tree is pulled from that tag at
build time (nothing is committed to this repo), and published to npm with the same version.
