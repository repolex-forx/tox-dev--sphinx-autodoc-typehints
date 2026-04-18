# Repolex Knowledge Graph of tox-dev/sphinx-autodoc-typehints

RDF knowledge graph data for [tox-dev/sphinx-autodoc-typehints](https://github.com/tox-dev/sphinx-autodoc-typehints), parsed by [repolex](https://repolex.ai).

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
lexq download tox-dev/sphinx-autodoc-typehints
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1daf515e3660a5a5f52739d7963951e3cac39b92
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 1daf515e3660a5a5f52739d7963951e3cac39b92.nq.gz
│   └── repolex
│       └── 1daf515e3660a5a5f52739d7963951e3cac39b92
│           └── chunk-001.nq.gz
├── blob
│   ├── 04b28b0db4063b458d4409efe35ede4a32740997.nq.gz
│   ├── 079621cd68f3a95e523ea4d42fb71694434df60b.nq.gz
│   ├── 0e5345ba5c060361357cbc21c2f4b4dd8c251661.nq.gz
│   ├── 0fa35a85c2390fbbcf4f073addb23cce706a383f.nq.gz
│   ├── 116a9c6faeec88177d82c0a9a0f85493aa9bd2f7.nq.gz
│   ├── 11d7421369a44378c89d0b26115d9fd14e134521.nq.gz
│   ├── 123014908bebbfb7ecfa1d15daaceb272fabe05b.nq.gz
│   ├── 131417a0982f154262080ee92329b37de5754f76.nq.gz
│   ├── 157ac7565f679366e4f37043cd46c749dfc521c3.nq.gz
│   ├── 15ddef83a54e598b2ac2f62e9a3e468f90aea312.nq.gz
│   ├── 186f1a8e988dcfeb8fb56c99c87032f8102ed319.nq.gz
│   ├── 1a6602172a38e03e448fc994bddbd599a7f1ca52.nq.gz
│   ├── 1c1a7fbfadc6d8434911cb1979bec044a8debb9e.nq.gz
│   ├── 1e1b3ee59df9509d4693329b121b0838562d2925.nq.gz
│   ├── 262342654b06b6744ed02a6063b3f1ff435b65dd.nq.gz
│   ├── 28dcf074f1d23bc73208ea91d66045ea7f785d9e.nq.gz
│   ├── 2f77cb68260cb182cdeff6bf5d0c146d7ae4390b.nq.gz
│   ├── 2ff089fd8dd930195eb2d18a16ff44dd902bf4c1.nq.gz
│   ├── 325cc91f38de19b07378419b90bbdc6cefd538c9.nq.gz
│   ├── 35f43c1c0addbb5ca2658ee1dd7af03053e5219f.nq.gz
│   ├── 378e079509d568c7b6a9db76088c3112cb799658.nq.gz
│   ├── 38812b10c6cc78870d59ec8b4f748085b76d8b61.nq.gz
│   ├── 3f575de2ae1de46a41471956a09b89568cffae03.nq.gz
│   ├── 409cb142ee3ed7f907d7252adcd1829bca8574d8.nq.gz
│   ├── 467ca2ec54fa79ea5f45219133b10b7cc6e5e81e.nq.gz
│   ├── 479ba3f0ddeb7e73df7549388adf1a5908f42d79.nq.gz
│   ├── 514190016af588384a8ed694b24d2c66c3a444e6.nq.gz
│   ├── 59102581e605854898689a251c852158dd370131.nq.gz
│   ├── 5b98f2b097c3e0f947352bfb4ed166a96bdc5f57.nq.gz
│   ├── 5c4389d55db744cf28d4adc76f4f5293445406e9.nq.gz
│   ├── 5cf968eb4423b12323226474cce34a9e2345e99f.nq.gz
│   ├── 5e7a453862d85a891f228ca88cab76665e2692ad.nq.gz
│   ├── 5f89818f9e63c2f6829c7706c57f223cdb5bbd38.nq.gz
│   ├── 6415d72dab57b15617b44e39d82e5c67934d66f8.nq.gz
│   ├── 642cc03ba96b261e15fe8e60441ee6c5da751a7a.nq.gz
│   ├── 6aa1f9899394fb34a732874b41d6907d0948b62f.nq.gz
│   ├── 6b3319fec521f5b62bdbda02cba888f6640d6b77.nq.gz
│   ├── 6bc54fa64069d670cadf534435e355c30d5e9745.nq.gz
│   ├── 6f695a37b68939ea50581fc739bebbeec96a5d73.nq.gz
│   ├── 745afca1aa01b64651e7eb0f764a8ff2766e0996.nq.gz
│   ├── 7525626dbb20b73b6a9e04ac123acd03f6ad4068.nq.gz
│   ├── 76df337963446dc15a4c5d3273f5d409ea639cae.nq.gz
│   ├── 798b8f86525f881bb29129812e54e10d50da8c45.nq.gz
│   ├── 80c34262392fe64138b1131415cd714330045c45.nq.gz
│   ├── 863b2bc55f8ffcd8388807b348eb4bf5430aa0e1.nq.gz
│   ├── 8b36cc60f69b580c5460334e3e2fa7fde4c4e876.nq.gz
│   ├── 8b6d1fb79345fd8341d6151aab0a7fa27b03bc1e.nq.gz
│   ├── 8efad7a1d14a9bddeecf710ec35f2ecb218991fd.nq.gz
│   ├── 91485fc0305b8c3b41dd749bc83a58fcdef79615.nq.gz
│   ├── 91580ea61f6e7caf509bf57ed039f4e51c462f7b.nq.gz
│   ├── 95505e5c3e122b9b1fb3777eeb534671e354250d.nq.gz
│   ├── 976ab5dc3cf24cf84b3c0b29f3151baf111f7154.nq.gz
│   ├── 97c2bce15bec48cf9517f6ca3581daee13662223.nq.gz
│   ├── 9dee2f33625dee178a8a57d8e449c434c6164d62.nq.gz
│   ├── 9f9e5ef03cc0b872f5ca4634d59d32464e5e4e45.nq.gz
│   ├── a327e5bd9ce0b9fafa49f099465fbab2fd9dc0e0.nq.gz
│   ├── a5a5333b1c56462c3732f22ef860e648545e1037.nq.gz
│   ├── acee63f6974ae85a96799c58c9636d05da891156.nq.gz
│   ├── b0a71342ab00cabd77f975bc1dac7c921c1169da.nq.gz
│   ├── b1b03ed0a01f84a29bdc449ff80229485aeceb97.nq.gz
│   ├── b41e16dd8c9c2609b858c19d7d94339d2fd3ea49.nq.gz
│   ├── b5522f7eb9ba2a0e1d11f6def3da86537388bb76.nq.gz
│   ├── b6b8208db658eeb8a9558b1cf30455622a361603.nq.gz
│   ├── b7c8277de91a4e3db9ef1a649b97f8797fbfcdd4.nq.gz
│   ├── b98f0b3eba76b3e51cc888946cad047470d038be.nq.gz
│   ├── bbd417a1cef7b4b8d4aee88e556d5481db99f0ad.nq.gz
│   ├── be4419a79f72a5dfb087ebff492386a7e75bfb71.nq.gz
│   ├── bf02806e54b8fc7dcc18ff898c8cd0f71229a840.nq.gz
│   ├── c23996acc43878f0128acecda55c37a80654c9da.nq.gz
│   ├── c920b7dedf10ae25366682cd728947dc91aa2a6a.nq.gz
│   ├── cbc30c7a85f895b6bdc54c2c1716d680eb2af8c0.nq.gz
│   ├── cce55fa3c288725c931a7e969e9fef57ff432c50.nq.gz
│   ├── cf4a24c9979677780274af43c78aefbb88069c90.nq.gz
│   ├── d5ca70140431abf793250eda23fbff4fd43ac288.nq.gz
│   ├── d6f113cbdfd7feb0a17031d25df1f9ce26b3172b.nq.gz
│   ├── d93aec48639a5ab8d15661b1cadc160d6eb8c110.nq.gz
│   ├── d9da84c83cbaba4d73b10cfd09fab68217dc231f.nq.gz
│   ├── dbe108e1c1986d2df673ab8e984f2d5ae8ef7fc9.nq.gz
│   ├── e09fa6b8e48a0e554e684cd937befaf5962708e7.nq.gz
│   ├── e5542ed2d5bf2d966e47978133d275d1fae3bf31.nq.gz
│   ├── e5749e98ed56f5151967da9f319e29380e3a72a1.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eacdfcbf9ec09360753bca36e1298fe5dbc461c6.nq.gz
│   ├── eb387fc51f2dd491ebed981d1d92125ec32804d5.nq.gz
│   ├── ebbf98ffb9a7de2e0aa760ab6504b1feb2434740.nq.gz
│   ├── ebd5f0faac9fc9d0c669711b45c07de713ea61ae.nq.gz
│   ├── ecdf33d80bbb91cef9bf6a184e3043832e219da0.nq.gz
│   ├── ef5f2504accd6e2a70f16bbecdac70f90e033e46.nq.gz
│   ├── f0f2753519e23af8126d65f8ae1a020da854ca9c.nq.gz
│   ├── f30749b7b12bf6545aeb3c51494d2919470f5db4.nq.gz
│   ├── f342eaaa6a0a1cb2b53eb307c1c668ae67d7a9ee.nq.gz
│   ├── f7b30345638defb53d7eaa266fe0b7fa8340a981.nq.gz
│   ├── f92eae8195d16da097eaccf6e130bcffd8eb340e.nq.gz
│   ├── fb1efd3eaee1459dd6b8614c20777e39ae86d1cd.nq.gz
│   └── ffc6443642acaeeb4cdc55ec31251d4ffe99da22.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 1daf515e3660a5a5f52739d7963951e3cac39b92.nq.gz
├── filetree
│   └── 1daf515e3660a5a5f52739d7963951e3cac39b92.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 105 files
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

[tox-dev/sphinx-autodoc-typehints](https://github.com/tox-dev/sphinx-autodoc-typehints)

---
*Parsed on 2026-04-18 by [repolex](https://repolex.ai)*
