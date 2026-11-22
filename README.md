# Repolex Knowledge Graph of zopefoundation/zope.lifecycleevent

RDF knowledge graph data for [zopefoundation/zope.lifecycleevent](https://github.com/zopefoundation/zope.lifecycleevent), parsed by [repolex](https://repolex.ai).

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
rlex download zopefoundation/zope.lifecycleevent
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 10dc7544c476f39e4c232f7fd124d8cdba91f11e
│   │   │   └── chunk-001.nq.gz
│   │   └── 92cd18ce99b7ac961adfc681b7817f459d553b3d
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 10dc7544c476f39e4c232f7fd124d8cdba91f11e.nq.gz
│   └── repolex
│       ├── 10dc7544c476f39e4c232f7fd124d8cdba91f11e
│       │   └── chunk-001.nq.gz
│       └── 92cd18ce99b7ac961adfc681b7817f459d553b3d
│           └── chunk-001.nq.gz
├── blob
│   ├── 034043e1628b277e8c3805e50acd2ac1e6e85255.nq.gz
│   ├── 0ab12fe1e0c8eb6cb0d68fce1b14a2209cdb0def.nq.gz
│   ├── 0f9c712385a18d50bf87a020deea51e1ba885b25.nq.gz
│   ├── 1a152663adb76dbe08560c820f06ba38dc40ed6c.nq.gz
│   ├── 1f321f52abb7db6f79c285bab56e2852dc575699.nq.gz
│   ├── 246e1ce40a7756c413dfbdccc756f3f6f95f7bf5.nq.gz
│   ├── 29ec3f193f83c61a6d05f2299e18175ac83d3d4f.nq.gz
│   ├── 2adb54864ab37ee7409f257de97eec200287d204.nq.gz
│   ├── 2d402fcced378cb3fae13ba626de3c81d9d50938.nq.gz
│   ├── 377bb802970da036e89e8c9ef531e0b6ce195162.nq.gz
│   ├── 3dba0106cd0dc105ae28d10fb9538c908950c194.nq.gz
│   ├── 567e1fa8f7a327cc7de9fa088892c52b98e95516.nq.gz
│   ├── 5b503773613d6b5bb47381f67512b8a05385d8e1.nq.gz
│   ├── 6735e4bd18a7aeba057339338006e6ab9081bbf1.nq.gz
│   ├── 717bb607f8a664ec726e9216cbe5c07025598268.nq.gz
│   ├── 75379d2f72cb37aee5c848563b9ae7b3ce8acdb7.nq.gz
│   ├── 79859e06010bf4967c5b4b044afea6ef39742938.nq.gz
│   ├── 79c074d908e191653f665468e5058276f12c2341.nq.gz
│   ├── 812351e67cb72eda106742b42f1b5c11459b6554.nq.gz
│   ├── 81607fba0256a5f5e60a07e37345b6418def4911.nq.gz
│   ├── 87bafefe3b9cc8305ced7e12e1e19b3f660a3ad9.nq.gz
│   ├── 8bf8775e23a19bf8a0c15f4747a64db520602ff4.nq.gz
│   ├── 9326e86a82379b0f461b6f862c1aba4b4d71685d.nq.gz
│   ├── 9f14a277c8ebced823fdf6c4374d439a03dc117b.nq.gz
│   ├── a78ef8e93e20951709df85d0f2b0a72ac7bf9fb7.nq.gz
│   ├── aec74c983733d1e4b0c9548f1a554df261398305.nq.gz
│   ├── b44c7f73084e2574f696e5fd4f9aa96746a0a883.nq.gz
│   ├── c5508b9f083362a81185d598327e7801d837cb18.nq.gz
│   ├── c5aba8e9a3e72023d24d1caa823aed09ad2b6226.nq.gz
│   ├── ca6833d95dd09d2d8a635bcaf8b88af8c36932e8.nq.gz
│   ├── ccdedc28073a0ba8303c52c91284a4e7e70bb471.nq.gz
│   ├── d8b8a363e44b3a900af2f025e86cfb90a4d0dd64.nq.gz
│   ├── d9e113ec685b92b018297dd2f200341d1fba01f9.nq.gz
│   ├── dac99ba7245eb3cbd60e9f15b7f80720212a387b.nq.gz
│   ├── de40ea7ca058e07a399acf61529d418c07eeee61.nq.gz
│   ├── e1f9ad7b3b48377bfbfaa1b380c384ddea24060f.nq.gz
│   ├── e235f162f07f7075ca7b9c21da8e1ef766cabbc4.nq.gz
│   ├── e2facc99f4010333da9ab18ad86009576922074f.nq.gz
│   ├── e63c60bc4dd5d871bd0292887bab50ecac6d0af9.nq.gz
│   ├── ec7a5ad483a7c78d19bb5b90b0c5d1658274ccb4.nq.gz
│   ├── f0ed9d001e553f388470f3a0b5eca7e9269311c7.nq.gz
│   ├── f2315be002695c9306ce1ec0ab3625e08899e55e.nq.gz
│   └── fc02f1dff26e08df28ccc084c5e9c8675241fb72.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 10dc7544c476f39e4c232f7fd124d8cdba91f11e.nq.gz
├── filetree
│   ├── 10dc7544c476f39e4c232f7fd124d8cdba91f11e.nq.gz
│   └── 92cd18ce99b7ac961adfc681b7817f459d553b3d.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

17 directories, 56 files
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

[zopefoundation/zope.lifecycleevent](https://github.com/zopefoundation/zope.lifecycleevent)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
