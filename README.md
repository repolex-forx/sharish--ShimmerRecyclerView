# Repolex Knowledge Graph of sharish/ShimmerRecyclerView

RDF knowledge graph data for [sharish/ShimmerRecyclerView](https://github.com/sharish/ShimmerRecyclerView), parsed by [repolex](https://repolex.ai).

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
rlex download sharish/ShimmerRecyclerView
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 24cf1a07538bd55fa51a16c101d8bc568dd46850
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 24cf1a07538bd55fa51a16c101d8bc568dd46850
│           └── chunk-001.nq.gz
├── blob
│   ├── 03b18413cc4a86342a6c01c24bfc7f956f58aa8c.nq.gz
│   ├── 0a93f7091d6db430d32c32c99e40cb1d0e445ea1.nq.gz
│   ├── 0b9375e05ffa4ddfd7fd2718456f0360c1ea8ac2.nq.gz
│   ├── 0dc08dae6b394b253918c0e89e3397458857a864.nq.gz
│   ├── 1043359c01011bd6b64e668b27b0a6c462c17365.nq.gz
│   ├── 13372aef5e24af05341d49695ee84e5f9b594659.nq.gz
│   ├── 1bcd3cd1bbb5147ad1d7d971ce5d799c2685f39f.nq.gz
│   ├── 1d66e37ff4373e5ca92ca09e2911ce8c4c41f123.nq.gz
│   ├── 2376884f1c425174ae81605af893de2e7096efba.nq.gz
│   ├── 23c5316077d6cf85497fb7e1cd6bb8c640824ac5.nq.gz
│   ├── 25bf2aef6f76c69e814d0a877b6a429a832a5561.nq.gz
│   ├── 272fb92cf7d9719417a7a47824c39c37b96d9daa.nq.gz
│   ├── 314d10164f33741459e7cf4d62040b98f446d5ec.nq.gz
│   ├── 324e72cdd7480cb983fa1bcc7ce686e51ef87fe7.nq.gz
│   ├── 336c2876a7807697129ee758d2ab9e8e59eee7f2.nq.gz
│   ├── 33e32fc7eb86309d8db33252029811d5cfd303e8.nq.gz
│   ├── 36e9855aff9adfac8ac2d8d6185d9253c6d83d66.nq.gz
│   ├── 3a02f545a25dac108f2de6477a21bdbcc00220eb.nq.gz
│   ├── 3e70be4c72b69f36bc618e0fbeea361f7cfac07c.nq.gz
│   ├── 530c1cbd3d0caf4161f135a3828b292a5a57b5a8.nq.gz
│   ├── 5bca0c3b1db2ab71ea06125075aa0b831e2783f8.nq.gz
│   ├── 5df75685ca99a58188298100e57710d6a60f0f39.nq.gz
│   ├── 6038babb1aed3a17df67f8c4b3bfa09fb53e17bf.nq.gz
│   ├── 6172bdaf8f968b5cf8e43730af47e2c643ad4577.nq.gz
│   ├── 652db9ce08439f0c78a50d14cc265a4984c2e878.nq.gz
│   ├── 6d157b8978fb8da18ea196f615bb732cfb9c14aa.nq.gz
│   ├── 702333dee592475cc74b68d54b64503070e52c65.nq.gz
│   ├── 791d8f7addc974ae0760bacf933fed6b976e2ea1.nq.gz
│   ├── 796b96d1c402326528b4ba3c12ee9d92d0e212e9.nq.gz
│   ├── 7c41ed5772b5f43e9f3d603972a9797c50d6e51a.nq.gz
│   ├── 7ec0147524e9a28ca3731a3aa9ea9549995fc65e.nq.gz
│   ├── 81968827d9d2c589738908b52f3b3db3a5cd156a.nq.gz
│   ├── 831b0135c327d431b375c952d98a1a254aa85e42.nq.gz
│   ├── 84660cea1d3a270f2e31e16085421ece536e6927.nq.gz
│   ├── 8af986ed7073b055371ae0c4b42d2bf524f2266e.nq.gz
│   ├── 8eb5ce89b187a09add0b7b445521eebde4eb8385.nq.gz
│   ├── 9a91e86d2919f709952bf3079cee793754aea618.nq.gz
│   ├── 9bd413aa461b77c951ab05475b2446b9c6093445.nq.gz
│   ├── 9d82f78915133e1c35a6ea51252590fb38efac2f.nq.gz
│   ├── 9e9ef60034b1920c06c1a494701cecfcdafec4c7.nq.gz
│   ├── 9eeaca289f0767d9886bd94ad104a1f8a24c6211.nq.gz
│   ├── 9f2efbbc98b0c83d5bca7ab9fa75d4494b60ccbe.nq.gz
│   ├── a2bb540d54ae32c21839b892732de5509cc2038a.nq.gz
│   ├── a31b1a9c13453eeb888425c7dd12074eb5d5e155.nq.gz
│   ├── a3226160ae2c14217f7fe002b111a7c35a7a9d72.nq.gz
│   ├── a6ea5e4ed0ce4e6157353ee0d6c1a27b4181adb4.nq.gz
│   ├── aec99730b4e8fcd90b57a0e8e01544fea7c31a89.nq.gz
│   ├── aee44e138434630332d88b1680f33c4b24c70ab3.nq.gz
│   ├── b5b2f772999e9150fce2392de7bf7bb35956839f.nq.gz
│   ├── bfa42f0e7b91d006d22352c9ff2f134e504e3c1d.nq.gz
│   ├── c133a0cbd379f5af6dbf1a899a0293ca5eccfad0.nq.gz
│   ├── c5e586aaf432df4231ff3db8341f262f4ac63005.nq.gz
│   ├── cde69bcccec65160d92116f20ffce4fce0b5245c.nq.gz
│   ├── d15baa55bbfd6ccbf771700a7f305ef4c190c5e7.nq.gz
│   ├── d53e3e2e226ca8933d2b6061bb5dba9309796a46.nq.gz
│   ├── e9d99543bc14b802c1aee64f57a4727bf4ff9f86.nq.gz
│   ├── efb1d39e809cf561b0c8a626ef4d4741f913421e.nq.gz
│   ├── fa6643b716f5d1835eab6003bec3bc68dedb114e.nq.gz
│   └── fd84a66bd5c8f91a36971b11fa13bd363e823c9f.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 24cf1a07538bd55fa51a16c101d8bc568dd46850.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 67 files
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

[sharish/ShimmerRecyclerView](https://github.com/sharish/ShimmerRecyclerView)

---
*Parsed on 2026-11-10 by [repolex](https://repolex.ai)*
