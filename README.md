# Nanopublication Ecosystem

This repository holds some general info and issues about the nanopublication ecosystem.

### 2nd Generation Nanopublication Services

- Applications
  - provide (graphical) user interfaces
  - get data from Query, Registry, and Archive services
  - _e.g. Nanodash_
- Nanopub Query services:
  - have coverage by agents/pubkeys (and optionally types)
  - run queries
  - get data from Registry and Archive services
  - are open or restricted
  - _currently in alpha version_
- Nanopub Registry services:
  - have coverage by agents/pubkeys (and optionally types)
  - provide lists of nanopublications by pubkey/type
  - publish new nanopublications
  - are open
  - _currently in design phase_
- Nanopub Archive services:
  - have coverage by URI/hash prefix
  - provide individual nanopublications by URI/hash
  - get data from Registry services
  - are open
  - _to be developed_
- Nanopub Dump services:
  - provide bulk nanopublication files
  - get data from Archive, Registry, and Query services
  - can be based on existing data repositories such as Zenodo
  - are open
  - _to be developed_
