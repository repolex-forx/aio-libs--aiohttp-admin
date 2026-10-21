# Repolex Knowledge Graph of aio-libs/aiohttp-admin

RDF knowledge graph data for [aio-libs/aiohttp-admin](https://github.com/aio-libs/aiohttp-admin), parsed by [repolex](https://repolex.ai).

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
rlex download aio-libs/aiohttp-admin
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 81ff53bcead274a7c5bbd00f46d0655f39a34a6b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 81ff53bcead274a7c5bbd00f46d0655f39a34a6b
│           └── chunk-001.nq.gz
├── blob
│   ├── 00eba85ac203b608d9b838ce28d972db57887544.nq.gz
│   ├── 04477e935fb0229905ccc756d3659648fee8a82c.nq.gz
│   ├── 0b3ebacb0bf7deea8ee9a68b7bfd20d10fc07be3.nq.gz
│   ├── 0f529308dabcfc478d783abc1bbf8717c8134f6a.nq.gz
│   ├── 137429147ec5cd97276cf0124732bcb98e9c266d.nq.gz
│   ├── 178ac9e83b935f84d323d9002371198d2f424105.nq.gz
│   ├── 1810a4f381cabcd7f22873f5aba124f48a5a23c1.nq.gz
│   ├── 1ae43bf8318ef2ec7cd410965488facfeef47467.nq.gz
│   ├── 1c8e54f3e7524abf6b09eadec786090998cb35f0.nq.gz
│   ├── 1d29d4822b6c69e6ddcfaa50d3b9b5707b4a3d9d.nq.gz
│   ├── 217e34576d8d97fe8a29396318f9b571933aa24e.nq.gz
│   ├── 22312fbae87697a485b7f528b4d37e100aeb5055.nq.gz
│   ├── 2369ddf87b093bd2b97a2fa7c2f9109e5d1aa8e2.nq.gz
│   ├── 25b9e889a7a80d4295e9f77cd70472642dc38a15.nq.gz
│   ├── 262bd7cffe30dcc722d7ba15488bca4d06f5cf49.nq.gz
│   ├── 26df46ea24dc8b77c9b16278e70d3ed70d38e065.nq.gz
│   ├── 2940d841948053f9b85f760d077c05d41680d208.nq.gz
│   ├── 29624fd1b6b44b480997ae670e4983b88cbf3a02.nq.gz
│   ├── 2f46ddb1829e15e25c67e06ac9be963665d61095.nq.gz
│   ├── 36979982708b367032730848375b2a457cf360b8.nq.gz
│   ├── 3ae2cb3f416ac47debdf9d05ca5efef08bc733d9.nq.gz
│   ├── 3c3cd0091c0558c91f0704428c8048d7676d22e1.nq.gz
│   ├── 3f4edc8d189c195d29b4628663f3ffd6b8f513fe.nq.gz
│   ├── 3fb438fcf8388135ea5017030ad00029fa5885cf.nq.gz
│   ├── 43e0a9048d287babf5fb7051a753333bd8895372.nq.gz
│   ├── 45b6d0c8cd4d900983f23d83fa9b49953f61dcc5.nq.gz
│   ├── 48911c0a02d5a3f45f68cd0106febd200d7b916d.nq.gz
│   ├── 4a477f11b71cdd3cc89e38a306b07bf85e31fa44.nq.gz
│   ├── 50212be7190d8c2cee66c08ac16a5c1c844ec344.nq.gz
│   ├── 5355a088c1b86d21a5f0b40c63bdc35678072009.nq.gz
│   ├── 5f7f3c422a52947ccb5cd35c70c56f8b7d26c67a.nq.gz
│   ├── 6434fbfce2ea5d4f829ee66e76523d7e3a9098dd.nq.gz
│   ├── 67f1a92926f642519294b789cee060ca7c222928.nq.gz
│   ├── 742e271f5932d262138dfefa079f82e8bcc0ea8e.nq.gz
│   ├── 7a49d0e28b12a5e2d2fe88f00d7f5f9c42e5e520.nq.gz
│   ├── 7b2b17fd18e31cc6e49b8006b266d1d1fbb91fe8.nq.gz
│   ├── 7c4082b39a5ffc1fc497e3b193483eba0b2a5b17.nq.gz
│   ├── 7f676f5ae3d2d7ea34076efc67ea73aa9d87b62e.nq.gz
│   ├── 8d70d385e1b6192ffee12a51a49a1d3a28bac801.nq.gz
│   ├── 9454b0e7168c8e6e78d678393c3ff90f6043b0fb.nq.gz
│   ├── 97faf9615f870898862ad27dd4a05000453791c8.nq.gz
│   ├── 98ce2f6051c8d45f9d0124632e0912f7c1fcfc12.nq.gz
│   ├── 98fd8774db6f4e0d2afe0229fe52936506337b8f.nq.gz
│   ├── a07c784fffd8de8209948fbdce1ea5936c5b35ef.nq.gz
│   ├── a2d87053546d5f1a9d42ede68db0ebefc0d62a82.nq.gz
│   ├── ac640603ab1dd7c21bca7f56fd9a6ed01520a14d.nq.gz
│   ├── b4f88507dc19a07f015ce59573a5dab3e7596d3d.nq.gz
│   ├── b4feadb381aa6d97561d77b62a7536764416aecf.nq.gz
│   ├── be4ba83794f6ba9826d8a716728f2335c2e61a5f.nq.gz
│   ├── bf6884767ab758b1145d2f13a92f458204289b88.nq.gz
│   ├── c420f408ab0e198bec3cf4717fb62adfec2df780.nq.gz
│   ├── c60676c1cad40b1b5da49e638a83193bca80c8cf.nq.gz
│   ├── c62bafe137909763ae36a9a03841f915cd4689fc.nq.gz
│   ├── cbc5e0f29ac97a0dcf33c71b592684e16cc19b45.nq.gz
│   ├── d46aa05f12ed5d7775f30020a6df614dca7d621d.nq.gz
│   ├── d83cce79fad4559abd3852b9483915996400c643.nq.gz
│   ├── de640c06ff484ae903bc7699ead5fb06d33618c8.nq.gz
│   ├── e074a90495d8589bfbac4d0e58e1b4846e4aecb0.nq.gz
│   ├── e0b1210681f58bd2cc354f5cb897749c78efe38f.nq.gz
│   ├── e4d26f3e0b9e080e4f266e25101ff05420c5def0.nq.gz
│   ├── e53c59b5a34babc665cd84d3b0e6afe84ffa05a8.nq.gz
│   ├── e582053ea018c369be05aae96cf730744f1dc616.nq.gz
│   ├── e9b528d53c55834ac35bd185f14b8b224413dba5.nq.gz
│   ├── ea28ffa9358c0b3f2cfa8626b2c2397883369d2b.nq.gz
│   ├── ed46543b3225de03b13b344c50a114bdb0f745dc.nq.gz
│   ├── ed83429ced4778c805c33a3b0bd0e6898f124ff4.nq.gz
│   ├── ef3f00f0eba57f5c4e6dc0a9e4816b956e64fe95.nq.gz
│   ├── efd8915827d02bf230668edd58dde463c8be0a40.nq.gz
│   ├── f038aa67b895144983e717c9e781fdb5849c30be.nq.gz
│   └── fd7c71a2fe134ac3d1b7c555ea32bc0364cc75b8.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 81ff53bcead274a7c5bbd00f46d0655f39a34a6b.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 78 files
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

[aio-libs/aiohttp-admin](https://github.com/aio-libs/aiohttp-admin)

---
*Parsed on 2026-10-21 by [repolex](https://repolex.ai)*
