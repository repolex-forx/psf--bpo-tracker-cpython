# Repolex Knowledge Graph of psf/bpo-tracker-cpython

RDF knowledge graph data for [psf/bpo-tracker-cpython](https://github.com/psf/bpo-tracker-cpython), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [rlex](https://github.com/repolex-ai/rlex) query tool:

```bash
cargo install --git https://github.com/repolex-ai/rlex
```

Verify the install:

```bash
rlex --help
```

**rlex is designed to be used primarily by LLMs in a terminal.** Start up your favorite AI assistant and ask it to use rlex. It handles the SPARQL — you just ask questions in plain English.

To load this repo's data:

```bash
rlex download psf/bpo-tracker-cpython
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1a94f0977ca025d2baf45ef712ef87f394a59b25
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1a94f0977ca025d2baf45ef712ef87f394a59b25
│           └── chunk-001.nq.gz
├── blob
│   ├── 02a95e9f7cc50f210ca2e44c4a26eeaaf2ec7739.nq.gz
│   ├── 032e866d2c432ec1dfd51dd1ca724d28fb6a710c.nq.gz
│   ├── 03a7f719983383c0aa08321cc549caf6a47c1cf5.nq.gz
│   ├── 054247f2c018592ac99edbac5366448d9e512012.nq.gz
│   ├── 06e09765ad166af2bbec178cff6bdfecebda93a4.nq.gz
│   ├── 07818e133c461e293017495edab811eb1389295b.nq.gz
│   ├── 08ec901c17462c89f09e1248c3a4af693ef4b3b6.nq.gz
│   ├── 0983d79d2b0775f8b89d91370db0be98d4c38a9f.nq.gz
│   ├── 0bcdca6e48e75017037e837b0d6fba8662769fd6.nq.gz
│   ├── 0d72e1f74b4e326ca6db160a892a4e0a35487b08.nq.gz
│   ├── 18d3db4b5ac7b525cf39d84ed116e6a470bda4b4.nq.gz
│   ├── 19d2c2facf1471559b290f1c650925d849f13bc0.nq.gz
│   ├── 1a2af03cf53f3fd5304905033e50ad700a8d088c.nq.gz
│   ├── 1e20376e2c6417e78b1dfd4624b701df2ceef832.nq.gz
│   ├── 2293175a0ee4451a9627dd9d66ad09c3dabc1447.nq.gz
│   ├── 23e0f9a13b3b591d3a4e341e5f97ee435f51e63b.nq.gz
│   ├── 26f7312ba5378d6dc9fbc6a5f2e744c80617aca0.nq.gz
│   ├── 270e480f2018be3629396abff84f6f94267bf28e.nq.gz
│   ├── 28ba88467461df6de936b27469162e727320332c.nq.gz
│   ├── 2ba6d830b4429d9f01dfd0aa9dab54dc2415fc0b.nq.gz
│   ├── 2e70f933949c302abe582efdf13dbd01004c2d7a.nq.gz
│   ├── 3056f95c8c83b57702830e471e45746e5f81850b.nq.gz
│   ├── 4162d5ec670fe99e1cc8e163ad6a0fe34e9baa42.nq.gz
│   ├── 418ca2aa5f7ff22c9736297af93843458ee2bade.nq.gz
│   ├── 48a6ee46b45ef3f56c82ef321570e05e7dd2062b.nq.gz
│   ├── 4cd2c4f834582550495082bad7fe58946e5a0a1e.nq.gz
│   ├── 5823ac4ff2d21debe53b429eabb63c8b07c93002.nq.gz
│   ├── 582f941f4653d55c6ba5352bf40025f5b9b160e8.nq.gz
│   ├── 59ffc38f44230e661e5cd3e747ad4f2425bbd0f1.nq.gz
│   ├── 5a14a954ff7f86f504c2f25cb1819370d53317e0.nq.gz
│   ├── 5aa06740b6d62935e18dd77328f5102c82e2d193.nq.gz
│   ├── 5bada78bb7cb7a999096bb43f219e99012433665.nq.gz
│   ├── 5e47dc1aaee3b7bded0784c399e1e8bb763d95a8.nq.gz
│   ├── 775b578673119beca5f712fd42f70918465f7aa6.nq.gz
│   ├── 7eaadd3954b3de25bb7ac881b925ed63eed29b6d.nq.gz
│   ├── 7f37562707d5f9790f243223c85532811a623a41.nq.gz
│   ├── 8513486420ba2dd39c67a53a56e1bd36c5762c71.nq.gz
│   ├── 8b25551a97921681334176ee143b41510a117d86.nq.gz
│   ├── 8b6b1aefb6e8eef99a62ab1f44cd82c9871a325b.nq.gz
│   ├── 8e4606825e4f4bca251d8fd1bb1f84da3ef30265.nq.gz
│   ├── 926dab7f9dfa148434edad1c26ba072c5002a339.nq.gz
│   ├── 9271984d8058635352aa339318d22a5b2d8e1457.nq.gz
│   ├── 96be4cb0326db97f8ca91ca9615dbbcb7f5eb5d4.nq.gz
│   ├── 97c4272aa938852b80df0f40e6f73304045f9e39.nq.gz
│   ├── 9c7138e979aff93b1ec4efb43927dc38eb758f44.nq.gz
│   ├── 9d54613452c33b6e62edf6db51d044ed076a54c7.nq.gz
│   ├── a211b72c25a22b02443056c393f7c3a1027251eb.nq.gz
│   ├── a31f59c6f696b5aa44f6663318485468d81d47c8.nq.gz
│   ├── a45bed80997ddafd0dc7672ad8d658f2af5ad370.nq.gz
│   ├── a7a670a7bbe3dafc1e10c61523691ce9a00e4adc.nq.gz
│   ├── ad515a8e1e319b3fd2db1e423b0264fb14fb63be.nq.gz
│   ├── b2f7f073a29cba3c7919383f1926d958b3487297.nq.gz
│   ├── b61613ba7484ca115deaa1ef2f7a91593438436c.nq.gz
│   ├── b992f6d9ff6500efdbe807bedcdb8c831f139558.nq.gz
│   ├── b9c246f7e44a9973a7b789a48aa8235e5dffc69d.nq.gz
│   ├── baea0dbd4e770150d890400bfb8472c546cb7184.nq.gz
│   ├── bdd8ec673d6c4d2a3deffe54f805154e474b64d5.nq.gz
│   ├── c41a9aec8cc13fb73627975a370e0717eca36771.nq.gz
│   ├── c5a0c44c1d174d8a3ddaaab5fcf79b53086f958a.nq.gz
│   ├── c9efc5844a2627a8474949724a2aefe4ab2baee4.nq.gz
│   ├── ce557452c3ffcf6234ecb9374d11d1c162fe340f.nq.gz
│   ├── cfeceaacadb4d3fe8bb9dc5211000c26859c2426.nq.gz
│   ├── d1c2d36620e3ccb0de3beced713da2b254518e94.nq.gz
│   ├── d52b8cd133bdb37e199d46b2f3e5c452c356938a.nq.gz
│   ├── d8759303ee0b7759e6f936ab221cf3a03a50f560.nq.gz
│   ├── d90d51da74932c3449c60fd186c4cc5ac3311227.nq.gz
│   ├── dc0ed4f59f70107a6f3b2000edc5396f83489b8e.nq.gz
│   ├── dc6f536d4fb7e8bf30a8ce48345f73a4daa1a9d9.nq.gz
│   ├── e179fa8d6a9b53820af441c22ed3f38b91b7a0bd.nq.gz
│   ├── e2d8377db023a3915cc9e8c2f1f5c7462622f0a1.nq.gz
│   ├── e5b7ee10be805f7275f652f9afb526d59e8b06e4.nq.gz
│   ├── e6833c7bd03207c5ea4e092f614c35853f3b0397.nq.gz
│   ├── e7cb815d95bd462c6d48ad7543268e4d7c0d0fa9.nq.gz
│   ├── eb9848e5a72f366ba03f54619912089b3eb4e661.nq.gz
│   ├── eff098b3ce808c9393f15d5939f7b57a6b336948.nq.gz
│   ├── f0d64f9e93a91c8317e5a9e0d482960d36e897e7.nq.gz
│   ├── f1664567a63b47cdf89a43ca3bd36517867c592a.nq.gz
│   ├── fb385b9a7d1ba6d81b59b5449b72f5b49cbfe04d.nq.gz
│   ├── fbc9dd1a150ae1133b9dce38f82a80838f5329b0.nq.gz
│   └── ff4dff3bbf2c83706f4d44c491a83d5eb80acd09.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 1a94f0977ca025d2baf45ef712ef87f394a59b25.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 88 files
```

| Directory | What it contains |
|-----------|-----------------|
| `blob/` | Per-file AST graphs, content-addressed by git blob SHA. Each file in the source repo gets its own graph. |
| `aggregate/ast/` | Combined AST graph per parsed commit. Merges all blob graphs for a snapshot of the entire codebase at that point. |
| `aggregate/lsp/` | Language Server Protocol enrichment: resolved symbols, definitions, references, and type information. |
| `aggregate/dataflow/` | Interprocedural data flow edges between functions and modules. |
| `aggregate/repolex/` | Combined graph (AST + LSP + dataflow) per commit. |
| `commit/` | Git commit metadata (author, date, message, parent links). |
| `branch/` | Branch metadata. |
| `tag/` | Tag metadata. |
| `filetree/` | File tree snapshots per commit (which files existed and their blob SHAs). |
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[psf/bpo-tracker-cpython](https://github.com/psf/bpo-tracker-cpython)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
