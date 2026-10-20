# Repolex Knowledge Graph of jaraco/jaraco.media

RDF knowledge graph data for [jaraco/jaraco.media](https://github.com/jaraco/jaraco.media), parsed by [repolex](https://repolex.ai).

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
rlex download jaraco/jaraco.media
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ccdeff8971268a88198dd2685562f7a5f75f850e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── ccdeff8971268a88198dd2685562f7a5f75f850e
│           └── chunk-001.nq.gz
├── blob
│   ├── 11d0a447306e2d3c5b97a7405acce57156bd8254.nq.gz
│   ├── 178cacdaf204d9e0cda2be62d44860d9ab8a1374.nq.gz
│   ├── 1f2aa7533b0423a8eb943f6f4ec02498e39581a0.nq.gz
│   ├── 213f4c5b6cc214f666a5a2f999f238e00f2841a4.nq.gz
│   ├── 22e9306837c2d20804417c096a5c9008c03c13f8.nq.gz
│   ├── 240329c3604d8ead4c10aa8c88352caa8e4ce7b2.nq.gz
│   ├── 240fea94869781a4a4da7ce042ad1803218985d9.nq.gz
│   ├── 249e5bebf9b1a8ad848fe6823c4c2eb4de5da73e.nq.gz
│   ├── 2b364ddafdc9a566693ed32d06b05a479a0a7f72.nq.gz
│   ├── 2e3f4dd791a6372b427d618eb0baa8c4dc58e5f0.nq.gz
│   ├── 304196f81e11a168c9894f966e4a617ebf4ed53c.nq.gz
│   ├── 54c9000ec94341dd65c2053251b85b124017b9b5.nq.gz
│   ├── 54cc8303b22089e12053e552d4e6cb852a865b8a.nq.gz
│   ├── 577e87a793a20e413f7321f4f17ec1eba2ea1962.nq.gz
│   ├── 5bdc232005af9be104a00437ae9bc64417a4c1cc.nq.gz
│   ├── 5c05f9e27d57a4b7a3c3a9fdfecf8cddb8be499f.nq.gz
│   ├── 6cdf738cdbcd0cdbd529b58c6b473607995be7d3.nq.gz
│   ├── 700235be57c1b2872455c0be5333f59cf568e252.nq.gz
│   ├── 724370638fc188317bbc7dc868f1a571995fd796.nq.gz
│   ├── 76160cf80bc9a2e77c429e5a85664970d284ee20.nq.gz
│   ├── 7794ef56ebbd6bb4975e7e4a34d5132f716b47c1.nq.gz
│   ├── 7816e14605a24b832d75a7761abe8c52566e64ad.nq.gz
│   ├── 8343e8ee423f148128750ac2352c9ba15c08b91a.nq.gz
│   ├── 84b154680211b6c3b72decd495310188b2510480.nq.gz
│   ├── 88e3f701e38c8847cf7e4a6d1701015e4de619b1.nq.gz
│   ├── 89e04a6fff4c1fab89fb48822ef18c6a44bcbd0e.nq.gz
│   ├── 8c125ce143b8b024136004e7ef45f867e9db2e45.nq.gz
│   ├── 92c42f1eb03bb074621c6ea5808d02c9036d2845.nq.gz
│   ├── 97983d38da57ba4a9eaa4c90abd60a1d67bd9c89.nq.gz
│   ├── 97e42ea439fb84bbb3d53e4031e7e29ef40e2213.nq.gz
│   ├── a216e0689b1c66e4b5deed605fc7ff2b48008db2.nq.gz
│   ├── a7b7a7827f5f34252b8c58ec8b6cad581d3a3d52.nq.gz
│   ├── b248737dbd0bd0ce8af1640a63fcaa0305f20a83.nq.gz
│   ├── c0d9029d8fe08596ae8adc9e398cab1a9693df9e.nq.gz
│   ├── c4aa8ae33377f8986603f19669c376fe9c98cc6a.nq.gz
│   ├── ddd8b112b78a537d7bbe58602363bce66ff33189.nq.gz
│   ├── e05a3d4a2ab888e32952006d8cd380864368db5f.nq.gz
│   ├── e16ca7c2c9ace4b9b46d70be4b45780cad758974.nq.gz
│   ├── e43b7397693dbe91a4bada78b657737ebbc6a11d.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ef318d18dd3882913265c89deb902708fe85873b.nq.gz
│   └── f7e3f3eeaf714645be29d756a16fc95c3ffeecd1.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── ccdeff8971268a88198dd2685562f7a5f75f850e.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 50 files
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

[jaraco/jaraco.media](https://github.com/jaraco/jaraco.media)

---
*Parsed on 2026-10-20 by [repolex](https://repolex.ai)*
