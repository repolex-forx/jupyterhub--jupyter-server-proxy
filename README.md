# Repolex Knowledge Graph of jupyterhub/jupyter-server-proxy

RDF knowledge graph data for [jupyterhub/jupyter-server-proxy](https://github.com/jupyterhub/jupyter-server-proxy), parsed by [repolex](https://repolex.ai).

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
rlex download jupyterhub/jupyter-server-proxy
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 240a3ac397dc4a4ff4098bbd58594d25655896b8
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 240a3ac397dc4a4ff4098bbd58594d25655896b8
│           └── chunk-001.nq.gz
├── blob
│   ├── 012ba5e22cb2450bcd694f10e30865ddd983d10c.nq.gz
│   ├── 0a06b827161eab05831e6a92ef486db71cb02b05.nq.gz
│   ├── 0e5cf9112644d7a32791126095b5db375b35f8f1.nq.gz
│   ├── 117d4ac6526e55317d856291918997332d5971ab.nq.gz
│   ├── 1855314cec69bb32a7090056b423ab8dc34ea936.nq.gz
│   ├── 19ddd757d07b1d64ec8b60bba7f04bbabdd5dcd4.nq.gz
│   ├── 1b798c64ffa423f1e09b604a0846fc727b5e5ba6.nq.gz
│   ├── 1e58154e64ce5d2f6286e3cd45734a3517c98a2e.nq.gz
│   ├── 217f7a7de06918bb677c5db064e2346d50447782.nq.gz
│   ├── 2ae1485b309b2b948d2d95113b1cdf47eb9d8e43.nq.gz
│   ├── 2d9531c3c79fcb3443c17f52786540e72558ddf0.nq.gz
│   ├── 385441258f717ed6636c71dd813dc838d28ad484.nq.gz
│   ├── 3b6c28f3067857b5501852537321c83a4f3f6727.nq.gz
│   ├── 3fee9dd8fb237c155c187eb1bc1903b61b3c2662.nq.gz
│   ├── 41725abaf840ea45ca56f7fe6bebbabdabe7e137.nq.gz
│   ├── 421dec69c714c5ad8be59e63cc53a5a5d47ef110.nq.gz
│   ├── 434ede719f031c05b24a1c6a31ea07f0cbb08266.nq.gz
│   ├── 44f3beaa720ba54ef90c889211dc51e458bc2e3e.nq.gz
│   ├── 457db5e24ae6d62cf5dc294c4d4849c2fa6edfb4.nq.gz
│   ├── 45f77475c33a85862841a6b4914a86fc1c95e401.nq.gz
│   ├── 4695b5dc6daabb8df4acb536c3bee099ad230e3f.nq.gz
│   ├── 4697681cceffc6fa2d7458d8ec63de774b9e8460.nq.gz
│   ├── 4950642017eed728614877b2c3cbc89a38accdfc.nq.gz
│   ├── 4b09b02639d4f36e959e4e6271e92dcc341939bc.nq.gz
│   ├── 4e21cf6a30d1dd3d8c336e87b1ad07a9d9f64c4e.nq.gz
│   ├── 4fc2e136b6a106f69c369f081d7cedcf946b57eb.nq.gz
│   ├── 5b9d515e8592fef81552cdd2707be89703da4825.nq.gz
│   ├── 5c76871400af07eaa0850b11e4a55b85f08faf15.nq.gz
│   ├── 61470e3b38578188b7b8cf5ca6eefab75a107120.nq.gz
│   ├── 63f4be10086890efcdec64ed403c93649ce26f92.nq.gz
│   ├── 64779a108a8e489d84d37d58df8d4a435ed46e47.nq.gz
│   ├── 666a80f40dfe584766b5fe953daee814a210e0b1.nq.gz
│   ├── 692fe05b000a62838502013aeeca594fafb95ec0.nq.gz
│   ├── 6a944f765860506269017f99a5936b6bf729f4ba.nq.gz
│   ├── 6bf99912962fa7cac96e52d95b28ff30badc962f.nq.gz
│   ├── 6c1be1002be1a2f5babf4feaa6d82185b4e3ec33.nq.gz
│   ├── 6da91571ab9a5d395b2de147140aa15e95fa425c.nq.gz
│   ├── 6f002f9b0955ce80f35aa327b6db6bc1c3b0ba4e.nq.gz
│   ├── 772861812775e21ace0ea74838847e51bdbd8f7d.nq.gz
│   ├── 7c360aa4d703dc05c2d82256e7f96cb115fab7b0.nq.gz
│   ├── 8028ca7dc7d492b019b7a133aada983f183d1d41.nq.gz
│   ├── 822efd89f2e9cdef22f691ffdfa28ce83ff8fea2.nq.gz
│   ├── 84a5617b61983532c877037349f065ba72e61ddb.nq.gz
│   ├── 85da63054d284560df6e6654af139bfdac726f30.nq.gz
│   ├── 866d9ba4e4d797a1840fdfa3a9fc04ce58002e83.nq.gz
│   ├── 89159168e930ec3cc00be11dbda6bf748e44965b.nq.gz
│   ├── 91e1ef218fa2439664fb75a231b61137995bd362.nq.gz
│   ├── 929e1b951a48b37b5be79b3462f2538c69ff3e79.nq.gz
│   ├── 960886dfc563e8bc91c96cef34d39d18eec8247c.nq.gz
│   ├── 97320dee634c286f76ff9809831e3ae195f08969.nq.gz
│   ├── 9d72250017bc717593a5ed8d1b2294fae84cae5b.nq.gz
│   ├── a08c02e1589ff492ee7548433c42fa99b1200717.nq.gz
│   ├── a3fd20bf736754758827299109601a72a705b699.nq.gz
│   ├── a43b7795b9fc94e3b9b711179bca2032ce99df34.nq.gz
│   ├── a5200b291dcc4b383d297f126d6e574a0cf919d7.nq.gz
│   ├── a7cc7360748f9cd535dbf439c7460d9831b388cc.nq.gz
│   ├── aa2543db4aa9d982763b573969d2b70423a22a10.nq.gz
│   ├── ab255087431725b5ae37c0fe279a6572f1064252.nq.gz
│   ├── ae8e6d6c97baee1c8a2da00ebca0605fddd8df78.nq.gz
│   ├── b0341d5851148c52f237503ee3745996a5e08c73.nq.gz
│   ├── b6a21a04e4d37ecc33bd50bdfae50e59d7c2b145.nq.gz
│   ├── bb77d5fa9ab55fe71fac29a1c14a61528e7dfaf9.nq.gz
│   ├── bfd515896e9f85480d342c0e06d9fda5bc4fc152.nq.gz
│   ├── bfdebc8e000546650003bc94bf9e68b310c3c136.nq.gz
│   ├── c0918aa45a94e44b1181367853380c29dedd436e.nq.gz
│   ├── c62a4edaf3344662f8a9d4803c52a6650810f64c.nq.gz
│   ├── c983ee0758d3db1678ec1e95f1a9280ed3663ab8.nq.gz
│   ├── cadab8682eff23dfe6270f91476c724e78818cc8.nq.gz
│   ├── cc0b3a54667c566df3e420ae5175f13e4f30d395.nq.gz
│   ├── cc1cf642036e4a2ba27906f6ea0ccc4a38a798e7.nq.gz
│   ├── cc266102b9481b6ba9d6d0aef07d51fac9116e18.nq.gz
│   ├── ce4d6e2804ee0d26da073ddc7589d688573c2d29.nq.gz
│   ├── d0aa25cc5e9f3dee99fead10cbbed5c02792499e.nq.gz
│   ├── d23d35085ade55aeadb4a047b7cf085f3608349f.nq.gz
│   ├── d7da11c804202cd2254da1c4573d4c1e679fe682.nq.gz
│   ├── e6b7e9f4df517321fb94e6664d10581125b2baf1.nq.gz
│   ├── ed312ebdb25e7252083fce92f740ebea9973d22f.nq.gz
│   ├── ee9cb5f9d66b7bb57c39571b939d18e036cf0134.nq.gz
│   ├── ef3b33e5f7cd13db1dbf93f192757c0611dd5e13.nq.gz
│   ├── f1f1371cea449141d374690dc50eddc95c5e7705.nq.gz
│   ├── f891e302a218920e8862476c86c675e466162d70.nq.gz
│   ├── fb3e380534c76203e2d6b3d756deb19885629ea5.nq.gz
│   ├── fbc0066a29523067d81f7e3a7ecb002c718d94d6.nq.gz
│   ├── fc7d336a17be1f096f0726e472140a8a320c9fbb.nq.gz
│   ├── fe0cf5024ca9db354875db4afb7f98712a6ca5e8.nq.gz
│   ├── fe8bf82ace3c7aed705166dffc6c2bc6c215b82b.nq.gz
│   ├── ff06292ef7d457f2d4beeeb46e086271fc2d0588.nq.gz
│   └── ffdf84e2314ca24a8b508642368dbba3bc61c7cc.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 240a3ac397dc4a4ff4098bbd58594d25655896b8.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 96 files
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

[jupyterhub/jupyter-server-proxy](https://github.com/jupyterhub/jupyter-server-proxy)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
