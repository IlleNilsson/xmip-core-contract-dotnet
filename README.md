# xmip-core-contract-dotnet

Content contracts authored as .NET modules over the Xmip ABI: the .NET
counterpart of the Rust contract technologies, holding well-formedness always
and conformance when a contract is named (ADR-0042). A technology of
[xmip-core-contract](https://github.com/IlleNilsson/xmip-core-contract).

A module in .NET implements the same C ABI a Rust module does (ADR-0012); it
references `Xmip.Abi` from xmip-core-abi as a project and no Xmip Rust crate,
and none may be. Declared and not yet written; `architecture.toml` carries the
maturity.

## Verification

The included workflow is manual-only and calls the versioned shared workflow at
`IlleNilsson/.github@v1`.
