# Repolex Knowledge Graph of All-Hands-AI/OpenHands

RDF knowledge graph data for [All-Hands-AI/OpenHands](https://github.com/All-Hands-AI/OpenHands), parsed by [repolex](https://repolex.ai).

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
rlex download All-Hands-AI/OpenHands
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 045290739f0af2ae4cc89d2a209c6bd930bb81ee
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 045290739f0af2ae4cc89d2a209c6bd930bb81ee
│           └── chunk-001.nq.gz
└── blob
    ├── 001d91cf22e023f6851bf692d54c32a2d578934a.nq.gz
    ├── 00999b82eb047bb2db6345fc9393f54a3eb7a554.nq.gz
    ├── 0262dcc3e9fdea6c5dc531f9c40d6a5f8c44343c.nq.gz
    ├── 027c8a5fb2f3df742acbfc078f60cf0e3cd86916.nq.gz
    ├── 028327cc611967929f1572a04cf5d59ebc3f090f.nq.gz
    ├── 0284351300f98c4565ec40bab959d7e179c5a2e7.nq.gz
    ├── 02ef015073723a5d8c91e152293747da298de77f.nq.gz
    ├── 0316fe8b80e35dc51d05a2e75e16d37d3c189afe.nq.gz
    ├── 0461dcaac5f0816e905f7688ee947b535e86d59e.nq.gz
    ├── 04d2f2a5c718885b3af3d57e46d1fb0aef6dc523.nq.gz
    ├── 04dabec85dd1ce884076b39b5f6a7c5833858427.nq.gz
    ├── 0519076637424ab95532bbb4e2bfcede688b2e5b.nq.gz
    ├── 05656fa316e85feced5d710b11b785323f3a3b6b.nq.gz
    ├── 05af26fdde6aa4723a8b8584271a1fc370d3549c.nq.gz
    ├── 06165cb1aabf8818e9b124b02796f87e10fed426.nq.gz
    ├── 062e3fc7f77bd8488cd8dd0c09cdb4057bbc95a0.nq.gz
    ├── 06651901d908e9ad8d0994495d24392ccd98c57a.nq.gz
    ├── 067f2e4d40613fa55daeef50eb23c0d59994aa42.nq.gz
    ├── 06e4c370d1580fbb901d4ac80b7a613a68b75869.nq.gz
    ├── 07008eab9b6bc4f08559e9ebada0b752118e4198.nq.gz
    ├── 07b30ddc65812f37b443f5589c18bfa8d1a93723.nq.gz
    ├── 07f0908709c0df3649a05af6abb630a72cc4a872.nq.gz
    ├── 0836f8296db4afc7eb690ba80a252af30f720828.nq.gz
    ├── 0841a2e2ab5248bae80cc4d6422a25e9cf8905b8.nq.gz
    ├── 0902694bb5e2c64bcea5e3ad4f17258abf8668dc.nq.gz
    ├── 090b020535be51f52438eaf61378463cc702643d.nq.gz
    ├── 0926b404e1a998c484598232af95e559ee7f3cb9.nq.gz
    ├── 0b3ba345f8bfeb711797fdf475bafbf143fc10b4.nq.gz
    ├── 0c98b1ea91c48c6636466b98ce495a4af0a35f96.nq.gz
    ├── 0cdd49e098f9e683ccf752d8a87af16b909e01df.nq.gz
    ├── 0d2139ccf24aaba3185764a02f188d5b9fc3c27e.nq.gz
    ├── 0db39f83b76314b698bc0b2cb05bfa2416e8514e.nq.gz
    ├── 0ef3d943b59244981e32d5ce0f8d4b60946a287f.nq.gz
    ├── 0f0ad38f477cde47bf821402a8486a0a70a6bc7f.nq.gz
    ├── 101a31f462f41828aa9e22da9eca80777449dd0c.nq.gz
    ├── 121573ec101c02c726c7417d67b754661a345f28.nq.gz
    ├── 12a73d3b83171e974f02f0d28e208d746053aa9a.nq.gz
    ├── 1366ce77ccfbed7852ce2919d9383e0cec308cc7.nq.gz
    ├── 14493ef5e0aa6b0d1395445de06f634502288028.nq.gz
    ├── 14817d15421135b757ba113c00da456c2ba3bc67.nq.gz
    ├── 1484a8b4abfb4b9e1199cafa6ab1d37bee315ae4.nq.gz
    ├── 152c29b8c51896fecd0ec3f23a5dadfe899121ab.nq.gz
    ├── 1720384e99e4b59908117b09685daf659b24830a.nq.gz
    ├── 17de80a730e60a3cc30d45ca27ffbdb5a12305c0.nq.gz
    ├── 180c501a4ed7ae631b0ce576e7da5abc04c7bd9c.nq.gz
    ├── 1888d08c184dbfe9319839e81740d1a0e1ddd38c.nq.gz
    ├── 19c838558178bff0181839d18fcc56d5b3ab78ab.nq.gz
    ├── 19ce187ecec515640503f5023bd8e2c7e93c47fe.nq.gz
    ├── 1a4a3acaa2952fc874d6789d87fe56c5d8270364.nq.gz
    ├── 1a76a3aa9cad096b86df1de4a4a9f0cbfddbd236.nq.gz
    ├── 1c105626df12d5a5a1eef73205f2849e9dcf5172.nq.gz
    ├── 1c5259ae5c01bd880f9c7bd91c43ade199b8b8f3.nq.gz
    ├── 1cbc8cdc31d9bbbca1d3030ac97c361d22a1bae5.nq.gz
    ├── 1d1ff5235090846c9d2b470503e3e08334f9bc29.nq.gz
    ├── 1d7b9bde75e0d3eab689bba48b9fc5cf92b6e33d.nq.gz
    ├── 1e3bc21db6fe49c6a58dfbab9dcf53267ebebf85.nq.gz
    ├── 1ee6a53d8da69456b2a5ff7307c337c422a586d2.nq.gz
    ├── 1f1cc4229823c469ad7c6a9fb9156349b8a3ea96.nq.gz
    ├── 1f7fc2fc7e179df6805faad81a64ed1e7d202cb0.nq.gz
    ├── 202ada9fd100f45151e023bc6c9ed183230d0ad3.nq.gz
    ├── 2234301371873b41b08d5306cbfe849258b87ede.nq.gz
    ├── 224ab8b9054d66dcf051ae467febc4c3304dfc61.nq.gz
    ├── 2264ab5cddcfbc499c9efdd46b07d46d37c8ef79.nq.gz
    ├── 22f9c5441127215781ae8c32dae1631725d92375.nq.gz
    ├── 2315b30e1e2ce3110ac119f0662ff241da4176ea.nq.gz
    ├── 23362eeb6782805e708599096f1fac73aff0e896.nq.gz
    ├── 245d565c8427521eb41e7cc8c437a27b5731acd1.nq.gz
    ├── 246ddb124bd2b5e8ee0c843d7e3ead16bf6cf522.nq.gz
    ├── 248b50ab811df33f85db817ac29bd772a1ef5f9b.nq.gz
    ├── 24e1684596fde338548affae86bbcc561be72107.nq.gz
    ├── 2513a7c23888c0de341e07f01486dea768d70782.nq.gz
    ├── 256e994c8ad3d2d04e089e8154ec63085fa1366f.nq.gz
    ├── 25b58002d66cf4f9d8a919eb485801d2e954f981.nq.gz
    ├── 26184f80ea84f7677c4a71fb1d28a7b0e5c6e50e.nq.gz
    ├── 26241f541a77d7b12a5bf4fbad7f110ed011faa6.nq.gz
    ├── 266a3935f7da70341fa06ed6f0ba16e3976c66f6.nq.gz
    ├── 27451ee4a641cb955c5acdeb433b6f97f460c531.nq.gz
    ├── 2798ceb7ec700b52d22431f0dae89c7dfddeff03.nq.gz
    ├── 27e7d26f182112d0831e091f4511e0ecd3a52e95.nq.gz
    ├── 285ccfaa0da3d3f4a4fbee8f7815bc31892fd336.nq.gz
    ├── 287e41055ab1f96517653deadd5d87c34a56c604.nq.gz
    ├── 295b99220dd415498f9af1ecd7017ec42928ba4b.nq.gz
    ├── 2a1d9f0e5e37a36b0f6218fab8c973189de7af0c.nq.gz
    ├── 2a3ae7f1d0e2f17c10fb4da11e3dc929e105f9a5.nq.gz
    ├── 2a7eb29503e62d1a30b9156a11fc9c3d695d667c.nq.gz
    ├── 2c753d8e0b64509872dd3e46bcf80d67a892bc0c.nq.gz
    ├── 2dbc9f83f67db4b78a4a80d63c6b3d1431e9dfea.nq.gz
    ├── 2e01263c5f3dd3428882871acb9d10c6700cd6f9.nq.gz
    ├── 2f0d8576610b10234c40cccd03563c7f7e19b9f8.nq.gz
    ├── 2f4dd233887bf5d130cebf1546e15e6f1b191cf5.nq.gz
    ├── 2fc29b52c6ea40b6e3c1a235403045285e9701af.nq.gz
    ├── 300efb6097a8db3b086945e24b42c7c8a4d1daa1.nq.gz
    ├── 31054bbf06ba7ebc3719654a1f9907245ae35462.nq.gz
    ├── 3123b3c5e23ade160c0c3befd6d7b058b89edada.nq.gz
    ├── 31a0844fbbe681886bc6ef032915f5dc0380a0b5.nq.gz
    ├── 324d1187549b1a5e67080cd836386badbc30bc58.nq.gz
    ├── 32e2f41f519155999bd949112b9e5276311fb5c0.nq.gz
    ├── 33084b985f8410163f2d4f9cc84f1353570c6f0c.nq.gz
    ├── 34952463bd875c2639cd5a35d8ab6be32fb2cedb.nq.gz
    ├── 35b224d5a75e3347e862516248092ecb5512239b.nq.gz
    ├── 35c0ac7d5ac2fa476a2be9ff04d6f13c0ea71038.nq.gz
    ├── 363c6400e6284d662daaa13b3631305640cbc01d.nq.gz
    ├── 3661c71ce5c0f7879e19ed35c50b988f381b7337.nq.gz
    ├── 370f8dfe503f772d33b4565e00f163a620b0b124.nq.gz
    ├── 37d3d67bc453a001fcc5fe96ff83c15870451bc6.nq.gz
    ├── 386f35ec98c7508979ce352d0196a7c86ab0a67c.nq.gz
    ├── 3a0406b52565b7ceaeb9d921db9898d004638bbd.nq.gz
    ├── 3b48686a0b13fe0a37343e1c60d4cc543452fed0.nq.gz
    ├── 3b9f0e229093231efe7ce7abfa428403abbb3969.nq.gz
    ├── 3baa23f9331511ae8960b311c10a8a32458adc39.nq.gz
    ├── 3c04b8c36886171214fe727420ed6c4147b2543e.nq.gz
    ├── 3c067d2fde144b4aabc69e22eb4a0c60f151d663.nq.gz
    ├── 3cce5054a19bc5c3f574f4b88edb62a3a60a4b94.nq.gz
    ├── 3ecc89cfe55c65dc328eebe3a5e85249bd2a92d9.nq.gz
    ├── 3efad1c84bb82a7beba11dc7688f269fe0d15f6e.nq.gz
    ├── 3f1b37b0a33e425c427be05247dcbd63a7367305.nq.gz
    ├── 3f3643bf7de84083bccc6398273b1dc3b151595e.nq.gz
    ├── 3f5cc3a14e120fa7c815789fa773a53569215e54.nq.gz
    ├── 408619a361e52d7272e28065109705ab92cee67f.nq.gz
    ├── 409ca4a3d4cefb32fc235f7bea793a067ee4f722.nq.gz
    ├── 414bcf1b3002301d084cda3649cb8a442201cf95.nq.gz
    ├── 41b432569e7f6d8ad90b05ce1affaf914c6ddaa2.nq.gz
    ├── 41c5056a741b550d62fe07ed31285478b3115b4e.nq.gz
    ├── 41d4c3c483d1a349f43a0a7b4ec06a3d5bb04b48.nq.gz
    ├── 43268c5812bf350857d36d83b063048a4b7df709.nq.gz
    ├── 432cbbe125e54b51ce99dc3b0968f943b862bd52.nq.gz
    ├── 43786749f4898c2226c0cbb7a804fad406f39b2d.nq.gz
    ├── 43fbf4b90bc85ef065ef3802c2e20991cc3eee20.nq.gz
    ├── 442f8af6cbc513855eeb4fc5a6ea10fe645e037d.nq.gz
    ├── 44ad6b2ce4163cd0569f080f31944cecad8f75ae.nq.gz
    ├── 450c6699edcb960abbb18473b9836ce1d9ec0982.nq.gz
    ├── 4573cb19e9c0be9e37e899cee36ada16ac9191a9.nq.gz
    ├── 4647c99503b0ea0f1e01f1bf4a7b853b4a770c6a.nq.gz
    ├── 46d6ca2f51d4b0b940d610f37a765f2e51912416.nq.gz
    ├── 48cbc0f8c7027e108f6b79a9bc5657b4752f5d9d.nq.gz
    ├── 4905956e7fe2f0a277b44c0d755698868becc20a.nq.gz
    ├── 49509d4ce0d9a054b6de7bd78947a6e5ea303a03.nq.gz
    ├── 49cb944a23ffd4676a994fd7b3a5b0549b2305d3.nq.gz
    ├── 4a4941c6eafbbd64b6560b6aeeaa2817b06b3279.nq.gz
    ├── 4aaa4f229896a570d9f70cd527dd0caf3bf22bd3.nq.gz
    ├── 4af44228f4024e4315084a80f9c8d8c98baaccbd.nq.gz
    ├── 4b7037d91952e9753d3ce614ac8538adc0783f12.nq.gz
    ├── 4c747c4ede37f1ce375ee2261c4df5178a8c79a6.nq.gz
    ├── 4c8134823cf3dfd1e832e22925a1fb21c7aa7eed.nq.gz
    ├── 4ca74d749ac7a0d6c8e29018f4fd0985921b9b4a.nq.gz
    ├── 4d3dfe9fcd7a8daa5c7409535a4eccc3b218cb2a.nq.gz
    ├── 4e439a7d4fb28eb41667d99a41adc8eb634ec285.nq.gz
    ├── 4ea6b3882f798318c4683ed1bce79516252ec0c5.nq.gz
    ├── 4ebb59ea91db1f352e20451ce3bbad5a512c1567.nq.gz
    ├── 4f885f00f810ee36544549390a3542738493b476.nq.gz
    ├── 500c10d74148dccce0f3c538a635b41fc522e65b.nq.gz
    ├── 50fd4f6cc84a2600b5a89aeb745f905e7510cc27.nq.gz
    ├── 521b436a8ef5ef401252e1f846ef7d6690b45174.nq.gz
    ├── 529a259429d8210cafea330f3cfec590dd30fd04.nq.gz
    ├── 52ea49177afe422636280dc76a53b354e1f2c497.nq.gz
    ├── 533cf30c1ba292f9bbfc4ee02a6fa1fa85978516.nq.gz
    ├── 5372cdc4e30951910a6f1c2e5379d5f8a46c7821.nq.gz
    ├── 54d3e182f7e42052797ca57cb49dc46983171f32.nq.gz
    ├── 550cab583e8d22bde48edf17dcdbcb9c9aa784ae.nq.gz
    ├── 5534f1d0ed7c3065ca8050c6052370b2173909dd.nq.gz
    ├── 56bc9bc2f4aba25ae049316e581aa5c9cf57da88.nq.gz
    ├── 56d0f891c2adbd1cf336dfebdb5346eac1b526ac.nq.gz
    ├── 575f4e0a8b6914e3bf461d89f88800e81d564256.nq.gz
    ├── 57981cfbae792c5e109e0bc9269ec264ebe745ae.nq.gz
    ├── 57d7889b16a161f49fc2ebf6f4924749d62c7078.nq.gz
    ├── 5a3cb5954be7537100b3ce8d0915e4e5e5d19c98.nq.gz
    ├── 5a79a36a4c3507e507bb4c57aec03cd4e3bbe919.nq.gz
    ├── 5d0fe84da1860a7dc856a984e3053ae8ade8d346.nq.gz
    ├── 5d81f758834d9c90871bb6cfdc9959e60a13698b.nq.gz
    ├── 5ddd144c107c9d9a1e8da4d943656117d19db2ab.nq.gz
    ├── 5ed5ab6d614830f3889c0fbe29899ba921675f49.nq.gz
    ├── 6065ca30fbdd8b6fc428f2c6cedf741d52aebc31.nq.gz
    ├── 606cabc4f5f16e471de80c5234d810c722880032.nq.gz
    ├── 60b40c32c96a415b96cf861cb14c4afdb3deb873.nq.gz
    ├── 612fda52f52b90a1f0af7a6cf24bb302c0aebfdc.nq.gz
    ├── 61a64bec07849ff74f644b121dc95ef8dfdf8ff4.nq.gz
    ├── 61cdc6dc59c343e2edfd9bd1bd13b0517a12e123.nq.gz
    ├── 62a969d553039d0d04c9da8a6dc81e983a17b8ae.nq.gz
    ├── 62b98d48ba3e5149ff36a3c721c391ccb3a16a23.nq.gz
    ├── 62e5edbf0468621f3dd5d128ef0c40e08bc2999a.nq.gz
    ├── 63481958e4314d5db9b1d18dc808494c2de27b3c.nq.gz
    ├── 63b95d25bdeea802553be8e6a58502368ba95acb.nq.gz
    ├── 63c4c66d528e92fb732071cc308eff13e76fcc4f.nq.gz
    ├── 6404cc36be298e3e8233bc0badc778e73d99aada.nq.gz
    ├── 6678ab15f78027f9d2fad377c80cee8f9abb9f50.nq.gz
    ├── 6705872d0f1e7b40dada5bafac8dbe1dbb9f0d0c.nq.gz
    ├── 68dba2a0bf8ba2258a670974c06629433228b981.nq.gz
    ├── 6941629a8a85563cc54a1044857cbe05a916148d.nq.gz
    ├── 695f49016f260af0d0830d97b44b5361e0acd1a8.nq.gz
    ├── 6a4c0cc6545ca81fa24e470300236b7bd4a5d1ea.nq.gz
    ├── 6a5dd2ead5412a62a5e09995a88eec7ef730a580.nq.gz
    ├── 6a6874155c088a835e5a5ad850f3b66c63bf7ff9.nq.gz
    ├── 6acc155120f3c2d2c3023e6b9d8e811810732020.nq.gz
    ├── 6b66d71ace4e08499a71aa5e7b5296ef461f7540.nq.gz
    ├── 6bc7aac9c3128b54e6c7f09b3c457eb5eea72a60.nq.gz
    ├── 6c0540790cf1f459b31d556b4f70f224a2e81383.nq.gz
    ├── 6e259747846b75d91f1d9e57058830e26a429dba.nq.gz
    └── 6eff56672c6585eb85e747f250e3d61d46327732.nq.gz

7 directories, 200 files
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

[All-Hands-AI/OpenHands](https://github.com/All-Hands-AI/OpenHands)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
