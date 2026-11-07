# Repolex Knowledge Graph of ansible-collections/community.vmware

RDF knowledge graph data for [ansible-collections/community.vmware](https://github.com/ansible-collections/community.vmware), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/community.vmware
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d554084c3012cde02daeae62892232fabdf259ec
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d554084c3012cde02daeae62892232fabdf259ec
│           └── chunk-001.nq.gz
└── blob
    ├── 00f14d3428667486df133ef6e09e4e6b33d4e441.nq.gz
    ├── 0119d33eb02f935c191485c359621daae87c7305.nq.gz
    ├── 01a17d2921aff6bfc09b1621c68005a096ac9db5.nq.gz
    ├── 0298cfafb273def75d6afc2ef62c60fe8161a229.nq.gz
    ├── 039378f23244220f31fce074f8684f837e8138b4.nq.gz
    ├── 041c5ee067dd7acf50165e597556f93bfc5d13e5.nq.gz
    ├── 042d4ef3bdecbc5a031cc4c7002dc999998f4195.nq.gz
    ├── 043b4fc36fd244ef3f7825424b6fab4f8ebc3e5b.nq.gz
    ├── 04690fb598db6536bb8aeadf650c39ad2eb023fb.nq.gz
    ├── 0499b9980a620605fc44d35ef797049114d558f9.nq.gz
    ├── 052b27c648372f0c4aa4dbb16de0f9689fac8721.nq.gz
    ├── 054ddf72848c31fa912b846cdae90f62507520c3.nq.gz
    ├── 05afef6c0c178fce459fd8562ee39741ccdde9b2.nq.gz
    ├── 05b3950feaa97c14ebc21532b3b91e58ea37fb10.nq.gz
    ├── 0608bf27e298399b67a0ab8c5ee2a823cae008e1.nq.gz
    ├── 0633c38282393b5f0be1e49a85e268a12d92d8cc.nq.gz
    ├── 07d9f37d5bb7638bae5adee98cb70b72b0522f61.nq.gz
    ├── 07e8732a30fe2369b693d6f07ba4fa6c70e65ba1.nq.gz
    ├── 086bf03991bdafac978b076a798521f3a9c72c12.nq.gz
    ├── 09b7b0655dade575714dbdd06bf23d822bd58496.nq.gz
    ├── 0a076624ef705214633d3f73aceecad2a850d07a.nq.gz
    ├── 0a9d1acea6e1cde346ac7b09ac2b507a2588f1d4.nq.gz
    ├── 0b3c3f10bce38cd4b3d900478ca331533ec5a752.nq.gz
    ├── 0bb24023d60245114479c3139386778b37304622.nq.gz
    ├── 0bbefc96f7fa44b2202c1d48741431892b3a56e3.nq.gz
    ├── 0c156bf12e28d28c60c2f1ae7ab32c50051c9118.nq.gz
    ├── 0c6a2156c72b6a129d288c178dde6e96d44f5e35.nq.gz
    ├── 0cbd9f08cab329e021531cee6fd9798dbbe74a9a.nq.gz
    ├── 0d017ea053afbc68bb44bd0171a7dc27d483e72d.nq.gz
    ├── 0d589d8c94e656576f4f61b66f5558d448b8fd0c.nq.gz
    ├── 0dad050e76cbaf3b14e68b6d9737a0d87bc01e40.nq.gz
    ├── 0e6b00158946679721efe74ee953f30318112867.nq.gz
    ├── 104363fedd7c4bb7caa38a7e35801f0cd8d263e4.nq.gz
    ├── 105364722dfba79d3536d447531921fd0ea0cc69.nq.gz
    ├── 10926e87f113fb026c366866d6fa466061562870.nq.gz
    ├── 109f4dcfb2f165424957406db09b65fc6651c7f9.nq.gz
    ├── 10c78f6e5583269ffef6ff22275169bb6101ccfa.nq.gz
    ├── 120bf5b362d72f40c629f21fa41a35d5591659a1.nq.gz
    ├── 120fc9e56fc21b305c3a2899dfad957dc31777cc.nq.gz
    ├── 128f7a37fe9f5008950f86cd393564ccf831b3ff.nq.gz
    ├── 13276bdefb2f610b8c852be29efe47c7cef60495.nq.gz
    ├── 138021f77f93bf7aedbe8ad4d784867e7a8b5aad.nq.gz
    ├── 13abb2da36660507917a2056759f7c396c30b0c6.nq.gz
    ├── 14c9c5d0168142862e5a17835b114d7878f444b3.nq.gz
    ├── 16c7c0f2d5c8e44ffab96de85f25a1c2c5ff8485.nq.gz
    ├── 16f14ac66a0d92e62c7b26956744f272b101f900.nq.gz
    ├── 173508da31217f1e8a8bd151ab3d0d2905a21563.nq.gz
    ├── 17e3cd81902c4dfe9497d5f4924cb4355de8af15.nq.gz
    ├── 19236c5b499ad5dbf61d9f2c4cc932cad7d859ff.nq.gz
    ├── 1977a0157924a9b14672aefdef0cd7c30859339a.nq.gz
    ├── 1a0a3240b7e5460f41b722e8290a90d0b4788c67.nq.gz
    ├── 1a335f42d25b67143ed73d304b80475e2e16225b.nq.gz
    ├── 1a854af577dcb38e9744ef031b0d5ab56ad0394d.nq.gz
    ├── 1abfff23db8a3ebb14bae05fe29bf4787b830a62.nq.gz
    ├── 1b3bbbe1b09938e750c6606ac387bbe1f22c3ae0.nq.gz
    ├── 1bb7cd4bf53e0fdb459f71b1b069dfef069324e3.nq.gz
    ├── 1c2694d226b2d9e474aa27fe00f489cfb4ae160f.nq.gz
    ├── 1c5cd64c87e7f761e4a72cc26b79dc128bc5021d.nq.gz
    ├── 1c783e4ac092e37f55e80b6e8677b04629026d0b.nq.gz
    ├── 1d37af0067baf92d4d1ac246e7086ec813ebe969.nq.gz
    ├── 1da2aa1f14a8086c972c09fa52c1f4e7410a4567.nq.gz
    ├── 1dd8be43497695887558802b54be668360d46687.nq.gz
    ├── 1ddfbec218dcaae5ab58412c8846590cd460c424.nq.gz
    ├── 1eea226def96876251d6f8fd7c620a28f06acc3e.nq.gz
    ├── 1f77cff167b1feb232450b7fdb5c7f7c763e8712.nq.gz
    ├── 1fb452c43a6b24ff1674f25fe1e9c97028085784.nq.gz
    ├── 208889bf1cc131c3c059b937d8db730abffd4744.nq.gz
    ├── 208f1431776c2712a1935681ffea3b836d932f41.nq.gz
    ├── 20b146bc084a98408ac4922f306acd3ceb6a93b7.nq.gz
    ├── 210dfc4cb7313f894cb0f429ea11e6cad2533e99.nq.gz
    ├── 21619746814906bf9fbe7de655410ce8b2222301.nq.gz
    ├── 216a8573dd044b2e94d1cfc181cb42e3ac6149ac.nq.gz
    ├── 22260ffb3d0f1307d9e9a6512144808ed868cf49.nq.gz
    ├── 23c24206280b282b983405cb53099fe537fd3716.nq.gz
    ├── 23c4eceb600c142de77356c912c8b68aeed44b83.nq.gz
    ├── 23d35a9c890c3a365e5f64768773c0546989885c.nq.gz
    ├── 26767ae2e3f2e2a3559d66662458c796f1d2d016.nq.gz
    ├── 26793cd6fba85632a57bb77704e128d1cf7c9e96.nq.gz
    ├── 271a32b80c07f42ca97912d18986c8616a7f12a3.nq.gz
    ├── 2896c01c3dd57f0ba0eb7ac68151d8a58ae17363.nq.gz
    ├── 28ceae442d87403acc58c99b05bef08c385e4323.nq.gz
    ├── 29378cf28f60af7c9e2eb50dbcbe8413c6e7090f.nq.gz
    ├── 294d9abbffaf5795436627db8f8428bdb8391ed8.nq.gz
    ├── 29a70aad2397ee3b4ded8ac13c5b46d74ab54ae8.nq.gz
    ├── 2a5d76551b5dff4c97c8c3a13832527c3c74ed79.nq.gz
    ├── 2b2b39285ee224d413d8fa3ef934499be28fc526.nq.gz
    ├── 2d1ca980126bbbc3cd0a6b12e1223ee9ac691213.nq.gz
    ├── 2dcc6782755b25906ab3e805e3ffa54bdf54fc10.nq.gz
    ├── 2f76016296a66567d5f180cf0ace8d3818f981c5.nq.gz
    ├── 307fd1faa9367d26749d300947622aca5587e833.nq.gz
    ├── 31b495c0f4a7bcb8ae53dfc32fe36f42d0efae11.nq.gz
    ├── 32254f8d2c22a7b0f974d49bc680af7c7d551b93.nq.gz
    ├── 329eae16adf76bc09ffacbab5a03058795d16c03.nq.gz
    ├── 330f32264c3d52c3a45f3ce67d2fc5f1f9d39a48.nq.gz
    ├── 33941df9561bbcc67f14e53db460d061b49be49f.nq.gz
    ├── 36406f61242263932d330727c0602a680381bbc1.nq.gz
    ├── 367481497eb1497f4c00e24f08aac7dd3f3ce354.nq.gz
    ├── 36ac588e1ac6946455d6bcb5ee2bc721d8a59a52.nq.gz
    ├── 3715ab65c7da0c6653014b09e3837308cfee811f.nq.gz
    ├── 381cca03b89235166a0151a5fd0464d303b180c9.nq.gz
    ├── 396be3b643cd5679dddae12270cc4244feeac84d.nq.gz
    ├── 39ea00a0dcc42cd2da968197a35a2c43700ceb7d.nq.gz
    ├── 3a57a0ba02952aede5df9ef5561425b7035468a0.nq.gz
    ├── 3a74e2c94dd4e69b4a080f61955c71a81838755a.nq.gz
    ├── 3aa96625e883b72cbdda3fe19f203eeb0c281660.nq.gz
    ├── 3b7ae0afb0e3600a54f923e3226ce0298ddf96fa.nq.gz
    ├── 3d4f74ee3c03f44a92b263729817f8d14131fb59.nq.gz
    ├── 3d7e1f938e53b7251e8b56439ece14063b38bf05.nq.gz
    ├── 3e6586c97945a55d4bee0e6118bc2c475910c5d9.nq.gz
    ├── 3eeab3c350cdb94191dfb30c4006b44f37131b48.nq.gz
    ├── 3efb53f402e02f1d1a8a7e01856922d1e63a0d6d.nq.gz
    ├── 3f096b4cac553042cae343abd657b5cf40fbc539.nq.gz
    ├── 3f3d08a49c2bde2b3b2b77cf61afcdbad8e52f6b.nq.gz
    ├── 3f8a3477790469b8528fad3a2506a006eb75bdfc.nq.gz
    ├── 3fd30c9ffaadb01c9a4a298bb1ba2d604b656116.nq.gz
    ├── 400a99878a5f215cc9a873bcca22698092f7041f.nq.gz
    ├── 4251bd5514976bf4816a0a18b0d5468ea66bd655.nq.gz
    ├── 42dee5555fd944eecde4598d7e9c4a90e614b482.nq.gz
    ├── 4301879746081c3f9b8c8280ef9ede123abfec7e.nq.gz
    ├── 439405de7b03375c735108f8bafe09ae5814a7e1.nq.gz
    ├── 443392133927bff92723afc20c0bcf204e301f47.nq.gz
    ├── 45e94331f9b3be7834c0dc0fe10cab2cfe00109a.nq.gz
    ├── 478d5b18f329a5ea986817f08525fd1981ae407f.nq.gz
    ├── 47aaf0d8cb5f443d609d554568bc3eae388e7b3e.nq.gz
    ├── 483391ecdae47989d2f440947ac8ab1eecf327c9.nq.gz
    ├── 49de53ae7180f49b477c8f9febfb3bce95bef958.nq.gz
    ├── 4a8abdec436d8f51c19a967a2992f8066c9d3681.nq.gz
    ├── 4aaabc421a0857e6af5ee5491a6700feb0c54305.nq.gz
    ├── 4bde04c2888ef2e07e19460add0473393b237861.nq.gz
    ├── 4c0fe56348b7178b886dbbb56f2a772983544ebf.nq.gz
    ├── 4cb20dbe2f947ff8463dd33a379b66108cad445f.nq.gz
    ├── 4d21d84c54b50bf52824af979de5795518d04068.nq.gz
    ├── 4d4cf96cb96eb9c7d2f3c54ad6e909376ab96bfd.nq.gz
    ├── 4d6f8399610000390c4011b40f00d842eb5d0b55.nq.gz
    ├── 4dba790c9a0c5eb282d3332979462037c5c798ec.nq.gz
    ├── 4ded94b2743e75b359cb595ff002d6b0516cb4f4.nq.gz
    ├── 4e0699a7078d85cf4277b18d9ebb4494dabc5507.nq.gz
    ├── 4e45cc934b42862e573906c2d043fdedaae6e3b3.nq.gz
    ├── 4e4af6be59945e1c8814d7fd88e42d90653205d6.nq.gz
    ├── 4e8cc20dcc4fb429d2a469baf1cb36d3d2a067e1.nq.gz
    ├── 4eeb11cf55e29bb2cc95b5512fe96066e6fcb04d.nq.gz
    ├── 4f699379839023745466c5f380903a08ee21306e.nq.gz
    ├── 4fbeff74fc2c3e0ebad23f6bc730b98d023e49ab.nq.gz
    ├── 4ffaec317e5547f3d19d0da01765d9cdec5ef499.nq.gz
    ├── 50566cad083e64a6383ee6641fc3169972b3668f.nq.gz
    ├── 51db56b12bffd7fe9c8ea5461837e73304f5b282.nq.gz
    ├── 5241b98a49c3b228d623cb863f22f3ff9ad14149.nq.gz
    ├── 52fff585dbfe14b56b0951c1e23217998e02ffca.nq.gz
    ├── 53a6fe6f4bb86cc43905585003517241b757322c.nq.gz
    ├── 540c6cafc900d69b2504e86615416f115cd7da31.nq.gz
    ├── 5529a8a8ada1bb32d1e540d0c1ca63981367d5a2.nq.gz
    ├── 567692a044deaf1fa570e10590318e12951b58bb.nq.gz
    ├── 58560b5619f786691c01c106de51a510a7a70121.nq.gz
    ├── 5a74c9fe07281c585322d4c4e3ea4e70f1ccad7d.nq.gz
    ├── 5a88b24ef5f1fd7dfd0d2c98b347063224bb81d9.nq.gz
    ├── 5ab20d06af20ec264a10ebe7b5e3e78763510275.nq.gz
    ├── 5b69c45d8f58253b3e28898b01dec4b5ddf40bfb.nq.gz
    ├── 5b7dac53a1d3e429a46a5a451e576544e95540b1.nq.gz
    ├── 5bda522eddf8064e500961d5a8e20b35cb826e02.nq.gz
    ├── 5c4e18fbf9f9a5df3ac9606e99b5147f94d8e572.nq.gz
    ├── 5c858049e1328598bec88e42ad7723c1748f12bd.nq.gz
    ├── 5d9a66aa4939c1535252d35d5306cf7d471ea2bf.nq.gz
    ├── 5e13458885f655dadc0bdc7bb8e0d435e1685343.nq.gz
    ├── 5f993f44bc4bc47105739ceed28f169c7136d5f8.nq.gz
    ├── 5fbc7797391be0953268bd7d26b27301ebccd829.nq.gz
    ├── 60dd2bd9bb0c1a29e9c6389bf7fec52c7cd00de3.nq.gz
    ├── 61d3ffe4f9416869d4fff5118f784dd567977025.nq.gz
    ├── 61eb6ed96fe356fb35fb8d064c756303269fb0e3.nq.gz
    ├── 62aad771f22fbf236630e48259f74541a4378f34.nq.gz
    ├── 630fe4d70aa07cf5517e9f812c46dfae94225c9c.nq.gz
    ├── 6311cdbcba53e816621a6721cae9b6b0fadc181c.nq.gz
    ├── 6332ce5287750cf0e58f1a959281d9fb6bfcd7d0.nq.gz
    ├── 63ab7e741e97b3b098ca554888445eb1c30e5903.nq.gz
    ├── 64c12be57664e3105b3e5aef3f1aba4eabc11c64.nq.gz
    ├── 64de8cf340f21edee6231e8df9264962293f3a68.nq.gz
    ├── 6513df6b96c2618b91b067215f8ef1b909f6e086.nq.gz
    ├── 654aec541bf11a72976fb54546e7420de5b7a82b.nq.gz
    ├── 65d2ead8b4d988c1c5a441432a952d9e4ad59746.nq.gz
    ├── 6655325edb83d1cd3b6bf28ccf8fe12b100bd389.nq.gz
    ├── 67e4df30b78267ae0b64636684a2b626ceeafc04.nq.gz
    ├── 6810e04e32878215c32b2039277d4b1809f4de4a.nq.gz
    ├── 6b0203b4ac7bb98b5d0706eec8fada933fc63a4c.nq.gz
    ├── 6bf6a37109285eb82023782e150be015e32dfbeb.nq.gz
    ├── 6c7b955f7f96a4f370fbd817b8e4933b93421d0e.nq.gz
    ├── 6ca52cef0155e18e876567dafdec598125fdbcd4.nq.gz
    ├── 6d2b09299c88c2de8538b297d00a5dd1901270b9.nq.gz
    ├── 6e28d7d741022b7761bd47bf1f573a7f8992768b.nq.gz
    ├── 6f2b4c1836e0db214ae9b3f0cc4ab82c0917d348.nq.gz
    ├── 6f9488a09f8fa6ad92c62512e4b10233edbabbd9.nq.gz
    ├── 6ff9d522d2855b8f41d36929b4bbff3d6ef1d456.nq.gz
    ├── 707a7cebd5535091aca2774121083d60587ded2f.nq.gz
    ├── 70b0d3f4c25a062dfd8d10fe9a5fe1144706425f.nq.gz
    ├── 70d60198c9e230ce000b443e825e54811cfd7e71.nq.gz
    ├── 70e75991a4aa77cb931e85e6e151111ec22789fa.nq.gz
    ├── 726e06a2f696499ae4ec5521eb1fa2670be4c40a.nq.gz
    ├── 7334a97644e41a1e0490c8702976b54cf9b272b8.nq.gz
    ├── 73758966f478a42e498bcb902fa9b9477264895c.nq.gz
    └── 743d8940d75d8929d12eeca3c98e8f60d9169808.nq.gz

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

[ansible-collections/community.vmware](https://github.com/ansible-collections/community.vmware)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
