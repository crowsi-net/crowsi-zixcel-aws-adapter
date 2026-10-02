# crowsi-zixcel-aws-adapter

Connect an authorized AWS operation to credential use inside Crowsi custody.

## What you can do

- Validate the AWS operation and principal purpose.
- Compose declared signing and runtime interfaces.

## Current scope

The caller supplies exact scope and transport. Neither adapter availability nor a valid plan grants AWS account access.

Package distribution is not activated by this documentation. Use the checked-in source and the declared dependency versions; published availability must be verified separately.

## Getting started

Install Rust 1.97 or newer and make the declared dependencies available. Use the configured private registry when a dependency is not distributed publicly. Run from this repository:

```sh
cargo test --locked
```

## Documentation and source

[Interface reference](docs/interface-reference.md)

[Usage guide](docs/getting-started.md)

[Schemas](schemas) · [Detailed documentation](docs) · [Implementation and public interfaces](src) · [Verification cases](tests) · [Contributing](CONTRIBUTING.md) · [Security reporting](SECURITY.md) · [License](LICENSE) · [Attribution notices](NOTICE)
