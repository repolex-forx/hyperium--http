# Repolex Knowledge Graph of hyperium/http

RDF knowledge graph data for [hyperium/http](https://github.com/hyperium/http), parsed by [repolex](https://repolex.ai).

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
lexq download hyperium/http
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b9625d83b524f7a8306883484f29a746eefc1bab
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── b9625d83b524f7a8306883484f29a746eefc1bab.nq.gz
│   └── repolex
│       └── b9625d83b524f7a8306883484f29a746eefc1bab
│           └── chunk-001.nq.gz
├── blob
│   ├── 00642f83799e7c7a2b997c26cea2e7fa04fded37.nq.gz
│   ├── 031c08df2b3d347f0bef58c0739d3e12c5bc86e4.nq.gz
│   ├── 0a9623980433f88a370a1218124b5d58b31bf57e.nq.gz
│   ├── 0ab5bdfd0bbea92cafaa567c7c83a1dbcf0f1013.nq.gz
│   ├── 0cbc550492304b54320d9320d475c9f067adcebd.nq.gz
│   ├── 0d881f52ecbcbd72774ac3e89b021b54a2c89fbf.nq.gz
│   ├── 0eb36b7d8928ff480e8e3010dd792839aae9fdb0.nq.gz
│   ├── 1a3eb15d1a9e93bae4633cd362e8f1d3d5756476.nq.gz
│   ├── 1a5f1ede6baf486ecbd0feb8b63a1f3e92f09159.nq.gz
│   ├── 1b4a39d6981e252c31f1d02c9b24201cd50424ba.nq.gz
│   ├── 1c8906f0203a7cb4738b50fefc1880633d792c04.nq.gz
│   ├── 2a7028e2aa06bc016fd8495604191b01f87ecd24.nq.gz
│   ├── 2e1004e96ef1767796957fe197e4d4da64f94ffd.nq.gz
│   ├── 336b2347848a893445acf1a981d55adc3d1dd048.nq.gz
│   ├── 34f393c396ab41ea2cc8d47163fbfe431a80af26.nq.gz
│   ├── 40db0494b612d58c683f4fc62fe397fffb3c444c.nq.gz
│   ├── 4249f9877801c5c9baba8b5c8fa45ae1418002bb.nq.gz
│   ├── 4562fd6633f729ce87e258be1c5567f56786f80a.nq.gz
│   ├── 48308cb46378f550db2f691be2876656e490d119.nq.gz
│   ├── 49994dbe65a0a516e0b17f32f035a11d0a230590.nq.gz
│   ├── 608a38fa408d8baa017d4c137501ecc8f4eb9ac7.nq.gz
│   ├── 67754e454d62db361c260b102f98d748e5fcbf6e.nq.gz
│   ├── 682e0ed5a865142e0bce1600591574ef660f52c6.nq.gz
│   ├── 719cb94ee35f4cce5e7e998cf9c4e1407007f6e2.nq.gz
│   ├── 762ee1c26a659e2d67eb8009a1f37ce1dc3cd709.nq.gz
│   ├── 767f074339be9b60409a5744f9d1315adb88e64d.nq.gz
│   ├── 7b4584ab79899a2ace692f94cc2435dc8870fa84.nq.gz
│   ├── 80176c2b2399dd0827805600dd7422c96c662484.nq.gz
│   ├── 8c198a026abef04ac5f3c1bf765775db6147eb18.nq.gz
│   ├── 8f9356e87d40ecd226db7f33ce1eb6dddaabe6c2.nq.gz
│   ├── 94e285cc973b521de7da7bb82749d6acc9e80873.nq.gz
│   ├── 9a9d7e1235b35a8be998ecdf267d79be73d04ae9.nq.gz
│   ├── a9d37c560c6ab8d4afbf47eda643e8c42e857716.nq.gz
│   ├── ab7425ee564d3ae1edd880b69d37d13973efcd4c.nq.gz
│   ├── af6b623b0af27917bc839f9c6a8463bf63ea3137.nq.gz
│   ├── b49af1b03f22c3ca63397c7baf6501bf8e4ead0c.nq.gz
│   ├── b8fc9b2aa182d29beb1cb353dabf355d48e1acc7.nq.gz
│   ├── bc58ba452d218c6bf25bcc76d9af18ce76766d57.nq.gz
│   ├── d0317b333a75fbd5afce5c66d2331d76baeddb9a.nq.gz
│   ├── d5f7f49b1151cf609f5e9f67276ade8062e0741e.nq.gz
│   ├── d8b713061e3caccc26804936afcd1ce2267d2a4a.nq.gz
│   ├── dbcc8c3f2d47edd73f9cc71a691aef7bd2a83ef2.nq.gz
│   ├── dfc4f03169dca421dc6687871670ebac833bfdaf.nq.gz
│   ├── e69bf0a8976e62e075466a8d1981b155f63fa6ee.nq.gz
│   ├── ece9b77ff696f80370aadba7e4ce6e0af4b13e71.nq.gz
│   └── ed6f85c293ee1c23f9617b0c5255b8b65cd8b5c2.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── b9625d83b524f7a8306883484f29a746eefc1bab.nq.gz
├── filetree
│   └── b9625d83b524f7a8306883484f29a746eefc1bab.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 56 files
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

[hyperium/http](https://github.com/hyperium/http)

---
*Parsed on 2026-09-07 by [repolex](https://repolex.ai)*
