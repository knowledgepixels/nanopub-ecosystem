# Nanopublication Ecosystem

This repository holds some general info and issues about the nanopublication ecosystem.

### 1st Generation Nanopublication Services

- Applications, e.g. [Nanodash](https://github.com/knowledgepixels/nanodash)
- [Nanopub Server](https://github.com/tkuhn/nanopub-server)
- [Nanopub Services](https://github.com/peta-pico/nanopub-services) / [Nanopub Signed Services](https://github.com/peta-pico/signed-nanopub-services)

### 2nd Generation Nanopublication Services

- Applications
  - provide (graphical) user interfaces
  - get data from Query, Registry, and Archive services
  - _e.g. future version of [Nanodash](https://github.com/knowledgepixels/nanodash)_
- Nanopub Query services:
  - run queries
  - get nanopublications from Registry services
  - have coverage by agents/pubkeys (and optionally types)
  - are open or restricted
  - _[currently in alpha version](https://github.com/knowledgepixels/nanopub-query)_
- Nanopub Registry services:
  - provide lists of nanopublications by pubkey/type and by URI/hash prefix
  - publish new nanopublications
  - get existing nanopublications from other Registry services and new ones from applications/users
  - have coverage by agents/pubkeys (and optionally types)
  - are open
  - _[currently in design phase](https://github.com/knowledgepixels/nanopub-registry)_
- Nanopub Archive services:
  - provide individual nanopublications by URI/hash
  - get nanopublications from Registry services
  - have coverage by URI/hash prefix
  - are open
  - _to be developed_
- Nanopub Dump services:
  - provide bulk nanopublication files
  - get data from Archive, Registry, and Query services
  - have coverage by pubkey/type or by URI/hash prefix
  - can hosted on existing data repositories such as Zenodo
  - are open
  - _to be developed_
