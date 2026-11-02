# Repolex Knowledge Graph of enthought/pywin32-ctypes

RDF knowledge graph data for [enthought/pywin32-ctypes](https://github.com/enthought/pywin32-ctypes), parsed by [repolex](https://repolex.ai).

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
rlex download enthought/pywin32-ctypes
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 06a3514d2f6b784293d209fd2e54a3c810fd6c65
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 06a3514d2f6b784293d209fd2e54a3c810fd6c65
│           └── chunk-001.nq.gz
├── blob
│   ├── 038e76195039bb9cb72237103e0d10202e5550d4.nq.gz
│   ├── 0992071a5524af9b6ae93ed1fbbcb14790cde54d.nq.gz
│   ├── 0f37f1dc9f5f7ebe7b44c293908b4aa04796d6c7.nq.gz
│   ├── 103834888aa69fd1fef1bc524d5764839f677bc1.nq.gz
│   ├── 18e193447efac824947b2f6ef74a89d2334c5918.nq.gz
│   ├── 1a387574b48db82e0591bd1a807efb891c366249.nq.gz
│   ├── 2067bb76983bf7417d45406dd2915b0d27a6ded5.nq.gz
│   ├── 23adb1fa2f1fdee4ef05daae1d8ff003b757c96f.nq.gz
│   ├── 27b5fc406926b9facb7d7573a937b79568fd3860.nq.gz
│   ├── 2de6bf2597eb3d13e78849dd8bdbc8c4823420a4.nq.gz
│   ├── 39ce680deeda866e329f96c7f0b10ee58dc85370.nq.gz
│   ├── 3d7baa7efac87e1223a33a93cfd57ec217b62050.nq.gz
│   ├── 3fc135b4bf4fc03f273c695081d85455e8a830d9.nq.gz
│   ├── 42bcbde601ee2efccdf1a863df591331df99fc7c.nq.gz
│   ├── 44e7289fdba4ad333f838282c75023c33eac782d.nq.gz
│   ├── 493974b67c3261bcd53fa9ccab5688559588944c.nq.gz
│   ├── 508f4b13c6cf00e57e9c6b1f051176768a3f80f1.nq.gz
│   ├── 51697392f411f6ff76647694191e3eee8fb3d9d0.nq.gz
│   ├── 51f7194aa2cab76084cc27c84a7a064356c24757.nq.gz
│   ├── 52a316443e284021bbc7eb4abe5215259c4dd7db.nq.gz
│   ├── 5c0e230b950fe08835df71059eca1d8efeac0b7b.nq.gz
│   ├── 5cf10154cbf799a627d925e985ad94d2f8e1c79c.nq.gz
│   ├── 6209e1fcc2ecbeffdf4afcad5ba0d2e99377abd3.nq.gz
│   ├── 628b1ebc051eb585a6ceef3b1663d57cd7a69a47.nq.gz
│   ├── 65be37d4107519a20375d3c122c048078791e999.nq.gz
│   ├── 6711251350269e715a8a2af4dc2a2578ff2b2712.nq.gz
│   ├── 6fac1f44bc8ba54e6941acda193ff9c661addc7a.nq.gz
│   ├── 735aa847a2290e87833e342273f0e4833a2266c5.nq.gz
│   ├── 7d752d57b8c26df3111304bb247ff6b2af0e024c.nq.gz
│   ├── 80d071c708309728053fdeb6f1ecb7e947733f3f.nq.gz
│   ├── 81dab387c6e9cc96ecb7a627cd9fe786fa9fc0f1.nq.gz
│   ├── 887bb0382a06dbcfad6442b19455036734123be3.nq.gz
│   ├── 94e16e15710ce99c3b3bca5b24a025eae1dbb510.nq.gz
│   ├── 97a7de80b314fa86a4bcadee8a8211bcdf5ae154.nq.gz
│   ├── 9a3a07da13cc6d884aeec19f624568ea5264f07d.nq.gz
│   ├── 9ebe025a7c7ee2fa4f4b6fb3a6a444f7c3aff566.nq.gz
│   ├── a74b8fb1ee6eaf6633cc22489daa72ab740375a0.nq.gz
│   ├── a880e653472495c805c3b0698f52e03655745ea5.nq.gz
│   ├── a88ebb8a52ae6cd598b7dba8cda5974a47749907.nq.gz
│   ├── ad3384617f501dc4f3a7aacadf0f3b3e933eaa38.nq.gz
│   ├── b34506a385efc28e29e23e36feafaa606d86b7c6.nq.gz
│   ├── b4ce1ff837b3ff0a9e0d70d0c76ef4988c2c80fe.nq.gz
│   ├── bb760d51e48542fb494a439c228e814aab9091ec.nq.gz
│   ├── d0ce125fb63c6222084fd0f4b1f5e5057cc73905.nq.gz
│   ├── d0e7945be888ee51fb94cbc0e3948a9a51e29c4d.nq.gz
│   ├── d769d606f95c68dc34e30b88acb3eb7a52f53250.nq.gz
│   ├── da8a9368bc3f6c52089108d85f2789ab1f182ca8.nq.gz
│   ├── de4cd6680a8ecfed723bf9df92d1c73a75b72de8.nq.gz
│   ├── df7e0ec86b00d27020c0fded4253e43964c18977.nq.gz
│   ├── e44c663dd1cf72d8448de3940de190912f590923.nq.gz
│   ├── e84dff92945db11f4a7c23e576317dac8b14daa8.nq.gz
│   ├── f4451a76d6767d052a4cb80c4e7733f00ea7646e.nq.gz
│   ├── f642da81a8396a5b4aa4b70906cb4a98d7f32071.nq.gz
│   └── f7427122cae65342edfcf688ac449804d12f2291.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 06a3514d2f6b784293d209fd2e54a3c810fd6c65.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 62 files
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

[enthought/pywin32-ctypes](https://github.com/enthought/pywin32-ctypes)

---
*Parsed on 2026-11-02 by [repolex](https://repolex.ai)*
