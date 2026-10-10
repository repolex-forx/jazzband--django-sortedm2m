# Repolex Knowledge Graph of jazzband/django-sortedm2m

RDF knowledge graph data for [jazzband/django-sortedm2m](https://github.com/jazzband/django-sortedm2m), parsed by [repolex](https://repolex.ai).

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
rlex download jazzband/django-sortedm2m
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6c9285dfb8b42ee3ae94cbe2c94fe6288408eb0c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 6c9285dfb8b42ee3ae94cbe2c94fe6288408eb0c
│           └── chunk-001.nq.gz
├── blob
│   ├── 05acff5a346a128bef38f5eb5e67c6dcdc90fa84.nq.gz
│   ├── 153ce4f2003763185af98c55094685ae45187645.nq.gz
│   ├── 1d49cd9983137f791c0deccd5353a639301931fa.nq.gz
│   ├── 1f9e0b0c3aa1bae25e06661867b6c5116c1edd0a.nq.gz
│   ├── 21b7c5eedead63a7ebd39495e5fcd2859010b2b2.nq.gz
│   ├── 283740dc6b4c0cececc92bfe64b4ebc9d4c71570.nq.gz
│   ├── 2920c34b24340edd9dbc2ac83e27080158431ad8.nq.gz
│   ├── 29aac7bc69ba07975cefe5e9e2bf9e8eabd17fd8.nq.gz
│   ├── 2b6fcec93850e04b098bfa59488329a932b3e1b6.nq.gz
│   ├── 2f314f2dde7fe5ccada50ba4dbe3a19c8bdeeb99.nq.gz
│   ├── 301d8cd99e823976369dad4d3858cea1ac15caaf.nq.gz
│   ├── 35474d3e34b4355950663e6298b67e0cf22f20e0.nq.gz
│   ├── 376bd071e3b21732ac0fdf4db40c4593dcf56662.nq.gz
│   ├── 39755b28c0101a6fe256637cc420208515bb73d3.nq.gz
│   ├── 3dafc2875ea6d3eee834cf3ee4fc16518340d337.nq.gz
│   ├── 4131ab4251c23dd9d82834cfc51cad15f5629ed2.nq.gz
│   ├── 49c93c68fb98613ea7b11f0c17c53ba60148bdcb.nq.gz
│   ├── 4d028031e8a070f88192dd762c4ce2473135a1ac.nq.gz
│   ├── 522a12701628ecd5648a36bbe1b9d301e2ae8d36.nq.gz
│   ├── 532810f02f7782ce01e898a69585a5d25ca1e84c.nq.gz
│   ├── 567397dacbf6a1d25b81ab70757ccc2aac11a8c6.nq.gz
│   ├── 58b37a1bdecf474f403bf0565de7788effe9b79f.nq.gz
│   ├── 630aa146faa8d91a0264fe7404054075898f3a8e.nq.gz
│   ├── 6d5f4c74923af2daba13baa484364380fb1614b9.nq.gz
│   ├── 7290558bf7cd09a9893c5162280419f3c819810c.nq.gz
│   ├── 758bb56f6b87b8751021b357158334d80d98324e.nq.gz
│   ├── 781f42131b6c24a49b7236a601e1cbd6b6a806be.nq.gz
│   ├── 7c4c8950a7e5da3bed663fa549790d38bdd6fdbf.nq.gz
│   ├── 7fbe040b7b9b33d529efdb7cc13811d8e5504d14.nq.gz
│   ├── 82de930c7d4b1bab7d88cfe49852a50b361bd0ef.nq.gz
│   ├── 83373eff7d108c286fe11d35c58855bd8a95106c.nq.gz
│   ├── 871c70127225ee77feeff023bc94cc4a93a901ad.nq.gz
│   ├── 872ea4e65e3033b7212f2df0052499a7bfa3a7f2.nq.gz
│   ├── 878ef8e99c0924cfbce06fa1b1b5253e68a77c9f.nq.gz
│   ├── a7e55b9d3d265de97bd59b57a7f16d4804e927cb.nq.gz
│   ├── aacbdf52471a1c4a5e49e7d8229b2f5839cb32d8.nq.gz
│   ├── ad78220bf6ae7568b9e1aff6428f7851beaa7865.nq.gz
│   ├── b2af6056146b9f00330fe70b492971ae1081af0e.nq.gz
│   ├── bc6ce2356263a07774de8e0aad27685925b09a45.nq.gz
│   ├── bda594b5b130ebfddfba4bc0b0eedcec46ef990e.nq.gz
│   ├── c1306f8654dedf32d5f43e41aa1dab1581731bfe.nq.gz
│   ├── c5f95c9c34ed4f182e6657cf10ce244fa482fe5d.nq.gz
│   ├── ca1cc714da30a0b0cc5981986c06b6301469afc7.nq.gz
│   ├── cf8a11c3f72c8fe75bcebe2f0505fab424583118.nq.gz
│   ├── d4529c2c4a6cabdccbd3c0910bb8fccacb902d00.nq.gz
│   ├── d6497a814c169fcedb9c339f376d752466f22481.nq.gz
│   ├── da6a6c2964f791a19cc83e368c1ec5aab16d281b.nq.gz
│   ├── e0d5efab56fb94577e7804603eb6f21f36977cb2.nq.gz
│   ├── ecb7eca0062b46db86e1e31b331a23ffd2933958.nq.gz
│   ├── f1e81cd4fe1cb1742217c4431fdc07ffe9f2c125.nq.gz
│   └── f2ec50ff81cb8923bda952e16b0e743547ccbe23.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 6c9285dfb8b42ee3ae94cbe2c94fe6288408eb0c.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 59 files
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

[jazzband/django-sortedm2m](https://github.com/jazzband/django-sortedm2m)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
