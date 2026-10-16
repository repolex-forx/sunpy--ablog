# Repolex Knowledge Graph of sunpy/ablog

RDF knowledge graph data for [sunpy/ablog](https://github.com/sunpy/ablog), parsed by [repolex](https://repolex.ai).

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
rlex download sunpy/ablog
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3f18064e416b0f7d23c4a4a3bd23fd959fedc63d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 3f18064e416b0f7d23c4a4a3bd23fd959fedc63d
│           └── chunk-001.nq.gz
├── blob
│   ├── 006e1aec00a063841b2815b4f848aef351a9dacb.nq.gz
│   ├── 01c64d2d57a7bcb2111ae55f86466e92104eb708.nq.gz
│   ├── 043969355970752e5ab3148f3ea4b680d1957038.nq.gz
│   ├── 044878919d156a25fc4d8565d619a8687b0b0ffe.nq.gz
│   ├── 04f19d16054004a0ad977997aa7888ab2fa7f67b.nq.gz
│   ├── 0a5b023c8b3c22a991d9a847ab9e00c3b719fe0a.nq.gz
│   ├── 102e2c327eceab29ae2c39bd657b34bc216dea80.nq.gz
│   ├── 123464522aee0c88c9bbff977a01e755fb378365.nq.gz
│   ├── 128bb597896ee282ad4d804e4da7c388df8b869a.nq.gz
│   ├── 12e27d057710b8b10c09db3acd80e8948facd58d.nq.gz
│   ├── 1411a865591df2570268be5138b462a2240e0014.nq.gz
│   ├── 16095203c05e65065f07c772128e87c8fd5e299e.nq.gz
│   ├── 1ae9a0f924be840b836a2abe677ec649b54fece0.nq.gz
│   ├── 1b0fbcd64aef92168e2e58143cda9da318eca056.nq.gz
│   ├── 24c35d6d0ecab0563cf17881cc53e06873d811fd.nq.gz
│   ├── 251baddef45a2e486730f47dd7b42a6f6837fa76.nq.gz
│   ├── 2a953fce65c55d9acbab7346bf07f6dc0ed1b8c2.nq.gz
│   ├── 2bae7ff039c6ac3d10e6209aa7be0ced47903445.nq.gz
│   ├── 319dc2f622578087997a193691ddd7f378ebaa87.nq.gz
│   ├── 31b1671429954565e6486ef46872a213f14f4272.nq.gz
│   ├── 3383e9906eb2dec73c66e1040a5803f1532317d1.nq.gz
│   ├── 364dd23a43587184b60d51e1a906c074e7e0a7e0.nq.gz
│   ├── 37af594551e15d149497cac666ca45d07f9084c9.nq.gz
│   ├── 37f2856c246d74bd0a8ddcdd2ad9f48e7f9f76f2.nq.gz
│   ├── 3823ac92cb720a34f0cd69a9d3b5db4f3cf8590a.nq.gz
│   ├── 3e925214d9ecefe76535899d4825f20e49d169ae.nq.gz
│   ├── 407451f939ec0a9780d20b4d92b265f9164542f6.nq.gz
│   ├── 409cf821829700b2958ce2f6aafbd0303ac94e26.nq.gz
│   ├── 40db42c6689bd157e91cec65fda28693350b6332.nq.gz
│   ├── 41f0e3bf3d1ce7f7c353dbfd8b61402b6f3c4ef8.nq.gz
│   ├── 460fa1231ba684a636e961335afce9e016706ca1.nq.gz
│   ├── 46ac2929ee6550f67b3f3eca42b565456c657897.nq.gz
│   ├── 4a0bb51bb7f4676d81ff1244f1d0697dc0430389.nq.gz
│   ├── 4b2c42834dc368eabf3b5f2d4547c8085542b3c3.nq.gz
│   ├── 58680ae0140f1180d08d5c87e1a400c034bf8167.nq.gz
│   ├── 5fed9384c347f561ab7a49584df9a46385d8912c.nq.gz
│   ├── 605680f9042930d020c5cef980987e8ec85ad2f7.nq.gz
│   ├── 6105661ceb218ad41182b0b7512fdca475923903.nq.gz
│   ├── 63a38aac6ddb8b6442f7492bd6a1f41ac55daef4.nq.gz
│   ├── 6512aad2b9ca80fd3c931801817b2f7e27a7af7f.nq.gz
│   ├── 68cd106615e8a4dc7b4b3770672097ff687e76e1.nq.gz
│   ├── 6bccce125ba4518a3bf776333cb84763c91fee96.nq.gz
│   ├── 77a786065c40cc944bd09fcd01f42502cd9894ce.nq.gz
│   ├── 7a6d07eb6811a9c4673beb40c927105a0cd21054.nq.gz
│   ├── 7e97032878bd05e235bf7a5057afcb274d6b8659.nq.gz
│   ├── 7ef72d7b838c04f8fa3eaf3af7fa695bd7987608.nq.gz
│   ├── 7f269dc5b8c328b1622bd708070f688a6e305305.nq.gz
│   ├── 84da97bc55faeb4aaea56b22514d10f350c9d685.nq.gz
│   ├── 8a58b65c6dcfacd26f684b67ed402ec18ccb0c41.nq.gz
│   ├── 8ac6b8c4984dcd382e54c7923325af6d226ca3df.nq.gz
│   ├── 903b3dada07eb719065e33bbf4ac5fcd1e77d1d1.nq.gz
│   ├── 9704c3cb304371ab789511e5b649dba92ecd9640.nq.gz
│   ├── 99075be76d4f2a6011d4e1a461ca80b247425e9d.nq.gz
│   ├── 9936afd3076abd64459ba8150d30f5fd9651d37b.nq.gz
│   ├── 9b25fb3bfec7f2dbfb7e4b6555520167a3c08ebd.nq.gz
│   ├── 9caa3fac36a4dbdf3dd07f70986c546dfe9be2cc.nq.gz
│   ├── 9eb19ab6ec9f5cb1f7ddefacdb2eaa03d1720bf4.nq.gz
│   ├── 9fefc4cd4844c0b25dc1f74d157d9fec1896c997.nq.gz
│   ├── a11fbc148f8bd5ff8e317196e3ecfc733d70ab72.nq.gz
│   ├── a3d282dffbc7bbb130444aec2c8645d3d4b762b3.nq.gz
│   ├── aa80a42afc01e52747079f25fffb637deeea4d0a.nq.gz
│   ├── b063e4228159bb73f16846dbc2b6779c3acd9e43.nq.gz
│   ├── b47d627a7974b526cdd68295dafe2032c5abc1fe.nq.gz
│   ├── b4b0f4cc1c07b805280a3b0d821d4802f7b0c890.nq.gz
│   ├── b8ddd5f08010dd9ee4af42abd4a9b5190e54be89.nq.gz
│   ├── ba27087bb8cfb113d11c929879ab7ff668da534a.nq.gz
│   ├── ba29ffa96a6c7d0b6f99ccded3842e4775c5c5e8.nq.gz
│   ├── ba5a3a3c2cea1c2a2b35a2f2288f511fd1a5abe6.nq.gz
│   ├── bb7a77f56b2506eb525cc3f8565375bb2a00b344.nq.gz
│   ├── bd4b86b268b969d4c7b8a35fa7330ddcd38c271e.nq.gz
│   ├── c1c9092e3c7f44ef7a55d71cd0c603abae9feb64.nq.gz
│   ├── c3ef0f7ecf95a42b91d2f5fb62e06d1196505bf6.nq.gz
│   ├── c50cbd7da6c4475e45873e7dab9e7301a6e2afb6.nq.gz
│   ├── c5e706bc87edbd19cf031f345f0c2bdac14d6c23.nq.gz
│   ├── c98da9a665f594ffcdb2e44ecea5740cc025f0fd.nq.gz
│   ├── ca292e8c897bdb0c843402e88d5e130668ae360c.nq.gz
│   ├── cac2afb00989c9f088c8656ccb4eaef609eba6c3.nq.gz
│   ├── ce87887350931b2a3fc12317ef6bb7458ccaf98e.nq.gz
│   ├── d2e3a270d70786071fed94ac11bd6eb3a4bd6a87.nq.gz
│   ├── d38d40a945f9ceb8f7f6b2b5529f6abd389239f3.nq.gz
│   ├── d85ed391a53c2d1cd620f915be91d2cf028d706a.nq.gz
│   ├── d8efda79af2edfebbc8ba877f1898cf1534db0a9.nq.gz
│   ├── d944b64967bd55405c0cc70e436449d1964b7c0d.nq.gz
│   ├── dae9fb381f0567f7f2e6cf9c2ce70f4453850008.nq.gz
│   ├── dbffded76dee85870696b463eaec9191fd2861d4.nq.gz
│   ├── e2221dfebc12434533f81b69d1f43da7a8aa6890.nq.gz
│   ├── e222aed38108a76dc5926fbbecf05199cf458e4f.nq.gz
│   ├── e5951bd34aafcaabd6531efaa4b8439cde4c3c33.nq.gz
│   ├── e602d242ee12820119902ce57c883cb10db53040.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── f2c4dd2347949477459f19a58217872d785126fe.nq.gz
│   ├── f621dd97b2818be39a788aad90b306e6fb4b4c5d.nq.gz
│   ├── f931ebe82f86878dd2cf8bf6eb532add0febc1bc.nq.gz
│   ├── f9d2069fbcaf1efe90c14d6aed66756079c386cc.nq.gz
│   ├── fc21bf3ae5cac3d952462c421cc3b9ac3a44c820.nq.gz
│   ├── fcf1c1241793b87137cb6adddd190c3ff959265f.nq.gz
│   └── fe976130c4721890ded352958dad844acb9d67c3.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 3f18064e416b0f7d23c4a4a3bd23fd959fedc63d.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 105 files
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

[sunpy/ablog](https://github.com/sunpy/ablog)

---
*Parsed on 2026-10-16 by [repolex](https://repolex.ai)*
