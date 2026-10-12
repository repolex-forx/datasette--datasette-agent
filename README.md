# Repolex Knowledge Graph of datasette/datasette-agent

RDF knowledge graph data for [datasette/datasette-agent](https://github.com/datasette/datasette-agent), parsed by [repolex](https://repolex.ai).

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
rlex download datasette/datasette-agent
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c811e82352157611862bfcbfbf38c4f0e22d3804
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c811e82352157611862bfcbfbf38c4f0e22d3804
│           └── chunk-001.nq.gz
├── blob
│   ├── 03191992b76f5f242fc71401a9596055d37e9d7a.nq.gz
│   ├── 0f710d16a0ab1e2f60df431205e25ebd003999a6.nq.gz
│   ├── 1b5da789b4e67869d45e27bc08536fb084eeb318.nq.gz
│   ├── 1d3ee1c364110f2b7dd3ba4519975064c1fcb0d4.nq.gz
│   ├── 1d7c18469d042a1c2e5d163f3704d6d8b8c25014.nq.gz
│   ├── 1e1c0439423e8a6172bc8b0e689d3120af00a215.nq.gz
│   ├── 1f99a9f829db5b4f79453f89695fe5db0e0d4ecc.nq.gz
│   ├── 229ba778d705a2ee0e07236b6698d0d440494c95.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 29ad38731a34d93ae15a1d2e2df5b913b9381703.nq.gz
│   ├── 2df71ddbcb26fadcae4facc3a2aa586138e23b06.nq.gz
│   ├── 36ba38584128c5add79f1bfcef64f408a9901a14.nq.gz
│   ├── 3fe7e7ec40ef2555920c88cddfb45f9d4815cfe8.nq.gz
│   ├── 412e2301734676845da61e51d1cce4bcbbaf7eaa.nq.gz
│   ├── 44d9bea2f75a721c9a5a66d1d4c71da531621b32.nq.gz
│   ├── 47bea61b07d8d2b9a900432d4947a1a59599c256.nq.gz
│   ├── 48ff363dd40e2a208b38b000cec92d9b4609d3e7.nq.gz
│   ├── 58e119d71d0b6873f4e842220ca9b3fbdc45600a.nq.gz
│   ├── 5e25b8385301a5ada80ac2e00f4261477324a62c.nq.gz
│   ├── 6899435056c32799ca93e04a2fdb2f9d2bfe05e7.nq.gz
│   ├── 7309d969efbd5eecda58554e617a485f1c15c010.nq.gz
│   ├── 7b05d5efde1df29ed12972c58e64dd09926d3c6f.nq.gz
│   ├── 83a1a86a847ecd1a83c2bc292e8848038191599a.nq.gz
│   ├── 906f21f1514f996faabcfb85191461bf84b848a4.nq.gz
│   ├── 93980b6d4ca9a8c9a70bc5f1d8af97ba242a3384.nq.gz
│   ├── 9621373c9d35120c78e20cdb1a0f731b5c4e5129.nq.gz
│   ├── 99fa00420193b3fe28204b0cc36e2de648a75f21.nq.gz
│   ├── 9b1b0f68e8bbc503f6ce23d2874409c84dccc81c.nq.gz
│   ├── 9b96f2a25a63f3f74f610068c1ba5bc65f92d1b5.nq.gz
│   ├── affd368a0acee7b184a12f844b70c60705ab0a2f.nq.gz
│   ├── b2a842768aa1b1cf0563e9cd74230eafac971f78.nq.gz
│   ├── b6f40dfa091cbaa09fec5949389fc38fb7e71b20.nq.gz
│   ├── b8a2a436b293016758b373603c0d35e3fb9ebbf4.nq.gz
│   ├── bff0250c02b52a143f3c354a45f0c1b5c312c72b.nq.gz
│   ├── c2f9bceb5c79c9fd985942431ff2e6ff47f3fdc0.nq.gz
│   ├── d0b9a9b4488936340e4d606002def832c69e738c.nq.gz
│   ├── d2715b740d0a2f5cccfc1f6f8771618b75e485df.nq.gz
│   ├── d6c0c50faafa4249214f24038b0f49b2a0e77c28.nq.gz
│   ├── dff886fd0f811a60e57c0e06b4cdc4b185e9cca0.nq.gz
│   ├── e7ca2a7f92556c53e66c8868adde495f07483819.nq.gz
│   ├── e7f4961a3ea491fb6910c3c335598f14a755dc9c.nq.gz
│   ├── e8124d592eaeafb4977fa95774afbf976353f184.nq.gz
│   ├── eed0f6c65d0c9c552a06e2704cf5031b47794af5.nq.gz
│   ├── f30c9ae3e6d3ad53c1046dd99da8d6c0faf9c898.nq.gz
│   └── f69f6b4d0bb613fe31b896c9dc90ee38082ae22e.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── c811e82352157611862bfcbfbf38c4f0e22d3804.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 53 files
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

[datasette/datasette-agent](https://github.com/datasette/datasette-agent)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
