# Crowsi Zixcel AWS Adapter

`ZixcelAwsCredentialExecutor` composes the Crowsi credential-use boundary with
Zixcel's AWS-specific operation handling. It runs inside the trusted credential
runtime and does not expose secrets to callers.

Zixcel owns AWS schemas and operation semantics. Crowsi owns authorization,
custody and bounded execution. HAT grants, Hatter state and product UI do not
belong in this package.

## Acceptance

Verify exact operation/target binding, refusal outside the authorized scope,
secret-free projections and cleanup after provider failure. Configuration and
real provider execution must be verified separately from fixture tests. No AWS
account, external operation or credential is provisioned by installing this crate.
