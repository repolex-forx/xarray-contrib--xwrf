# Repolex Knowledge Graph of xarray-contrib/xwrf

RDF knowledge graph data for [xarray-contrib/xwrf](https://github.com/xarray-contrib/xwrf), parsed by [repolex](https://repolex.ai).

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
rlex download xarray-contrib/xwrf
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a238d69560f2f7216df3fd9e9ea495658a6bc252
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a238d69560f2f7216df3fd9e9ea495658a6bc252
│           └── chunk-001.nq.gz
├── blob
│   ├── 01e1a125f13d50619d81dec1010959f7e5d6322d.nq.gz
│   ├── 12437f65fd5d26e0860a45d36d87ed197129b4ae.nq.gz
│   ├── 13304e5f5ee974f5f23260871857d14a3029ce14.nq.gz
│   ├── 13da28343ffb409fb3449d69d4b103f4558f963d.nq.gz
│   ├── 168436e062bb7001dd8cb1b94f9677abf8dc9df6.nq.gz
│   ├── 169206455b9f9e4f14790397563ae74bf0c3e07f.nq.gz
│   ├── 1af0976bcf506061e12a9fc4318e9d091d93acfa.nq.gz
│   ├── 1be8151d1bf08fe9c997cfc2c272056bcc1725e1.nq.gz
│   ├── 1c363ceeec04f0685123ef1ee76ac04a1a5368a7.nq.gz
│   ├── 1e5973efafbb33be820253babed489ff17482100.nq.gz
│   ├── 2372c899488d10483f78b56d79dff6a2db70290e.nq.gz
│   ├── 2df9a8cbbb680a1e83d41f835efafaefffc4888b.nq.gz
│   ├── 3032ce63dd4acd88f25c4edb637b3e1f792c1808.nq.gz
│   ├── 303357ab45fbedebdafc14e7970b1c4b37b05a00.nq.gz
│   ├── 3189daaa6119e55169d127068f1c3a72f7c32b89.nq.gz
│   ├── 320f2ceb87dae684b06d28ace1f9be38bdc3ba72.nq.gz
│   ├── 3961bafacccffffc2a1b08012c461da60cc1627f.nq.gz
│   ├── 39fb679e1d2b4eb6f535df5bdb6b243dc4bfc970.nq.gz
│   ├── 3d8461a14265af1447911932a34a81df39fd0c13.nq.gz
│   ├── 3e66e2b73efa6f16c84f58d0f3956010ca7b5ed3.nq.gz
│   ├── 4152e837cf578948ee300833b44c21947134500b.nq.gz
│   ├── 42ad60c4394f9ac584174fc2b0ef9597b5b87eba.nq.gz
│   ├── 46c8bb8b33fdf88e040be0757a4d9386b217c9b0.nq.gz
│   ├── 4d6e28c3e65dde88f6a4e545f907f71218c3d54b.nq.gz
│   ├── 5797c60e488f936f31901ffe0b8b8cfaadacf5e6.nq.gz
│   ├── 59d5a9ee618d15358d74b57674384b8e0472451b.nq.gz
│   ├── 5b324aa69691ad08e983b6bb2249286956c79094.nq.gz
│   ├── 647d23c54d8064d94bb62748cac78545d0f98548.nq.gz
│   ├── 67158a2471c371dce1d1f7a3b2341f5c1379256e.nq.gz
│   ├── 6996ad953275938dca9e1610d6524b955fcb2d77.nq.gz
│   ├── 6ba86b699e3860b3cd5debec14306671cdba346b.nq.gz
│   ├── 77fa41f1ff93b8c56cf80b74c8ab83c1cc469360.nq.gz
│   ├── 7a921ffe22547b5f8ddd8de0d81c08acce4e3f9c.nq.gz
│   ├── 7c084094277b659eaf7365cfaaffee59146d2ac9.nq.gz
│   ├── 7d28112549bdf41491538c476d843034544b1f25.nq.gz
│   ├── 825c32f0d03d98995ebe3e6d797f14daf2df51d9.nq.gz
│   ├── 85ff168957c9260f83effa922cd68dbe9e4b89b4.nq.gz
│   ├── 8663b5e0ec9639076ce1dcb83214f16d62a7cf19.nq.gz
│   ├── 8746a866e8f1dad229782ee594aa53eb1e7411b8.nq.gz
│   ├── 8c86bccf5a4b4934f1482d23d14728062956f0bb.nq.gz
│   ├── 8ece9d897fd7e3713664830dc22b1b360a946d17.nq.gz
│   ├── 93740d35ec9548d38096e90cd37d1642a5fb4816.nq.gz
│   ├── 93fef34854cb72b2f0a0b656640c8a19293ea36c.nq.gz
│   ├── 98a23b0b0e842aeb28e4ea16920fda9d8c3c9cd3.nq.gz
│   ├── 9dbb85779161e16c3a7fbd51a43c32d16366857b.nq.gz
│   ├── a3d16b5b2145588e5e8cceabb1a18fd11c678f56.nq.gz
│   ├── a53761a1fcd89487e1234054a37ddd4d40781b59.nq.gz
│   ├── a5d497d85594f0994c4b495faf83c82a44ec23cb.nq.gz
│   ├── a6f4a23d9b44bece5796c3160b832da3dd0c7358.nq.gz
│   ├── addd6d363c2e940176d19bab85cd344df3952e9f.nq.gz
│   ├── b0d87ad2084841dee592140d51ce1f40e2d573b5.nq.gz
│   ├── b1303b40c82442b3905c3fa026828ddbe2ae508e.nq.gz
│   ├── b1e14af702524dfd2e1ef80e9b7eb343a73537eb.nq.gz
│   ├── b7377f7ad51d91b1d210e1c57da855ee1593fd75.nq.gz
│   ├── bc2555c6db74a02027ccad651478aa0288db4831.nq.gz
│   ├── c5a260b68f55584ba32a35dd9bcb4c9380f69a09.nq.gz
│   ├── c617248077ef62f3f1431910dcb9b61f710a7c2a.nq.gz
│   ├── ca05f163bda7ffee14dfe89e48e21cdac6860d62.nq.gz
│   ├── ce9df8b69ffca020f0fec2697192d7cb98fda78c.nq.gz
│   ├── d7f5e2f02cd6b3505d8ef770bb05273af4ba9c84.nq.gz
│   ├── d834e9bf2bcb166466f682756a78c8dfb0c51d67.nq.gz
│   ├── d9b192217ea0e96ed86e334c4c9bc249bfafc6a9.nq.gz
│   ├── e2a049dc27b8bd6b87670007b8e6841b4a35a48b.nq.gz
│   ├── e641e4542c11f14ac9a1e37b91510a5e18483559.nq.gz
│   ├── e727b82b2840f08b98d69ba6940ee084137a5605.nq.gz
│   ├── ed886b163b8c7cf45cc0c3e54647c0df396120e6.nq.gz
│   └── f490e7325a57dd54cb6678983179903cfa0584c3.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── a238d69560f2f7216df3fd9e9ea495658a6bc252.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 75 files
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

[xarray-contrib/xwrf](https://github.com/xarray-contrib/xwrf)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
