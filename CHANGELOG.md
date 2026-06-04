# Changelog

All notable changes to this project are documented here. The format follows
[Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

## [Unreleased]

### Added

- Initial extraction of the code generator (`cmd/modusgraph-gen`,
  `internal/{generator,parser,model}`) and the wrapper-entity runtime (`entity`) from
  the modusGraph fork (https://github.com/mlwelles/modusGraph).
- Generated code splits its imports: the generic typed primitives resolve to
  `matthewmcneely/modusgraph/typed`; the wrapper base resolves to
  `mlwelles/modusgraph-gen/entity`, aliased as `mgentity`.
