# Contributing to AllSense

Thanks for helping. AllSense by OtterBridge is spread over several repositories; this guide applies to all of them unless a repository has its own.

## Where things go

- **The app** is closed source. Report problems and ideas in [otterbridge-allsense](https://github.com/wen-da-ng/otterbridge-allsense/issues).
- **The protocol, test kit, clients, starters and docs** are open source (MIT), each in its own repository. The list, with how each one is tested: [Contributing](https://docs.allsense.otterbridge.org/contributing/) on the docs site.
- **Security problems:** report them privately, see [SECURITY.md](SECURITY.md).

## Sending a change

1. For anything bigger than a typo, open an issue first so we can agree on the approach.
2. Fork the repository, make the change, and run its tests (its README says how). Clients also run the shared conformance scenarios from the test kit.
3. Open a pull request that says what it changes and why. CI must pass, and a maintainer reviews every change before it's merged.

Keep changes small and focused, match the surrounding code, and add a test for new behaviour. Protocol changes start in [otterbridge-allsense-protocol](https://github.com/wen-da-ng/otterbridge-allsense-protocol): the spec, the shared vectors and the test kit change first, then the app and the clients.

## Licence

By contributing, you agree that your contribution is licensed under the repository's licence (MIT for the open-source repositories).

## Conduct

Everyone taking part follows the [Code of Conduct](CODE_OF_CONDUCT.md).
