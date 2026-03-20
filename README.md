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
│   │   ├── 300b052015f4a6909ce17e2013a3e8ca574d2ad7.nq.gz
│   │   ├── 3232536b968d8668f5cfc2032248fa598e1933aa.nq.gz
│   │   ├── 4aa87e88bf3511c915247af89caf0e66c7aec129.nq.gz
│   │   ├── 8c0bd7e581591b4180055896cbf72ae8b36003fc.nq.gz
│   │   └── d601c88e38dd6cd5738980e1e6e9e0e63580c419.nq.gz
│   ├── lsp
│   │   ├── 300b052015f4a6909ce17e2013a3e8ca574d2ad7.nq.gz
│   │   ├── 3232536b968d8668f5cfc2032248fa598e1933aa.nq.gz
│   │   ├── 4aa87e88bf3511c915247af89caf0e66c7aec129.nq.gz
│   │   ├── 8c0bd7e581591b4180055896cbf72ae8b36003fc.nq.gz
│   │   └── d601c88e38dd6cd5738980e1e6e9e0e63580c419.nq.gz
│   └── repolex
│       ├── 300b052015f4a6909ce17e2013a3e8ca574d2ad7.nq.gz
│       ├── 3232536b968d8668f5cfc2032248fa598e1933aa.nq.gz
│       ├── 4aa87e88bf3511c915247af89caf0e66c7aec129.nq.gz
│       ├── 8c0bd7e581591b4180055896cbf72ae8b36003fc.nq.gz
│       └── d601c88e38dd6cd5738980e1e6e9e0e63580c419.nq.gz
├── blob
│   ├── 02acf41c647ba5e398a022fc67b07cf4c547b73b.nq.gz
│   ├── 05a27c313567d617c75e75376888e080e0b800ee.nq.gz
│   ├── 067b933e77e04156da70191e1e60d08236a44d3f.nq.gz
│   ├── 07806f8af9dd3253ebdb5710b67e73124aea4941.nq.gz
│   ├── 0a731d5366cd4d742808a0e37568da73a0f5b569.nq.gz
│   ├── 0b3967a49c56bb2b5f3283b068be6f346654e5b1.nq.gz
│   ├── 111433c19de36aed5d33e349e75b0d332b6697af.nq.gz
│   ├── 1ad1c9f663fae2aa86719ad20806e3ee33d0afbd.nq.gz
│   ├── 1ad991b631d7305fb800b595b6ad93ee65cd8d99.nq.gz
│   ├── 1c1efc9103455673b38c8bc6c1ff292da7849b13.nq.gz
│   ├── 21b2f782732c8b7eeb1e6a350a41559b8a0fe302.nq.gz
│   ├── 27245d8e96b7ca1faceae38aeab5aab6b3adb38e.nq.gz
│   ├── 273a06fd01383b27031660bae08cd1f8acb6c52d.nq.gz
│   ├── 28f1f8b6fa95bb668572a42fead9fa4a9a39b999.nq.gz
│   ├── 295a74fdda359fbf14b6f821a648793d684450de.nq.gz
│   ├── 2c6570ee1cf2557a0ea52406f9b811469d97e7e4.nq.gz
│   ├── 2e698a92b2f0bfba3363b83b0199cda4d8366de1.nq.gz
│   ├── 33ff8a659427d6a9a22b7e53014ee51117a5829f.nq.gz
│   ├── 34b828d0f882e989485191f8c14c4a047a57110c.nq.gz
│   ├── 372cb0f80b62920300cce644c2ef29e5d5e0a83b.nq.gz
│   ├── 3ac073faba2a4a6ff24f47ccb03c556dc1f81ff3.nq.gz
│   ├── 3cd5b871ca9b725ad2e58aef99e9cd2f901675da.nq.gz
│   ├── 3d285b0f7f23894b3c4e363a0f261830070e6cb5.nq.gz
│   ├── 3e51f8b5159c55d1ebfbd6294a346f4d1764e516.nq.gz
│   ├── 42072b99b05c772cedbd10f62a2d99079fd1e597.nq.gz
│   ├── 4306f5d42242bbaf9c285fd3c4809e314ef47614.nq.gz
│   ├── 46f67f105ceb74b78c69d7b4a4a53d689e258fa5.nq.gz
│   ├── 4923d060ed58545b479c55f73243237cffee7a54.nq.gz
│   ├── 4a94d649f497d2b16c55132a7b4993894a954bc3.nq.gz
│   ├── 4b519a4e379f1f9608308323a995ec0e8bbcd542.nq.gz
│   ├── 4c401e50836116271bf5308e37b4b9e4336d7ec6.nq.gz
│   ├── 4c49ab7a677074185038f5f893a1ed4093cd47e5.nq.gz
│   ├── 4fb793c3514048602adcdf00916150b2dea05014.nq.gz
│   ├── 50ea1d8c67aed3e507ab27ff88d5d0a672e4e9b7.nq.gz
│   ├── 512a7d9f2fa279535d5d1c997f190be91c0a6fe6.nq.gz
│   ├── 53df9a55bb273373f55dd7c82930761e503705d6.nq.gz
│   ├── 55dea1494f7c5504ce0661f9097058a8aa4fbd88.nq.gz
│   ├── 581d994ac1ed147f5e571846d4f27096499346b7.nq.gz
│   ├── 5849379588ea9b6cea8de47707076431da255b31.nq.gz
│   ├── 5b9358c302c0893c8deddcdcffc655b6cd2ace85.nq.gz
│   ├── 5c19a83eaea7e4d116996f78854cf2dfb4a65f2d.nq.gz
│   ├── 5f571fb16f8f4ca390ff220d9910914fcad131ef.nq.gz
│   ├── 5fab937fe2b0c1ecf8d1e544f7b4a19aaab06149.nq.gz
│   ├── 623ee67888b901216f3a5fa9a15ba6df509c5e3b.nq.gz
│   ├── 6842d0d3ef01d68540e67c3ec6dac7f13037810f.nq.gz
│   ├── 6b301a5c56958694ce0b5da8f989e8d00b6ad6ee.nq.gz
│   ├── 6b48e0a2354c857c8db36316a6e0b52cabfd8487.nq.gz
│   ├── 6db2724e7ff911e1acc59578e9065a67dbe7a72c.nq.gz
│   ├── 6debbca99baf9929e3e5edc198cfa73241dc1c6e.nq.gz
│   ├── 6fbe8d251867da3707de5b8c2aec1d3eaa273da8.nq.gz
│   ├── 7a7c8de926ff0b19548d5fe71862b57fd2f3040f.nq.gz
│   ├── 7afec192b764dd4a84e428d6d86c57715890f2e3.nq.gz
│   ├── 7d2831804d4f40cd5520dea47bcc3317e90384a9.nq.gz
│   ├── 81eb6d990cdaf0d0887b282a9c84e43c51c0f0ed.nq.gz
│   ├── 84dd9dbe9370088365e7320d38ac089064ce0a92.nq.gz
│   ├── 864ca2ccf17aa356a1a227402c37aa7a15fef81a.nq.gz
│   ├── 872516370c33bba87c944d2b57f0f02679b8e576.nq.gz
│   ├── 87e3241d21599025cb62a41a67cecb61ad01a603.nq.gz
│   ├── 881257570b791c5a9e348c639282c9ed0183fbab.nq.gz
│   ├── 89d9abb93e21bcc528e9b6996174da8bf82525a7.nq.gz
│   ├── 8d4b7d2f66bbc4e8518a8a93337746fb10a1b9cf.nq.gz
│   ├── 8e1598127c5d7d8626e36900d7d51f810bf67556.nq.gz
│   ├── 8f8c74697e4255d4ef5afe08437a5a0072cca8a6.nq.gz
│   ├── 94909342c16126bb205e060d216788a4742d6da3.nq.gz
│   ├── 95168bc95685f7a3b831dc55698ee4c9f320e8d5.nq.gz
│   ├── 95b48accaf6ab7cca1bf1eb6f729f62708e4d0ee.nq.gz
│   ├── 97089f3dc47aa239f505e4f61538baecb54eb423.nq.gz
│   ├── 975f7b437236e70aab53f58481a469dc0c680c61.nq.gz
│   ├── 97f0b7a7b0345beba1f492f881ec7f4c5ed71127.nq.gz
│   ├── 9829505ecf6e1aa20ec40c239e2377f1d1d5bde3.nq.gz
│   ├── 9b05776a680b1ef1f7b202b893e0a67a25950d74.nq.gz
│   ├── 9c8cdfdf72a80198ccc513f3805db5df05771510.nq.gz
│   ├── 9ede637bd3e6e3147d7c845614cf8a159438a248.nq.gz
│   ├── a3c12d583c37374cf2d70fbe12f500ce940c8e40.nq.gz
│   ├── a4ed8f708cedd77d7e9bb6cac55e6ccae3646b76.nq.gz
│   ├── a57b5396a8ad930c80eca8308e2981d096b6d02f.nq.gz
│   ├── a7997da7963ad20a2eaed8f837296255c5288e1a.nq.gz
│   ├── a7a5d21cc2d218ef61c351db2715c6004dc0a134.nq.gz
│   ├── a7edb4697c11f06e614c4483d549c8f9fd4313b1.nq.gz
│   ├── aada5639aef93bd280a8814a4341dc0b22e08553.nq.gz
│   ├── b77725d383dc460f7fbf785f9ecd9fc25764a0a7.nq.gz
│   ├── b77e9ca45661bb5b291dd331379e2b84c296157d.nq.gz
│   ├── b7adc90c3615d2118355e908363d88b8ebf6e918.nq.gz
│   ├── bcb38c01699818ee95312787e3dead48c4a34fb3.nq.gz
│   ├── be9ab54a76d607cdaf22b9082d677428c3910224.nq.gz
│   ├── c115010e2ce7f1c0ef3b650a35dca63991317995.nq.gz
│   ├── c289ddabaf1120bb5fd08edb54f0a6c864615562.nq.gz
│   ├── c6f54f2bd112cb18897940ec529ee990ceadd21a.nq.gz
│   ├── cb1744d187fd6e9405d2993e2751e69fba255e9b.nq.gz
│   ├── ccd742cb579fd42398148b74fd0f022af2f579fb.nq.gz
│   ├── cd1fdbd2306e1258207b6edba778e4d3ddb1d987.nq.gz
│   ├── ce55fb3aa3ef509d75bb6b37983b6d7147a66273.nq.gz
│   ├── ceb6db1eefc982b1a1666a9cd06a2faf10057fa2.nq.gz
│   ├── d0663db0d8f1edb38b29fd27b71a2cbf4636fcc0.nq.gz
│   ├── d07be0dc1bedc58c3ce32bb8a3c86f4b7cd86c0d.nq.gz
│   ├── d144ba55df594cc3fd23bf72f9f06aeb25e05a56.nq.gz
│   ├── d51bdbc76cbbf46fbebfe7f98321196ceeae9003.nq.gz
│   ├── d894e090972176fb1ee0d9f1ce53c1608cec1ff5.nq.gz
│   ├── d96a5f192f5831134f7b28732dcf4d3c1c475c05.nq.gz
│   ├── d9c1b63984011e4266bfa65535fedcf74efd5f76.nq.gz
│   ├── da05082de614a66aaa8764a783d47719c1ca6eda.nq.gz
│   ├── dad7bad5baf8a17b0bbef0dd26f35ad5f90c634b.nq.gz
│   ├── db617408dfe8c558932df5799c3a4b2d583814b0.nq.gz
│   ├── e0428ba9d3171bbcdadd6c2d892a57fc73fd2940.nq.gz
│   ├── e2a290cb654c5386559ac799b8bcc5f5dae30386.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── f0e710daf401e7cc39a24814534c4ac74634d363.nq.gz
│   ├── f2c4456c732a5fddfaff99d420191ba4d6163b85.nq.gz
│   ├── f36c0b2141965b38bc7abab370d50e8fdadf5217.nq.gz
│   ├── f65849413c897183a733b46f3218e7c5c123cd26.nq.gz
│   ├── f6f98598bb9119a5b3fe5e1ce65c86ccc5023086.nq.gz
│   ├── f7b3a4c0c688d7dbacc300f3fb654b35b4bb102c.nq.gz
│   ├── f915b1ecb5c225f43797e70be2f64a603be21bc1.nq.gz
│   └── ff9381a7e6e9f836d82a420a7dcc019f7a2d5a72.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   ├── 300b052015f4a6909ce17e2013a3e8ca574d2ad7.nq.gz
│   ├── 3232536b968d8668f5cfc2032248fa598e1933aa.nq.gz
│   ├── 4aa87e88bf3511c915247af89caf0e66c7aec129.nq.gz
│   ├── 8c0bd7e581591b4180055896cbf72ae8b36003fc.nq.gz
│   └── d601c88e38dd6cd5738980e1e6e9e0e63580c419.nq.gz
├── filetree
│   ├── 300b052015f4a6909ce17e2013a3e8ca574d2ad7.nq.gz
│   ├── 3232536b968d8668f5cfc2032248fa598e1933aa.nq.gz
│   ├── 3a69815be35b5e64795498598e6f2a17233df7c4.nq.gz
│   ├── 4aa87e88bf3511c915247af89caf0e66c7aec129.nq.gz
│   ├── 8c0bd7e581591b4180055896cbf72ae8b36003fc.nq.gz
│   └── d601c88e38dd6cd5738980e1e6e9e0e63580c419.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 145 files
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
