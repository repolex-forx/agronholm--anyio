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
│   │   ├── 08737af202f6610cdb8ba53fecaefd9c03269637.nq.gz
│   │   ├── 1c23ba9f8184c624c893f93ce473bed7f8982ef4.nq.gz
│   │   ├── 1c8bc55cc8519bb655710d09f8acfaed77b4f7ed.nq.gz
│   │   ├── 21bf6ac7d5e31c385090a244106aae507fa11052.nq.gz
│   │   ├── 246ec4295f05d8fb943a23d366f036346cbfe091.nq.gz
│   │   ├── 2fcfe886735f790f07e72673e74e24b3a4673a7d.nq.gz
│   │   ├── 300b052015f4a6909ce17e2013a3e8ca574d2ad7.nq.gz
│   │   ├── 3232536b968d8668f5cfc2032248fa598e1933aa.nq.gz
│   │   ├── 3a69815be35b5e64795498598e6f2a17233df7c4.nq.gz
│   │   ├── 3b4c10cc96f1c6a6bf96bd095ca1d10b478f8b83.nq.gz
│   │   ├── 3e182fa619002d90c7c3c531a25d76cab0e92893.nq.gz
│   │   ├── 3e3f988abdd97435d06e57fe183a53d230ab0142.nq.gz
│   │   ├── 3f1eca1addcd782e2347350a6ddb2ad2b80c6354.nq.gz
│   │   ├── 3f8ad4bf6c81ee8944bd71cc1ff0718df485e422.nq.gz
│   │   ├── 46a45c7454e4d87ab5671b158f746a2b3beaaae9.nq.gz
│   │   ├── 48efdec45e70a833cc939c1d2752f24e29d1bf0b.nq.gz
│   │   ├── 4aa87e88bf3511c915247af89caf0e66c7aec129.nq.gz
│   │   ├── 518ea7f0ecb9ca6170ed49834fa984eb24b29492.nq.gz
│   │   ├── 5376d62a423aedab5ede02086b33805588f0e94a.nq.gz
│   │   ├── 538b739b8a33bbdbf305e11d93c8bc34154e50d7.nq.gz
│   │   ├── 552ae2c8eb581767526f84946ec36884dab92637.nq.gz
│   │   ├── 58beb78726e76ab3d4ea2635d6b63ac597c32788.nq.gz
│   │   ├── 67545bfae69c8491711646c926d8043146a83e21.nq.gz
│   │   ├── 72baca901c599e7fdf22c2777b9b6a304ddd975d.nq.gz
│   │   ├── 7388defc3eb0422e001f2cbf473d921ba7c48835.nq.gz
│   │   ├── 74e8a3321ea99880fcf320f359abaa1e80654ee1.nq.gz
│   │   ├── 787cb0c2e53c2a3307873d202fbd49dc5eac4e96.nq.gz
│   │   ├── 7c55e2cb3653d9af93515408fb13c3c9f504482d.nq.gz
│   │   ├── 87b56ab82133f083733034526be344bcc37d713f.nq.gz
│   │   ├── 8c0bd7e581591b4180055896cbf72ae8b36003fc.nq.gz
│   │   ├── 93f80779b985db6d8e723d4db891df18f4b068fc.nq.gz
│   │   ├── 9ad5e71e71d414d7775de20cc747961708afdc24.nq.gz
│   │   ├── a0dccbd78d75886247ae7846b460fd390cc94fbd.nq.gz
│   │   ├── a15ec925c1d7a2daece9b5a844b001c0a52bd0bc.nq.gz
│   │   ├── a4816a82870725638b8b3f40ebcc93a74c9d9cbd.nq.gz
│   │   ├── ac3e7c619913bd0ddf9c36b6e633b278d07405b7.nq.gz
│   │   ├── b5b26553054623037b4332c66b54374c38c3a2bd.nq.gz
│   │   ├── bc021b634291223d6829c0a689152173443a8545.nq.gz
│   │   ├── c0002bfbcbe83d69ea394cf7c8c9318c62426b26.nq.gz
│   │   ├── c1c827b91d5db4fac91f26a0071fcc7d26ff8403.nq.gz
│   │   ├── c44c12fceeaa35bcd93009f66fb95cb32f0bffb5.nq.gz
│   │   ├── c92851a660e95a5379a7b8fcf2ae6b03bc789aaf.nq.gz
│   │   ├── cfd8c04213e7ecd1796ae9e542d293d6630e80f4.nq.gz
│   │   ├── d1072ba2c5621b70a0086cc765bb8c96d0376160.nq.gz
│   │   ├── d601c88e38dd6cd5738980e1e6e9e0e63580c419.nq.gz
│   │   ├── d684f91b06fe0119bb854c3b7a804a9f1ce7cd6d.nq.gz
│   │   ├── d95b1b0c276b70bf58849e54214389aaa6b8af12.nq.gz
│   │   ├── d973403730cd687bba29f8c52f2ca19f7fb4f55f.nq.gz
│   │   ├── dda3c913d884056d98e7b5f1220b2d9ba455f0c4.nq.gz
│   │   ├── e0b986e975968ec6b42816a629f1b8c26690d040.nq.gz
│   │   ├── e579d2c33a4a7d8f087fb9f9b251aa9e9f03bb37.nq.gz
│   │   ├── f080174565c2942ca772c33c01375b9453fe6601.nq.gz
│   │   └── ff9b1159f238f828a18b9d49e27f938e3d60fdad.nq.gz
│   ├── lsp
│   │   ├── 0455cd9b2b0e08ce916476e22e4f198c45a15f83.nq.gz
│   │   ├── 0828b4ffe0cdf83df60410315cb59002824f4b9b.nq.gz
│   │   ├── 08737af202f6610cdb8ba53fecaefd9c03269637.nq.gz
│   │   ├── 1c23ba9f8184c624c893f93ce473bed7f8982ef4.nq.gz
│   │   ├── 1c8bc55cc8519bb655710d09f8acfaed77b4f7ed.nq.gz
│   │   ├── 21bf6ac7d5e31c385090a244106aae507fa11052.nq.gz
│   │   ├── 246ec4295f05d8fb943a23d366f036346cbfe091.nq.gz
│   │   ├── 2fcfe886735f790f07e72673e74e24b3a4673a7d.nq.gz
│   │   ├── 300b052015f4a6909ce17e2013a3e8ca574d2ad7.nq.gz
│   │   ├── 3232536b968d8668f5cfc2032248fa598e1933aa.nq.gz
│   │   ├── 3a69815be35b5e64795498598e6f2a17233df7c4.nq.gz
│   │   ├── 3b4c10cc96f1c6a6bf96bd095ca1d10b478f8b83.nq.gz
│   │   ├── 3e182fa619002d90c7c3c531a25d76cab0e92893.nq.gz
│   │   ├── 3e3f988abdd97435d06e57fe183a53d230ab0142.nq.gz
│   │   ├── 3f1eca1addcd782e2347350a6ddb2ad2b80c6354.nq.gz
│   │   ├── 3f8ad4bf6c81ee8944bd71cc1ff0718df485e422.nq.gz
│   │   ├── 46a45c7454e4d87ab5671b158f746a2b3beaaae9.nq.gz
│   │   ├── 48efdec45e70a833cc939c1d2752f24e29d1bf0b.nq.gz
│   │   ├── 4aa87e88bf3511c915247af89caf0e66c7aec129.nq.gz
│   │   ├── 518ea7f0ecb9ca6170ed49834fa984eb24b29492.nq.gz
│   │   ├── 5376d62a423aedab5ede02086b33805588f0e94a.nq.gz
│   │   ├── 538b739b8a33bbdbf305e11d93c8bc34154e50d7.nq.gz
│   │   ├── 552ae2c8eb581767526f84946ec36884dab92637.nq.gz
│   │   ├── 58beb78726e76ab3d4ea2635d6b63ac597c32788.nq.gz
│   │   ├── 67545bfae69c8491711646c926d8043146a83e21.nq.gz
│   │   ├── 72baca901c599e7fdf22c2777b9b6a304ddd975d.nq.gz
│   │   ├── 7388defc3eb0422e001f2cbf473d921ba7c48835.nq.gz
│   │   ├── 74e8a3321ea99880fcf320f359abaa1e80654ee1.nq.gz
│   │   ├── 787cb0c2e53c2a3307873d202fbd49dc5eac4e96.nq.gz
│   │   ├── 7c55e2cb3653d9af93515408fb13c3c9f504482d.nq.gz
│   │   ├── 87b56ab82133f083733034526be344bcc37d713f.nq.gz
│   │   ├── 8c0bd7e581591b4180055896cbf72ae8b36003fc.nq.gz
│   │   ├── 93f80779b985db6d8e723d4db891df18f4b068fc.nq.gz
│   │   ├── 9ad5e71e71d414d7775de20cc747961708afdc24.nq.gz
│   │   ├── a0dccbd78d75886247ae7846b460fd390cc94fbd.nq.gz
│   │   ├── a15ec925c1d7a2daece9b5a844b001c0a52bd0bc.nq.gz
│   │   ├── a4816a82870725638b8b3f40ebcc93a74c9d9cbd.nq.gz
│   │   ├── ac3e7c619913bd0ddf9c36b6e633b278d07405b7.nq.gz
│   │   ├── b5b26553054623037b4332c66b54374c38c3a2bd.nq.gz
│   │   ├── bc021b634291223d6829c0a689152173443a8545.nq.gz
│   │   ├── c0002bfbcbe83d69ea394cf7c8c9318c62426b26.nq.gz
│   │   ├── c1c827b91d5db4fac91f26a0071fcc7d26ff8403.nq.gz
│   │   ├── c44c12fceeaa35bcd93009f66fb95cb32f0bffb5.nq.gz
│   │   ├── c92851a660e95a5379a7b8fcf2ae6b03bc789aaf.nq.gz
│   │   ├── cfd8c04213e7ecd1796ae9e542d293d6630e80f4.nq.gz
│   │   ├── d1072ba2c5621b70a0086cc765bb8c96d0376160.nq.gz
│   │   ├── d601c88e38dd6cd5738980e1e6e9e0e63580c419.nq.gz
│   │   ├── d684f91b06fe0119bb854c3b7a804a9f1ce7cd6d.nq.gz
│   │   ├── d95b1b0c276b70bf58849e54214389aaa6b8af12.nq.gz
│   │   ├── d973403730cd687bba29f8c52f2ca19f7fb4f55f.nq.gz
│   │   ├── dda3c913d884056d98e7b5f1220b2d9ba455f0c4.nq.gz
│   │   ├── e0b986e975968ec6b42816a629f1b8c26690d040.nq.gz
│   │   ├── e579d2c33a4a7d8f087fb9f9b251aa9e9f03bb37.nq.gz
│   │   ├── f080174565c2942ca772c33c01375b9453fe6601.nq.gz
│   │   └── ff9b1159f238f828a18b9d49e27f938e3d60fdad.nq.gz
│   └── repolex
│       ├── 0455cd9b2b0e08ce916476e22e4f198c45a15f83.nq.gz
│       ├── 0828b4ffe0cdf83df60410315cb59002824f4b9b.nq.gz
│       ├── 08737af202f6610cdb8ba53fecaefd9c03269637.nq.gz
│       ├── 1c23ba9f8184c624c893f93ce473bed7f8982ef4.nq.gz
│       ├── 1c8bc55cc8519bb655710d09f8acfaed77b4f7ed.nq.gz
│       ├── 21bf6ac7d5e31c385090a244106aae507fa11052.nq.gz
│       ├── 246ec4295f05d8fb943a23d366f036346cbfe091.nq.gz
│       ├── 2fcfe886735f790f07e72673e74e24b3a4673a7d.nq.gz
│       ├── 300b052015f4a6909ce17e2013a3e8ca574d2ad7.nq.gz
│       ├── 3232536b968d8668f5cfc2032248fa598e1933aa.nq.gz
│       ├── 3a69815be35b5e64795498598e6f2a17233df7c4.nq.gz
│       ├── 3b4c10cc96f1c6a6bf96bd095ca1d10b478f8b83.nq.gz
│       ├── 3e182fa619002d90c7c3c531a25d76cab0e92893.nq.gz
│       ├── 3e3f988abdd97435d06e57fe183a53d230ab0142.nq.gz
│       ├── 3f1eca1addcd782e2347350a6ddb2ad2b80c6354.nq.gz
│       ├── 3f8ad4bf6c81ee8944bd71cc1ff0718df485e422.nq.gz
│       ├── 46a45c7454e4d87ab5671b158f746a2b3beaaae9.nq.gz
│       ├── 48efdec45e70a833cc939c1d2752f24e29d1bf0b.nq.gz
│       ├── 4aa87e88bf3511c915247af89caf0e66c7aec129.nq.gz
│       ├── 518ea7f0ecb9ca6170ed49834fa984eb24b29492.nq.gz
│       ├── 5376d62a423aedab5ede02086b33805588f0e94a.nq.gz
│       ├── 538b739b8a33bbdbf305e11d93c8bc34154e50d7.nq.gz
│       ├── 552ae2c8eb581767526f84946ec36884dab92637.nq.gz
│       ├── 58beb78726e76ab3d4ea2635d6b63ac597c32788.nq.gz
│       ├── 67545bfae69c8491711646c926d8043146a83e21.nq.gz
│       ├── 72baca901c599e7fdf22c2777b9b6a304ddd975d.nq.gz
│       ├── 7388defc3eb0422e001f2cbf473d921ba7c48835.nq.gz
│       ├── 74e8a3321ea99880fcf320f359abaa1e80654ee1.nq.gz
│       ├── 787cb0c2e53c2a3307873d202fbd49dc5eac4e96.nq.gz
│       ├── 7c55e2cb3653d9af93515408fb13c3c9f504482d.nq.gz
│       ├── 87b56ab82133f083733034526be344bcc37d713f.nq.gz
│       ├── 8c0bd7e581591b4180055896cbf72ae8b36003fc.nq.gz
│       ├── 93f80779b985db6d8e723d4db891df18f4b068fc.nq.gz
│       ├── 9ad5e71e71d414d7775de20cc747961708afdc24.nq.gz
│       ├── a0dccbd78d75886247ae7846b460fd390cc94fbd.nq.gz
│       ├── a15ec925c1d7a2daece9b5a844b001c0a52bd0bc.nq.gz
│       ├── a4816a82870725638b8b3f40ebcc93a74c9d9cbd.nq.gz
│       ├── ac3e7c619913bd0ddf9c36b6e633b278d07405b7.nq.gz
│       ├── b5b26553054623037b4332c66b54374c38c3a2bd.nq.gz
│       ├── bc021b634291223d6829c0a689152173443a8545.nq.gz
│       ├── c0002bfbcbe83d69ea394cf7c8c9318c62426b26.nq.gz
│       ├── c1c827b91d5db4fac91f26a0071fcc7d26ff8403.nq.gz
│       ├── c44c12fceeaa35bcd93009f66fb95cb32f0bffb5.nq.gz
│       ├── c92851a660e95a5379a7b8fcf2ae6b03bc789aaf.nq.gz
│       ├── cfd8c04213e7ecd1796ae9e542d293d6630e80f4.nq.gz
│       ├── d1072ba2c5621b70a0086cc765bb8c96d0376160.nq.gz
│       ├── d601c88e38dd6cd5738980e1e6e9e0e63580c419.nq.gz
│       ├── d684f91b06fe0119bb854c3b7a804a9f1ce7cd6d.nq.gz
│       ├── d95b1b0c276b70bf58849e54214389aaa6b8af12.nq.gz
│       ├── d973403730cd687bba29f8c52f2ca19f7fb4f55f.nq.gz
│       ├── dda3c913d884056d98e7b5f1220b2d9ba455f0c4.nq.gz
│       ├── e0b986e975968ec6b42816a629f1b8c26690d040.nq.gz
│       ├── e579d2c33a4a7d8f087fb9f9b251aa9e9f03bb37.nq.gz
│       ├── f080174565c2942ca772c33c01375b9453fe6601.nq.gz
│       └── ff9b1159f238f828a18b9d49e27f938e3d60fdad.nq.gz
└── blob
    ├── 002d77fb801dc01389d5711981899fa56c1657f5.nq.gz
    ├── 007af65ea1ded88b9087d37e69db064acb884e21.nq.gz
    ├── 007e541ff7091167de146a29f844275e530c6b2e.nq.gz
    ├── 00974b58efc2e85ab19a759703935d72334214cb.nq.gz
    ├── 00da7280efdea4809e17618b72f2fa9077f961dd.nq.gz
    ├── 0122ebb973eb69af0a289cc377c800796d54cfdb.nq.gz
    ├── 014e7fb9290480abd55a196815e65a142524d106.nq.gz
    ├── 02053e4c5f7ca92b500607688160f35fe0198588.nq.gz
    ├── 02234fd2295542ec1ea110cae710baffacffd797.nq.gz
    ├── 024b38783566ebfed2ea426d2ceb89d6f7372f45.nq.gz
    ├── 026cf64ca7622efbf85222343cbf8e83ee94c87d.nq.gz
    ├── 02acf41c647ba5e398a022fc67b07cf4c547b73b.nq.gz
    ├── 02eabd4d62825f659022e841891b6f5f98be5096.nq.gz
    ├── 02ff38137ae0f5f23975d61a9d34f1b03135df63.nq.gz
    ├── 0320ae9d3ccd91400cd0097a505c47c681aece73.nq.gz
    ├── 033193785f78324929919f2862fffb21866bf4cf.nq.gz
    ├── 033c3840453cccbdee9c16d5ef2ede01b898e8c1.nq.gz
    ├── 033d73c881305c7df501d4e92979c2dba64ecad7.nq.gz
    ├── 038b0aafe9ed07b1e414f69baf8dc3694a7832ff.nq.gz
    ├── 03ef3e602c7628a3e6c439d1a43774da51370abd.nq.gz
    ├── 044ce6914dd70a200cbc90cbbb9abc9135a66340.nq.gz
    ├── 046527c67883a6ab83c78d3623a57a37b64462e3.nq.gz
    ├── 04cf5e1a92683d6a8309e059451c7a6e9c4f4d15.nq.gz
    ├── 04ec6c8be354cecb991487352639c98ce34de684.nq.gz
    ├── 04f494145444984eeb68bd533a10f1971d26fba5.nq.gz
    ├── 055f11913a2a7f59fc95cf87b057b76146e09f4a.nq.gz
    ├── 05638f4608ce201621df85a1ee00ebeb29deab07.nq.gz
    ├── 0599b31cdcf618288f7ebf1cb5d6ff087fb2cc8a.nq.gz
    ├── 05a27c313567d617c75e75376888e080e0b800ee.nq.gz
    ├── 05ee35eba2dab7f746c0c6b9e226e9747def09fb.nq.gz
    ├── 061f0d7e100b04a338249ae592ead886fa54335e.nq.gz
    ├── 064f99c113df80f2094d727c2f6a4b73f7be49ee.nq.gz
    ├── 067b933e77e04156da70191e1e60d08236a44d3f.nq.gz
    ├── 0688bfe960cf9747373c93e482a64d1369befa11.nq.gz
    └── 06d23c992eba77ae844dce9f71a2a6c7e461b184.nq.gz

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
*Parsed on 2026-03-31 by [repolex](https://repolex.ai)*
