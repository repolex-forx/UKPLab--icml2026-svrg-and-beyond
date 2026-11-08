# Repolex Knowledge Graph of UKPLab/icml2026-svrg-and-beyond

RDF knowledge graph data for [UKPLab/icml2026-svrg-and-beyond](https://github.com/UKPLab/icml2026-svrg-and-beyond), parsed by [repolex](https://repolex.ai).

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
rlex download UKPLab/icml2026-svrg-and-beyond
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ae0fc095c89540917b0df1f70b47602b24f7ea25
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── ae0fc095c89540917b0df1f70b47602b24f7ea25
│           └── chunk-001.nq.gz
├── blob
│   ├── 05c794f27f4cec179cb2aeda72f43624678c038a.nq.gz
│   ├── 0791591871b3cd422ec0a57d091526fffe16eeca.nq.gz
│   ├── 0d03bf268c448d14aeb9becbc045bcde4ae6c9b7.nq.gz
│   ├── 0d39a67c24f01c1af1e9cb675f380c3a1d1b2422.nq.gz
│   ├── 0d9360dc35d158ea1ccd025d9520994762579eec.nq.gz
│   ├── 10e260a99a1a4ea0e61d483eac9c505394998e72.nq.gz
│   ├── 120c6893b8af8f69dddc51b2734ed561b78c6091.nq.gz
│   ├── 122b5fed90c3243b45675ac0d0311cbb4a1224ec.nq.gz
│   ├── 14411fd93d699377c6e17280cabaf9a39d67dbdc.nq.gz
│   ├── 211809a4dfdea7ff8ad1e26378f47ec2860660a8.nq.gz
│   ├── 229edba242bb190698662cdce6bdacde9f0769fe.nq.gz
│   ├── 329db5e33310fd5d98343e2bca690bfb07317526.nq.gz
│   ├── 3c7bf3c37186f90ef4553ad2ec6e8cae9cd61c17.nq.gz
│   ├── 3dc429a6613bf85898a47643fe31d4439fe9d973.nq.gz
│   ├── 4003b3efdaaf1b47494a98c42e67ff429515345a.nq.gz
│   ├── 439037ffe4eb8238b0174e00778e2389694c3106.nq.gz
│   ├── 446cae0129ea79b2ce7c5c68f7d02c75120e78f8.nq.gz
│   ├── 45c94f6d8e39f3b7ace728febbb20e6294eff290.nq.gz
│   ├── 48fc9153abde80ccc6042c7e96c008196d9a7deb.nq.gz
│   ├── 4b41f286aa7e0357efb8c303fdf35071a4e4aeb0.nq.gz
│   ├── 4cef27e61ea9ac6f982e68a89dcb12432298bb71.nq.gz
│   ├── 51c6f2743f2405de7d45f2bf01f9d4240d8f6dd9.nq.gz
│   ├── 5dcef726f671e400c7a0873dc8e9d9f061889630.nq.gz
│   ├── 61b4c75d20a2872883e6c4e8c31d5f5a24841bd2.nq.gz
│   ├── 64e65ff7865e91c66505607f1657f923d99c905e.nq.gz
│   ├── 68eb69b23434984ce6053d307b6b6b7f709a7e7e.nq.gz
│   ├── 698e9f972a96948e15606d89ceda254e571d2692.nq.gz
│   ├── 6a171a558f6a2db926e56026b27c8a2cc3de9a48.nq.gz
│   ├── 7063e9ca28ad8fa0c61369c89756eb1f764e2567.nq.gz
│   ├── 7634e90bab6821b8082c28ba7e97f2456c1821fb.nq.gz
│   ├── 80f9dedb22582266a9daa4b5a74a2b7ef60f99a4.nq.gz
│   ├── 8871abfdc9c3745a372d1b55952f4d24481e3ea0.nq.gz
│   ├── 89f79d04b69ed907c42ae436aa16e9cfa7cfd9bf.nq.gz
│   ├── 8a32ee34b1603953ed79a91dec01453f67fb93c4.nq.gz
│   ├── 8b137891791fe96927ad78e64b0aad7bded08bdc.nq.gz
│   ├── 8b14d41f730e3642c5986d15e956bb8af5134367.nq.gz
│   ├── 8b529ec4e54efa50614740b0217eeb2a339bff03.nq.gz
│   ├── 8c35b34c3cbe3e4b7fe4dc6b72b4e1bbe3440396.nq.gz
│   ├── 921329f796062b68c1f9e6379d6316f0b2b30652.nq.gz
│   ├── 936837a38202b473d312eb583dac9ee0ea4295a4.nq.gz
│   ├── 93d646ef8c4be89121cd952ca7b03077569512a3.nq.gz
│   ├── 9b3703a912d40f58fb0fb57d20742e53d9fe7671.nq.gz
│   ├── 9be69bcbd25d82996d8cec58fcf044c0a13c9b9b.nq.gz
│   ├── 9ccc7363dcc9155dec920e64a9820737d3fff0e3.nq.gz
│   ├── 9ce4954153c4b54def9e0f7f85afacb6ca9ee2a1.nq.gz
│   ├── 9e5d829ffe3abde5a8cd2d9ff2d0a4165486d204.nq.gz
│   ├── 9fd1621d55b2e0fd268ca1a79cf3b056ed23d16b.nq.gz
│   ├── a1e9490ec8c629f16922836230bb3414b78d6b0e.nq.gz
│   ├── a70d291241eea483a3e2ca58d7c779b17cc164b8.nq.gz
│   ├── a8bba9599537cbb34b378399a077b525a87d497f.nq.gz
│   ├── af8902205522e13c82e362deac628a6a53218af7.nq.gz
│   ├── c08a79032592be8f5e7318991b0242323389469d.nq.gz
│   ├── c31a30411a2fa706195b02c9fbcc87d030792cd0.nq.gz
│   ├── c444b512c9092eed4b6454252392cdfe007ecafe.nq.gz
│   ├── c6718de5c5ae59d2c22141a147f5afba41af9cbb.nq.gz
│   ├── c7a351776c6d721e4c4b745d42d4091fc5346cc1.nq.gz
│   ├── c7f22993ba71f7dc1faf2b2fa36c0cf6feb28a7b.nq.gz
│   ├── cbbd302d6c483dfe24d7a1d19548dd050efa41de.nq.gz
│   ├── cc98b6933cd0df2705fd39225f24282258cd3685.nq.gz
│   ├── cdc528e0b8eee8ca1b16729577f5388db606d31f.nq.gz
│   ├── d55ac7896658139816f7ed1100610b16a102bbda.nq.gz
│   ├── d62fc66df4b9acdd5381753fde4173a5775b1ddf.nq.gz
│   ├── dd329f5bca97ed792c89586c5d671f37293183f7.nq.gz
│   ├── e08cd171a16edd1d23c3a7d2c8360fd14986d21a.nq.gz
│   ├── e57d58549b0615f70424f21c4a30a2bb1f674e08.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ed3a9d377ba3c30e6eb8b2a35e08e8dc814a0725.nq.gz
│   ├── f1519cbbe97bbd58ee60b92250c7e39d5814b7d6.nq.gz
│   ├── f2a99fc93ae331e65611fee0044dd0b697587a4e.nq.gz
│   ├── f47c06cc18baa434989aa2d46756a0b678957242.nq.gz
│   └── ff64129d1540036c5a2644b4614d4a3bb45cd93b.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── ae0fc095c89540917b0df1f70b47602b24f7ea25.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 78 files
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

[UKPLab/icml2026-svrg-and-beyond](https://github.com/UKPLab/icml2026-svrg-and-beyond)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
