# Swift IEC

Swift implementations of IEC (International Electrotechnical Commission) specifications — a per-authority organization of [swift-standards](https://github.com/swift-standards), Layer 2 of the [Swift Institute](https://github.com/swift-institute) ecosystem.

## What this is

One package per specification, named `swift-iec-<number>`. Each package implements its source document as literally as possible — parsing, validation, and formatting enforced by Swift's type system — and defines its own namespace (`IEC_61966`). Where several specifications govern one subject, the unifying `swift-*-standard` package lives in [swift-standards](https://github.com/swift-standards).

## Coverage

| Package | Specification |
|---|---|
| [swift-iec-61966](https://github.com/swift-iec/swift-iec-61966) | sRGB color space |
| [swift-iec-80000-13](https://github.com/swift-iec/swift-iec-80000-13) | Quantities and units — Part 13: Information science and technology |

Every repository description carries the specification's full title; the [repositories tab](https://github.com/orgs/swift-iec/repositories) lists them all.

## Status

Public alpha. Maintained by [Coen ten Thije Boonkkamp](https://github.com/coenttb) — contributions welcome via pull request.

## License

All packages use the Apache License 2.0.
