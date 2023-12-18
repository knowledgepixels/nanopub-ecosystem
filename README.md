# Nanopublication Ecosystem

This repository holds some general info and issues about the nanopublication ecosystem.

### 2nd Generation Nanopublication Services

- Applications
  - provide (graphical) user interfaces
  - get data from Query, Registry, and Archive services
  - _e.g. Nanodash_
- Nanopub Query services:
  - run queries
  - get nanopublications from Registry and Archive services
  - have coverage by agents/pubkeys (and optionally types)
  - are open or restricted
  - _currently in alpha version_
- Nanopub Registry services:
  - provide lists of nanopublications by pubkey/type
  - publish new nanopublications
  - get existing nanopublications from other Registry services and new ones from applications/users
  - have coverage by agents/pubkeys (and optionally types)
  - are open
  - _currently in design phase_
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
