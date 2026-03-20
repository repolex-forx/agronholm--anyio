# Repolex Knowledge Graph of agronholm/anyio

RDF knowledge graph data for [agronholm/anyio](https://github.com/agronholm/anyio), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download agronholm/anyio
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d601c88e38dd6cd5738980e1e6e9e0e63580c419.nq.gz
│   ├── lsp
│   │   └── d601c88e38dd6cd5738980e1e6e9e0e63580c419.nq.gz
│   └── repolex
│       └── d601c88e38dd6cd5738980e1e6e9e0e63580c419.nq.gz
├── blob
│   ├── 05a27c313567d617c75e75376888e080e0b800ee.nq.gz
│   ├── 067b933e77e04156da70191e1e60d08236a44d3f.nq.gz
│   ├── 07806f8af9dd3253ebdb5710b67e73124aea4941.nq.gz
│   ├── 0b3967a49c56bb2b5f3283b068be6f346654e5b1.nq.gz
│   ├── 1ad1c9f663fae2aa86719ad20806e3ee33d0afbd.nq.gz
│   ├── 27245d8e96b7ca1faceae38aeab5aab6b3adb38e.nq.gz
│   ├── 273a06fd01383b27031660bae08cd1f8acb6c52d.nq.gz
│   ├── 28f1f8b6fa95bb668572a42fead9fa4a9a39b999.nq.gz
│   ├── 2c6570ee1cf2557a0ea52406f9b811469d97e7e4.nq.gz
│   ├── 372cb0f80b62920300cce644c2ef29e5d5e0a83b.nq.gz
│   ├── 3ac073faba2a4a6ff24f47ccb03c556dc1f81ff3.nq.gz
│   ├── 3e51f8b5159c55d1ebfbd6294a346f4d1764e516.nq.gz
│   ├── 42072b99b05c772cedbd10f62a2d99079fd1e597.nq.gz
│   ├── 4c49ab7a677074185038f5f893a1ed4093cd47e5.nq.gz
│   ├── 50ea1d8c67aed3e507ab27ff88d5d0a672e4e9b7.nq.gz
│   ├── 53df9a55bb273373f55dd7c82930761e503705d6.nq.gz
│   ├── 5f571fb16f8f4ca390ff220d9910914fcad131ef.nq.gz
│   ├── 6db2724e7ff911e1acc59578e9065a67dbe7a72c.nq.gz
│   ├── 81eb6d990cdaf0d0887b282a9c84e43c51c0f0ed.nq.gz
│   ├── 94909342c16126bb205e060d216788a4742d6da3.nq.gz
│   ├── 95168bc95685f7a3b831dc55698ee4c9f320e8d5.nq.gz
│   ├── 95b48accaf6ab7cca1bf1eb6f729f62708e4d0ee.nq.gz
│   ├── 97089f3dc47aa239f505e4f61538baecb54eb423.nq.gz
│   ├── 9829505ecf6e1aa20ec40c239e2377f1d1d5bde3.nq.gz
│   ├── 9ede637bd3e6e3147d7c845614cf8a159438a248.nq.gz
│   ├── a3c12d583c37374cf2d70fbe12f500ce940c8e40.nq.gz
│   ├── a7a5d21cc2d218ef61c351db2715c6004dc0a134.nq.gz
│   ├── aada5639aef93bd280a8814a4341dc0b22e08553.nq.gz
│   ├── c115010e2ce7f1c0ef3b650a35dca63991317995.nq.gz
│   ├── cb1744d187fd6e9405d2993e2751e69fba255e9b.nq.gz
│   ├── ce55fb3aa3ef509d75bb6b37983b6d7147a66273.nq.gz
│   ├── d0663db0d8f1edb38b29fd27b71a2cbf4636fcc0.nq.gz
│   ├── d894e090972176fb1ee0d9f1ce53c1608cec1ff5.nq.gz
│   ├── d9c1b63984011e4266bfa65535fedcf74efd5f76.nq.gz
│   ├── da05082de614a66aaa8764a783d47719c1ca6eda.nq.gz
│   ├── db617408dfe8c558932df5799c3a4b2d583814b0.nq.gz
│   ├── e0428ba9d3171bbcdadd6c2d892a57fc73fd2940.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── f2c4456c732a5fddfaff99d420191ba4d6163b85.nq.gz
│   ├── f36c0b2141965b38bc7abab370d50e8fdadf5217.nq.gz
│   ├── f65849413c897183a733b46f3218e7c5c123cd26.nq.gz
│   ├── f6f98598bb9119a5b3fe5e1ce65c86ccc5023086.nq.gz
│   ├── f7b3a4c0c688d7dbacc300f3fb654b35b4bb102c.nq.gz
│   └── f915b1ecb5c225f43797e70be2f64a603be21bc1.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── d601c88e38dd6cd5738980e1e6e9e0e63580c419.nq.gz
├── filetree
│   └── d601c88e38dd6cd5738980e1e6e9e0e63580c419.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 54 files
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

## Source repository

[agronholm/anyio](https://github.com/agronholm/anyio)

---
*Parsed on 2026-03-20 by [repolex](https://repolex.ai)*
