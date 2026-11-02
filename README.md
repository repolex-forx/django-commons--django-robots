# Repolex Knowledge Graph of django-commons/django-robots

RDF knowledge graph data for [django-commons/django-robots](https://github.com/django-commons/django-robots), parsed by [repolex](https://repolex.ai).

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
rlex download django-commons/django-robots
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3976432fbb3dc75672c714381e9dfcb96f996a50
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 3976432fbb3dc75672c714381e9dfcb96f996a50
│           └── chunk-001.nq.gz
├── blob
│   ├── 0213e916a7ee233a847fc0928a0a1048c08017c5.nq.gz
│   ├── 07f9d65a486f183428f488b003d8ef3cdf015bbd.nq.gz
│   ├── 100622e4d376d703dae17f1142ebadf715fa767e.nq.gz
│   ├── 113d09d6788096da0b42be0d9f17e00784a0892a.nq.gz
│   ├── 14c46d13acee7378eaeb2029e8c3b74f8a4045c2.nq.gz
│   ├── 1fedbc59aab89382066f54397c4d56e26bedc7ed.nq.gz
│   ├── 28b7ed253223337075c67618ce95cf327d239cb8.nq.gz
│   ├── 2ada98538a006826ecda2c68aaf102cb7d9442cf.nq.gz
│   ├── 2e1d5612241f9f08bcccfa6bf3f92624940bd8a6.nq.gz
│   ├── 3185908f6b0b3a21b71d04099b32da998c428325.nq.gz
│   ├── 331e1b19705976c679366347b71bc344fa65a687.nq.gz
│   ├── 35ed222c4b1f1974447fd88818c13a3e5538abfc.nq.gz
│   ├── 398a061f7cad06413d8984359b919e7dd51fe7ca.nq.gz
│   ├── 3c517cc9d485fdba61fd65710684be9a4fb61ceb.nq.gz
│   ├── 3d604e4b655570f0ea1b4a1438ddce2ac8bcf987.nq.gz
│   ├── 3e46a6d57f3c249cd2ef1cbd9d40cf71ae118b44.nq.gz
│   ├── 3fd72847f1a3e2003a90ca8415da993fd0c46bfe.nq.gz
│   ├── 450787729005bcad7a3242b45148928efdc6a825.nq.gz
│   ├── 45feed0b270f15a60b6a1760d1be3e424e15a78f.nq.gz
│   ├── 4abe8d50807d6ba6ccb7a87ee7841144ccbff8a7.nq.gz
│   ├── 4db587e61c036724be836fd747039eb46cc99e17.nq.gz
│   ├── 518e25ce7ab5ccb57432bd6421f8665406e388a1.nq.gz
│   ├── 5466d37226547379c7071af9ff8f339fab04402f.nq.gz
│   ├── 5a2003c80b87c6009352b65cbb56e9f3eb421ac6.nq.gz
│   ├── 5cd641a9e4a3ba9f0ab6b53626ae0bd9af99174f.nq.gz
│   ├── 62279a603bd6152dbf5d64f6d3f755e48bbaa09f.nq.gz
│   ├── 674d1c3b5cc1622674cce8df9652a798195a3be3.nq.gz
│   ├── 6978bd44d72f3e930b8a0098a5d8a08a8000e6d5.nq.gz
│   ├── 6b41e005f96766d5eea096cb9efd4314d7bfaf3f.nq.gz
│   ├── 6be46090ccd3cb61134e111f89b488820892c38b.nq.gz
│   ├── 6cf67f7df8e85453ec6289acb2a0c752d132e8cb.nq.gz
│   ├── 7038c3f7ce7d451df9e531e5a4217de6df44479d.nq.gz
│   ├── 807f705029f0e3fba6e6ef191a5a9dd52f458ef9.nq.gz
│   ├── 8b85688c4600a07f3caee84540679c6ee14fb0c3.nq.gz
│   ├── 8bf0c461d9c9f7d1b128463ba3c00e3ef307c2f4.nq.gz
│   ├── 91f04cb8e6c7253d5feb1b30d4114299ebe49c26.nq.gz
│   ├── 9b5950ff4f61392b480aedcfd66a8283683a4f44.nq.gz
│   ├── 9f7db0bf478d6dc4845bd2d3950e1a05d91e952b.nq.gz
│   ├── a47ad5d333c8f25952797164d5f518649ec3797f.nq.gz
│   ├── a6a80d91c0fcac085d4f71055a181deb6652378d.nq.gz
│   ├── a977c1e7d16fe6f8755e52d4476373eaaa8a813a.nq.gz
│   ├── b129d3566d5ed6f1051438a5bf9c44c1081de775.nq.gz
│   ├── b1d4f5c534aca35f61db9ed5c72119e40db4c69f.nq.gz
│   ├── b2d3309d7361ff6a6929fc92be38f42fff40f828.nq.gz
│   ├── bb5f045675788dedf65c7f17c812a690220038dc.nq.gz
│   ├── bcd58daa975f5398504b2d47a990010eed4a8cfd.nq.gz
│   ├── be7f4be679799953f87ba1c3ad03a8c547729830.nq.gz
│   ├── c69bca8551b42b3da78e79b3bfe76ada54650bfc.nq.gz
│   ├── c966f53ca3c227908031eb270253c040f1b98a88.nq.gz
│   ├── cb666fe68ff35e09ff24c60295172d91ae5a9333.nq.gz
│   ├── cf3f54be4183f57ea75c1c4771df7867e157b44e.nq.gz
│   ├── d22de6ca32637bf5aa5392149c8a4440528f5fda.nq.gz
│   ├── d859852949ee5f5aac95861cfef641688625fd0a.nq.gz
│   ├── d9a4405e7c50801c4263fef023ff03fda962453c.nq.gz
│   ├── db57c83795403c02c2d8a5d84e155f48406a5ebc.nq.gz
│   ├── de640bb0ea6bca49f5e2c080c52d60c82a96b46b.nq.gz
│   ├── e3c70bdfcb9db802c9c78cbdbe3754e4e3595c5a.nq.gz
│   ├── e66f52c3aec87b692c81b53551cbc448b775ee57.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7627eb878eb63be4562b8839acb617439680a97.nq.gz
│   ├── e9aceb067b96cd0c291e7f999de9c8308e97a449.nq.gz
│   ├── ec9b1f31676f56a0db107df474ff734bb2c097dd.nq.gz
│   ├── ef24492db1cdf4f0df3f2e3ae8eae6d89ea7d643.nq.gz
│   ├── f1b9b2331db2d068df2741bb092dc739dabf6a27.nq.gz
│   ├── f9b07772a5d18649c73394d3f803e246fade653e.nq.gz
│   └── fa260fa3f682906514b98da7d52981043bd5303c.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 3976432fbb3dc75672c714381e9dfcb96f996a50.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 74 files
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

[django-commons/django-robots](https://github.com/django-commons/django-robots)

---
*Parsed on 2026-11-02 by [repolex](https://repolex.ai)*
