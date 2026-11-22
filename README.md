# Repolex Knowledge Graph of rust-lang/backtrace-rs

RDF knowledge graph data for [rust-lang/backtrace-rs](https://github.com/rust-lang/backtrace-rs), parsed by [repolex](https://repolex.ai).

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
rlex download rust-lang/backtrace-rs
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 775f6a1ba62e7d35a1fac76e64c61d9d4687b5f2
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 775f6a1ba62e7d35a1fac76e64c61d9d4687b5f2.nq.gz
│   └── repolex
│       └── 775f6a1ba62e7d35a1fac76e64c61d9d4687b5f2
│           └── chunk-001.nq.gz
├── blob
│   ├── 01270a71c90081638e184b0780050190cf4739f5.nq.gz
│   ├── 025eb250fdebaab684d00cbe566f838bd68567d5.nq.gz
│   ├── 031afea0a80a978ec20821c1855914a18f427fc4.nq.gz
│   ├── 0564f2ead3a98c3376a36e3faf5d803bc2fe004e.nq.gz
│   ├── 125fb76459ad6a407c38b9382959e22f80bfb650.nq.gz
│   ├── 15e3626d898455955f5b70c0914b5d116e951785.nq.gz
│   ├── 166224b99ff8f2c25c8df12fcc4c3ff4fa527042.nq.gz
│   ├── 16fe87b06e802f094b3fbb0894b137bca2b16ef1.nq.gz
│   ├── 18c61cbd51f650941924d1fab8fe0daf6bf07fc2.nq.gz
│   ├── 1d9a74ccd2dbff5075b87e141c61181208ffd82d.nq.gz
│   ├── 1eace1a238c56db2ec9dc58ac2b9663eb7c7bffd.nq.gz
│   ├── 2002ef17dd6526767e2a0f4595fa8fc9f4f4f6ff.nq.gz
│   ├── 201807797f008ec40b8e19ae590fc4b8cdcdd2ac.nq.gz
│   ├── 243eb2777dfebbb9f3484e0aeec59b21f6a2c097.nq.gz
│   ├── 24665972c276618a961658330532d683095ea2b2.nq.gz
│   ├── 24ebeb3c79bf86cb3c0dccf12c5fceba30e63cd4.nq.gz
│   ├── 2a36214bd71cb81e4fcf4d0d9a805a6b55be7879.nq.gz
│   ├── 2c36be4241979b66c0d93811cd1974261c3ec0b7.nq.gz
│   ├── 313236fd23692c40ace3d7bf98e59dcde1c71b36.nq.gz
│   ├── 316a233e34ee35612b5e59b95448440c2c1eb8ad.nq.gz
│   ├── 350c247dbbeef40b0558fb52b74327a6eee86ab5.nq.gz
│   ├── 37f10a651e13d7400287c0d94b67207a7f30b160.nq.gz
│   ├── 39e0ed6602151f235148e6c08413aa7eda5b9038.nq.gz
│   ├── 3c07934fd75eb4684534c8b29a0c9b412d9b91b5.nq.gz
│   ├── 4746ee0d18a8277987a512f6000dc904bd2d7c9a.nq.gz
│   ├── 48b5e9bacc0c3402c33137e92bcf5c49bf5d384b.nq.gz
│   ├── 4a03825b6c889e1abe75fa53a07b25a305c4d85a.nq.gz
│   ├── 4c89229362ec594e37652438056dd0a491a79345.nq.gz
│   ├── 4df9064c99f3349117bcd9802d252138cf35cbb1.nq.gz
│   ├── 551ab1378cf3d1ad93a71d2276b4dae5b7adb7e2.nq.gz
│   ├── 5803d5dcabdd547febd9ac954cc2090441b99639.nq.gz
│   ├── 5a0dfea15be57c0a8bc7ace327fc5120baea08ba.nq.gz
│   ├── 5b0dc3084b748a91563526f77605d646cf1abf4e.nq.gz
│   ├── 5ddc63d828d0a07cbb8de8110bd5e0b5c073fe87.nq.gz
│   ├── 5ec06e240352c12cd0469c866f2794ce70002956.nq.gz
│   ├── 61e09604c82b6234538b8814bb25881204553677.nq.gz
│   ├── 62714f04dc4ad7b5e2e7775789874c5c76390e6b.nq.gz
│   ├── 65e2cc340450ff02e1979e1078919bfc66f534aa.nq.gz
│   ├── 6d57ded35abfef3bd0d8a9f199909ab1ed9f6abe.nq.gz
│   ├── 6f7d0fd36f31d9ec003bea8fd53e8e21861032ed.nq.gz
│   ├── 7018b1017df320ff3c8d15854b0a18b46611fe63.nq.gz
│   ├── 71697fc30c9d738513c30b9134a0e6a74f732038.nq.gz
│   ├── 766e7ae2612085282b17c0d3363f5c1716ed1eac.nq.gz
│   ├── 7810b39eed8bbf18ae5eb685b17b0d26168edf5c.nq.gz
│   ├── 78f5276eabdbccbac7ada9f1f2d9d2c68ec3d07d.nq.gz
│   ├── 7c19dcbb48b8fcc8d499c7013f03e0090e1bef9e.nq.gz
│   ├── 7ca5a64bf05d986774a3a4bb659880f4cad4f5e1.nq.gz
│   ├── 7d2d12f246a19b60bbed29ae348a1f903f7dce73.nq.gz
│   ├── 7f2807804e81bc6d09da51437de0bdd600c9a7ef.nq.gz
│   ├── 7fde9a97f912b5163e9bb248af1c2bbcced9bfab.nq.gz
│   ├── 7ff6cd39eb8f51c42b59ee6f78d43ac309d31f91.nq.gz
│   ├── 81f635851bf7aac53d5dcd7ab613b5540729b615.nq.gz
│   ├── 860d3db59c269ed06202a11cebf4417a433ae5b0.nq.gz
│   ├── 871b353c06251c2a4d0954d725ddb3e859228629.nq.gz
│   ├── 888840eee478980cc6166da9b8cf3974c28018b9.nq.gz
│   ├── 897c498770d0103a51f0b7869b0d9c9f44f6342b.nq.gz
│   ├── 89e64ac2743ddb48158923aa331efbed080441ec.nq.gz
│   ├── 8e1883513296c444e5995aa19fb931e5f4247e49.nq.gz
│   ├── 906c68789afe4893a8a3766c40b748e591d8f6d8.nq.gz
│   ├── 95e17dbd5ec2de43ac9a92440112c0f14b0ab19c.nq.gz
│   ├── 98dbcfadb6087c562bcfa02caa6c00da2accba0c.nq.gz
│   ├── 9a2cc4f3deb58e22e5ed799416db56f608b366a8.nq.gz
│   ├── 9b70e41af03144cc2b1a21f0ddc24096330b9856.nq.gz
│   ├── 9c459306a83d3fdaff07a0908db235a0554d1b3e.nq.gz
│   ├── 9c8015d9ae2adc5fc8f9fde922eadfffcfa99a73.nq.gz
│   ├── 9cdd22b430e723a11edcb8869dcabb3b94a3e144.nq.gz
│   ├── 9d74db39ed4621a225257ebca0dea25dc2ccde20.nq.gz
│   ├── a303562f9ea57d85c6d45f9360de0c11d828b6c8.nq.gz
│   ├── a8e859e6783f273f36e84022b8383a816c4393c1.nq.gz
│   ├── acb19e98bcbc3729f470e33f575f5cd253c804f4.nq.gz
│   ├── b0f4063d73492f47e51c785dc6b461750b8c57e7.nq.gz
│   ├── b2da2013dee3a1c2c6d13d34ef9c13093502fcdd.nq.gz
│   ├── b50e4451f0db9e7fcf03903770f0d75b65ad7904.nq.gz
│   ├── b7cf5a5b5acff6d006a79251ce1aa9f52c399442.nq.gz
│   ├── c29a8b67a080551e3f9214be798fc97afe4da365.nq.gz
│   ├── c419247a6db63a25add7fe79af80bc73b8df2a5c.nq.gz
│   ├── c53336531bd0b671ee7f178dba44fb6395a0bafc.nq.gz
│   ├── c9d5d072abe7b33db6db059f8a1492cb01972578.nq.gz
│   ├── cab83d054b93eaecf959af5cd69421c5e6dda52d.nq.gz
│   ├── cebbad6d90db19159dc24f9adbc12504c72f661a.nq.gz
│   ├── d3c02723e1e9f2c1d584592bafba2b3fd83568a4.nq.gz
│   ├── d52819f6560cd4780c4e05b894598999ab87ba22.nq.gz
│   ├── d7ff410ce449a1f4c874fa4b6eab89e8a64c617c.nq.gz
│   ├── d99c574ac132cb70e7f94cfcd177c858a7ad184e.nq.gz
│   ├── dc70121dc82e05a142973d62c1de7c1e1aac77f4.nq.gz
│   ├── ddd5393c25952955b7bb2a67e8bcd4738397663e.nq.gz
│   ├── ddfd6b47535f01cd3c544ce56f44c6b800691510.nq.gz
│   ├── df31fefbb9984c9649d04e098096c733a4af5853.nq.gz
│   ├── e14e733b8d0361d94416545df7b4ab655b3b0276.nq.gz
│   ├── e32fbad4578f79592bbb716fe6618d72505145d2.nq.gz
│   ├── e62a1603efda10309cd09346a4d613f26043067b.nq.gz
│   ├── e6cc9c23b348d202d618318878e245ab30ac354a.nq.gz
│   ├── e77e41f5bccbe70b45e86f81a6ab73529352921c.nq.gz
│   ├── e7de8792b1a001ff9bbc3dfe5d89f080c30cb974.nq.gz
│   ├── ea77c785d55d954122becaa87aebd4ce86d02fa4.nq.gz
│   ├── eb5a316cbd195d26e3f768c7dd8e1b47299e17f8.nq.gz
│   ├── f65811b2b8df81a80244e6c6a50fb4054b774d3a.nq.gz
│   ├── f83232051cc3ceab766897b254b7efc206bda54a.nq.gz
│   ├── fcbe609866a0a157ff7c55d3c20c1bd9c1a585a9.nq.gz
│   └── fd5684f97cf51a331ca4ce1c102bb7915991cd6c.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 775f6a1ba62e7d35a1fac76e64c61d9d4687b5f2.nq.gz
├── filetree
│   └── 775f6a1ba62e7d35a1fac76e64c61d9d4687b5f2.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 110 files
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

[rust-lang/backtrace-rs](https://github.com/rust-lang/backtrace-rs)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
