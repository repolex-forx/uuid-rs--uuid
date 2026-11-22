# Repolex Knowledge Graph of uuid-rs/uuid

RDF knowledge graph data for [uuid-rs/uuid](https://github.com/uuid-rs/uuid), parsed by [repolex](https://repolex.ai).

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
rlex download uuid-rs/uuid
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 00ab922d5351607dfff520f37eb49cb9854fda73
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 00ab922d5351607dfff520f37eb49cb9854fda73.nq.gz
│   └── repolex
│       └── 00ab922d5351607dfff520f37eb49cb9854fda73
│           └── chunk-001.nq.gz
├── blob
│   ├── 03314f77b5aa454994bf08c40943f4012964eb0a.nq.gz
│   ├── 0c2fa5b9be749a1c8d7a2f8871d3d9072eda6ac1.nq.gz
│   ├── 14ca302f280822d0d825e45e575198532543a35c.nq.gz
│   ├── 15fec7bb3f81b22aac3bbd39bd9382e68b143f88.nq.gz
│   ├── 16d14cc33d2b32715479b5e7be3691c51a5b0f31.nq.gz
│   ├── 16fe87b06e802f094b3fbb0894b137bca2b16ef1.nq.gz
│   ├── 1eefd741f23423aee0d389c6bb54fe36e36cc24a.nq.gz
│   ├── 1f536dc0430cc371b15c0d9a3c29d9dea945e586.nq.gz
│   ├── 321172efeff051af09f0c75c1224dc19ab00e931.nq.gz
│   ├── 34936372955a0065121e3b310a5325905634a6cc.nq.gz
│   ├── 43ff03c15ff8b273e83eecc0c792fd8c9e6d25db.nq.gz
│   ├── 52f9035e3d996d1b55c204a3821cf4a4fafd237a.nq.gz
│   ├── 655773a54651c2e58787212c8b4dbbea413be259.nq.gz
│   ├── 655e1806c48eee256507503bbfb1071d4db704fc.nq.gz
│   ├── 6636d848d918ff0e4ee0956800b2d4d865df4ffb.nq.gz
│   ├── 680c401a18c96e1185acd003c4da640199c198ba.nq.gz
│   ├── 6cbc10ed682626102edd450ed18df2a6ee4e4de9.nq.gz
│   ├── 6f20d8fd92d61cb2170670bbda3dd82bd7220e81.nq.gz
│   ├── 7280964ca56bffd6a8568aeb80749eb5c7fc4487.nq.gz
│   ├── 7b0b22e1636e349e8fe55b0a2190ea023355e0e7.nq.gz
│   ├── 7b22335b4c888b7379b5bf065758acbec23bc040.nq.gz
│   ├── 807a9c644daafb097ece2eddaa95a854cc1a41bd.nq.gz
│   ├── 80ce43e7faf33630d47253dcc045a8ec7316400e.nq.gz
│   ├── 81b008f7ee5cc2fc7281a76839e803acdebf7c90.nq.gz
│   ├── 83db260c1b6c2b456144c05fba85800ae0ba416d.nq.gz
│   ├── 88c183246ba77f4b0546595c3a150ea7029b4109.nq.gz
│   ├── 8bbc686d19dc53e26275dd4aa64d619a4e05737e.nq.gz
│   ├── 8e2580bd1eb9d44052d6b07ce6058e4b196da1d9.nq.gz
│   ├── 8e7c3afd3133186b9ee0527a412f250f8d4e8ed7.nq.gz
│   ├── 925929c167c921ef7881d6ce8801ad72a9c30ba0.nq.gz
│   ├── 977ebb7f32add187239b33f7b54fc2dda5b5f86f.nq.gz
│   ├── 97e1c2c75a6bdc1c0ba98cf690be34096d9ebff8.nq.gz
│   ├── 987d5d096ef42114ec98e0259f45857d4883e3af.nq.gz
│   ├── 99a3078e627e2b84bdcced87abd0bfc4911f7803.nq.gz
│   ├── 99e134a2aaf0933ce38d48b726267ecd1e064800.nq.gz
│   ├── a0925114d619b8cee7d72961b052ddcc42023a24.nq.gz
│   ├── a746f22faff07f2fcbd835e792347aef14e38fdd.nq.gz
│   ├── b3b596b0ad782bad78df1278ec1412c7bf07ec6f.nq.gz
│   ├── bdd9dbef4115e0752534933b338883e685f6246a.nq.gz
│   ├── c2961f3f45eff3c0d8ff77206501fa874bc91648.nq.gz
│   ├── c85d68f5cfb7ef70c0350c819af7dbf9f17e8dcd.nq.gz
│   ├── cbeae8652c12a7ba363d1b46fd8abfdd4d21e366.nq.gz
│   ├── cedcf89c8e452b53d6d154a46480f34770844cc3.nq.gz
│   ├── cf399afa1ac1c0e8af9ca919cbb4408d7d19048d.nq.gz
│   ├── cfd8ae30917a690d31b753dc296a2d3f5f4a3a4f.nq.gz
│   ├── d022f25a6028243d1d7c0437b08a1aa86a67a3c0.nq.gz
│   ├── d36d38064c23625e01f273a173849bec08b51bc4.nq.gz
│   ├── d84e47cfe5087f5f4100dddf0bf0a8c40304237a.nq.gz
│   ├── e135d7f60542e9550da3df879930c69b9d86afd6.nq.gz
│   ├── e53ba242d36a3a2ae4d0f4f39509d39be7e78fb3.nq.gz
│   ├── e61b9d515da9b8e713d57f3be5ad878f7467f28d.nq.gz
│   ├── e987f3e5aa38dc2139ebaa11568004ca6974a40c.nq.gz
│   ├── eb4fd10bfbc5e459c3818e1a349cb1049653c5d3.nq.gz
│   ├── efc17cfcb84abf0e772927c75e7df6de995551be.nq.gz
│   ├── f328e4d9d04c31d0d70d16d21a07d1613be9d577.nq.gz
│   ├── f6650498645ae4b25afec3b6905ba7ab8efac1a8.nq.gz
│   ├── f67456b935eed4ceb4bce5e59b62a1556ff818c0.nq.gz
│   ├── f74f5d617f0dfd753cd5152a8de2f7ddae820ba9.nq.gz
│   ├── fab89297bfb6e3a51da044bbcd0b0cbf79f58ec7.nq.gz
│   ├── ffa9b2a7076d2a59be3de03d5cf5d77e4dad527e.nq.gz
│   └── ffd7ca6fde498b7913b10e15cacb315504339114.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 00ab922d5351607dfff520f37eb49cb9854fda73.nq.gz
├── filetree
│   └── 00ab922d5351607dfff520f37eb49cb9854fda73.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 71 files
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

[uuid-rs/uuid](https://github.com/uuid-rs/uuid)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
