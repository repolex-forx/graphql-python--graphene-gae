# Repolex Knowledge Graph of graphql-python/graphene-gae

RDF knowledge graph data for [graphql-python/graphene-gae](https://github.com/graphql-python/graphene-gae), parsed by [repolex](https://repolex.ai).

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
rlex download graphql-python/graphene-gae
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 7cf364eddb6d5b76575f5e80fb97a588c92634a1
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 7cf364eddb6d5b76575f5e80fb97a588c92634a1
│           └── chunk-001.nq.gz
├── blob
│   ├── 026a1f7cb80a3a982a0aaa6758bd28a15e2a816c.nq.gz
│   ├── 035bede248748700546b9119569e4050f6c0e57d.nq.gz
│   ├── 07ae83efd3c4b2d60eea4ecc05b2aa8ec8d26b0e.nq.gz
│   ├── 080af774ddae14b54af72f133c26b9f0070bf8d1.nq.gz
│   ├── 0f54ad33c9ad527d220a7c77e400069f15c57a25.nq.gz
│   ├── 0f852e7502518d5054804c8da96fc73dd9e1cb4b.nq.gz
│   ├── 1037a61643b07db65dc67b94c6afc34156a51c0b.nq.gz
│   ├── 11008aa29bed1524d7e77a9dec77299071479d90.nq.gz
│   ├── 1472f3966357c4153ef22872a7cc41dca1751b9f.nq.gz
│   ├── 1bf9b2ce8dd86b7ca792022357124173bdfb4357.nq.gz
│   ├── 20cd2f0829bf2371e51691456190d4be833427b0.nq.gz
│   ├── 250649964bbc36f4bec2942f69238aa6f7c02c1a.nq.gz
│   ├── 40a96afc6ff09d58a702b76e3f7dd412fe975e26.nq.gz
│   ├── 43dac2a66447108e06fa7f3f43234d7621747e0a.nq.gz
│   ├── 532efc1d9d2313991eb45019bbbbd608689d5745.nq.gz
│   ├── 5e4090017a9bec5de60a745d17007a9e95f31a43.nq.gz
│   ├── 5ee7e89ae9487aa84ec385160b5a44ca32a876b8.nq.gz
│   ├── 671bf3cb4a9ac5f27b15ea8394cbed7302fb9b08.nq.gz
│   ├── 689e86fbf508d4269529277c46694547aa57e801.nq.gz
│   ├── 72a33558153fb57def85612b021ec596ef2a51b9.nq.gz
│   ├── 75bbef86ef3dbac91906acb93ad9c17c418ed46b.nq.gz
│   ├── 78d314a7391c96f9ba23ec119e391e0915456d85.nq.gz
│   ├── 857f00be36b14d12f90bca1172cfd0a3aa4dd28b.nq.gz
│   ├── 95b45a8e2b76d35cee723e06a10ece4f1bcaafb4.nq.gz
│   ├── a60bbbf6e57e3a598cb5092ec130252be591a2d1.nq.gz
│   ├── abadddc068d2dcc7fa97df1e2135dad4aaa9518e.nq.gz
│   ├── ad238758ac2d14a51733da792c61b0ab1e5b0377.nq.gz
│   ├── b5414ca648cbd6269486fa6fc4a2d182394733fa.nq.gz
│   ├── b5b1e7ee5c3bd687d37b4c096f9d186bea5f2c09.nq.gz
│   ├── bd453b5cf9a14867478f6bf49f0ea9c38961b84e.nq.gz
│   ├── c701300df55a0d1fb7abe6ffbd92bc98d00da6f2.nq.gz
│   ├── cb0f282b49f115abcfa14a95920dae642eb3e917.nq.gz
│   ├── cb64e9ed46c5fffb54874d617926cb3ba58be83d.nq.gz
│   ├── ce08cbe01721432e8ece50e144ec6e92aa417be4.nq.gz
│   ├── d46ef570341376e5279c25cbec2ee477b321ce56.nq.gz
│   ├── d4a2c4405ec2e962c521a13af91bf5f7098a62a8.nq.gz
│   ├── dbbcf83577cff6f8cc12ea85c57668c81bf093c3.nq.gz
│   ├── e122f914a87b277e565fc9567af1a7545ec9872b.nq.gz
│   ├── e582053ea018c369be05aae96cf730744f1dc616.nq.gz
│   ├── e83a2e827727d7ad1b760c7bfa3fff28f265a56d.nq.gz
│   ├── e98ef4ee182bba8b9cb4e2bb95cd69a29091dd73.nq.gz
│   ├── ece0c0c6d74eac3f87828537af6388532f1a3f22.nq.gz
│   ├── f51540c8edc9f8326318f18037d2aea4b28cc7c7.nq.gz
│   ├── f61404842cc85e2ec6240fdb77914f3b8e9f4d0e.nq.gz
│   ├── f70079abc23e2a4161a080f73867e8d2f28c4762.nq.gz
│   ├── f8787665ec89d76f7327fb11bdf63c0948b95b3f.nq.gz
│   └── fdd9e3e04aa0a8d9675b9bb1afbf812883ef9220.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 7cf364eddb6d5b76575f5e80fb97a588c92634a1.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 55 files
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

[graphql-python/graphene-gae](https://github.com/graphql-python/graphene-gae)

---
*Parsed on 2026-10-20 by [repolex](https://repolex.ai)*
