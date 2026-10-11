# Repolex Knowledge Graph of pydantic/pydantic.run

RDF knowledge graph data for [pydantic/pydantic.run](https://github.com/pydantic/pydantic.run), parsed by [repolex](https://repolex.ai).

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
rlex download pydantic/pydantic.run
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3fa1680b1d34e0b24fcff697e6f65cc3978bb9ce
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 3fa1680b1d34e0b24fcff697e6f65cc3978bb9ce
│           └── chunk-001.nq.gz
├── blob
│   ├── 04280c8c919b65b5279992999a43749fce7bbe89.nq.gz
│   ├── 0562784136ad5f8b00520c7f75e7525a8c4edfed.nq.gz
│   ├── 0fb3bd9bdeb2f9c269ca4bb8769d2ed0dde3b274.nq.gz
│   ├── 11f02fe2a0061d6e6e1f271b21da95423b448b32.nq.gz
│   ├── 17856d0bdf0555f509af35f326176773896339ca.nq.gz
│   ├── 1c3b6696f6ebfa6cf622b060f6718bf002f49d17.nq.gz
│   ├── 206d1700ff3f10c025b5108137a014046b3484e7.nq.gz
│   ├── 27649c54efe07ebcedca52817e606e0a832476c8.nq.gz
│   ├── 33fcc57febbdf10a9001a10da82d41a71bd34a07.nq.gz
│   ├── 35330d50b7afbf524c27a140bb33641b0867be61.nq.gz
│   ├── 38ea04d82862d20ec2a239d9e537eaeff6dae9a9.nq.gz
│   ├── 3f7ddb018ff665cccff5b4555017e7f4b2d435d6.nq.gz
│   ├── 40da37612d237c0585c5e5ebec9813a736904521.nq.gz
│   ├── 4941d4db61dde518f319319d7c3484133a596327.nq.gz
│   ├── 4e7eb57e1a1df56de359c03bafce87bd6b829391.nq.gz
│   ├── 566450fbc7c898965a12c2cd5ad13b8a04e82916.nq.gz
│   ├── 5d4016c665a6fec2f03ef7da350129e49d4b2d4a.nq.gz
│   ├── 6233832ea9b43afde6284b57b39ddc1e0f6cd308.nq.gz
│   ├── 71554bbda8b647928d31b1f83a67e67dd727cbbd.nq.gz
│   ├── 742a8bb3ac5e305d5e07fdba21681d18a44aa12b.nq.gz
│   ├── 75d9766db981cf4e8c59be50ff01e574581d43fc.nq.gz
│   ├── 76ad5fc1972f80a8fedf0d5097eb68381b3715a3.nq.gz
│   ├── 792a2a928c14771a7d11c1774069f81d45ac25d8.nq.gz
│   ├── 9313c075569ef9d71d498d2a68928474a347152b.nq.gz
│   ├── 935f564ee94f5c21ed7d96d1948801997ba2ef4a.nq.gz
│   ├── 9db8393761d37e443156a039fb6f5b54d1077d1f.nq.gz
│   ├── 9e27ffd7d62e6de625a72a62e5673e806ca12804.nq.gz
│   ├── a2ac955a2525bdec9747d9be41ec0a4f23145c92.nq.gz
│   ├── b52e26ef8583bd19d27940b0f75203ba10042448.nq.gz
│   ├── b80bdd27d704a6168a3dc4c1b966cfd976314d7c.nq.gz
│   ├── ba9c6746cfcc2493f6fa618d5364337ad83b2812.nq.gz
│   ├── c69e5e592050e863302f9227bf93ecd6120213f5.nq.gz
│   ├── ceccc24590ecf928e2cc422866e4425a707a5a6e.nq.gz
│   ├── d5dfd1310e6687d80ab71f086e4efb6204e010f0.nq.gz
│   ├── d999e6a467a658a9e872ec4850a32baa27ddbc31.nq.gz
│   ├── d9cc38e8dc5360e3a74a46e603893ccb8f51c369.nq.gz
│   ├── da78b870cc662baeaca059058f6d526139236075.nq.gz
│   ├── dd2f5882bbe734ef8bac9b565a436b13e877c714.nq.gz
│   ├── e23506e26e846758d7fdb66f75c3986d76608afd.nq.gz
│   ├── e2b5662f5a92ec2269b52f226208a0b499a58584.nq.gz
│   ├── e8720d15f9e427ad4dd3941ee4a99a210e83463f.nq.gz
│   ├── e9a43220379cd23c032a9a5895667be495f0b7e2.nq.gz
│   ├── e9aa3ff17d562bba4f9e77bb2d507e1e79b17e34.nq.gz
│   ├── e9acbb876365132455be3e46ed7e14a3c6a8b7d3.nq.gz
│   ├── eb0536286f3081c6c0646817037faf5446e3547d.nq.gz
│   └── fb48eb5b4f7ec34eaf1acb55630da34a52912a3c.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 3fa1680b1d34e0b24fcff697e6f65cc3978bb9ce.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 54 files
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

[pydantic/pydantic.run](https://github.com/pydantic/pydantic.run)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
