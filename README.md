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
│   │   ├── 0828b4ffe0cdf83df60410315cb59002824f4b9b.nq.gz
│   │   ├── 1c8bc55cc8519bb655710d09f8acfaed77b4f7ed.nq.gz
│   │   ├── 21bf6ac7d5e31c385090a244106aae507fa11052.nq.gz
│   │   ├── 246ec4295f05d8fb943a23d366f036346cbfe091.nq.gz
│   │   ├── 2fcfe886735f790f07e72673e74e24b3a4673a7d.nq.gz
│   │   ├── 300b052015f4a6909ce17e2013a3e8ca574d2ad7.nq.gz
│   │   ├── 3232536b968d8668f5cfc2032248fa598e1933aa.nq.gz
│   │   ├── 3a69815be35b5e64795498598e6f2a17233df7c4.nq.gz
│   │   ├── 3b4c10cc96f1c6a6bf96bd095ca1d10b478f8b83.nq.gz
│   │   ├── 3e3f988abdd97435d06e57fe183a53d230ab0142.nq.gz
│   │   ├── 3f8ad4bf6c81ee8944bd71cc1ff0718df485e422.nq.gz
│   │   ├── 4aa87e88bf3511c915247af89caf0e66c7aec129.nq.gz
│   │   ├── 552ae2c8eb581767526f84946ec36884dab92637.nq.gz
│   │   ├── 58beb78726e76ab3d4ea2635d6b63ac597c32788.nq.gz
│   │   ├── 67545bfae69c8491711646c926d8043146a83e21.nq.gz
│   │   ├── 7388defc3eb0422e001f2cbf473d921ba7c48835.nq.gz
│   │   ├── 74e8a3321ea99880fcf320f359abaa1e80654ee1.nq.gz
│   │   ├── 7c55e2cb3653d9af93515408fb13c3c9f504482d.nq.gz
│   │   ├── 8c0bd7e581591b4180055896cbf72ae8b36003fc.nq.gz
│   │   ├── 93f80779b985db6d8e723d4db891df18f4b068fc.nq.gz
│   │   ├── 9ad5e71e71d414d7775de20cc747961708afdc24.nq.gz
│   │   ├── a15ec925c1d7a2daece9b5a844b001c0a52bd0bc.nq.gz
│   │   ├── a4816a82870725638b8b3f40ebcc93a74c9d9cbd.nq.gz
│   │   ├── b5b26553054623037b4332c66b54374c38c3a2bd.nq.gz
│   │   ├── c0002bfbcbe83d69ea394cf7c8c9318c62426b26.nq.gz
│   │   ├── c1c827b91d5db4fac91f26a0071fcc7d26ff8403.nq.gz
│   │   ├── c92851a660e95a5379a7b8fcf2ae6b03bc789aaf.nq.gz
│   │   ├── cfd8c04213e7ecd1796ae9e542d293d6630e80f4.nq.gz
│   │   ├── d601c88e38dd6cd5738980e1e6e9e0e63580c419.nq.gz
│   │   ├── d95b1b0c276b70bf58849e54214389aaa6b8af12.nq.gz
│   │   ├── dda3c913d884056d98e7b5f1220b2d9ba455f0c4.nq.gz
│   │   └── ff9b1159f238f828a18b9d49e27f938e3d60fdad.nq.gz
│   ├── lsp
│   │   ├── 0455cd9b2b0e08ce916476e22e4f198c45a15f83.nq.gz
│   │   ├── 0828b4ffe0cdf83df60410315cb59002824f4b9b.nq.gz
│   │   ├── 1c8bc55cc8519bb655710d09f8acfaed77b4f7ed.nq.gz
│   │   ├── 21bf6ac7d5e31c385090a244106aae507fa11052.nq.gz
│   │   ├── 246ec4295f05d8fb943a23d366f036346cbfe091.nq.gz
│   │   ├── 2fcfe886735f790f07e72673e74e24b3a4673a7d.nq.gz
│   │   ├── 300b052015f4a6909ce17e2013a3e8ca574d2ad7.nq.gz
│   │   ├── 3232536b968d8668f5cfc2032248fa598e1933aa.nq.gz
│   │   ├── 3a69815be35b5e64795498598e6f2a17233df7c4.nq.gz
│   │   ├── 3b4c10cc96f1c6a6bf96bd095ca1d10b478f8b83.nq.gz
│   │   ├── 3e3f988abdd97435d06e57fe183a53d230ab0142.nq.gz
│   │   ├── 3f8ad4bf6c81ee8944bd71cc1ff0718df485e422.nq.gz
│   │   ├── 4aa87e88bf3511c915247af89caf0e66c7aec129.nq.gz
│   │   ├── 552ae2c8eb581767526f84946ec36884dab92637.nq.gz
│   │   ├── 58beb78726e76ab3d4ea2635d6b63ac597c32788.nq.gz
│   │   ├── 67545bfae69c8491711646c926d8043146a83e21.nq.gz
│   │   ├── 7388defc3eb0422e001f2cbf473d921ba7c48835.nq.gz
│   │   ├── 74e8a3321ea99880fcf320f359abaa1e80654ee1.nq.gz
│   │   ├── 7c55e2cb3653d9af93515408fb13c3c9f504482d.nq.gz
│   │   ├── 8c0bd7e581591b4180055896cbf72ae8b36003fc.nq.gz
│   │   ├── 93f80779b985db6d8e723d4db891df18f4b068fc.nq.gz
│   │   ├── 9ad5e71e71d414d7775de20cc747961708afdc24.nq.gz
│   │   ├── a15ec925c1d7a2daece9b5a844b001c0a52bd0bc.nq.gz
│   │   ├── a4816a82870725638b8b3f40ebcc93a74c9d9cbd.nq.gz
│   │   ├── b5b26553054623037b4332c66b54374c38c3a2bd.nq.gz
│   │   ├── c0002bfbcbe83d69ea394cf7c8c9318c62426b26.nq.gz
│   │   ├── c1c827b91d5db4fac91f26a0071fcc7d26ff8403.nq.gz
│   │   ├── c92851a660e95a5379a7b8fcf2ae6b03bc789aaf.nq.gz
│   │   ├── cfd8c04213e7ecd1796ae9e542d293d6630e80f4.nq.gz
│   │   ├── d601c88e38dd6cd5738980e1e6e9e0e63580c419.nq.gz
│   │   ├── d95b1b0c276b70bf58849e54214389aaa6b8af12.nq.gz
│   │   ├── dda3c913d884056d98e7b5f1220b2d9ba455f0c4.nq.gz
│   │   └── ff9b1159f238f828a18b9d49e27f938e3d60fdad.nq.gz
│   └── repolex
│       ├── 0455cd9b2b0e08ce916476e22e4f198c45a15f83.nq.gz
│       ├── 0828b4ffe0cdf83df60410315cb59002824f4b9b.nq.gz
│       ├── 1c8bc55cc8519bb655710d09f8acfaed77b4f7ed.nq.gz
│       ├── 21bf6ac7d5e31c385090a244106aae507fa11052.nq.gz
│       ├── 246ec4295f05d8fb943a23d366f036346cbfe091.nq.gz
│       ├── 2fcfe886735f790f07e72673e74e24b3a4673a7d.nq.gz
│       ├── 300b052015f4a6909ce17e2013a3e8ca574d2ad7.nq.gz
│       ├── 3232536b968d8668f5cfc2032248fa598e1933aa.nq.gz
│       ├── 3a69815be35b5e64795498598e6f2a17233df7c4.nq.gz
│       ├── 3b4c10cc96f1c6a6bf96bd095ca1d10b478f8b83.nq.gz
│       ├── 3e3f988abdd97435d06e57fe183a53d230ab0142.nq.gz
│       ├── 3f8ad4bf6c81ee8944bd71cc1ff0718df485e422.nq.gz
│       ├── 4aa87e88bf3511c915247af89caf0e66c7aec129.nq.gz
│       ├── 552ae2c8eb581767526f84946ec36884dab92637.nq.gz
│       ├── 58beb78726e76ab3d4ea2635d6b63ac597c32788.nq.gz
│       ├── 67545bfae69c8491711646c926d8043146a83e21.nq.gz
│       ├── 7388defc3eb0422e001f2cbf473d921ba7c48835.nq.gz
│       ├── 74e8a3321ea99880fcf320f359abaa1e80654ee1.nq.gz
│       ├── 7c55e2cb3653d9af93515408fb13c3c9f504482d.nq.gz
│       ├── 8c0bd7e581591b4180055896cbf72ae8b36003fc.nq.gz
│       ├── 93f80779b985db6d8e723d4db891df18f4b068fc.nq.gz
│       ├── 9ad5e71e71d414d7775de20cc747961708afdc24.nq.gz
│       ├── a15ec925c1d7a2daece9b5a844b001c0a52bd0bc.nq.gz
│       ├── a4816a82870725638b8b3f40ebcc93a74c9d9cbd.nq.gz
│       ├── b5b26553054623037b4332c66b54374c38c3a2bd.nq.gz
│       ├── c0002bfbcbe83d69ea394cf7c8c9318c62426b26.nq.gz
│       ├── c1c827b91d5db4fac91f26a0071fcc7d26ff8403.nq.gz
│       ├── c92851a660e95a5379a7b8fcf2ae6b03bc789aaf.nq.gz
│       ├── cfd8c04213e7ecd1796ae9e542d293d6630e80f4.nq.gz
│       ├── d601c88e38dd6cd5738980e1e6e9e0e63580c419.nq.gz
│       ├── d95b1b0c276b70bf58849e54214389aaa6b8af12.nq.gz
│       ├── dda3c913d884056d98e7b5f1220b2d9ba455f0c4.nq.gz
│       └── ff9b1159f238f828a18b9d49e27f938e3d60fdad.nq.gz
└── blob
    ├── 007af65ea1ded88b9087d37e69db064acb884e21.nq.gz
    ├── 007e541ff7091167de146a29f844275e530c6b2e.nq.gz
    ├── 014e7fb9290480abd55a196815e65a142524d106.nq.gz
    ├── 02234fd2295542ec1ea110cae710baffacffd797.nq.gz
    ├── 024b38783566ebfed2ea426d2ceb89d6f7372f45.nq.gz
    ├── 02acf41c647ba5e398a022fc67b07cf4c547b73b.nq.gz
    ├── 02eabd4d62825f659022e841891b6f5f98be5096.nq.gz
    ├── 0320ae9d3ccd91400cd0097a505c47c681aece73.nq.gz
    ├── 033193785f78324929919f2862fffb21866bf4cf.nq.gz
    ├── 033d73c881305c7df501d4e92979c2dba64ecad7.nq.gz
    ├── 03ef3e602c7628a3e6c439d1a43774da51370abd.nq.gz
    ├── 046527c67883a6ab83c78d3623a57a37b64462e3.nq.gz
    ├── 04cf5e1a92683d6a8309e059451c7a6e9c4f4d15.nq.gz
    ├── 04ec6c8be354cecb991487352639c98ce34de684.nq.gz
    ├── 04f494145444984eeb68bd533a10f1971d26fba5.nq.gz
    ├── 055f11913a2a7f59fc95cf87b057b76146e09f4a.nq.gz
    ├── 05638f4608ce201621df85a1ee00ebeb29deab07.nq.gz
    ├── 0599b31cdcf618288f7ebf1cb5d6ff087fb2cc8a.nq.gz
    ├── 05a27c313567d617c75e75376888e080e0b800ee.nq.gz
    ├── 067b933e77e04156da70191e1e60d08236a44d3f.nq.gz
    ├── 06db05ddf4262761d67c598c5c0d37f6afa5fdfc.nq.gz
    ├── 073434ad5e100b7b4ae2f04890980ec2ef54083c.nq.gz
    ├── 07738b2e4d62d5b6f3fbcd48d600b1f6a9444da9.nq.gz
    ├── 07806f8af9dd3253ebdb5710b67e73124aea4941.nq.gz
    ├── 08037c7399ab310d79f67f9460acc6c628d5dc5e.nq.gz
    ├── 088ccb3966464c967eee872cc7aedb8e19a541e9.nq.gz
    ├── 08adb23913bf61b582dbf7b7e695e493b01c3858.nq.gz
    ├── 08ee428df3a7ee972accabaec1d0eb7e478a74aa.nq.gz
    ├── 0a2eca24ab4d57cbd1ce418415fa20da59305015.nq.gz
    ├── 0a55151e6256e512cc4128fdefa2a8309038cb1e.nq.gz
    ├── 0a709c94877eb197ec8c3413ffe8861ee9a2b4d1.nq.gz
    ├── 0a731d5366cd4d742808a0e37568da73a0f5b569.nq.gz
    ├── 0b38821d16b73eaa58eaefc64e284f66b4236653.nq.gz
    ├── 0b3967a49c56bb2b5f3283b068be6f346654e5b1.nq.gz
    ├── 0b51a02ff7cae1d52196fe61bf43ccbace294b8b.nq.gz
    ├── 0b56db25c244aed43eca02d3207ce1b59d2f2d9d.nq.gz
    ├── 0bccb86e4b98d9c0f3c50d8ded61f7dc5e29738e.nq.gz
    ├── 0cc9337203260b6e3dab9fb98eb7a3492ca9e59e.nq.gz
    ├── 0cdfe227d84d23601d6033eaeebb3e632d073672.nq.gz
    ├── 0d04ab46c01922808ef9834b14dd246d892c5ea1.nq.gz
    ├── 0d5e7fb20f3b50a5a144fa75c492ddeb842e970a.nq.gz
    ├── 0dfcec9faaf4967c8b95fdc44e30011ec87658b7.nq.gz
    ├── 0e99a4568b2c0e0ed5997bafff62a90a52c2da67.nq.gz
    ├── 0ebfeb2da19d28973a0dafcc28f6776be5b1690f.nq.gz
    ├── 0efd2067643372cdb3c19265c6b94afb52b988a6.nq.gz
    ├── 104eebf5a3002fccdaceef3a4cb936173c1c2035.nq.gz
    ├── 105d30c14f15e52df5c2b37c8a4477586f1b7220.nq.gz
    ├── 10606447e85f3f1ae356ff08f376c2edc1fa8db9.nq.gz
    ├── 1065ab96fff42ea2195dd07e12b7de240764cff1.nq.gz
    ├── 10b4ed09f8e5d2ca48defc513642930d444ac8c3.nq.gz
    ├── 10e797f50a2e9017723e9f6e4f4ac842af1a5bf2.nq.gz
    ├── 111433c19de36aed5d33e349e75b0d332b6697af.nq.gz
    ├── 11673a434335ad8d20602c7dbf33bce32609842c.nq.gz
    ├── 121bd3769a26ca941f6dfa3ac372171f758eb319.nq.gz
    ├── 12442ad3e0f12ca06a174d2b9cfc036654b9ebed.nq.gz
    ├── 1268ecebd8a583e33bc8ac13d6121bbbcaba8dea.nq.gz
    ├── 12d85ea7ac8438c0c95b21c335ec6171f87be05b.nq.gz
    ├── 1339d4b5739655d5fc74d6b74aa0697a10e64bd1.nq.gz
    ├── 1367be5a3171dda1b9f1bace68123cf623c2dbd4.nq.gz
    ├── 1370294a04bd6e1b397e03b611afbef0e402f8fd.nq.gz
    ├── 13b393675163ba888edb5007e1cc357fcb9083d5.nq.gz
    ├── 13c900561469cc046b41d3d78c49d2d7eac605cf.nq.gz
    ├── 1406443230111ac80fc6fd5e1df86f01205e9864.nq.gz
    ├── 149a9087ed173947a66dab71446e24c942f6b82c.nq.gz
    ├── 1503b3e4f6cc9ae25f0cfa5fe39d7b270541d45e.nq.gz
    ├── 151aaeb7af3813b995d47175afac8732303d65dc.nq.gz
    ├── 15a5b6c98d31e88808fae858b8b1d9c39f87fcc8.nq.gz
    ├── 15d4afcdb20e2fdf5eec5581f78a2531197a9497.nq.gz
    ├── 16374dcea2b4e8db0382046a60a27bd447aea426.nq.gz
    ├── 1699326b67e4c79feb5e16308f05d6ece7aa1437.nq.gz
    ├── 16f7d961d9dfa73cbf93b59af3088accbff268de.nq.gz
    ├── 17abb5660d5577fd08a3c9ddab481c55cf7d159c.nq.gz
    ├── 17fcbe39b8e7d98867168be1a6df2245555dd70f.nq.gz
    ├── 181ef7f596dc189561838ed0cc83f5ac7cc3f5b1.nq.gz
    ├── 18b3dff703f0de902f77b01a8fc680b4fdaf4b05.nq.gz
    ├── 18b67aa73540a17823cee24e6fc4064421bcb2f9.nq.gz
    ├── 1980470e665e2f19941d5d25b8450bdf2695de56.nq.gz
    ├── 19a9179ec46d763ce7268ad9f9994501035aa6d4.nq.gz
    ├── 19c1e8344c1dac85312fab04d44c191e6b19cdc7.nq.gz
    ├── 19cc7bd906dcd5917787d1a514c1b33b2d4e9ba6.nq.gz
    ├── 1a50a04f5d01889b551fcf6170787cf3e1e35db1.nq.gz
    ├── 1ad1c9f663fae2aa86719ad20806e3ee33d0afbd.nq.gz
    ├── 1ad991b631d7305fb800b595b6ad93ee65cd8d99.nq.gz
    ├── 1b29972fc5f4ae1650efc10f9e8a90b3519df358.nq.gz
    ├── 1b78732d888e646a17c2134c4898574b3ce2d21b.nq.gz
    ├── 1c1efc9103455673b38c8bc6c1ff292da7849b13.nq.gz
    ├── 1d613af03fc0b6d38f87b3b726d43a73b5201346.nq.gz
    ├── 1d84c05cba0e62985c710bb0cecb8a0857b47281.nq.gz
    ├── 1d87fb99dbec8065b5a2689e3d07ba416510e5f5.nq.gz
    ├── 1daf6c1024092897fb2a394142eb1452b1c371f5.nq.gz
    ├── 1db517646ccdcbf72cecabda4a5cdcfacf3b01d5.nq.gz
    ├── 1dc25374b37c129ca2fb1383eb21f9bc219b5e1a.nq.gz
    ├── 1e315bdde0cb5f8bb982149588f0eca3883f95c5.nq.gz
    ├── 1e337ef62c5c2c5708bd0c000e03bfc926d099f2.nq.gz
    ├── 1e633fb9c665e360d07e6d98535e997f4ad63955.nq.gz
    ├── 1ec4e5b93605f68f38bcbb3e7fdc38974f2be290.nq.gz
    ├── 1ef5c35ef7f42bc146a76739364149a77d2db993.nq.gz
    ├── 1f5a9a2748ae36519ed7e8562742531744ce9c3f.nq.gz
    ├── 1fa8737860eeef5c6b739fd9c19e80e68929b270.nq.gz
    ├── 1fbf04e8592de5fac3b1c35a0c0a02df1b2c04dc.nq.gz
    └── 1fefde7089b0bbd51e1a52068f9be53e361cd233.nq.gz

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
*Parsed on 2026-03-23 by [repolex](https://repolex.ai)*
