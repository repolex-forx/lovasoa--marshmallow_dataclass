# Repolex Knowledge Graph of lovasoa/marshmallow_dataclass

RDF knowledge graph data for [lovasoa/marshmallow_dataclass](https://github.com/lovasoa/marshmallow_dataclass), parsed by [repolex](https://repolex.ai).

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
rlex download lovasoa/marshmallow_dataclass
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5c428f493ef3059246974bedf9a7d89599994b34
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 5c428f493ef3059246974bedf9a7d89599994b34
│           └── chunk-001.nq.gz
├── blob
│   ├── 0295ccd7d3594adc64de017ae5103f7fa8691f00.nq.gz
│   ├── 02da4179a09f6d682d07ecd1d4144c46155be076.nq.gz
│   ├── 10742dad88756354e4029398f39e6b40462b132f.nq.gz
│   ├── 1aba38f67a2211cf5b09466d7b411206cb7223bf.nq.gz
│   ├── 20026ca68f041fcc2deedf795cb6443ae84e88e0.nq.gz
│   ├── 22db2f7c168edfca6aa410005724fb86f4426e62.nq.gz
│   ├── 28185a47e3245215745b50a5bc77c3ba789dcf6b.nq.gz
│   ├── 2a2fa9654194c990d6f523f66f9fc4108f6f8422.nq.gz
│   ├── 2b9d121879b44aa383879da25b05cc85be0451f0.nq.gz
│   ├── 2c4eb014ad63537de6913a3cedeca4a4b2880a20.nq.gz
│   ├── 2dbe4a4bdde31e2b769dc52341c6c11c0961aa54.nq.gz
│   ├── 2df7fb597c6195e22710da80cf1702db1b9cd18d.nq.gz
│   ├── 2e53c2c2f2419918057efc6d8b28b42a45b612a3.nq.gz
│   ├── 306430ec15ba85b59be27e55a42558bd75576ce5.nq.gz
│   ├── 30a50ff5e4dd77090e702cd04652708fc2e9c853.nq.gz
│   ├── 4767319356fdd3c52a49c6048274a16b7bfd87f7.nq.gz
│   ├── 47c0b01a2b2fbd3ea76e1a4601e08553317aaf43.nq.gz
│   ├── 4db2f152dc174e25c04750773d9c7685db15cc2f.nq.gz
│   ├── 5189a0564844b3e204c79fcee1ff68d08c357dbc.nq.gz
│   ├── 57a8c3dfeeeef467b7fda8b86f1d7e4c19a806c1.nq.gz
│   ├── 5e9dc0b7a34b5d9053cbebc60b7be04fcba8867c.nq.gz
│   ├── 5ec6c6d18d40747b48bb6cba3d9b7c7e7e8d8837.nq.gz
│   ├── 6823b72afe75f41272f02c9050c0582eb27dd77c.nq.gz
│   ├── 6d9487d92d3aa619e7022bee5b1e654cdb6cbac1.nq.gz
│   ├── 7aad9414ad43fbef8695c8a5ac67b19c82362872.nq.gz
│   ├── 7c0f00292b9f709384062bad5009b6c2f03716ff.nq.gz
│   ├── 7ffceb7fa4e97012b630ed5ca5d527da8d0c25b5.nq.gz
│   ├── 885fe18e2fe4ac419afcfa778c07a8d5b59144ae.nq.gz
│   ├── 8d52b236682b58ef6a48b5c86d9c26de5bf282b4.nq.gz
│   ├── 98395729a0cef34350948a9981e1b1efc04d3eb0.nq.gz
│   ├── 9841fa75ac84e1bc522de85c873e6a023032a96a.nq.gz
│   ├── 9d47786b423d4d30c6362f1eed70229e7b0d7db0.nq.gz
│   ├── a5dffe23f125c510411463db27bda8133acb188c.nq.gz
│   ├── a9b2bdc94c1965cea9b189aa2becb50ffe1ff506.nq.gz
│   ├── b0627d9c26ce52e7285ae706f9d4e7d5d15d92e2.nq.gz
│   ├── be763d9ba0c1639af43cc6ec24a034c7dabc2654.nq.gz
│   ├── d33a5ad3e62d8a6f587b71ba1bc88dd4a9e57240.nq.gz
│   ├── d5d5ec6a19ab01296b3de662e2de610671d306f4.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e9105a6106e51145b22b170d9e6652d6898325a1.nq.gz
│   ├── ea4028e809506b44073839a60e363e36f92a30da.nq.gz
│   └── f9a8cd761e9b2e47b2f49419b968d4751fd80439.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 5c428f493ef3059246974bedf9a7d89599994b34.nq.gz
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

[lovasoa/marshmallow_dataclass](https://github.com/lovasoa/marshmallow_dataclass)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
