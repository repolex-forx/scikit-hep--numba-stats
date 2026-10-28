# Repolex Knowledge Graph of scikit-hep/numba-stats

RDF knowledge graph data for [scikit-hep/numba-stats](https://github.com/scikit-hep/numba-stats), parsed by [repolex](https://repolex.ai).

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
rlex download scikit-hep/numba-stats
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5a97575a4424d68955dfffaf254564ffbc496508
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 5a97575a4424d68955dfffaf254564ffbc496508
│           └── chunk-001.nq.gz
├── blob
│   ├── 000d628787826985f5243317e1a678d59ce4c008.nq.gz
│   ├── 0029b9e66f904ef10f6088b542879471c548917e.nq.gz
│   ├── 005e7cae912596a8ae0a5786608eae7c8fd1baa1.nq.gz
│   ├── 035c12683e3291512706d30e89ba0ced585c0a02.nq.gz
│   ├── 08650ab4769e565c7518e40b703af544cc60bfb9.nq.gz
│   ├── 0a38de12bda15069fd15b5fcd28d8524710c4748.nq.gz
│   ├── 0b3ba233238c3b213e0f13bc2ae4f217794c612f.nq.gz
│   ├── 0cbae1fe4086748b16d6903d541201c7794ce99a.nq.gz
│   ├── 0e31b9252633fd1b38fe9d4d6327575873147398.nq.gz
│   ├── 0f549ebc44f95bd6fcfd63a33491194d9f2dab02.nq.gz
│   ├── 14a187a59ede9c5e9342953e05a16b2b13bd90a7.nq.gz
│   ├── 14ffc2c8f485357075c38130ec029b95a4574054.nq.gz
│   ├── 159aa86ed8cee2ba91fc4aaa147d6beebd1ca8a8.nq.gz
│   ├── 1704a4b4d29edc65394b38d3b0ccc2889624f381.nq.gz
│   ├── 1937139f2f4a3e960acc1ead0b0bbe29d39ad3e5.nq.gz
│   ├── 1b36b36833966c778a87290cf13405e726946d24.nq.gz
│   ├── 1e106f69fc1810bd760a6b19062482c3c867e9b5.nq.gz
│   ├── 22ad20079d826f80034a8f9efbfac949f8a7d662.nq.gz
│   ├── 231fa72a031b24f8c851e79fb7226e737f420ccc.nq.gz
│   ├── 23ed870e72fee4f6a06b811438c558a1c4580e2f.nq.gz
│   ├── 290a697a44581095753e7efbf41a9dcb7f4fb5d6.nq.gz
│   ├── 2996e2419f265fbc60ff1967d32010b8d4bf774f.nq.gz
│   ├── 2a21a5164ca63fde3c01ac65f0f11e67f37ef620.nq.gz
│   ├── 2b2f8de943890419bfcae8318ed725287d94e531.nq.gz
│   ├── 34481afa2acbe5f0dae1568b04a499a7f7ff4de6.nq.gz
│   ├── 34a6ca879436c0707929ff4da9dd5b8321a3cdde.nq.gz
│   ├── 34fb0295ca6d2b014556be6db49f37fea9c9911a.nq.gz
│   ├── 376cc7dc8fb487c5721e9f599c0e8c630244320e.nq.gz
│   ├── 377b63a2ae0b025e7b48fc46d74152db739d4b0c.nq.gz
│   ├── 3785188178f4a606b69beb6375824852f04740e0.nq.gz
│   ├── 37fbed3360e7c234386f48bf02813222d70cc237.nq.gz
│   ├── 393b98d660ea56b6c0fccf13818e0ab4e57c0a81.nq.gz
│   ├── 3fa4dd98fbf713638ea0afd2868bb4ce19e4553b.nq.gz
│   ├── 41041a320e8e66b01f8924a8c958389b5d74c139.nq.gz
│   ├── 44b1c98b076f9ceaf9b595602ba8d9efb1142d68.nq.gz
│   ├── 450c51b8f6f4762cf1129d8b29b1a4cbaebf9f9e.nq.gz
│   ├── 47b4c615b04f3a5b6558230ab173a2a06913e660.nq.gz
│   ├── 482bae738072ea141f5fd77329933b8c374d0d08.nq.gz
│   ├── 4a9bc35e5dee47f74cfc5e3ebe5b753a0555c154.nq.gz
│   ├── 4bff056239c9af0af781cf8cdeb82716f183feeb.nq.gz
│   ├── 5162e47d824682a19efc9ac0cea9a5def870ef60.nq.gz
│   ├── 54bd8c0b001633650dfc53d427ff14ba1708a2bc.nq.gz
│   ├── 56e6d812332b09b5960b50e53e31e5af0361cc21.nq.gz
│   ├── 5aad4fd8265a674f6441286e181c0f850e51ad50.nq.gz
│   ├── 5bfad3b988164237bfb819f81cf0053a6d0d5c93.nq.gz
│   ├── 5ee73a920a8a84d76cdb3de3bde9140af7a8b5d6.nq.gz
│   ├── 6084949c2d108efdb61dd41f734df60a7bd33f5e.nq.gz
│   ├── 615e22e47ea2fbac9982fe273cbfb486cfac9285.nq.gz
│   ├── 6516e910d61a5293a3a37859fa7d394fd9169b64.nq.gz
│   ├── 6891682b72167ceb8c31507ae10b10765ddf3f4e.nq.gz
│   ├── 6a6a6ad9bb47fac79a17271804dc0d4b095cc793.nq.gz
│   ├── 6e32c00aa779d7222b8ea57e1c3fa4888a11621e.nq.gz
│   ├── 774c32848aa53002c3ca87c351039e281326a2c7.nq.gz
│   ├── 7d954e7fc3ca3ebee08e41c67b6a12e795c06807.nq.gz
│   ├── 7efffc32bb9750333ede0925e72d67f3f462c23b.nq.gz
│   ├── 804601b2c7af0deb7dcba3195ba5410a1f93f00a.nq.gz
│   ├── 8404ba8b194854a75e47055665fab21bf523b6ca.nq.gz
│   ├── 841c266e057801fa27c7f7f72c00619eb10dbb13.nq.gz
│   ├── 85502869d5e41291fd1ba391e1eff5863ab0ea78.nq.gz
│   ├── 8691e5d1cfa442c91717cfcf2ff4878b70968cf3.nq.gz
│   ├── 8b1e44c6c1880b597ab3fc4fcd50fb83dd3ff0e6.nq.gz
│   ├── 8b5c65bd40c036978a5e16425cf52277d674705e.nq.gz
│   ├── 922c0a1a98d2c21915a60a6ec451415818d4fcf4.nq.gz
│   ├── 930080dcfa78d06f0226535536524d24ed96e6bc.nq.gz
│   ├── 94bfee778be4025397bb6b2c9c6b05f88e61a5e3.nq.gz
│   ├── 9527402cedf6921478d7f9f2db9b6202d7a17183.nq.gz
│   ├── 9ca8b335fb00dec5627dfd15f39500dd69887311.nq.gz
│   ├── 9fbdf5dba1099a79ac675651094e2e03880e2a70.nq.gz
│   ├── a02dd79b50463a7af45beabe2231e0a2d362e917.nq.gz
│   ├── a1ee919ea6c4a136694ff7d13e3e936e30df450d.nq.gz
│   ├── a29cc4d75988ed3580eaae5bb55ed4887fe005b0.nq.gz
│   ├── a2d9d138449047b7a31267e0e22725008c5799af.nq.gz
│   ├── a4ac41439a5a80530b39d678feb83729503f586b.nq.gz
│   ├── a4b53fc7af396131959c8a2fca7152c012ade82b.nq.gz
│   ├── a598dc1cb859e5b4633fed0297ff169c6de1a6fa.nq.gz
│   ├── b0c0d17734a929067b9904361b64a087100fa8da.nq.gz
│   ├── b692c13893cf0d4d475085bc393e42f2665e9523.nq.gz
│   ├── b6c197499759a0411d1053515a1c3c1d831d1ea9.nq.gz
│   ├── becec13a30bf9bea34a1a93e8c8bcf41b7064577.nq.gz
│   ├── bff60c8c98afe3e744673d0cdea15625045abdd4.nq.gz
│   ├── c2a26e77f30f596746f7974671a1d66f9fb10b0b.nq.gz
│   ├── c6c4cf0afac20e95f3594b15c6ac3a8c49d2ab31.nq.gz
│   ├── cb7e1b061cf495e729001e633666587b34f2c623.nq.gz
│   ├── cc48550b5d694e665338bd30aec23fdbd17ebd8b.nq.gz
│   ├── cfda9f7be168870b50a0dcf5bc810c5f078b3a57.nq.gz
│   ├── d37f4b8ef93ca6b94cd9264b8f823106a918319a.nq.gz
│   ├── dfcc0b7b0a9a4db9dc239fa01bec7daae00f7030.nq.gz
│   ├── e4d8a811b6ece02e5748cd3c1c102d41f2dc1fec.nq.gz
│   ├── e7214fc6598305227000427d150d35e4737cf15a.nq.gz
│   ├── e7bb06dbfc4192171554222724e4bcbcfa7a84dc.nq.gz
│   ├── e7ece3b3e99e554d3cacf08326ed92517a31075d.nq.gz
│   ├── edca1b7ab14cb5c8cda0719ca37257940b2119d8.nq.gz
│   ├── eebb20a979da993c3361db42c353ae272fe2d140.nq.gz
│   ├── f0e9597f8a314d3fd91b898d4f9f08c2553749cc.nq.gz
│   ├── f5abc1d6394ea9f4da81f70857d8542f50bb1644.nq.gz
│   └── fa70943f7b4216b1ea5ace0cba768e5c95a9bb8a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 5a97575a4424d68955dfffaf254564ffbc496508.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 104 files
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

[scikit-hep/numba-stats](https://github.com/scikit-hep/numba-stats)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
