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
│   │   ├── 21bf6ac7d5e31c385090a244106aae507fa11052.nq.gz
│   │   ├── 300b052015f4a6909ce17e2013a3e8ca574d2ad7.nq.gz
│   │   ├── 3232536b968d8668f5cfc2032248fa598e1933aa.nq.gz
│   │   ├── 3a69815be35b5e64795498598e6f2a17233df7c4.nq.gz
│   │   ├── 3f8ad4bf6c81ee8944bd71cc1ff0718df485e422.nq.gz
│   │   ├── 4aa87e88bf3511c915247af89caf0e66c7aec129.nq.gz
│   │   ├── 7388defc3eb0422e001f2cbf473d921ba7c48835.nq.gz
│   │   ├── 74e8a3321ea99880fcf320f359abaa1e80654ee1.nq.gz
│   │   ├── 8c0bd7e581591b4180055896cbf72ae8b36003fc.nq.gz
│   │   ├── c1c827b91d5db4fac91f26a0071fcc7d26ff8403.nq.gz
│   │   ├── d601c88e38dd6cd5738980e1e6e9e0e63580c419.nq.gz
│   │   └── dda3c913d884056d98e7b5f1220b2d9ba455f0c4.nq.gz
│   ├── lsp
│   │   ├── 21bf6ac7d5e31c385090a244106aae507fa11052.nq.gz
│   │   ├── 300b052015f4a6909ce17e2013a3e8ca574d2ad7.nq.gz
│   │   ├── 3232536b968d8668f5cfc2032248fa598e1933aa.nq.gz
│   │   ├── 3a69815be35b5e64795498598e6f2a17233df7c4.nq.gz
│   │   ├── 3f8ad4bf6c81ee8944bd71cc1ff0718df485e422.nq.gz
│   │   ├── 4aa87e88bf3511c915247af89caf0e66c7aec129.nq.gz
│   │   ├── 7388defc3eb0422e001f2cbf473d921ba7c48835.nq.gz
│   │   ├── 74e8a3321ea99880fcf320f359abaa1e80654ee1.nq.gz
│   │   ├── 8c0bd7e581591b4180055896cbf72ae8b36003fc.nq.gz
│   │   ├── c1c827b91d5db4fac91f26a0071fcc7d26ff8403.nq.gz
│   │   ├── d601c88e38dd6cd5738980e1e6e9e0e63580c419.nq.gz
│   │   └── dda3c913d884056d98e7b5f1220b2d9ba455f0c4.nq.gz
│   └── repolex
│       ├── 21bf6ac7d5e31c385090a244106aae507fa11052.nq.gz
│       ├── 300b052015f4a6909ce17e2013a3e8ca574d2ad7.nq.gz
│       ├── 3232536b968d8668f5cfc2032248fa598e1933aa.nq.gz
│       ├── 3a69815be35b5e64795498598e6f2a17233df7c4.nq.gz
│       ├── 3f8ad4bf6c81ee8944bd71cc1ff0718df485e422.nq.gz
│       ├── 4aa87e88bf3511c915247af89caf0e66c7aec129.nq.gz
│       ├── 7388defc3eb0422e001f2cbf473d921ba7c48835.nq.gz
│       ├── 74e8a3321ea99880fcf320f359abaa1e80654ee1.nq.gz
│       ├── 8c0bd7e581591b4180055896cbf72ae8b36003fc.nq.gz
│       ├── c1c827b91d5db4fac91f26a0071fcc7d26ff8403.nq.gz
│       ├── d601c88e38dd6cd5738980e1e6e9e0e63580c419.nq.gz
│       └── dda3c913d884056d98e7b5f1220b2d9ba455f0c4.nq.gz
└── blob
    ├── 024b38783566ebfed2ea426d2ceb89d6f7372f45.nq.gz
    ├── 02acf41c647ba5e398a022fc67b07cf4c547b73b.nq.gz
    ├── 033d73c881305c7df501d4e92979c2dba64ecad7.nq.gz
    ├── 04cf5e1a92683d6a8309e059451c7a6e9c4f4d15.nq.gz
    ├── 04ec6c8be354cecb991487352639c98ce34de684.nq.gz
    ├── 05a27c313567d617c75e75376888e080e0b800ee.nq.gz
    ├── 067b933e77e04156da70191e1e60d08236a44d3f.nq.gz
    ├── 07806f8af9dd3253ebdb5710b67e73124aea4941.nq.gz
    ├── 08037c7399ab310d79f67f9460acc6c628d5dc5e.nq.gz
    ├── 088ccb3966464c967eee872cc7aedb8e19a541e9.nq.gz
    ├── 08adb23913bf61b582dbf7b7e695e493b01c3858.nq.gz
    ├── 0a55151e6256e512cc4128fdefa2a8309038cb1e.nq.gz
    ├── 0a709c94877eb197ec8c3413ffe8861ee9a2b4d1.nq.gz
    ├── 0a731d5366cd4d742808a0e37568da73a0f5b569.nq.gz
    ├── 0b3967a49c56bb2b5f3283b068be6f346654e5b1.nq.gz
    ├── 0b56db25c244aed43eca02d3207ce1b59d2f2d9d.nq.gz
    ├── 0cc9337203260b6e3dab9fb98eb7a3492ca9e59e.nq.gz
    ├── 10606447e85f3f1ae356ff08f376c2edc1fa8db9.nq.gz
    ├── 111433c19de36aed5d33e349e75b0d332b6697af.nq.gz
    ├── 121bd3769a26ca941f6dfa3ac372171f758eb319.nq.gz
    ├── 149a9087ed173947a66dab71446e24c942f6b82c.nq.gz
    ├── 1699326b67e4c79feb5e16308f05d6ece7aa1437.nq.gz
    ├── 16f7d961d9dfa73cbf93b59af3088accbff268de.nq.gz
    ├── 18b3dff703f0de902f77b01a8fc680b4fdaf4b05.nq.gz
    ├── 19cc7bd906dcd5917787d1a514c1b33b2d4e9ba6.nq.gz
    ├── 1ad1c9f663fae2aa86719ad20806e3ee33d0afbd.nq.gz
    ├── 1ad991b631d7305fb800b595b6ad93ee65cd8d99.nq.gz
    ├── 1b29972fc5f4ae1650efc10f9e8a90b3519df358.nq.gz
    ├── 1c1efc9103455673b38c8bc6c1ff292da7849b13.nq.gz
    ├── 1d87fb99dbec8065b5a2689e3d07ba416510e5f5.nq.gz
    ├── 1fa8737860eeef5c6b739fd9c19e80e68929b270.nq.gz
    ├── 21b2f782732c8b7eeb1e6a350a41559b8a0fe302.nq.gz
    ├── 25bce177df1a8017c2c9c5625213e9bf6a01f1e2.nq.gz
    ├── 261d3aa609e3ea7221a3bc44c26c22cbc51b5c96.nq.gz
    ├── 27245d8e96b7ca1faceae38aeab5aab6b3adb38e.nq.gz
    ├── 273a06fd01383b27031660bae08cd1f8acb6c52d.nq.gz
    ├── 2740bb7217cf619987256d4dd4ef8094d2b96928.nq.gz
    ├── 278d24d4590ef891059015a86dcb0cd27d46a30b.nq.gz
    ├── 2821829f018c076d83fe94d1bb5342925a282f35.nq.gz
    ├── 28f1f8b6fa95bb668572a42fead9fa4a9a39b999.nq.gz
    ├── 295a74fdda359fbf14b6f821a648793d684450de.nq.gz
    ├── 2b1dd1a88457a746506928977fe73d367af973eb.nq.gz
    ├── 2c451e8e9f5d52c456b5a6aef36a827fb5c2908e.nq.gz
    ├── 2c6570ee1cf2557a0ea52406f9b811469d97e7e4.nq.gz
    ├── 2d3008a54a4a5a8a5c4642cbef4de93979cab0cc.nq.gz
    ├── 2dfdbad62df84ede37da5312af73a798f132debb.nq.gz
    ├── 2e698a92b2f0bfba3363b83b0199cda4d8366de1.nq.gz
    ├── 33ff8a659427d6a9a22b7e53014ee51117a5829f.nq.gz
    ├── 3497c78c32b7a07df4c6796e9e38e92382236ce3.nq.gz
    ├── 34b828d0f882e989485191f8c14c4a047a57110c.nq.gz
    ├── 370c6924f2c77ccdb3a33213aa63b80c6114924d.nq.gz
    ├── 372cb0f80b62920300cce644c2ef29e5d5e0a83b.nq.gz
    ├── 394870b8db1c926100572184ae08df4eac6f69b4.nq.gz
    ├── 39d58ebc4a09d1185a0ceaaf259e2a06767ab2b2.nq.gz
    ├── 3a1d94648e4567fe3ab4c84c535dfffb7e3fbc3c.nq.gz
    ├── 3ac073faba2a4a6ff24f47ccb03c556dc1f81ff3.nq.gz
    ├── 3c68652152cf06fb7db18e58e82004fab36f3572.nq.gz
    ├── 3ca102680faa20d7c47cc9f831bf6a3fdff680f1.nq.gz
    ├── 3cd5b871ca9b725ad2e58aef99e9cd2f901675da.nq.gz
    ├── 3d285b0f7f23894b3c4e363a0f261830070e6cb5.nq.gz
    ├── 3e51f8b5159c55d1ebfbd6294a346f4d1764e516.nq.gz
    ├── 400a89ae9d40ef332d608d0db46e8d494bdbeb1f.nq.gz
    ├── 40bab39ae360e3aeb646e6868121031aaf00f789.nq.gz
    ├── 4153039f1f6bc0d9f418e8df64285984eb32e03c.nq.gz
    ├── 41a7b401ff41139c2bb33a45949f8638dd887070.nq.gz
    ├── 42072b99b05c772cedbd10f62a2d99079fd1e597.nq.gz
    ├── 4306f5d42242bbaf9c285fd3c4809e314ef47614.nq.gz
    ├── 46f67f105ceb74b78c69d7b4a4a53d689e258fa5.nq.gz
    ├── 478082cc21ea6d1a03203186be1fa1db2c9410c9.nq.gz
    ├── 47ba8f9af85598c46131a114bed4f461cc799f47.nq.gz
    ├── 4910ed1046f5bd3d09b6bd35568c9c5b2d292e2d.nq.gz
    ├── 4923d060ed58545b479c55f73243237cffee7a54.nq.gz
    ├── 4a94d649f497d2b16c55132a7b4993894a954bc3.nq.gz
    ├── 4b519a4e379f1f9608308323a995ec0e8bbcd542.nq.gz
    ├── 4b814e739aa533eb0ca403f0466fe8a7ca93ca08.nq.gz
    ├── 4c401e50836116271bf5308e37b4b9e4336d7ec6.nq.gz
    ├── 4c49ab7a677074185038f5f893a1ed4093cd47e5.nq.gz
    ├── 4c5f0f8b730e3a4c8fb8d94cea54a709b8890984.nq.gz
    ├── 4d0f66eda9b7699a11c71814f13844307a201827.nq.gz
    ├── 4fb793c3514048602adcdf00916150b2dea05014.nq.gz
    ├── 50ea1d8c67aed3e507ab27ff88d5d0a672e4e9b7.nq.gz
    ├── 512a7d9f2fa279535d5d1c997f190be91c0a6fe6.nq.gz
    ├── 513882f043c9bf6dcea2dcc9fc12238777d509de.nq.gz
    ├── 51e8c67b0a37ae5c09c1d37c5d79d1cbfffb95dc.nq.gz
    ├── 5343b2b4c9dd83dd6b1731e14315ac7992d0d307.nq.gz
    ├── 53df9a55bb273373f55dd7c82930761e503705d6.nq.gz
    ├── 54f2aa444ba6e5d9f58d508736aebfde933357c3.nq.gz
    ├── 5582c5784406e099068d0b5f31230f66c2365b32.nq.gz
    ├── 55dea1494f7c5504ce0661f9097058a8aa4fbd88.nq.gz
    ├── 560a8d2858c09e5fe1b2776be218101984d45fe4.nq.gz
    ├── 577f3f9d29d30d333d3be09bbc1a27628ed8e5d6.nq.gz
    ├── 581d994ac1ed147f5e571846d4f27096499346b7.nq.gz
    ├── 5849379588ea9b6cea8de47707076431da255b31.nq.gz
    ├── 58acfc9ea55a02e0236ab1111e19529b0216b5f9.nq.gz
    ├── 58bc249cafdb6de7879c0e148f26a27e9ec9a785.nq.gz
    ├── 5b9358c302c0893c8deddcdcffc655b6cd2ace85.nq.gz
    ├── 5c19a83eaea7e4d116996f78854cf2dfb4a65f2d.nq.gz
    ├── 5d207d77713d547ad091f8c60db59a38faea0025.nq.gz
    ├── 5f571fb16f8f4ca390ff220d9910914fcad131ef.nq.gz
    ├── 5fab937fe2b0c1ecf8d1e544f7b4a19aaab06149.nq.gz
    ├── 600d3f00d9f806fb63d09e0b78faeade7878a55e.nq.gz
    ├── 606849326a4002007fd42060b51e69a19c18675c.nq.gz
    ├── 608956494c7010c8fb93b9d61b8797a9ad58ff3a.nq.gz
    ├── 61b8fed4a1450177648ac907af5dbf410edca395.nq.gz
    ├── 623ee67888b901216f3a5fa9a15ba6df509c5e3b.nq.gz
    ├── 62740e5ecc19f218dd3c1c40a241721d69fdb14d.nq.gz
    ├── 63a8410222ac8b353e45d26f189d3037229b8b19.nq.gz
    ├── 66f81aff092a1823348823e55053b4adc1ddfc21.nq.gz
    ├── 680092410f0f1563a310f0904e5d65e0422c610b.nq.gz
    ├── 6842d0d3ef01d68540e67c3ec6dac7f13037810f.nq.gz
    ├── 689fdfd350ce50240957ec3f463b9f4e10d1c5b8.nq.gz
    ├── 6a0da5295f380e65241e9bfb028f03dee2d503ff.nq.gz
    ├── 6b301a5c56958694ce0b5da8f989e8d00b6ad6ee.nq.gz
    ├── 6b48e0a2354c857c8db36316a6e0b52cabfd8487.nq.gz
    ├── 6c364c6e4493bb23832e901ba96ca639591ab4f9.nq.gz
    ├── 6ca65b0cadf627f04c903570e346cd3419db03d7.nq.gz
    ├── 6cf447861091aca2ec8fbab76e28438c0eb82274.nq.gz
    ├── 6db2724e7ff911e1acc59578e9065a67dbe7a72c.nq.gz
    ├── 6debbca99baf9929e3e5edc198cfa73241dc1c6e.nq.gz
    ├── 6e5e7fae978c25e68fb155cc8c9f5e4acfdbda59.nq.gz
    ├── 6efd6c851de096af8c95790ee7b0931f6be2966b.nq.gz
    ├── 6fbe8d251867da3707de5b8c2aec1d3eaa273da8.nq.gz
    ├── 71c92853aa7cf86c153dd9e8e609307443d21b57.nq.gz
    ├── 74fc1f26e4dae5a5503d5c3b2df6786c503f4582.nq.gz
    ├── 78147e4aefb9924f50bb817898c39a8dd916ff35.nq.gz
    ├── 7a7c8de926ff0b19548d5fe71862b57fd2f3040f.nq.gz
    ├── 7afec192b764dd4a84e428d6d86c57715890f2e3.nq.gz
    ├── 7d2831804d4f40cd5520dea47bcc3317e90384a9.nq.gz
    ├── 81eb6d990cdaf0d0887b282a9c84e43c51c0f0ed.nq.gz
    ├── 82e505bde1adeeb6c85d282c738b9f680308935a.nq.gz
    ├── 84dd9dbe9370088365e7320d38ac089064ce0a92.nq.gz
    ├── 859549a651e18835d641d8a090a9e4ee50e8e6c2.nq.gz
    ├── 85fa1c29e529765fd87bb6893ef729397cc7cf0e.nq.gz
    ├── 864ca2ccf17aa356a1a227402c37aa7a15fef81a.nq.gz
    ├── 86d5e32fedbccde884d278f07baa4abb1c15ff32.nq.gz
    ├── 872516370c33bba87c944d2b57f0f02679b8e576.nq.gz
    ├── 87e3241d21599025cb62a41a67cecb61ad01a603.nq.gz
    ├── 881257570b791c5a9e348c639282c9ed0183fbab.nq.gz
    ├── 882a4a960659364f63260df52438a7d931778a38.nq.gz
    ├── 885c3f5dda47fe823fa17dc629609aacb85554ee.nq.gz
    ├── 8867b1fb68be849536586235f02d14d00185e530.nq.gz
    ├── 89d9abb93e21bcc528e9b6996174da8bf82525a7.nq.gz
    ├── 8b284146615eaa4b3fc22c371518bb3d1ec2baa7.nq.gz
    ├── 8c9daa3155ed1c416abe01c1b0332adfb02ffc58.nq.gz
    ├── 8d00597be532b295b397df864b8fd675ea296ecf.nq.gz
    ├── 8d4b7d2f66bbc4e8518a8a93337746fb10a1b9cf.nq.gz
    ├── 8e1598127c5d7d8626e36900d7d51f810bf67556.nq.gz
    ├── 8f8c74697e4255d4ef5afe08437a5a0072cca8a6.nq.gz
    ├── 8fbf68d156ad5684bde979e89a8bbaff01748eab.nq.gz
    ├── 94909342c16126bb205e060d216788a4742d6da3.nq.gz
    ├── 95168bc95685f7a3b831dc55698ee4c9f320e8d5.nq.gz
    ├── 95304b352683af285d37f3431c7d7f2b6a813655.nq.gz
    ├── 955bb0a678ec81e4fd7608529c086bb3bb3ec926.nq.gz
    ├── 95b48accaf6ab7cca1bf1eb6f729f62708e4d0ee.nq.gz
    ├── 96c79311b15298bca00bdfe9e9b3333cba94fdd8.nq.gz
    ├── 9702d6ae54a60ee214a3fe9ac115a96f77370cda.nq.gz
    ├── 97089f3dc47aa239f505e4f61538baecb54eb423.nq.gz
    ├── 975f7b437236e70aab53f58481a469dc0c680c61.nq.gz
    ├── 97a6735946917afaff0539633a2f33dceb1f1767.nq.gz
    ├── 97f0b7a7b0345beba1f492f881ec7f4c5ed71127.nq.gz
    ├── 9829505ecf6e1aa20ec40c239e2377f1d1d5bde3.nq.gz
    ├── 9a11eb84d2b73e3ccb57af40e57efdc94dcd29eb.nq.gz
    ├── 9b05776a680b1ef1f7b202b893e0a67a25950d74.nq.gz
    └── 9bbf975a1609cde485b9a05f698a37c8063b0088.nq.gz

6 directories, 200 files
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
*Parsed on 2026-03-21 by [repolex](https://repolex.ai)*
