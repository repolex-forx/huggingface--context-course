# Repolex Knowledge Graph of huggingface/context-course

RDF knowledge graph data for [huggingface/context-course](https://github.com/huggingface/context-course), parsed by [repolex](https://repolex.ai).

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
rlex download huggingface/context-course
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e4fefaec7bd4843139df705f5e169750a441b273
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── e4fefaec7bd4843139df705f5e169750a441b273
│           └── chunk-001.nq.gz
└── blob
    ├── 0010472acbc6693b0c604da7136aa91361e5d019.nq.gz
    ├── 00cfeb82c3f28fc29ce51bce4cb528ec2616ee0e.nq.gz
    ├── 00eb1b51a669eaae63f632fd0b4a248c5604cb0a.nq.gz
    ├── 01e16b2d386b7424b8d0889510b8314603331f1a.nq.gz
    ├── 0264300413585e50820422a3d6b148dbd5f15c10.nq.gz
    ├── 03d3e1460686e958b69170bc1466dd32dbf373e1.nq.gz
    ├── 044da122515421dc385e9f9d46afc748437d4b80.nq.gz
    ├── 045455addef95533680e0476f3d912a58da08889.nq.gz
    ├── 0500e80228574b96264f489130537697f8d3285f.nq.gz
    ├── 0822c723e7c6fbe28a4f21de66c2b8ded1a50487.nq.gz
    ├── 091a89fe5ba3aa71de44271e9136810cc7961c90.nq.gz
    ├── 0bc51abc9f1a3f3bb73fd551318401127bebe027.nq.gz
    ├── 0c2ec83ea4bc56626f6bc068b2c16bb5c0f3b548.nq.gz
    ├── 0d3726566353741a93fdc8af1f3356a190342289.nq.gz
    ├── 1047af2fb8ddb6ca9f9d8a98aee793e5dd9e850e.nq.gz
    ├── 11a1e4f2758e84c456c029ec5e7af53ef78602ce.nq.gz
    ├── 129471dbfc6b89a3657291a855758b91fbe4c21a.nq.gz
    ├── 12d61d9796d80c90c92698f7c593c5739b60e346.nq.gz
    ├── 1316dd4514a559043bdf448724b26fbe4275c660.nq.gz
    ├── 13976e952c8d5833bff963f602fd62f7b9c00374.nq.gz
    ├── 13f035625d419e722534e4df4109e9dd91332089.nq.gz
    ├── 15ebaf2eba80aa5021ebfb063d6bc93077fc19fa.nq.gz
    ├── 1603b644f5c3210669eece3ee24c6d3b2e299114.nq.gz
    ├── 19c125ecd190c6c10fef159ed998e24fe7399189.nq.gz
    ├── 1c83700808de0533cd036b6c55c26b9a857d50bd.nq.gz
    ├── 1cfe34eae830db1adcdbc6016a4dea3f554c535c.nq.gz
    ├── 1d09ad763e5bc9601bd39dc946d0117621e65013.nq.gz
    ├── 1e5c1360d5d1ad1311ad29dd78a534e35e401b05.nq.gz
    ├── 1e92cc2a987672863f4e1a56c98cf3f145eb6019.nq.gz
    ├── 1efa091c61ae0b9abf1f6e523a995c4f28c923c4.nq.gz
    ├── 2407eb62294650832a6994e24cef0bc8a93748ad.nq.gz
    ├── 2681ce3bf3e0aedb912e7f4f71044d5d0422981b.nq.gz
    ├── 26bf32d2b53112a2644b83131fd256d3b7322f85.nq.gz
    ├── 26c2a694f1e04cc773e6829d69fe8c4636f6ba1d.nq.gz
    ├── 28eefc26d9a4da27084a3e201b5f91634fecd7a6.nq.gz
    ├── 2905a8109552f929ff71625baadc7216d8cae228.nq.gz
    ├── 2b44984587042331f747deeed771dfdb06c12277.nq.gz
    ├── 2bfec6b7e1fe8173913031e4a94f050219bf7ced.nq.gz
    ├── 2c14def8b4f339a36e5e876d8afbcce4a0a99bcf.nq.gz
    ├── 2c44dcfaa1be9066a241f09fef0c5fe91d07afa6.nq.gz
    ├── 2c91b1432eca3d0fc28dcdce5701d1e1fbf99c1d.nq.gz
    ├── 2ce85f4ef61f99199551a1ef44397eda5c8e9142.nq.gz
    ├── 2fade3ffd2540c79823cf5668b643deb4282b441.nq.gz
    ├── 3034e0e75f1dd02710bcc3fde57a1295f56063ce.nq.gz
    ├── 34822d91f920e3e51c0fa811ac038574700e5fe4.nq.gz
    ├── 365851da9f5274d3807429452b3f08b5d0264b73.nq.gz
    ├── 36f833fdd2b93b5b0a3c191128762086e488db3a.nq.gz
    ├── 38749b336ecb55c38aa5b66430880cadc59d3528.nq.gz
    ├── 3a1f5e194a69285da4d7258d989d78dfb38232dd.nq.gz
    ├── 3a2b7547011e62f54e211192335683a1061357b4.nq.gz
    ├── 3c26d18ebc85a9c23e54cdeab6f215b0f6258ae0.nq.gz
    ├── 3dac96366129cf5a208bfe71d4b894fbd715dfc8.nq.gz
    ├── 3e02f069b359caecb132ef11d44edf1f6967bfcc.nq.gz
    ├── 3e95b719050df0be96da5d3a8bc40c769328777b.nq.gz
    ├── 3f6fbb057d55c8804d6d633ce037fbc871966762.nq.gz
    ├── 404e4bdfc62ce1ab729a0536d4f778675e110572.nq.gz
    ├── 4415627f99e7eef7409f6378df3587ea1f26d4cf.nq.gz
    ├── 444ba5d8ed837c6abf36e3783476c84336584681.nq.gz
    ├── 455e5e8ab62b7fe594128fbb047478ddc0608316.nq.gz
    ├── 45909bf88d2e64e7c3ed71b90140a52086760765.nq.gz
    ├── 467a51f64824babbaa300c29c5dddf25e6826886.nq.gz
    ├── 46f4113d2535ad234e378de87754baa830a5ce3f.nq.gz
    ├── 484968d6e9686c1ed3b4b0cb84412feaba67d8ac.nq.gz
    ├── 4a4a748a07928cdde537187605af502d90ed6339.nq.gz
    ├── 4b7659989494cc0b9909c26fbaa3fb1fb245aac6.nq.gz
    ├── 4d7e43421f10d09620b37e66624b0345c40c80f4.nq.gz
    ├── 4dd9d2c6a24a1a9daa48ab06f8b263d34ec6c29f.nq.gz
    ├── 4e7cb74d5f791ea20fc9c88b13025c1ea2c8c913.nq.gz
    ├── 4ec188ec497fdc987fe603da2b7691c005e3be69.nq.gz
    ├── 4eefa93a186e63fcefc35896f02913ad4c45150e.nq.gz
    ├── 4f9b65f4536e0b94ff11bad92bbf3e4d172a1540.nq.gz
    ├── 50d10a39f7ce228d5221a30aadeae18728c92f94.nq.gz
    ├── 5101a7255ecdef9140105b12eefcd0c5cce829fd.nq.gz
    ├── 522c10179bdd2d86d31556f0f7aae7c1b079b9b8.nq.gz
    ├── 53add283380b36cd3c6d6f00732f1aeeb764d6d5.nq.gz
    ├── 5494c65e6609f7eded74189c7619cc1a6614d7e9.nq.gz
    ├── 55efcf7093dd4311b65ece8057c5a7446667d4c6.nq.gz
    ├── 563ed0f18809c95d9c9ca8c1e90ec5f07343d303.nq.gz
    ├── 56707dcab6d2d776a8f1e3908e3c32bb8d1dab2b.nq.gz
    ├── 5674c7dbc4c9201681d79a0bf1f84d46fa888461.nq.gz
    ├── 57a03995c1dbe637691191e3fb3c57c47e2858c1.nq.gz
    ├── 5a1864a9f3044736f2d214ac686fd50a2309a0eb.nq.gz
    ├── 5a483c300a854e327d1bd2681b9c57e18229ac3f.nq.gz
    ├── 5afdf3544321ec1f973efca69217938d7c23d74d.nq.gz
    ├── 5bd21c98732ebfb5a10e7f44893eb8970e650de0.nq.gz
    ├── 5bec0b581daaacb736309f925dea4b3842594f96.nq.gz
    ├── 5cf99bb33dd7cf502de66983b4a789c57d51b754.nq.gz
    ├── 5e8402661124ff8c11650a7ffc254ef5bcc2d78a.nq.gz
    ├── 608408bff1ebc19c1578df9581e1766db498c9db.nq.gz
    ├── 621daf14c3162f1952ef81f905159c6f1b90cc71.nq.gz
    ├── 62607b9af9024c2af7625b743d65b57fe86fc676.nq.gz
    ├── 6315632766a8c1002f00d656f7306643b6e77101.nq.gz
    ├── 632055d5d4dd9afdcf8c385d07096a5bc8ae53fe.nq.gz
    ├── 634d9966a1cb2a0ee744af10056b564c91d053b5.nq.gz
    ├── 63cf245c6f83410b99707628ab11beefbb8534cf.nq.gz
    ├── 64994ad9f5b7ee2812be2124d927eb92f0067f9c.nq.gz
    ├── 66b6ea7e664dae5f2ec217f7cea1c44d087ef15a.nq.gz
    ├── 672b4e59f8abc13548ee9e5591804f8eaf779a54.nq.gz
    ├── 67d845b9c05fbdcb6de7dc030badc2b8e1066d1f.nq.gz
    ├── 68e47d4a6ca907c6b26414ed0e3a7b13a72a29bb.nq.gz
    ├── 69ec6f5e670e790e0d349840ea390dbb61b58015.nq.gz
    ├── 6a5a0598e719415e18730cd9df6b250bf6046b87.nq.gz
    ├── 6ad79ca4ce538e550ffc92d190a9089b3686f688.nq.gz
    ├── 6d6b5c84fb1e0cd6bb435b0f33894fa2e0c906ff.nq.gz
    ├── 6e078daf7698ff966102cb47a51b3ef784856733.nq.gz
    ├── 6fe6f0a536b770836e2d4e885898b22b23994b10.nq.gz
    ├── 70dfe9aecd54887a99cc925e45cae5faaf53b184.nq.gz
    ├── 72bfe0010f027a1fc4be0d11451d5286490b3583.nq.gz
    ├── 7440d62673579033e29e5809d5a549ba42b94834.nq.gz
    ├── 7764ce9186273a1da58fea1060352314e337eace.nq.gz
    ├── 791c274481ba913d3ed47886f614a34dc9eba197.nq.gz
    ├── 79b739ed0d2ee03c15fca4257466d322423e59be.nq.gz
    ├── 7a4bbb9fa3c3300a2caec4f6d6b55049a87606ea.nq.gz
    ├── 7b6869947a6150f237996380441b9e45fb17a3fb.nq.gz
    ├── 7ed0b240c6a3c6f950e14b0b6ee60ef476a5b0ae.nq.gz
    ├── 7f79f025c384fbc99959fcf1302a68df9beb80ed.nq.gz
    ├── 7facc2ef8b9a82c2359ed36b2ecbc586d605dd88.nq.gz
    ├── 80a8d1ac55ca050eb858d892bb7a5907db82e459.nq.gz
    ├── 83ea6e4b774d13f6e43fa34e672e3c4df0ca69b2.nq.gz
    ├── 8558d279f88304957982c695d26e3cfeb652e22f.nq.gz
    ├── 866b07154f27fb9bbd1693b368e6bca766364244.nq.gz
    ├── 871a41b26e81e65e159262366f7789b68f9c1984.nq.gz
    ├── 87a60c8b29c7d6fc97da32c4609928618cc03a1d.nq.gz
    ├── 87d06a45b1094f752370de264534481b6c4584ad.nq.gz
    ├── 87f7a0cefcf5105a0e2104cfef52b6fdf9ebccfd.nq.gz
    ├── 8871cf301889910199087b410b4b27a4e70a22ba.nq.gz
    ├── 887a2fffbd3ace1e77ba3359cc00c18ce80d1822.nq.gz
    ├── 889d543e9cce68b3871f54af567c2acaa2cdb5fc.nq.gz
    ├── 8a822fd65687492485c49b4700c3eb6e29851059.nq.gz
    ├── 8b137891791fe96927ad78e64b0aad7bded08bdc.nq.gz
    ├── 8b2d530864e7d02e1e1862339429795d7a84c7cb.nq.gz
    ├── 8bacae0ac70f66fe57349d16a9d76a29140bdd90.nq.gz
    ├── 8bf75e4f54b679e4efc760ba3eee3d6520c2d232.nq.gz
    ├── 8ef84b45767ee710466948b080118d690e1b4522.nq.gz
    ├── 8f10d83a5bd0aa17677c9ec9a26f2611b85f6fb9.nq.gz
    ├── 9051f8f0c347c00ea600934f375254ad89d735be.nq.gz
    ├── 91f5bffba5b386fbb21797718b212bc832d8abbe.nq.gz
    ├── 941087d517d853acf7c54dddb4f505ed07472fa4.nq.gz
    ├── 95dabf834dbbd31fffb0886e4b2734ddf1a08c0a.nq.gz
    ├── 98fa9d95554305356a5773ad43a7e2f5e4ccde8e.nq.gz
    ├── 99a3a2ba4bd16213f0c54d911a2eddc9ee3bfb34.nq.gz
    ├── 9c19db103efe370d01736a7b74d09facfd583147.nq.gz
    ├── 9cf69bb3282e6585d7e74209e585e4b7bd86ba56.nq.gz
    ├── 9cf91f4cfc01af6ecfdf88b2379ac58f23d34ce2.nq.gz
    ├── 9d2ecfb28a2d0d38b42163c0ea1bca830acc7009.nq.gz
    ├── 9e67bf3b67c4caff9115a70f73ceb2df6050cccd.nq.gz
    ├── 9ebd1427b6cba0c9850a064cf1e258f396abae12.nq.gz
    ├── 9f69cf7a6e4505717fae08087e313174528100c5.nq.gz
    ├── 9fffb86b84b83dd37394c450fc7ec6547eecdce4.nq.gz
    ├── a3a6f4795c248e041873e6e00ab1ed9be1bf02e3.nq.gz
    ├── a6373d45062ed0db2190f870a02027612d77ad86.nq.gz
    ├── a7c52972bd605957a1c20ea5e9cd240cded876dd.nq.gz
    ├── a9747c3e21b323a60ae0fbd06dcea6d92f149f35.nq.gz
    ├── aa95af872f43ea160b2697466d84e8433d68bd93.nq.gz
    ├── aaf4651a5507a00a2def40bc0adefc0df4ca3be0.nq.gz
    ├── aafb566c682cdd2f7fd9f2eb09e86aa4cf15edce.nq.gz
    ├── ab620faf762042f8aa599840d40da8dcebca258d.nq.gz
    ├── ae540e949138633b48009c1d0235e34814f6673a.nq.gz
    ├── ae94569ec8581d3e0b7420b2fefcb1cebef432d6.nq.gz
    ├── aef75b3c4f7b462fd256a44a835783125efff419.nq.gz
    ├── af15742bf19f4056e097d576c93764cffc6dde5f.nq.gz
    ├── b0e26b33789fca097332668b9a2d123593a09a8c.nq.gz
    ├── b26961ea84e35ff081a46b429ca8007486c55378.nq.gz
    ├── b271a3c07f0d5cbc14f54c2961a2f7b581dbc00b.nq.gz
    ├── b49fbd64d035e145311d0d8f637df892e8a74600.nq.gz
    ├── b4eb5b8b44264614a9fb22bc031badb56b650133.nq.gz
    ├── b53d509e9d2c076ca143a1137a0873ea1b4a28a8.nq.gz
    ├── b5776139980ea3896b8b34844e71f23695e0b038.nq.gz
    ├── bb03e8d0d551c1876c337f6f0e7a5ab253cac4ac.nq.gz
    ├── c00be33b98265fb4ce419a5ae729c6650bc0f5fe.nq.gz
    ├── c1f8b32003fa4a16e6d7132108d63406e3589e38.nq.gz
    ├── c32878271c22e23ccb12861d129ee4f4dbe172d6.nq.gz
    ├── c363ff2a3cb16554d2d1dd501b055c6f60a7de91.nq.gz
    ├── c419ec99014d408b5947b88c523135d3f8aa4e0a.nq.gz
    ├── c44b77b4e18e84611d7f52735bfc47ef10c13c3c.nq.gz
    ├── c50712aa4044b33d3e58b3cbde0256ecdb7ad859.nq.gz
    ├── c527446a720587d3fcbc2b2d493566d9802bdfda.nq.gz
    ├── c6ee7990df35d848945fdb8991ad6860725a301e.nq.gz
    ├── c7526150ef2f73e0d02bcbdbcabf233e7817e873.nq.gz
    ├── c7911a9ad58474834dd38fc5ad7fca8df37a6778.nq.gz
    ├── c7a10064c2d9ea773be0467cd40fffc5a3f9b829.nq.gz
    ├── c8cfe3959183f8e9a50f83f54cd723f2dc9c252d.nq.gz
    ├── c9ada076e19e1f257e2a69d9adbc34aed09c89ab.nq.gz
    ├── ca1c502b4385584b95fe0d8c039212ad2633ebe8.nq.gz
    ├── cb6091175c21785795dd8aba08237eafbbd55636.nq.gz
    ├── cb8527fdf9478bddb3b5f05c9a23ce72787422e5.nq.gz
    ├── ce814503b0dc598bcbc41ce2b92ba73b5d01ad27.nq.gz
    ├── ceaa3e1026a7927261a0c28f37ef1e87b2848588.nq.gz
    ├── cecc817e3af7a96430eaaa0610697da7b07c2944.nq.gz
    ├── d1cb0abc53707db6c08bc432ee2002d47b0d4625.nq.gz
    ├── d20d0c694d3e56ddfebe76f79c4c0b0a0354d17c.nq.gz
    ├── d2c4469e8bc8d72aa07f82c6b1e3d9195022c469.nq.gz
    ├── d49a6481153a7dd2744e4aaab0728fd7ff43a6f9.nq.gz
    ├── d57d668ee2d2a7aeaf8e20864fd1a0daa9146d57.nq.gz
    ├── d5fa4c061f617b75cca54391914b924d3f87b1bd.nq.gz
    ├── d9c02de12e8a8fd3ca71a54f4633bb99afce26af.nq.gz
    ├── d9f87f6b49348983d44d3bbc90707177a63de59a.nq.gz
    └── da724fd17e9b16264b9c36afaa81d4ecd34033d2.nq.gz

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

[huggingface/context-course](https://github.com/huggingface/context-course)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
