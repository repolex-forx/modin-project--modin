# Repolex Knowledge Graph of modin-project/modin

RDF knowledge graph data for [modin-project/modin](https://github.com/modin-project/modin), parsed by [repolex](https://repolex.ai).

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
rlex download modin-project/modin
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 7ca200b08597ed6ecfd2db2d08bd322f83c2cec1
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 7ca200b08597ed6ecfd2db2d08bd322f83c2cec1
│           └── chunk-001.nq.gz
└── blob
    ├── 002b7744fdd2420b9cf6206f6ce77a6e4a100b6f.nq.gz
    ├── 00a891fbe0eda2a21d41f6711e6902979be43a10.nq.gz
    ├── 010ee9e946c27282b3f994025e50c71ffecd8ebf.nq.gz
    ├── 0122f303963a77b6420bdfa49f3b302de47d98fc.nq.gz
    ├── 01cb2d274581f44109ff2c83f82ae62b93d0fefd.nq.gz
    ├── 021daea692a2a16358bb6eee3703784ca95763f8.nq.gz
    ├── 02ba21cd41490ce891d216e64a6f3773ef669725.nq.gz
    ├── 034b24bc199a5f6c4e4cf2413dc9a0683c165b76.nq.gz
    ├── 038cc600488aef8c5a19fe9161f2f09ed4d38f76.nq.gz
    ├── 03fdab1d54139b31be1226db9398453a2ea620e7.nq.gz
    ├── 052599434d707adf1a4aabde7f4e4e80d0047799.nq.gz
    ├── 0658ad77fbb5ea9f0eb86ad515f9006d9da5b13e.nq.gz
    ├── 06ca22132565adcb111afc37135c98dd8d2522b5.nq.gz
    ├── 06d8349207a794cc6b2e62a9eb8d43592a74f83a.nq.gz
    ├── 0748efb219a56f4de3e7e188320f72c453931174.nq.gz
    ├── 074cd0b095db7abd5f1bef297b47f74d14d61474.nq.gz
    ├── 08565a6cf2ec6d64456e02d84f31160321659baa.nq.gz
    ├── 094b7d057e8c1eff864cd9f038f083615941244d.nq.gz
    ├── 09710e520ced73e0290923885d8a6649f6bf367d.nq.gz
    ├── 0a80865f376acfe56d2970b475d03d95ae43e661.nq.gz
    ├── 0ae83dbaaf9530249ebf33874a66a08420db9ded.nq.gz
    ├── 0af0527064247b19ded6b594950a072006924f9b.nq.gz
    ├── 0b007470ab84d69b8f7ef9956b51ea606f662a2c.nq.gz
    ├── 0b9da2ae7dbc4e823e117e75766e84d776235d7a.nq.gz
    ├── 0ba27c6ddba17eca9e08ad8f95f8bc60bcb5fda4.nq.gz
    ├── 0ca77a9e3ef37fe3ef853487cd2ba36d38be87d7.nq.gz
    ├── 0cbedb98238fd5172e340e4fe8544a5fecb46187.nq.gz
    ├── 0cec15f07560e481d58701382d721b33786af796.nq.gz
    ├── 0cf383b538f096fe61d2712b045a9209514f9169.nq.gz
    ├── 0d307b4465002f6be24c940b7e7486774ebbc758.nq.gz
    ├── 0db119e2debf19809f309d11dffb83e8b808d54f.nq.gz
    ├── 0dba203346004af402bc70953d247b694e68892a.nq.gz
    ├── 0f2970ae62c3287c055396d78de6e844059c5a19.nq.gz
    ├── 0f3f40ef14952fa8d2fc0fddb6b3beb3f26ed406.nq.gz
    ├── 100e8b120dc5f2f1ef10372217fcfd830270338c.nq.gz
    ├── 10f452e7d235621afc51c9b158f6f294abe45479.nq.gz
    ├── 113208f3e355d36a1807d844fda713fb7d197e9c.nq.gz
    ├── 1158320ac53e1790969979ceeebb6198a7696ded.nq.gz
    ├── 11be62b68ac0b5b0058cca31c210c5b7970ef656.nq.gz
    ├── 120504b882ea76a845df33d613c0b3f22adacd76.nq.gz
    ├── 122b078257c6a55c2470153ecaf6ce28059518ee.nq.gz
    ├── 12bf8b0175658aaac04a34915064f40c990770bb.nq.gz
    ├── 1367d1dabbc078e8278147fc44462272c8c56034.nq.gz
    ├── 13bee9d4c3c51ccb996e8ab81425d91f030bb228.nq.gz
    ├── 13cfb02dd2599af926cfdb95f6ceef972a87fd16.nq.gz
    ├── 146b48a5cb20781c6e13e1bbf6e9df084e2274c4.nq.gz
    ├── 153148d879b3f23cc2f03569c643576c2aded2b1.nq.gz
    ├── 15967cc176b171bfe6e65fe950dbe7221d60d56e.nq.gz
    ├── 15df7be7106464efda56bd1c17369e62e7de8035.nq.gz
    ├── 15f873b5e67951574651edf7bfbed8e7e7334fb7.nq.gz
    ├── 16599d04d8ab43db92f935cbdb4ccb3663d8108b.nq.gz
    ├── 16e728784a688ac3c49a23691980ee0ec69fd7b9.nq.gz
    ├── 17249090cb47de6b715b7e6b70e293986b99d893.nq.gz
    ├── 181de9f3f72d950833429e8b70e403b58bf0ce06.nq.gz
    ├── 1899df8c7ab852f0e7ed2f61e54ee55914f79406.nq.gz
    ├── 190032003cbd49e57ff5fa657be159a34cabe433.nq.gz
    ├── 1902140a591dd800d4c12ed7500ac332e08945ac.nq.gz
    ├── 19da5a00467262bc4602555f1f15caa2563e9048.nq.gz
    ├── 1a6b8b173abab476fa48d990ec79a0fd6ee6f786.nq.gz
    ├── 1b17304a06b8ba72c77b4ca246d45db299c4fe1d.nq.gz
    ├── 1ba62de95ce2d67117b9903f0f8ae05b7d819636.nq.gz
    ├── 1bdb35472e76c85cf19a7689f1927abdc88a808c.nq.gz
    ├── 1c86ccb3d976c203e88c7194b8df163a4e1b08a5.nq.gz
    ├── 1d98dcfd6d6c71d5b170eff2de6b24d818dfd938.nq.gz
    ├── 1dcafe8af3fdaeb6261a31c134ea54e46787d60d.nq.gz
    ├── 1dd65599afd847c64adfa8d2e2b25cea443b6a55.nq.gz
    ├── 1e36e58207406b6673c40670c7d84396059e1311.nq.gz
    ├── 1e6029eafc3ecbbb2fdba8ef1e1f9bc1f638cb27.nq.gz
    ├── 1f82b67ef0c4fcd8882e601d601620c2106607e5.nq.gz
    ├── 1faaaca010750b61c36b92a6f7d6973d2176d892.nq.gz
    ├── 1fc106be775759892c7279a8d3fdc2e082dc95c4.nq.gz
    ├── 1fd2456af117d88bf8c93c71ea8a73303639f73d.nq.gz
    ├── 2036ae8056f35cd0572b6698bd215eb7a66466b7.nq.gz
    ├── 20c016a378021a2022d49c99609aa7aad06ef5e7.nq.gz
    ├── 213e0c9cc17bc6706f06cb2c06f6b16603c0a19b.nq.gz
    ├── 21f76f715af4c6096a86196e03d6b93650a72ff4.nq.gz
    ├── 2224a6a1ed17958948c29059aca5a50d1b32d359.nq.gz
    ├── 226479ac002b14165b3f4d61010de9debfbc01cc.nq.gz
    ├── 231e91e9203ab5d2c6aeed7191d761eeb1aa7a6a.nq.gz
    ├── 2387f08f85b5627792024e4d28eb232c057fa24f.nq.gz
    ├── 2390d8c809eea1d6587357cdad25ed4af134db32.nq.gz
    ├── 2505e7330b972c45edbf536f0dab4df03bffa5df.nq.gz
    ├── 253e20e02a22cc95d2af85cada5299a6b48ed9bc.nq.gz
    ├── 266447e1ae8e1b013810ba1a165379f6adc165c8.nq.gz
    ├── 2693b37d18f0f26b4a302d56339e78bf3db28754.nq.gz
    ├── 26bd0316e157dad1f1b5545bb78ff08842d7e63b.nq.gz
    ├── 2702149e604d0e467856c4e129f2cde37675ad0a.nq.gz
    ├── 28756e6c75903de07009d37126b554ad3a13cb5b.nq.gz
    ├── 29375f727027e638981f94af170530af4124f8d8.nq.gz
    ├── 29936c0b0f7c48bdc3a4f6df1d9eb00bd75be32f.nq.gz
    ├── 29f35ac6c170cff4120ed6d3f7b862d2a5ff5504.nq.gz
    ├── 2a942e1103dabd17959ffe9da97e3e035ccc57c3.nq.gz
    ├── 2ace6d8e41a40c7699a074ff037cbcff7299ebc0.nq.gz
    ├── 2aeee3ad2730cad862deac6b28f3097dd90f3f0e.nq.gz
    ├── 2b0a343956cc99424a668598c638ed3eb5243e5b.nq.gz
    ├── 2b186e5638b3151e3b50036b5687677c363ed07a.nq.gz
    ├── 2b1db9b044009cfd2c33e3c4f0689cbebbfabf11.nq.gz
    ├── 2bcec8b9c70c1b9c9523cdee801d216a1bf54b23.nq.gz
    ├── 2be15ea035a51d548ff4af2cc612ac91abf1d556.nq.gz
    ├── 2d5b69fcef26c2b6ffad67acd223ebcfd9978b1e.nq.gz
    ├── 2e8cc3fa9b58c982664579f661c57e4589003286.nq.gz
    ├── 2eec850865a5937cc191f4b5e1668f053490ebdd.nq.gz
    ├── 2f3a1e8bd00a277814713a078a729cc7b0aec87f.nq.gz
    ├── 2f72814fa2e2c9e4095879ca0467e077a4b9e0cc.nq.gz
    ├── 303e07ea334403e1e45d6e71180ac664b6975181.nq.gz
    ├── 308c506b7bfdcccc70730dab20215d5662eb0e70.nq.gz
    ├── 310415a4d0a96449dee488a543021de1e082aa2c.nq.gz
    ├── 327d64344f0260d0f1157590e887233edcc842d1.nq.gz
    ├── 328db54fb7e5f89d1c932cc0be1eb4d8bf4e2ff1.nq.gz
    ├── 334ca850cb47f1139adb560a548968bbad061644.nq.gz
    ├── 33532009626aecc90c9addc42fd13ff0b7355054.nq.gz
    ├── 3407698eb64a5c20184d548af195901aa0a1feba.nq.gz
    ├── 3664b4fb75119c096a1b7b6d87a600b3c438aad5.nq.gz
    ├── 3752b994136016d97ea5735f863b7dd470416acc.nq.gz
    ├── 3844fdb5ab44ddac94e2ef76552511f5eb6bc96e.nq.gz
    ├── 389176b59da6252b10d1d13824858d3e0a7fecf0.nq.gz
    ├── 38b08eb6351da12e134fdd06b65a43b56363c01f.nq.gz
    ├── 390892b48eb126f145bf58ada1281ecc52727088.nq.gz
    ├── 398edbf7f4c6a70069c75c0173e17ea02c6c8400.nq.gz
    ├── 3a6b429982ffff4686beb38996ba56415453d14f.nq.gz
    ├── 3b09ed0b87fd2223c64e54b75cacfcbcaf62adb5.nq.gz
    ├── 3b74b54caf7951561c5db47d4fd28f8bf3cfbeca.nq.gz
    ├── 3b8ba1b4fa7c5edcf6e5dfde9b3400fa93e0115f.nq.gz
    ├── 3c0d8677d20e931e6667fe9b4932b63cdd014691.nq.gz
    ├── 3cd3e979c1be792d53f0413704917d24ac09a472.nq.gz
    ├── 3d10b3966dc09a55979e70efa06f7c67a0d62aef.nq.gz
    ├── 3eb4591aa9752f35ae6f476d3fa7e1e8920a167f.nq.gz
    ├── 3ee0cb806afb685d9c379d235ce950192cba8de2.nq.gz
    ├── 3f18229e769d0ba45638e38afa42eb75fbccca11.nq.gz
    ├── 3f3299e50a008d81e79d38207b4705ab0662fc3e.nq.gz
    ├── 40e341aeb6106175429276290c3ecdcb6e1fe3fb.nq.gz
    ├── 412ef5e3089714be5342a20408b4d9d241723296.nq.gz
    ├── 4178c6b8188d36322cb0e6e57f81ffd602b63b14.nq.gz
    ├── 423724bd0818185871cc8902a3627e00c6e3999c.nq.gz
    ├── 4296cb97859ed1fb1205b08250983cf1128c65db.nq.gz
    ├── 42e4eaef42d5e34700f27a5cf6143a504eeaf30a.nq.gz
    ├── 4338b43a5fb8ab22f1bb65a9df441ff19a090996.nq.gz
    ├── 435ba39d60bb6aadb7ac231ffb55ee59d43afd85.nq.gz
    ├── 43ce6cbccb95016951b12fd9997aa27c72e1904a.nq.gz
    ├── 4449cb72aa747f12ba084bfa0baf3d3b1306b835.nq.gz
    ├── 445ccb3f9e669ed1c9e636d11c679e22d1ff4200.nq.gz
    ├── 446e4c1c52979503e3372f00e1c91c27e01d25c4.nq.gz
    ├── 4484f5f0f4ef239150ba02d27c658caad6d34445.nq.gz
    ├── 448e82150c2329ed4514e3f3e8b9d570a3dc34b7.nq.gz
    ├── 45743da5b4ea5337decb239546d35cbbda0bd468.nq.gz
    ├── 45e08b4f1a667a69c151063b0a29804f651cc123.nq.gz
    ├── 462299bc6a952a38e360592c3f10799dad8481a0.nq.gz
    ├── 46a9faa461df99ad360f7702a7ff6332d07dd809.nq.gz
    ├── 475edd2fe802311b85967b4acfb401a60962d737.nq.gz
    ├── 4874b9251f1340be5b36e28c1cb472ce76f32c34.nq.gz
    ├── 4882106e696f85c5f7099dc1561660cd41a7f712.nq.gz
    ├── 48b8c759233afc6657b06b84bc1cd73a3ca5ca17.nq.gz
    ├── 48cacb8f21b90a3e06f9f2b907e48727ecc3f422.nq.gz
    ├── 4989e847c61ea2a16b59a1c51c242f0ea5c6e9f3.nq.gz
    ├── 49ca2a96468853a9f4424cbf980b63e7f70ea3b9.nq.gz
    ├── 49ee410ff143b8b85eed6c0f0e95dd39c53a24fe.nq.gz
    ├── 4a61d7f4833b261b7efb51585ceb85c384306865.nq.gz
    ├── 4a93c5551d8651e7835500e26959b73a7af33243.nq.gz
    ├── 4adb88c5e19a9b81886f5e6b1a4361613b9e653b.nq.gz
    ├── 4b51eccd13b047128a9cc5f6d8447df510935ca5.nq.gz
    ├── 4c24e9325d7ac1bb13250bddc32270547b823fcf.nq.gz
    ├── 4c9a8b821b075911209b0ad91dcd36281eaf4797.nq.gz
    ├── 4d598e6cfa2ca18998055f49c7e99d6efc56148d.nq.gz
    ├── 4f9839be5130e4fd43162b81e22cec5ea67a2e4f.nq.gz
    ├── 4fcbddbb7e7f19aa3b8c4383f3183c5d1374c68a.nq.gz
    ├── 4fe88ac3c9b835bde574413cde8f6d410db391e2.nq.gz
    ├── 506501d0637e4680e5ac46d645b5422d8f850d53.nq.gz
    ├── 506896d42c8d0adf0ec6f2555e40f2660fdd3f19.nq.gz
    ├── 507bb21d0e3c60685b5c1d0a415171538db44252.nq.gz
    ├── 50ec0c1f6b83058261718c6fc34f287724d0c857.nq.gz
    ├── 51bf90136a5155126810faa1cc753c9889af6d57.nq.gz
    ├── 51cedb23609dd62787ccc2f234c1f8e38a461351.nq.gz
    ├── 5261a2c45cf627d795b16290e54224c181f53e6c.nq.gz
    ├── 52c354146c82d0cb08556719293327ad849d9587.nq.gz
    ├── 52ed7c2cd6f777c4614e0e0258d0c519195eb0d0.nq.gz
    ├── 531ee15f48ee284af498e7c557f95fab4fd95634.nq.gz
    ├── 5344e31f77cb588f4bb6b0733049e9f61aa70a6e.nq.gz
    ├── 5368e8d7121b5a349690fac3e7c7c47e4acd46ce.nq.gz
    ├── 53d7ebcde366468c44c021fc1b2c133b268a1053.nq.gz
    ├── 53eebda2bbac361777d4aa69fe877ed7be8a8484.nq.gz
    ├── 557a0d1c3ae7ad189ccf40a9244e6530ae8c1c57.nq.gz
    ├── 5581791382467624e8c64dc8990799103fcf77aa.nq.gz
    ├── 558ab4457950e2ef80ea56f333b58b2c1a565ef9.nq.gz
    ├── 55e522da1202043912716f9bacb07b7be980d17d.nq.gz
    ├── 55fa09677151c9215680fbea9de1db04786cf7ad.nq.gz
    ├── 57617d5919def46f01a20d65e71c8566d7fcf704.nq.gz
    ├── 57e11b45ea6b4aafc7790f5c778a43fea3350e1b.nq.gz
    ├── 594c8c78aedf7d393725107cc8ec9400ae145a51.nq.gz
    ├── 596deecd4f04015d7d8861d7d129c243ffff4e8a.nq.gz
    ├── 5aa9c29e910d2293d6e29fefe474701086f6fb7a.nq.gz
    ├── 5b97d14e4627cc84e38cb941ad729e2ba46c9d59.nq.gz
    ├── 5bc51cd24fc7478989e6a9157ec919a3b82d9bfb.nq.gz
    ├── 5c58b1e0623478339739ca2079db514a1cd7eeeb.nq.gz
    ├── 5ce4d52d58f502cd530c2c0c8b469f90e2ed8b1f.nq.gz
    ├── 5ded813f50a843e38abda313bbce59754013246a.nq.gz
    ├── 5ef1d30a2b266bfa7c98a7986729c25e8c9135bf.nq.gz
    ├── 5f103f66d779cf0c976842b5290a05d4a17d8358.nq.gz
    └── 5f2189b47d21f3d1face359c5fdff697683ac52a.nq.gz

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

[modin-project/modin](https://github.com/modin-project/modin)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
