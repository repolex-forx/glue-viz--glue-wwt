# Repolex Knowledge Graph of glue-viz/glue-wwt

RDF knowledge graph data for [glue-viz/glue-wwt](https://github.com/glue-viz/glue-wwt), parsed by [repolex](https://repolex.ai).

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
rlex download glue-viz/glue-wwt
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2be42f065687a2fabad65b1b0583d858e9c3ea73
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 2be42f065687a2fabad65b1b0583d858e9c3ea73
│           └── chunk-001.nq.gz
├── blob
│   ├── 03212e3f854537eda8f1df2d42cc4a958d799e35.nq.gz
│   ├── 071f2e46375babada75e4c2eebfd115fd1372484.nq.gz
│   ├── 1e25a6c47c910d36232da6da4cd190b20f347daa.nq.gz
│   ├── 2cdd67cb811d0924fea5909baacd9df964466d7d.nq.gz
│   ├── 2df1bd6bcb16f2a3207d1d6925b379201cfedb0a.nq.gz
│   ├── 2f7051677eba441a19720176783411ecf42aa7d0.nq.gz
│   ├── 3721278463b196b7f502f8503e4371b800acb225.nq.gz
│   ├── 3dcd7f3bbc83cfc1df8fd68b1bd293ed420570f9.nq.gz
│   ├── 3fadb19095e0072ee355f9e0ae45d0327960a633.nq.gz
│   ├── 43736a1377ba3b097ec5903f4dccc2ac00b95531.nq.gz
│   ├── 48f74ddb056a337f157c3a492a7b3b1dba5e6b5b.nq.gz
│   ├── 4c95c3cdf9f059143e7da607b4fa720838f55058.nq.gz
│   ├── 55629aff880c62d568ec26f484f23bb17bea9ad7.nq.gz
│   ├── 567f74c76c0e1f8262600b06c6db68d2ba2034ea.nq.gz
│   ├── 5ad2f30e8ef8f446bd6bcccd6b31b79714effe6f.nq.gz
│   ├── 5e4e1c474cad1c9884ac200894551a9840653107.nq.gz
│   ├── 772d787b35d10f83e6bbdf1d7b475fdc848656da.nq.gz
│   ├── 7a05d39016b4331c0375848dc6e49183e9646673.nq.gz
│   ├── 7a085181183382167ebf099dff4740f2af26ace1.nq.gz
│   ├── 8293e2f0f73d1360ffe0b051427a2c2fdee9e429.nq.gz
│   ├── 880bbc70441f015beccbfff5ce5752d257795957.nq.gz
│   ├── 91a4f8103e18ce92b15e3fb94dafe4a63d59f431.nq.gz
│   ├── 93cf2076e1720d19f01b7fefead09143a52f8b5d.nq.gz
│   ├── 9489a89d235c4eb93077a50e2f6777d80e326d25.nq.gz
│   ├── 9d753abdfe1d594c2da373d0b4cf22bfc9352bd3.nq.gz
│   ├── a336e5b9a0c593187d75e0720d4a5faa16900090.nq.gz
│   ├── a7031297ada1d7f3f7ab7bd55a2ff7a2f3c90e59.nq.gz
│   ├── ae74ea79662ff5eff57f3af32e71d83a46d1df5e.nq.gz
│   ├── b56d0abb6374800100a0883ee99d1f80bcf1ad63.nq.gz
│   ├── b67705a9636707626c6940aa88a040b60813549d.nq.gz
│   ├── bcef6c577011bc0b9c65b390cbbdef9a6f1c62ea.nq.gz
│   ├── c56cb1b8a99d0dfd371d99841e6120d3ab3749fa.nq.gz
│   ├── c5bdb56e92368230e5353fb4c4dee44b660bba8d.nq.gz
│   ├── cc94f9b8436b8c9e9113200ad723d33249458069.nq.gz
│   ├── d26353c6ca76fc3ebf415b6aca88d7573be5a19b.nq.gz
│   ├── d83e524e41597775008a717afaa992bfaa5cf51b.nq.gz
│   ├── dc41b87671e67274c8ad6fe633a79cefca8e73d4.nq.gz
│   ├── de3cd94d005cb6c4b5f533ae5bba970bbff5082b.nq.gz
│   ├── df6720d16da1591008d032c78eae6ec2117f3ec1.nq.gz
│   ├── e20c66f9ac17b7eba9a6cb6a89e3bb4dd4e5aa78.nq.gz
│   ├── e601a6062947fe5028472d57054ac5c5e34d59a4.nq.gz
│   ├── e631e5ea298758edb19a444d9682b8cd8ae89af8.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── f09e4e715f929ee0524a494d01eb216f89fbf035.nq.gz
│   ├── f1cc76aebc17a79671aa3a36b2e20f55da5507fa.nq.gz
│   ├── f2764a40c5a53caacbae15e3eac89ccb93fc1288.nq.gz
│   └── f7388aa3d41a79a59ae3134353ae8eacd832d1c7.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 2be42f065687a2fabad65b1b0583d858e9c3ea73.nq.gz
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

[glue-viz/glue-wwt](https://github.com/glue-viz/glue-wwt)

---
*Parsed on 2026-10-16 by [repolex](https://repolex.ai)*
