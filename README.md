# Repolex Knowledge Graph of pysal/access

RDF knowledge graph data for [pysal/access](https://github.com/pysal/access), parsed by [repolex](https://repolex.ai).

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
rlex download pysal/access
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c58aea7f5a1576d3f3b9a119b1998bf3a322c2fa
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c58aea7f5a1576d3f3b9a119b1998bf3a322c2fa
│           └── chunk-001.nq.gz
├── blob
│   ├── 0637604084d27f0f3b41ee80080013f15db1712d.nq.gz
│   ├── 069026f3f58df53b9e7b79397fae27aac1358425.nq.gz
│   ├── 06c1eef8376c6fa22326442be96774cede0ad49f.nq.gz
│   ├── 08277dfbda966072c8f8ba05f30a62bd5154158c.nq.gz
│   ├── 086b1614c510dc36759fab4dac558b27de6f3186.nq.gz
│   ├── 09d2529e0c009089674834f13417cf47f5a9151f.nq.gz
│   ├── 0cec291ed10ba2e54b904f715d8bf12622a534e7.nq.gz
│   ├── 0fff5c1e8262b87673e5af226fc9842c0ceab133.nq.gz
│   ├── 11abcd27591cc755dc71c4b7772a03ed3f2c5bbd.nq.gz
│   ├── 12be13531f1327100101f3a0bf5602732ae7d96d.nq.gz
│   ├── 157a7d31e965c53e006295d7deac147e1d616ac1.nq.gz
│   ├── 16ecf40f56117e4c97b42d2ad953ddfd14b832ef.nq.gz
│   ├── 176cbec681f556eb636691ddaf7d88bf8cd46ce4.nq.gz
│   ├── 1beca850af65feb0c27aee48d321db78fe464e8c.nq.gz
│   ├── 213b4e4b8c3bc5564c1247f7bcfa1aea07475fa5.nq.gz
│   ├── 2202e1c59c10db3aafae11a810330a67d93d25c3.nq.gz
│   ├── 2650b80f86572f3ce1e2acc1cb85169ef9eb28a5.nq.gz
│   ├── 27349cd08a903692c70d180c8a566203a6d4b234.nq.gz
│   ├── 277686a97f4be070d9eb97e0311dc0ea4ec271e8.nq.gz
│   ├── 285cc0256de1f32a9c57c1ac67438c2756cc0255.nq.gz
│   ├── 39ee9a20146b03d2e93710cf964cb51ed1479fe9.nq.gz
│   ├── 3b3511c99642d0f6b62fc53111628fa7599f7a27.nq.gz
│   ├── 3c2fd11c01b78bb6e8632981a36f1592b250e8bd.nq.gz
│   ├── 3c8a60c3eb1794b98caba1ccb4fdc5a556c611cc.nq.gz
│   ├── 3f97f0f5b102b6555dcecd863c4943e77e2e99e3.nq.gz
│   ├── 40ed8feb716943dcda8b22c7c9bbdb18ea043cb6.nq.gz
│   ├── 459f7f5d7164ea965f1cbe1ef7650a94029633eb.nq.gz
│   ├── 4bda0253ff2b8decc7422ecbaca9275a430c061b.nq.gz
│   ├── 4ffebb5e8eba885f646e26c56617f9d808cc11fc.nq.gz
│   ├── 500b846738c853e92bfdd55e156244743005688d.nq.gz
│   ├── 6658c4f866f3d8e8e07c1f423a561753f27220a8.nq.gz
│   ├── 685bc6116275f3f090e5eb59a882cc8cb781de59.nq.gz
│   ├── 703fb41f90217ce9c5a8b6267f62080b3b8ce3cb.nq.gz
│   ├── 71a8c1b8fefe526cd01717f33e3929a9a279150e.nq.gz
│   ├── 73f7b8bdac9bfaddf09bf0a18a54d2afc558c70a.nq.gz
│   ├── 75fcd52b00d747abdae166ee1719e3a749e213e2.nq.gz
│   ├── 77650b51c2abb5da0549a035766b362d64bdc5da.nq.gz
│   ├── 7c67c1f33f6b234ecaba5b4e6798238f29ff59da.nq.gz
│   ├── 7ca6757b605f5473fb8f22ed1d01d7bae79fe194.nq.gz
│   ├── 819f38ca4ae09154e58514dd9ee359f48ac39de2.nq.gz
│   ├── 868cd9a21493554f2d4abf90b1b45cf6d7c91374.nq.gz
│   ├── 8737defdd3d7f20686d973a03a3dcdf2a0c60685.nq.gz
│   ├── 87bbab0c25f9a04272a67af100e235f22fa08e01.nq.gz
│   ├── 898c9916ffa9ca4ee40859d44e4e54c8736e60c7.nq.gz
│   ├── 8f258ae31552511c5c2336a9820f4b0089f7af12.nq.gz
│   ├── 977d530be665b51d98a802480dff8c884a46e958.nq.gz
│   ├── 9feb65f936f456e3ad6371650093a723d05a3cf9.nq.gz
│   ├── a79ddc620dc69ad5bbac23ec678c3acab1ba1fa5.nq.gz
│   ├── a93983193a53bd6f4ea1603ff0e5cb212a6a9ce4.nq.gz
│   ├── aa2af31d2261425b7dd3856e8e5ab0770cb1b787.nq.gz
│   ├── af40de452ebf68b7b40f55b9f3818e0ecfd3af65.nq.gz
│   ├── bc1ab017c75f2d89732634b0b68753b722557f2f.nq.gz
│   ├── bf995ff62da7c66fd7437081b00754a670d20c4a.nq.gz
│   ├── c086dd5a261c8c3c5fde55cf83739bfb139fc031.nq.gz
│   ├── c67c502a9d05d32fd1536538ef9adeccd1d55de8.nq.gz
│   ├── d19cf0144fab98305d46ab803d15d548e6b0a8f6.nq.gz
│   ├── d355aa00ccdfcd08016f6cbf691dc0ad24d501cc.nq.gz
│   ├── d5de43a271010c13554bc4610c94a4f3750ee94b.nq.gz
│   ├── d77332184135aa6ea4aedc2558f4cc08ee4594cc.nq.gz
│   ├── d87bd3fad2c849cd01e4c3aa13a9c6c684d58ff3.nq.gz
│   ├── dc75555263deb59ffa0e4f45b3f7f64dd9697e2d.nq.gz
│   ├── dca29fecf33aaaa01e4091323669704d17461361.nq.gz
│   ├── e10ea888cd12e79c06239ee1c1f2b7282165c841.nq.gz
│   ├── e2bdb44ebac5921a4011aa8d9fa660a0077bf328.nq.gz
│   ├── e6704fd267aee9646efd2c55332dd308c86a2705.nq.gz
│   ├── e81a3ae1d253887204d78a5f3ebfe5862c3d8256.nq.gz
│   ├── ebcaa880f1bd0a3e9f7f482be996ee63b6d04ffe.nq.gz
│   ├── f104da12044cd6d3ae89a63528c99ea073bf5126.nq.gz
│   ├── f92b8d4acf5566946cfc950f1989569e3cebaf28.nq.gz
│   ├── fa6e0d0568b283d1d671e73d4cf7f7986cec5247.nq.gz
│   ├── fcb599b8c664bc4efd4285deebeebed9cb24f7e2.nq.gz
│   └── fcd6888b76b6433111bb023da2edc443565991b4.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── c58aea7f5a1576d3f3b9a119b1998bf3a322c2fa.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 80 files
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

[pysal/access](https://github.com/pysal/access)

---
*Parsed on 2026-10-16 by [repolex](https://repolex.ai)*
