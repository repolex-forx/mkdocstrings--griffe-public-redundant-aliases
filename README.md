# Repolex Knowledge Graph of mkdocstrings/griffe-public-redundant-aliases

RDF knowledge graph data for [mkdocstrings/griffe-public-redundant-aliases](https://github.com/mkdocstrings/griffe-public-redundant-aliases), parsed by [repolex](https://repolex.ai).

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
rlex download mkdocstrings/griffe-public-redundant-aliases
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── fc24c832817bd971ed5c775b49d0dd8b5f28ef78
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── fc24c832817bd971ed5c775b49d0dd8b5f28ef78
│           └── chunk-001.nq.gz
├── blob
│   ├── 002b2a0406a2be01fdcfcd78c4a90218458ac9cd.nq.gz
│   ├── 0536cbbe261b2d97ed3d94f5b1fd86596a2ae486.nq.gz
│   ├── 0b399b2ad8b4b26b5241a1412d7cf68597ec71c2.nq.gz
│   ├── 0ca7fabfe18b401de8974a8668482dfddfb3b9e3.nq.gz
│   ├── 13c3eeca9b130822ffbb6c44628060ffa3adf2bd.nq.gz
│   ├── 276c7e5e06bcf6635c7eace9cbc8092145f978db.nq.gz
│   ├── 286764126c465271953e44b045c6d1dc33f268a7.nq.gz
│   ├── 29a651f57282b5669a2e06bd284c7c3bd4c38411.nq.gz
│   ├── 2b37d3e32241fab2a7507c23c26e70f5753dfa1b.nq.gz
│   ├── 2d46305a68da4b9569bf6813f4d2fb1131653842.nq.gz
│   ├── 2df98fbcac88d8d93c9d18648ba7d5a800100ce0.nq.gz
│   ├── 2fcf869f97e3db32d04bba2de14fc59596538076.nq.gz
│   ├── 30571233ab2743c8bfa278db17f69b884823c94f.nq.gz
│   ├── 327785cd77692d6070d6a13b4f7bac59fc46d67e.nq.gz
│   ├── 332787e793adf2259bce52625ecc3ee1b801f683.nq.gz
│   ├── 35ec8f1917b21691560159f7e6051600f0674f58.nq.gz
│   ├── 461f7e3d73ca89f0dee46d673a8057f563b9873f.nq.gz
│   ├── 51587578d052005002f5e1f131bfeb180807caed.nq.gz
│   ├── 5b25a00f43bcb9d2a68e49250995865e6608c26c.nq.gz
│   ├── 61935e5d49e2b4f90babe55d6bda7b7401cfc1b9.nq.gz
│   ├── 640c03d38d9ae465d8b89310ce816ec1c13b6a61.nq.gz
│   ├── 646e8193395b2a7bd0b5d399c3a088165f6e99fa.nq.gz
│   ├── 68bec35537cb0dbe0c7d5ae73f80ce6bee97ef8c.nq.gz
│   ├── 698454950a6f8b591e80d33ba0b50a33136512ac.nq.gz
│   ├── 69c718c50fe10344008b3352744c768bafdd1c7b.nq.gz
│   ├── 6ec48d5821210cae0f7ce914b88fa04b4b7cde8a.nq.gz
│   ├── 6f0f2faf32486394750d5d5421e2261430b73fef.nq.gz
│   ├── 73145eec7e2a896212b2a9165dcc7449f0abd318.nq.gz
│   ├── 7402e8aeeeea371d9f4059a45ef6be41a33da387.nq.gz
│   ├── 767bbe280e6ddf497104f316fca52259955da077.nq.gz
│   ├── 76b6b516bf8063cd5deff98c4aeb8a44dbb0fd13.nq.gz
│   ├── 812789e68bf5688ca56d42a80caecd04c1e0c4b4.nq.gz
│   ├── 82377e2175cb6a3e81bcd4650e4c158db89a8004.nq.gz
│   ├── 86fa81046867db66be407a5d0d6f15205909a887.nq.gz
│   ├── 92ac8ec5dbe177b6e29da9600c7c3fd18d8069b9.nq.gz
│   ├── 97724fa80f2fd81fddb1eb8b00029dc4fee78054.nq.gz
│   ├── 98cbfdd106f6af898b9ceed1ec1f707b532c5173.nq.gz
│   ├── 9c399eb1d25bdeaad6cd0545eb5f67bebd3674de.nq.gz
│   ├── a09379f1b6893041a9e5249ae2b8e054b532cd23.nq.gz
│   ├── a752517a93d46e1edf6ace7e875fa10ed2c1f29e.nq.gz
│   ├── a870a24f9f15eb47b00bd3c3feef3c82d97687cf.nq.gz
│   ├── b56a2866c098400c2cdb660aa908a99bfd0cba34.nq.gz
│   ├── b84809ecde2efd18f642ba66b2025f8ffa6924b9.nq.gz
│   ├── c12e3db723b240655279e925c634aae51116ddbd.nq.gz
│   ├── c2eda0df52a5c1bd708ad342b50fcc917be81192.nq.gz
│   ├── c4a180a3325cd3b07f80af8b9720a194260373a6.nq.gz
│   ├── c53f3f6ce0e8f8affec56ad2d024489a628336dd.nq.gz
│   ├── d4dabb6e268995ab87c97f90d2f241a9231d6fe7.nq.gz
│   ├── dc711a48b9bd2f8029f3af22e74526a2cb8661f3.nq.gz
│   ├── dc9a8f17c6e3f0117661042120c4413a21065bce.nq.gz
│   ├── e20c2b641b7ace2fe94751c7a47f219ad509bfb2.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6bb5b91b56c550fab69e0f2898006069366f3da.nq.gz
│   ├── f072271cb235e97740a9887ebc76955c62749a18.nq.gz
│   ├── f6ab1aa2cdbbb6aa245be35e5090520815c3f7ef.nq.gz
│   ├── f97321a5d0ecc1a536fc3eeca5a23f446efb07bd.nq.gz
│   └── ff85b33461ae409eabebface6424f6bd01d30da1.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── fc24c832817bd971ed5c775b49d0dd8b5f28ef78.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 64 files
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

[mkdocstrings/griffe-public-redundant-aliases](https://github.com/mkdocstrings/griffe-public-redundant-aliases)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
