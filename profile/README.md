# Swift IEC

Swift implementations of IEC (International Electrotechnical Commission) specifications — a per-authority organization of [swift-standards](https://github.com/swift-standards), Layer 2 of the [Swift Institute](https://github.com/swift-institute) ecosystem.

## What this is

One package per specification, named `swift-iec-<number>`. Each package implements its source document as literally as possible — parsing, validation, and formatting enforced by Swift's type system — and defines its own namespace (`IEC_61966`). Where several specifications govern one subject, the unifying `swift-*-standard` package lives in [swift-standards](https://github.com/swift-standards).

> Swift IEC is an independent open-source project. It is not affiliated with, endorsed by, or sponsored by the International Electrotechnical Commission.

## Find packages

Browse the organization's [Repositories tab](https://github.com/orgs/swift-iec/repositories) for the current package set. Use GitHub's native name, language, and topic filters to find a specification; each repository description carries its full title.

## Status

Public alpha. Maintained by [Coen ten Thije Boonkkamp](https://github.com/coenttb) — contributions welcome via pull request.

## License

All packages use the Apache License 2.0.
