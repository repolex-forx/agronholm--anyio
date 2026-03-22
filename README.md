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
│   │   ├── 0455cd9b2b0e08ce916476e22e4f198c45a15f83.nq.gz
│   │   ├── 1c8bc55cc8519bb655710d09f8acfaed77b4f7ed.nq.gz
│   │   ├── 21bf6ac7d5e31c385090a244106aae507fa11052.nq.gz
│   │   ├── 300b052015f4a6909ce17e2013a3e8ca574d2ad7.nq.gz
│   │   ├── 3232536b968d8668f5cfc2032248fa598e1933aa.nq.gz
│   │   ├── 3a69815be35b5e64795498598e6f2a17233df7c4.nq.gz
│   │   ├── 3b4c10cc96f1c6a6bf96bd095ca1d10b478f8b83.nq.gz
│   │   ├── 3e3f988abdd97435d06e57fe183a53d230ab0142.nq.gz
│   │   ├── 3f8ad4bf6c81ee8944bd71cc1ff0718df485e422.nq.gz
│   │   ├── 4aa87e88bf3511c915247af89caf0e66c7aec129.nq.gz
│   │   ├── 552ae2c8eb581767526f84946ec36884dab92637.nq.gz
│   │   ├── 58beb78726e76ab3d4ea2635d6b63ac597c32788.nq.gz
│   │   ├── 7388defc3eb0422e001f2cbf473d921ba7c48835.nq.gz
│   │   ├── 74e8a3321ea99880fcf320f359abaa1e80654ee1.nq.gz
│   │   ├── 7c55e2cb3653d9af93515408fb13c3c9f504482d.nq.gz
│   │   ├── 8c0bd7e581591b4180055896cbf72ae8b36003fc.nq.gz
│   │   ├── 93f80779b985db6d8e723d4db891df18f4b068fc.nq.gz
│   │   ├── a15ec925c1d7a2daece9b5a844b001c0a52bd0bc.nq.gz
│   │   ├── c1c827b91d5db4fac91f26a0071fcc7d26ff8403.nq.gz
│   │   ├── c92851a660e95a5379a7b8fcf2ae6b03bc789aaf.nq.gz
│   │   ├── d601c88e38dd6cd5738980e1e6e9e0e63580c419.nq.gz
│   │   ├── d95b1b0c276b70bf58849e54214389aaa6b8af12.nq.gz
│   │   ├── dda3c913d884056d98e7b5f1220b2d9ba455f0c4.nq.gz
│   │   └── ff9b1159f238f828a18b9d49e27f938e3d60fdad.nq.gz
│   ├── lsp
│   │   ├── 0455cd9b2b0e08ce916476e22e4f198c45a15f83.nq.gz
│   │   ├── 1c8bc55cc8519bb655710d09f8acfaed77b4f7ed.nq.gz
│   │   ├── 21bf6ac7d5e31c385090a244106aae507fa11052.nq.gz
│   │   ├── 300b052015f4a6909ce17e2013a3e8ca574d2ad7.nq.gz
│   │   ├── 3232536b968d8668f5cfc2032248fa598e1933aa.nq.gz
│   │   ├── 3a69815be35b5e64795498598e6f2a17233df7c4.nq.gz
│   │   ├── 3b4c10cc96f1c6a6bf96bd095ca1d10b478f8b83.nq.gz
│   │   ├── 3e3f988abdd97435d06e57fe183a53d230ab0142.nq.gz
│   │   ├── 3f8ad4bf6c81ee8944bd71cc1ff0718df485e422.nq.gz
│   │   ├── 4aa87e88bf3511c915247af89caf0e66c7aec129.nq.gz
│   │   ├── 552ae2c8eb581767526f84946ec36884dab92637.nq.gz
│   │   ├── 58beb78726e76ab3d4ea2635d6b63ac597c32788.nq.gz
│   │   ├── 7388defc3eb0422e001f2cbf473d921ba7c48835.nq.gz
│   │   ├── 74e8a3321ea99880fcf320f359abaa1e80654ee1.nq.gz
│   │   ├── 7c55e2cb3653d9af93515408fb13c3c9f504482d.nq.gz
│   │   ├── 8c0bd7e581591b4180055896cbf72ae8b36003fc.nq.gz
│   │   ├── 93f80779b985db6d8e723d4db891df18f4b068fc.nq.gz
│   │   ├── a15ec925c1d7a2daece9b5a844b001c0a52bd0bc.nq.gz
│   │   ├── c1c827b91d5db4fac91f26a0071fcc7d26ff8403.nq.gz
│   │   ├── c92851a660e95a5379a7b8fcf2ae6b03bc789aaf.nq.gz
│   │   ├── d601c88e38dd6cd5738980e1e6e9e0e63580c419.nq.gz
│   │   ├── d95b1b0c276b70bf58849e54214389aaa6b8af12.nq.gz
│   │   ├── dda3c913d884056d98e7b5f1220b2d9ba455f0c4.nq.gz
│   │   └── ff9b1159f238f828a18b9d49e27f938e3d60fdad.nq.gz
│   └── repolex
│       ├── 0455cd9b2b0e08ce916476e22e4f198c45a15f83.nq.gz
│       ├── 1c8bc55cc8519bb655710d09f8acfaed77b4f7ed.nq.gz
│       ├── 21bf6ac7d5e31c385090a244106aae507fa11052.nq.gz
│       ├── 300b052015f4a6909ce17e2013a3e8ca574d2ad7.nq.gz
│       ├── 3232536b968d8668f5cfc2032248fa598e1933aa.nq.gz
│       ├── 3a69815be35b5e64795498598e6f2a17233df7c4.nq.gz
│       ├── 3b4c10cc96f1c6a6bf96bd095ca1d10b478f8b83.nq.gz
│       ├── 3e3f988abdd97435d06e57fe183a53d230ab0142.nq.gz
│       ├── 3f8ad4bf6c81ee8944bd71cc1ff0718df485e422.nq.gz
│       ├── 4aa87e88bf3511c915247af89caf0e66c7aec129.nq.gz
│       ├── 552ae2c8eb581767526f84946ec36884dab92637.nq.gz
│       ├── 58beb78726e76ab3d4ea2635d6b63ac597c32788.nq.gz
│       ├── 7388defc3eb0422e001f2cbf473d921ba7c48835.nq.gz
│       ├── 74e8a3321ea99880fcf320f359abaa1e80654ee1.nq.gz
│       ├── 7c55e2cb3653d9af93515408fb13c3c9f504482d.nq.gz
│       ├── 8c0bd7e581591b4180055896cbf72ae8b36003fc.nq.gz
│       ├── 93f80779b985db6d8e723d4db891df18f4b068fc.nq.gz
│       ├── a15ec925c1d7a2daece9b5a844b001c0a52bd0bc.nq.gz
│       ├── c1c827b91d5db4fac91f26a0071fcc7d26ff8403.nq.gz
│       ├── c92851a660e95a5379a7b8fcf2ae6b03bc789aaf.nq.gz
│       ├── d601c88e38dd6cd5738980e1e6e9e0e63580c419.nq.gz
│       ├── d95b1b0c276b70bf58849e54214389aaa6b8af12.nq.gz
│       ├── dda3c913d884056d98e7b5f1220b2d9ba455f0c4.nq.gz
│       └── ff9b1159f238f828a18b9d49e27f938e3d60fdad.nq.gz
└── blob
    ├── 014e7fb9290480abd55a196815e65a142524d106.nq.gz
    ├── 024b38783566ebfed2ea426d2ceb89d6f7372f45.nq.gz
    ├── 02acf41c647ba5e398a022fc67b07cf4c547b73b.nq.gz
    ├── 02eabd4d62825f659022e841891b6f5f98be5096.nq.gz
    ├── 033d73c881305c7df501d4e92979c2dba64ecad7.nq.gz
    ├── 03ef3e602c7628a3e6c439d1a43774da51370abd.nq.gz
    ├── 046527c67883a6ab83c78d3623a57a37b64462e3.nq.gz
    ├── 04cf5e1a92683d6a8309e059451c7a6e9c4f4d15.nq.gz
    ├── 04ec6c8be354cecb991487352639c98ce34de684.nq.gz
    ├── 055f11913a2a7f59fc95cf87b057b76146e09f4a.nq.gz
    ├── 0599b31cdcf618288f7ebf1cb5d6ff087fb2cc8a.nq.gz
    ├── 05a27c313567d617c75e75376888e080e0b800ee.nq.gz
    ├── 067b933e77e04156da70191e1e60d08236a44d3f.nq.gz
    ├── 073434ad5e100b7b4ae2f04890980ec2ef54083c.nq.gz
    ├── 07806f8af9dd3253ebdb5710b67e73124aea4941.nq.gz
    ├── 08037c7399ab310d79f67f9460acc6c628d5dc5e.nq.gz
    ├── 088ccb3966464c967eee872cc7aedb8e19a541e9.nq.gz
    ├── 08adb23913bf61b582dbf7b7e695e493b01c3858.nq.gz
    ├── 08ee428df3a7ee972accabaec1d0eb7e478a74aa.nq.gz
    ├── 0a55151e6256e512cc4128fdefa2a8309038cb1e.nq.gz
    ├── 0a709c94877eb197ec8c3413ffe8861ee9a2b4d1.nq.gz
    ├── 0a731d5366cd4d742808a0e37568da73a0f5b569.nq.gz
    ├── 0b3967a49c56bb2b5f3283b068be6f346654e5b1.nq.gz
    ├── 0b51a02ff7cae1d52196fe61bf43ccbace294b8b.nq.gz
    ├── 0b56db25c244aed43eca02d3207ce1b59d2f2d9d.nq.gz
    ├── 0bccb86e4b98d9c0f3c50d8ded61f7dc5e29738e.nq.gz
    ├── 0cc9337203260b6e3dab9fb98eb7a3492ca9e59e.nq.gz
    ├── 0d04ab46c01922808ef9834b14dd246d892c5ea1.nq.gz
    ├── 0efd2067643372cdb3c19265c6b94afb52b988a6.nq.gz
    ├── 104eebf5a3002fccdaceef3a4cb936173c1c2035.nq.gz
    ├── 10606447e85f3f1ae356ff08f376c2edc1fa8db9.nq.gz
    ├── 1065ab96fff42ea2195dd07e12b7de240764cff1.nq.gz
    ├── 10b4ed09f8e5d2ca48defc513642930d444ac8c3.nq.gz
    ├── 10e797f50a2e9017723e9f6e4f4ac842af1a5bf2.nq.gz
    ├── 111433c19de36aed5d33e349e75b0d332b6697af.nq.gz
    ├── 121bd3769a26ca941f6dfa3ac372171f758eb319.nq.gz
    ├── 12442ad3e0f12ca06a174d2b9cfc036654b9ebed.nq.gz
    ├── 1268ecebd8a583e33bc8ac13d6121bbbcaba8dea.nq.gz
    ├── 12d85ea7ac8438c0c95b21c335ec6171f87be05b.nq.gz
    ├── 1339d4b5739655d5fc74d6b74aa0697a10e64bd1.nq.gz
    ├── 1367be5a3171dda1b9f1bace68123cf623c2dbd4.nq.gz
    ├── 1370294a04bd6e1b397e03b611afbef0e402f8fd.nq.gz
    ├── 13c900561469cc046b41d3d78c49d2d7eac605cf.nq.gz
    ├── 1406443230111ac80fc6fd5e1df86f01205e9864.nq.gz
    ├── 149a9087ed173947a66dab71446e24c942f6b82c.nq.gz
    ├── 151aaeb7af3813b995d47175afac8732303d65dc.nq.gz
    ├── 1699326b67e4c79feb5e16308f05d6ece7aa1437.nq.gz
    ├── 16f7d961d9dfa73cbf93b59af3088accbff268de.nq.gz
    ├── 17fcbe39b8e7d98867168be1a6df2245555dd70f.nq.gz
    ├── 18b3dff703f0de902f77b01a8fc680b4fdaf4b05.nq.gz
    ├── 19cc7bd906dcd5917787d1a514c1b33b2d4e9ba6.nq.gz
    ├── 1a50a04f5d01889b551fcf6170787cf3e1e35db1.nq.gz
    ├── 1ad1c9f663fae2aa86719ad20806e3ee33d0afbd.nq.gz
    ├── 1ad991b631d7305fb800b595b6ad93ee65cd8d99.nq.gz
    ├── 1b29972fc5f4ae1650efc10f9e8a90b3519df358.nq.gz
    ├── 1b78732d888e646a17c2134c4898574b3ce2d21b.nq.gz
    ├── 1c1efc9103455673b38c8bc6c1ff292da7849b13.nq.gz
    ├── 1d613af03fc0b6d38f87b3b726d43a73b5201346.nq.gz
    ├── 1d87fb99dbec8065b5a2689e3d07ba416510e5f5.nq.gz
    ├── 1db517646ccdcbf72cecabda4a5cdcfacf3b01d5.nq.gz
    ├── 1e315bdde0cb5f8bb982149588f0eca3883f95c5.nq.gz
    ├── 1ec4e5b93605f68f38bcbb3e7fdc38974f2be290.nq.gz
    ├── 1ef5c35ef7f42bc146a76739364149a77d2db993.nq.gz
    ├── 1fa8737860eeef5c6b739fd9c19e80e68929b270.nq.gz
    ├── 1fbf04e8592de5fac3b1c35a0c0a02df1b2c04dc.nq.gz
    ├── 20bbb7da29a1ae0be0d9f35b206f5ba88bec2bba.nq.gz
    ├── 2120c765f5ae05cbc8d4edd77ee6e140770c3e18.nq.gz
    ├── 21b2f782732c8b7eeb1e6a350a41559b8a0fe302.nq.gz
    ├── 2214ecb104873027b557b622b7f45e7ef26878cf.nq.gz
    ├── 224f25faa5dd14995d98f1bbba78bc1a7ddc16c1.nq.gz
    ├── 235653f14f28737e030bb890903572d8b9bd8293.nq.gz
    ├── 238bc3bedb71f1b1f6299c35bda8bddcb758b079.nq.gz
    ├── 24e59b7bfa003caa451e88e7ea9cebd739f2507a.nq.gz
    ├── 25bce177df1a8017c2c9c5625213e9bf6a01f1e2.nq.gz
    ├── 261d3aa609e3ea7221a3bc44c26c22cbc51b5c96.nq.gz
    ├── 27245d8e96b7ca1faceae38aeab5aab6b3adb38e.nq.gz
    ├── 273a06fd01383b27031660bae08cd1f8acb6c52d.nq.gz
    ├── 2740bb7217cf619987256d4dd4ef8094d2b96928.nq.gz
    ├── 277940aa2205839a647296d44f74d373b97dff7f.nq.gz
    ├── 278d24d4590ef891059015a86dcb0cd27d46a30b.nq.gz
    ├── 27bc01d87c01ae1b9fcd851d26351eb785548eba.nq.gz
    ├── 2821829f018c076d83fe94d1bb5342925a282f35.nq.gz
    ├── 2889f77cd680c6e6002204710b5fb740eb3b52b7.nq.gz
    ├── 28f1f8b6fa95bb668572a42fead9fa4a9a39b999.nq.gz
    ├── 295a74fdda359fbf14b6f821a648793d684450de.nq.gz
    ├── 2a03c10b38ca2454fb1cffa2a60889038848b14b.nq.gz
    ├── 2a184c8592aafa981aeb089a96b3564bb3f39b06.nq.gz
    ├── 2b11c3b2edd1795191135d5736491efd03308b15.nq.gz
    ├── 2b1dd1a88457a746506928977fe73d367af973eb.nq.gz
    ├── 2bf14725cd8de784ddc86d7673bcbaa57d1ee2cd.nq.gz
    ├── 2c451e8e9f5d52c456b5a6aef36a827fb5c2908e.nq.gz
    ├── 2c6570ee1cf2557a0ea52406f9b811469d97e7e4.nq.gz
    ├── 2d3008a54a4a5a8a5c4642cbef4de93979cab0cc.nq.gz
    ├── 2dfdbad62df84ede37da5312af73a798f132debb.nq.gz
    ├── 2e698a92b2f0bfba3363b83b0199cda4d8366de1.nq.gz
    ├── 30ebf8a66e5c99cdddf1b0c3d52b5e3325cfaaf9.nq.gz
    ├── 322d411359293d94f25c79afc0e058b088d2036b.nq.gz
    ├── 32a31603b6a6b93b648b1ba60f9c629e20aa5b95.nq.gz
    ├── 33ff8a659427d6a9a22b7e53014ee51117a5829f.nq.gz
    ├── 340f94a9154c63bc8d7395c68b93f98c030e41bd.nq.gz
    ├── 344529b4ec5b6a8a226ff7f80b4238be6b2e487b.nq.gz
    ├── 3497c78c32b7a07df4c6796e9e38e92382236ce3.nq.gz
    ├── 34aab6f3bf928636d3de5be436ea8b9c2bb9525b.nq.gz
    ├── 34b828d0f882e989485191f8c14c4a047a57110c.nq.gz
    ├── 34d95299954ddcd74c7754d386e42e6dc4586d2c.nq.gz
    ├── 34fb9b845e5f5edc7fcb4cd5cc5f6311122c837d.nq.gz
    ├── 351f4a45f543a7b6fe2ca1b83e6317ba3846308d.nq.gz
    ├── 36f770640ff0bad2a64139e9b20a82bcc6bdf9e5.nq.gz
    ├── 370c6924f2c77ccdb3a33213aa63b80c6114924d.nq.gz
    ├── 3729a1e15d131b802175a8851e0d76fa25dfca6e.nq.gz
    ├── 372cb0f80b62920300cce644c2ef29e5d5e0a83b.nq.gz
    ├── 38d8eb6627c76e519e7b70b97f0b8b41fd4b6e93.nq.gz
    ├── 394870b8db1c926100572184ae08df4eac6f69b4.nq.gz
    ├── 394ee80cb927701068c87127c13c0895e8c91bba.nq.gz
    ├── 39d58ebc4a09d1185a0ceaaf259e2a06767ab2b2.nq.gz
    ├── 3a1d94648e4567fe3ab4c84c535dfffb7e3fbc3c.nq.gz
    ├── 3a374e3419271c19d04a784bb50c8567aa95a248.nq.gz
    ├── 3ab7d13797be67da4fc6c93a8e08db4cc0cbcf26.nq.gz
    ├── 3ac073faba2a4a6ff24f47ccb03c556dc1f81ff3.nq.gz
    ├── 3b0163f5efe974c1afa7bcd3289d987f45d57863.nq.gz
    ├── 3c5b10d6f429e07a4e7c68450ffef56bb16b1bba.nq.gz
    ├── 3c68652152cf06fb7db18e58e82004fab36f3572.nq.gz
    ├── 3c8c42ce7b07ac66b1c0a6c5b7b5b57cfd413518.nq.gz
    ├── 3ca102680faa20d7c47cc9f831bf6a3fdff680f1.nq.gz
    ├── 3cd5b871ca9b725ad2e58aef99e9cd2f901675da.nq.gz
    ├── 3d285b0f7f23894b3c4e363a0f261830070e6cb5.nq.gz
    ├── 3e013d02988fcdee2464216ea396a04a52a9c586.nq.gz
    └── 3e51f8b5159c55d1ebfbd6294a346f4d1764e516.nq.gz

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
*Parsed on 2026-03-22 by [repolex](https://repolex.ai)*
