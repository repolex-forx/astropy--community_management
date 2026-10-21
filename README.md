# Repolex Knowledge Graph of astropy/community_management

RDF knowledge graph data for [astropy/community_management](https://github.com/astropy/community_management), parsed by [repolex](https://repolex.ai).

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
rlex download astropy/community_management
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9d0a37edd919d651db034f4e68e7961c9b3ad224
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 9d0a37edd919d651db034f4e68e7961c9b3ad224
│           └── chunk-001.nq.gz
├── blob
│   ├── 11ba8b249f25905f5759be249ff7dc0139108dbc.nq.gz
│   ├── 12e89bdc261ea414ad341153c8c481a148a0cec0.nq.gz
│   ├── 15859c7d2467ddfa844d7e0567d59e98bd5b6cb1.nq.gz
│   ├── 1665870f06856c6600e889a9c1947d057eb7149f.nq.gz
│   ├── 16facfd472b4b9fe5225dd7ed8659264fbc0a941.nq.gz
│   ├── 1a218f5e5bc6f6fcf957402a14d721e762095351.nq.gz
│   ├── 1fc280ca379f85f0ebe33bbd1357ef8a779bc176.nq.gz
│   ├── 2ba947a6343a613e08fe74088a88d5ed4bbd8b8b.nq.gz
│   ├── 512d2326593d4878efbc48b61615aa31af0de4c9.nq.gz
│   ├── 52d83e7b06d714b2fa8af9fcc6f40742fc7cf097.nq.gz
│   ├── 534553ce2c4017b16ad53b0574c6570429f65d14.nq.gz
│   ├── 5c05198b7250678e8b348979d8c53463db392303.nq.gz
│   ├── 5c0c2b6dc4ac654e70210b64f5b69cc3e71b6b7f.nq.gz
│   ├── 5cc314a92d8ca4a909b9d52bc0e2a07b53f12eb2.nq.gz
│   ├── 5e2c8c92657bc5517fccd8d7ba2a2aaad3ec729f.nq.gz
│   ├── 6efa61fedc61b8a060b1e9b37470743ce5dc9eec.nq.gz
│   ├── 710184a2b2b11b3065ca12275998e77f7eaed6b3.nq.gz
│   ├── 74133095ac483880d6cfb8312306440e5a18c5bf.nq.gz
│   ├── 76a628df510b84017c428542c2609de64dea49c3.nq.gz
│   ├── 7754d694b439a1378bf25caaa340ef5f25f12409.nq.gz
│   ├── 7ae78586c3ccfafbb278c110b3834b8bf05ab76f.nq.gz
│   ├── 7b34c1692b69708a998a65bf3661916616c6df39.nq.gz
│   ├── 817dc2c2b6d43e0566fa6720aa87c89c7d4db94c.nq.gz
│   ├── 81bb5e06121adfb2226f1a990051c904e3f93e23.nq.gz
│   ├── 86cb09f048483b99272e28792d7bb8fd992645ad.nq.gz
│   ├── 87f995cec43151d279a41efc1820dc6e9c936ec6.nq.gz
│   ├── 891e096a2b2f20e4e27135c37f56a1084ff83ebd.nq.gz
│   ├── 8e9f7c48cb5fac7bbdc97c16dcd8e24820eb3a01.nq.gz
│   ├── 915f1e96587505d4138c7ecd6999042ad4f3fb0f.nq.gz
│   ├── 92d2719e8e568c8290e82347d627a5be1ddd017a.nq.gz
│   ├── 9b2b044c26bd569f5e6f1f3a25b162f19700f345.nq.gz
│   ├── 9c16245c794c98027a5e3cff56847bb9b7a84826.nq.gz
│   ├── ab2a2f63d639d9442b5bef4dbcd273dffdfce338.nq.gz
│   ├── b440d1d8d8cf641f1eb0aab6419e5a00d58446b1.nq.gz
│   ├── b6783225a00aef216526ea57569f22952dc8988f.nq.gz
│   ├── b79fa38b992cf9157a4113d94464208ec3433977.nq.gz
│   ├── b8a017a6d31545fe148ca94f1cf21026c780db09.nq.gz
│   ├── bfe27dac58a980739144f2c2bd69c586626592e5.nq.gz
│   ├── c68e2067eb408bbb021a6108e63dba95a6b86bb6.nq.gz
│   ├── ca7650f8e0c355492069c7b0145483390d871292.nq.gz
│   ├── cdeb8d140206a05995b6e5b0757564c1d47fc727.nq.gz
│   ├── d374a5153c50565d56aa09627442440b90380a3b.nq.gz
│   ├── d8538066cf84976a950240c7cf0aab39cf527a5e.nq.gz
│   ├── dd0031cb32652c244a6eef5bc2c1ee34bd935710.nq.gz
│   ├── def55dbfd1deb13d356a7b36467aa2cd5d2639e1.nq.gz
│   ├── e22db27bf9f6d12f35eb879be4e47bc1cba98b5a.nq.gz
│   ├── f20d5f81350cc29ce4cde51cd9a68fbee870bc53.nq.gz
│   └── f8665004187b2fe804269ee9b79768183ce3230f.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 9d0a37edd919d651db034f4e68e7961c9b3ad224.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 56 files
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

[astropy/community_management](https://github.com/astropy/community_management)

---
*Parsed on 2026-10-21 by [repolex](https://repolex.ai)*
