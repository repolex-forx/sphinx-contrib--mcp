# Repolex Knowledge Graph of sphinx-contrib/mcp

RDF knowledge graph data for [sphinx-contrib/mcp](https://github.com/sphinx-contrib/mcp), parsed by [repolex](https://repolex.ai).

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
rlex download sphinx-contrib/mcp
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9a7861472272a1f47449b17ac2d19e87d16fa870
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 9a7861472272a1f47449b17ac2d19e87d16fa870
│           └── chunk-001.nq.gz
├── blob
│   ├── 09915e084dcd6fb83bb1e92b0c3552ea67a64ca0.nq.gz
│   ├── 0d0e2672e865a9cc689cc03aab0d43b50831200f.nq.gz
│   ├── 157f958d7100297bc194d2e511b7a67690d44e0a.nq.gz
│   ├── 164649e6ac40d21cf37eca4c83dffd43dd8796e9.nq.gz
│   ├── 1d0ea60cf755c6e6204105916e26c04b28e60f3f.nq.gz
│   ├── 1db43f72494fc1c0ec8e2281608821c235f48337.nq.gz
│   ├── 1f105c3c116873f0996510362325f533436a16cc.nq.gz
│   ├── 2297f5b885bcb1eb613f95c2b2242ac52da468fa.nq.gz
│   ├── 32bb24529f92346af26219baed295b7488b77534.nq.gz
│   ├── 336f735d2b8e2f0c6f38b64af66ea8d594a5e0d0.nq.gz
│   ├── 3b9d72539479b0c9daa140dd7d1ffbbe833f5437.nq.gz
│   ├── 3ba13e0cec6cbbfd462e9ebf529dd2093148cd69.nq.gz
│   ├── 47dc3e3d863cfb5727b87d785d09abf9743c0a72.nq.gz
│   ├── 5332c33d7fa6c092a5d23af063b02d77fa509a72.nq.gz
│   ├── 53b56505ac45bf4cee1b7008516d5983c416fb74.nq.gz
│   ├── 5964c8ca5f2428a52bf7eaa3601cd5c9e26932ff.nq.gz
│   ├── 5e834c66b120545014a109c6fbc7187cf96b9833.nq.gz
│   ├── 68f35460aa29b245b516484dcb4f20ec770d24dd.nq.gz
│   ├── 694d17663c54b7b3a5bcc4c444364cdf381f480f.nq.gz
│   ├── 6a5f3ca03ed2ecf6bd4d56341eb2b05735a04bfe.nq.gz
│   ├── 6c57965e782685983c92b3d8ae17e6d3f8bebcbd.nq.gz
│   ├── 6ec7675326d5398a9acc0db13c4531249680598e.nq.gz
│   ├── 7885a0daf5c7c9b19370b1aebd48eca647343c0a.nq.gz
│   ├── 78b674b70d617b3acaeeb9e7c1aa92de1642d26a.nq.gz
│   ├── 81eefdd09749cc33227a63619c64de5639901931.nq.gz
│   ├── 836c5141d7327c63b5dcae9a0351e09061f7e45a.nq.gz
│   ├── 8f243cb19acc0a6a309e239070f231f365e01455.nq.gz
│   ├── 9d357c838730bd2537a7a388e1e71c7bc8c81bdb.nq.gz
│   ├── 9f3c44238acfe01abe4c980ac69b796a85435c7d.nq.gz
│   ├── a35ca76fb5edd2ae8e737028ced209944b210b68.nq.gz
│   ├── a5a5130ede83e3660ab8cfe9b485b559271d62f4.nq.gz
│   ├── a9aa0f3bf4ba2b8311c60e742885d671a3daa3b7.nq.gz
│   ├── aa898dbbdcbe40c262ee87bbf210034bedb31489.nq.gz
│   ├── aab9ff4bd1c48d97bd04657345c448713626ee89.nq.gz
│   ├── af633837516ca0da65bdb86c7834a8778def77bc.nq.gz
│   ├── b1d4f3634057da7364dc52ec3bd607f2f6e4e034.nq.gz
│   ├── b35ee3a49f09481919a16203b5f8b11e5b0d36ac.nq.gz
│   ├── b50dd1f92c8571fe0df160e2505dc0f142b90b6f.nq.gz
│   ├── c5089e768f9decb57329c823af14c3bb74b96a32.nq.gz
│   ├── c5541162f8622da9dabff2824815fe9a8cf5d220.nq.gz
│   ├── c79201f0e076c2fe5f42436caa51b1dbb439ae7d.nq.gz
│   ├── cf2014644141abcc488674675f5943bc97d330ab.nq.gz
│   ├── d27450bbf7b6645cfbc7d99c5dd56f1c8f8deca2.nq.gz
│   ├── d4bb2cbb9eddb1bb1b4f366623044af8e4830919.nq.gz
│   ├── ddbf28868026d8224636c2edfe938c33ee7c615d.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ef7d69f2dce7f73353ae7b25edc082e037f7be7a.nq.gz
│   ├── f1e49535b3494ee7fa190efe4b9d1c1b82cec300.nq.gz
│   └── f5adc9497f19ef562535a9a7c9d596fe36901560.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 9a7861472272a1f47449b17ac2d19e87d16fa870.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 57 files
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

[sphinx-contrib/mcp](https://github.com/sphinx-contrib/mcp)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
