# Repolex Knowledge Graph of celery/django-celery-results

RDF knowledge graph data for [celery/django-celery-results](https://github.com/celery/django-celery-results), parsed by [repolex](https://repolex.ai).

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
rlex download celery/django-celery-results
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 7f41f97b431396ab377a3f67ced906ea22d5423a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 7f41f97b431396ab377a3f67ced906ea22d5423a
│           └── chunk-001.nq.gz
├── blob
│   ├── 04572300296de286c86baeed72d9300d74f8afe4.nq.gz
│   ├── 09b53f938ea2f29e46044ebfd3f077d3e4a01d41.nq.gz
│   ├── 0a8d3da39da77ba53c53b7670594db00a1b1ffa9.nq.gz
│   ├── 0e64adfe2f2db1a226f58432b8a033efd0e9fe7a.nq.gz
│   ├── 0e786415498a535a8b9bea0459f288492824b659.nq.gz
│   ├── 11e06d79fa29cf62418298076b94970042ce67e3.nq.gz
│   ├── 154ba1d7f178b3b643e12e7613c8f581cd678b61.nq.gz
│   ├── 1794178ce01c46f5c10cfb6884f687eb8b34eb24.nq.gz
│   ├── 1eb8fa24c2a9e412be3693c3141f76fbf906e6ba.nq.gz
│   ├── 1f36ba928f47d16291eba814022279546eab436e.nq.gz
│   ├── 20270238bd048c2eb0779ffa2705e647c777ca3f.nq.gz
│   ├── 21f4e243b2e4db105ccc967998d713dc381344a1.nq.gz
│   ├── 22b8a7f61fc6e2db329d4033bb4688d1b80d8f04.nq.gz
│   ├── 23482bbd5d4d3e1ebba63e02d16607bda91783d9.nq.gz
│   ├── 26f1ac659b9ae43ae9dc14209e43612d95703d10.nq.gz
│   ├── 2bdc9e95bddf22b7d6fc601143437364b1ffdbb7.nq.gz
│   ├── 2d4dc9564d2cedc90160c357dd5acdc405c3bdca.nq.gz
│   ├── 32fcaa679aa612ed96ba17b435c155fc77a517a2.nq.gz
│   ├── 33b0685f1a8f3b2713ed330b7b2ea0eab06af9e2.nq.gz
│   ├── 3586787413c49423effade2ddc4d3e86a6c2a6ef.nq.gz
│   ├── 37752d48e2afc19bafe77aa4f5c861f5502fae93.nq.gz
│   ├── 391eac32b44419d6508ceec6aa9141cc3f4daf2d.nq.gz
│   ├── 4317e434bbb31a824a921944e55a520acf04bd3b.nq.gz
│   ├── 531a16326577d44af29d58a76a4190b6ca8b13d7.nq.gz
│   ├── 56d0f6ffb8a524228f9b2eaf33a13d6b8380fae4.nq.gz
│   ├── 58be49a5ba8231d8140c967d2822f0ada05cdd47.nq.gz
│   ├── 595485dbe0ddf39eba93b4bf609e41ac35da43f8.nq.gz
│   ├── 5b20da335b1980be7deed652749d4959d650f59b.nq.gz
│   ├── 5cfb3c23898be991cfc11c6cf5ec669a184f25ee.nq.gz
│   ├── 6001f914d0fa0805f087bfcec416b1e6000f3411.nq.gz
│   ├── 62a65e4f6564f48b4c52baad16c04286b2959e92.nq.gz
│   ├── 63c13c922ab1b451b2486d0a3d2a12539a887977.nq.gz
│   ├── 671a03615d154c12b85b54032226eea4d4d2213c.nq.gz
│   ├── 6795fc6b73deb49f773bc3a3091697b8eba6c11b.nq.gz
│   ├── 6a0a823f1d437421d3339302328d1ef21b88509b.nq.gz
│   ├── 6d6b3900e977ada6019b7c6f0639cea312f1f3f8.nq.gz
│   ├── 6e6df2f99dddc548f71f3995bb630cd0030a5b10.nq.gz
│   ├── 6e974b515afec0f5c71774f9e1a0351f3f91eeac.nq.gz
│   ├── 755973dff582b002e7ecc038e72b942b064d0077.nq.gz
│   ├── 77c5a510a8ed0041e5610bb33bcaf0cbdfcba749.nq.gz
│   ├── 78581dcd35c2c753492882060b83009bc6a86612.nq.gz
│   ├── 7a54ed3d696f93ecfe863d085b42a13b02326750.nq.gz
│   ├── 7c14608c32bc4e7a655ed95a83613ff41a44687f.nq.gz
│   ├── 7ca51660f9fc3d40ee3a6104df83f81535c64724.nq.gz
│   ├── 80e25fc3aeaac43b497ff6a1f963f43dc54f470a.nq.gz
│   ├── 8239afa6e75241c48f6dea8b82e58a5d1cc88a89.nq.gz
│   ├── 842fe33a9a45f49e1c9f1428c49792277baca8a2.nq.gz
│   ├── 86efa38196d792bc9f3abe8c0e891f865a695ef2.nq.gz
│   ├── 88561ae20aa69a7043123d8f274a8c5cd67d4f59.nq.gz
│   ├── 88fe2b55dd3adb9dd79537c04dd9c4d799f940d3.nq.gz
│   ├── 91599f96e51b9074f7fc5fde2a67705c985c93f8.nq.gz
│   ├── 916ae4ccd22c0bb2664660662dc1cfe54c95cae7.nq.gz
│   ├── 91e8b2772059656a0607aaa046e613a4ab7dba8c.nq.gz
│   ├── 95ad05550e01a3a9da278b5dce13041ec3c28c4f.nq.gz
│   ├── 95ff591d8d21e71f7c20d5f2e331794b63b599c6.nq.gz
│   ├── 9b1374b3d468f6b524de5660883c7d827ce59590.nq.gz
│   ├── 9b1f07c8e9b8d6f8b2596a118b12ccdb71e433b4.nq.gz
│   ├── 9c0a50dc09ee225a0c588da41a9d4e5b7835a07c.nq.gz
│   ├── 9d33e345ba911862c6308bcfa318d45edb761ea2.nq.gz
│   ├── 9e261406bbeacfbe87d26b2c9e19e6bb6819f0b3.nq.gz
│   ├── 9fa7932e9de0c6239cfdd9910d59d5ebf27dd71b.nq.gz
│   ├── 9fd4ed05250e621113d90795ce57110d7b0daf2d.nq.gz
│   ├── a07d2edbfd15f23e8f884671b8c900fab088ec58.nq.gz
│   ├── a40e1b41395a658c805383929f96ed0668ccb1af.nq.gz
│   ├── a4777961049b2122a2b6ea6f0ba6aa01cd79859b.nq.gz
│   ├── a4e364a63df38a76cc9130239e73169c46e25293.nq.gz
│   ├── a52375e6a0eaef90b78e7e8573f40a2416428828.nq.gz
│   ├── a5272e4edd17d0d25e28cad17cbdabb9c24b16c0.nq.gz
│   ├── a5e5459f780bc97d1d8dd7a213424549bed1fb61.nq.gz
│   ├── aa9ec70e853bfa2fd23d104dfd9df6b20f2811ea.nq.gz
│   ├── ad00baf2c6e82b6cdfa92e254decb1257ff27923.nq.gz
│   ├── ad4624a9a9cf22918d2d9a8206c1d9235db38d5d.nq.gz
│   ├── ae1bc64d12f4fcd76d7b239e42fa385beed0893c.nq.gz
│   ├── b38f1efa37b48b870c3fd39b8c79669335809f22.nq.gz
│   ├── b472a5af9c941d4944c98fc916bce28a550ca5a1.nq.gz
│   ├── b5843a7544fdbf9e9456ea6e3fa392d18b9ed063.nq.gz
│   ├── b5a4334573babd414a8d005ca606ac640cde880d.nq.gz
│   ├── b79b31e25cf0c351572cd474952a952687561700.nq.gz
│   ├── ba1c96c4efc7448c4c6b34b87b186b72a6daec4f.nq.gz
│   ├── ba3920fc3ddb6a5ff064c59d365036c4a290605e.nq.gz
│   ├── bec8fcaa58169349f53709aabb2283d89b1b19f5.nq.gz
│   ├── c05010a69d6f04cc5a34afeddf73c32e1edf222e.nq.gz
│   ├── c4f74989a14d01a258e8b803873866ec0738a912.nq.gz
│   ├── c61011f733ceddac60e36e12a460a9f45368e8e8.nq.gz
│   ├── c9cbba4288af83c4d28d6921faf9b2ecf393cddd.nq.gz
│   ├── caa9dc91cdfc090dddebff0279708307707b10c5.nq.gz
│   ├── ce70445e9c8b31fb86d9f38b64a53b43e947d0e3.nq.gz
│   ├── d1da272788b6aab7e7bd1b0a2c2f77818eac17a4.nq.gz
│   ├── d379de2805409070f2741d921cc1bca3d51fd552.nq.gz
│   ├── dd0e4a50619dcd6d86b2467d53a7e2ba16f2f242.nq.gz
│   ├── dfc73621fa8cf574f1b5cfd0410e2711ede5792c.nq.gz
│   ├── e5210e472c51eae181771de5ac92cbcf6f313f2b.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e9695e3726dd9d831a64df610051335f20ab7beb.nq.gz
│   ├── eec7d2ca944bc30e12d70485e4f1416ca969cbb5.nq.gz
│   ├── ef3b1a29132b437248b65a263d931ba6607cc11b.nq.gz
│   ├── f16149fc5e59d95aed603e8cd1d1f486c723ef69.nq.gz
│   ├── f24b0fa63729ba66518e2feb87472995ed86522f.nq.gz
│   ├── f2678a45f9dd88923cc022a5a9be87e900ac62ac.nq.gz
│   ├── f69634f9742b66ad231bbd403a89694a4e873fc6.nq.gz
│   ├── f7507619b2cb767df3653259387428f4e9d0e8bb.nq.gz
│   ├── f7aee07905131c1b491917402ca0afcf4a6145b4.nq.gz
│   ├── f89051ffcf2b64b21020c833a663b794510ef4c1.nq.gz
│   └── fe94982cd846a1e47dc36e8a399a130dcbac5d42.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 7f41f97b431396ab377a3f67ced906ea22d5423a.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 112 files
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

[celery/django-celery-results](https://github.com/celery/django-celery-results)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
