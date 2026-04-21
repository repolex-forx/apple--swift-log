# Repolex Knowledge Graph of apple/swift-log

RDF knowledge graph data for [apple/swift-log](https://github.com/apple/swift-log), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download apple/swift-log
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8c0f217f01000dd30f60d6e536569ad4e74291f9
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 8c0f217f01000dd30f60d6e536569ad4e74291f9.nq.gz
│   └── repolex
│       └── 8c0f217f01000dd30f60d6e536569ad4e74291f9
│           └── chunk-001.nq.gz
├── blob
│   ├── 0002f4b4ec11e9b324189f1cbec5cbb2841416d8.nq.gz
│   ├── 0023a5340637983755c8c19c18cc2c2bb1dbda1c.nq.gz
│   ├── 0776b8a0249ee99ac98e548953e3d18b44ca64de.nq.gz
│   ├── 08891d83f67181f147fc91135bf6c0016a2bea7e.nq.gz
│   ├── 09a79911cc8d3f1b320e461adc5fac154f80ccb2.nq.gz
│   ├── 0b3a8bc73e990c776805607289d9e79f6ffec2b7.nq.gz
│   ├── 0c52e880a586ea3b459094dee2ac8a694fb5eccf.nq.gz
│   ├── 0e22b2a06379e3547096926062512570666ae5cc.nq.gz
│   ├── 1d2a039acb95c871aac85de60fb7ce2f97ab1772.nq.gz
│   ├── 1ea82d11207e23f8a70385eff8d193f2003b69ef.nq.gz
│   ├── 227e0bb5ecbdbaa01ed13676bc626224410bd10d.nq.gz
│   ├── 2626ca0ab34eb7d7a114eb121d315b6340e68c40.nq.gz
│   ├── 2719bfce08f78c365954f5e006a8a3f01bb7bae0.nq.gz
│   ├── 272634fc49576e8ce8b33d1256afda011fa8e8e9.nq.gz
│   ├── 27b2a778f58926a2aea500c00d9be1c9cef9c683.nq.gz
│   ├── 2a37a1549e590bedd7f99624215492c94a5d89aa.nq.gz
│   ├── 2d277496fc90109be3390f7049d0caa53d2aa7d1.nq.gz
│   ├── 39fcf28dab8b3748ffd751fad61dafe4d2fe7f87.nq.gz
│   ├── 3c4cc7017ab2f932c7f2a873febe2ff961b37fa0.nq.gz
│   ├── 3e94947f7105729acfa6ad9c80eb26b16a03463f.nq.gz
│   ├── 42342dc8e5c6694e5934e7441aa4d67200ed7e1b.nq.gz
│   ├── 43e848d336be18dd1bf4e026bfd69f6b6df5fdaa.nq.gz
│   ├── 54965d760176141c94d55ff842dd9c9708e06e9f.nq.gz
│   ├── 592c3c64c52033ccf9144680768131ec52742c54.nq.gz
│   ├── 5ace4600a1f26e6892982f3e2f069ebfab108d87.nq.gz
│   ├── 5c9bacc62717fe93af176bae7b6c43a292441520.nq.gz
│   ├── 5d0ddbf536c1dd08328505736e8d94065cde7981.nq.gz
│   ├── 6b0f69bd09af75a948b094a3f09a2f084f9a6aab.nq.gz
│   ├── 74d12ca510ed0c8bf801bd0404edfd8435d6a65a.nq.gz
│   ├── 7bca0bd5e7def85a6af6d9f4070795897135f569.nq.gz
│   ├── 7f410ea27d9be194ff15a4bba3e53770e42673fc.nq.gz
│   ├── 7fa06fb305f0cce527bebbd49722fed34c6cb71d.nq.gz
│   ├── 80d661eb678530706a05ee4233d2f27a66ea59a5.nq.gz
│   ├── 869326d1812442600aa23034504cc88dda01f967.nq.gz
│   ├── 8aa15bd54ed9c291f6453ae2d632beffa2550632.nq.gz
│   ├── 8af03a46bd81140c8fbd3e0ee50d809eb39c773e.nq.gz
│   ├── 923a6cc98c2e0d45b09431397a304056fd4f885c.nq.gz
│   ├── 9b8e30f4fedaeb94ca07324359e9da015f2b00d2.nq.gz
│   ├── 9c4d6e8ac936364e346aef877fe857e7ac7eb41b.nq.gz
│   ├── 9ca153c6ebe49696c5f997c2e8384f0f173ab5a0.nq.gz
│   ├── 9f294bcc2ac3942823b12fc81ec435355ae4b20d.nq.gz
│   ├── a2e3cb5be9193e9bd9af1bb194e38ab3a5fab0fa.nq.gz
│   ├── a3274c228a635e29cfc94a9631a27f0ec2f6d05e.nq.gz
│   ├── a6b4fa210c676209ef1711e8cc354ffae553d3b9.nq.gz
│   ├── a7853859d01561c146e4180c4a0eed6d661cc96e.nq.gz
│   ├── a8c57416f78d056563554147af6eea9344848bd1.nq.gz
│   ├── ab90c7b9a1b5dce88c606d98a41c90f1eb85805a.nq.gz
│   ├── ad878a5fa0efcf095f27cd7c3f09139e98815864.nq.gz
│   ├── aef8c76334adf6c4e5b037d4897e02f0cbee9f27.nq.gz
│   ├── af70e8d531c487202f71c66522c8a7be9341eeb0.nq.gz
│   ├── b22d44eff4ee35c6f99b079f3b5ac81bb6db8692.nq.gz
│   ├── b7d94ce3c71ba8506eb6776ca77e0f5e4b0dc532.nq.gz
│   ├── bad91723cd7f7c9ae87705576cad0a1658a117d3.nq.gz
│   ├── bd747fce135bf67280519eba5cb27d966e7010fa.nq.gz
│   ├── be5252947b7549123c44f9804ba9b84b135b1ad8.nq.gz
│   ├── becf6185fae6025c47bd74cfb75d70f440f766fd.nq.gz
│   ├── c2f7e546a1e7104efa944b286e33c166ae892066.nq.gz
│   ├── c3ab6ffaa99f7ebf2a93bb7214e0a9a5f463da3d.nq.gz
│   ├── c4aeb9a345900c9ad628fe2013dec01238dbb821.nq.gz
│   ├── c52bfa1ad8878898dd946f0000dc2da7bd246ad4.nq.gz
│   ├── c8b91945a23e6c9939a4d81c2f54e7ad3aabbe56.nq.gz
│   ├── ca285d233e35cb292cce55fe6b6cfc3d41403f70.nq.gz
│   ├── ccd60897ceb246a7e7de2989f9b21db89c2d9b4f.nq.gz
│   ├── cecefff2f88de0544a2c643181241e3f06e7187a.nq.gz
│   ├── d191bf938c69554cb81d355a655961d564bbc7e2.nq.gz
│   ├── d2510b5948c8162696779ed6e391935a7676a2b1.nq.gz
│   ├── d336015cabb17d75c0d998a95a4f5c7a0587f4e4.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── d78b8754489601b958d3c24c65c1357c66e11b9b.nq.gz
│   ├── dc5cdca6193f1980345743d5a5a97a6308c392a0.nq.gz
│   ├── e29eb84641301518c171ed2374bf1c36f8140e5d.nq.gz
│   ├── e6b97ed4b2596a67b5f5d7c45ada033eaba870e9.nq.gz
│   ├── ed8754bdd6c763b121a646dc3cdfe0d3b161765b.nq.gz
│   ├── f1727856c37592f7efdc6245e701534113052a03.nq.gz
│   ├── f41a1fef1e4cfc4de6a4386bb5223bc1000db987.nq.gz
│   ├── f7c4808845624fffd17374fd9717615f2aa0d6b6.nq.gz
│   ├── f90455fb9ccd8f4228200ce6dcb9886b8676cafe.nq.gz
│   ├── fa4f73571e236e61b22293cb3f6ed758fd10600d.nq.gz
│   ├── fce4d75d0e31b690fb557aa224edb305d6aed193.nq.gz
│   ├── fd600cc7b40c2b3f6042d015c5d4a90b7b59593d.nq.gz
│   └── ff1b6cafe69044c9a866bc146e54efae993a3752.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 8c0f217f01000dd30f60d6e536569ad4e74291f9.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

14 directories, 90 files
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

## Source repository

[apple/swift-log](https://github.com/apple/swift-log)

---
*Parsed on 2026-04-21 by [repolex](https://repolex.ai)*
