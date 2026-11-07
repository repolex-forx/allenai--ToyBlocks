# Repolex Knowledge Graph of allenai/ToyBlocks

RDF knowledge graph data for [allenai/ToyBlocks](https://github.com/allenai/ToyBlocks), parsed by [repolex](https://repolex.ai).

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
rlex download allenai/ToyBlocks
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 931fd7aab1458fd58f4c23d810879ea4826b07d8
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 931fd7aab1458fd58f4c23d810879ea4826b07d8
│           └── chunk-001.nq.gz
└── blob
    ├── 000ee58dd70c14875580468083aa8e59f0b95f21.nq.gz
    ├── 0050da44519ae5732ee60ef3a4d1a70df39b1734.nq.gz
    ├── 0060ec570c60f5f73b96eadb1e162a3bc852c2cc.nq.gz
    ├── 00c8ba70a53d258c9266892052e773c3b2315495.nq.gz
    ├── 0112e4d742b25ea81f68a9e0d60e34a6174a58da.nq.gz
    ├── 011d0c44a0e69f76de096b3fb9def6250fe6fbf0.nq.gz
    ├── 01510e6edc8f7990a5c4e3ac9adef04d9a990889.nq.gz
    ├── 01d3046bc99f320aaedd1250e9cbbf46f1a270bd.nq.gz
    ├── 022c1247d2fb7ac05dab7192ed86e0cc593cdcbf.nq.gz
    ├── 02be7d271d007ee8064a7e3ac9047268e5f4338e.nq.gz
    ├── 02bf3f347acb4ce349ed4d8bc5591feab7563b44.nq.gz
    ├── 0346c7f0fc73b243cfbf947b4dcbfb9ff802fb18.nq.gz
    ├── 034a5e7070b1ee1f4383f0ba34954eb2f84272ef.nq.gz
    ├── 039387c4be6cad5278550126a3a127171939819e.nq.gz
    ├── 03a8dd7a7cc66587f6b98ed42b88b79176e16bb1.nq.gz
    ├── 043ba59535d1bee345504f9b2baa91606c8429db.nq.gz
    ├── 052fbc0bd6b2c7b44ee7c27e60aedae882088425.nq.gz
    ├── 0552bfa85a18bf1c9256e400454dfbaf69b2fc7a.nq.gz
    ├── 063bd755759af9c1c86de7451ae2c4af6848a1fe.nq.gz
    ├── 07bd26f7eb0982e7a82bdbfc25aa7da2b08fc326.nq.gz
    ├── 08d012c6fef912269bd3d2f1459b22cfb2fe6e0d.nq.gz
    ├── 0903ea7377b8b441f2d85fc0d0682a6c5847f760.nq.gz
    ├── 09a8225e47955ec6fcca56b09b9b7233f0daa3b0.nq.gz
    ├── 09c40108a7a287d1a6e324ffdfd627f854fcca6f.nq.gz
    ├── 09ee3c1c73f062665f3a3809f8ed5030c55abe93.nq.gz
    ├── 0a1a407cf08ed1d035e9876062242b29a6edccb2.nq.gz
    ├── 0a270d0a1c981c88089a021a37ca3b48cb3f464f.nq.gz
    ├── 0a86b767a8fb5da8cba57d3e088900ea1f684d85.nq.gz
    ├── 0a8ea6d51855c2e9dafa7b8e738289f66da7135e.nq.gz
    ├── 0abf19ef8733d289d7a74b93a8606847d9955c64.nq.gz
    ├── 0acc35d67d4483804ced217c42bb641089733e56.nq.gz
    ├── 0afbb0b71683beaef5e751faebe5fdbca4757bab.nq.gz
    ├── 0bf732a1445094ea2bde6107145b1eab47af8350.nq.gz
    ├── 0daf2b9e7f3f45ff71d3e568b188546ac49c7886.nq.gz
    ├── 0e09f6952755b5b8ca9c5fa75d64edf0425adc36.nq.gz
    ├── 0e10b98f46247c1720eba25138508a17aceba960.nq.gz
    ├── 0f30e0cbf2b406032b1b990a8a93af9c637ee40b.nq.gz
    ├── 0f4aa142b322aec22a8fee4aed2b1022cc2bf945.nq.gz
    ├── 0ff7ecea3a7e7ef044c7ad613d28478bf8fe98ec.nq.gz
    ├── 1145117220b13fdd3ea43f9c10116cafde31ebff.nq.gz
    ├── 11e941244bb8f517dd9353dc62865b615314560e.nq.gz
    ├── 12e59370a507115bbec1abe0078fb1b43cf5880a.nq.gz
    ├── 1350c46b211f01b9b5ba061489c8a60dbae71c16.nq.gz
    ├── 13784c852841227ee4284e2b657fea65001a7e00.nq.gz
    ├── 138711b4a9c36adb416ce93630da5162b7796f6e.nq.gz
    ├── 13c4fbb476dc2b85fe7ecf0c2a5339477e197305.nq.gz
    ├── 14111c2a7f3a15ccb98f2b4d0115af30d48ed044.nq.gz
    ├── 14ef78cfba87c5becb67c2b0f420267313214657.nq.gz
    ├── 158e7806a08a0683ec27c74e06b2ad07bcaff3c8.nq.gz
    ├── 160f63af677362610d043f9f10a28e735e6dbf1a.nq.gz
    ├── 169d5c5b4667debcdb36d5e0ca09a4db29749ff5.nq.gz
    ├── 171494eb1df4c8d9be7d2e535c326cdb88561b49.nq.gz
    ├── 17ac5e1cf509e9149bc93ad9306ced1eec4b36eb.nq.gz
    ├── 17f7f74c6de88fb987226edc62b54eb5ccb01d9c.nq.gz
    ├── 17fb9564a54b3af0304163ee90712534c5d00e05.nq.gz
    ├── 184f3f1f95cd9086861893fec8a0f50a2bf8a9e9.nq.gz
    ├── 185ade7b9f18a89a22ec5a1487af3bbc3b24a365.nq.gz
    ├── 1881e9feb3abd4df6527d31830352172fb84118b.nq.gz
    ├── 18aabda03baacf6b06b378117e637c77c54cd6e0.nq.gz
    ├── 19f8dfcbc7194e666ace5daacdbc54fc00db9abe.nq.gz
    ├── 1a3f04ad02bd4a4631791913d2f9363880da7abe.nq.gz
    ├── 1a42a772260b37c51c246167b1da15bba700b0ec.nq.gz
    ├── 1abcb4a9bce63a22adfdb7aeb6be2f60b0566609.nq.gz
    ├── 1b5557c69b559fc7f28a5befbff33f5044bb2088.nq.gz
    ├── 1dc834ffefd081f21dd977ea930a30017ac7e38b.nq.gz
    ├── 1dc93373ebaaac348a28b0e8121d0a44ac01ddac.nq.gz
    ├── 1e609fae7ebdc2ee2cec39bd6666be1ca17b16d1.nq.gz
    ├── 1eea971c3ccee7b16a6d7a1bca64202bdb78f64f.nq.gz
    ├── 1f440d37c9d939caee8cdfba708d46382d7f260d.nq.gz
    ├── 2074845a911a23c953012bfb30f574b82f70e6e0.nq.gz
    ├── 20a23b34a01f2eff5ed72f00967555b2a3aee6d3.nq.gz
    ├── 20daee6c9c65b8a24ab03000862e8bea551379b5.nq.gz
    ├── 20fe06c81f12cb94bf2976c316382ea56de8ce27.nq.gz
    ├── 2103b4b7b43c63dbad3c0d5c5dd8a0ea31b1408b.nq.gz
    ├── 226c2f8d0befc53e786b0762e102f5d400284b62.nq.gz
    ├── 22c7bebf1956199b591f1ce17d66410ac0c17b64.nq.gz
    ├── 22d7388a7f049dc8c0f95da3d84d2ae623605035.nq.gz
    ├── 2319b0fe0b28b52e1aa6f0128c3d85706567599b.nq.gz
    ├── 2377984d68194d5a19fffaaa4241fc3e0e5574ef.nq.gz
    ├── 239d9d6c959c5ec9f32d89015322ef196914e734.nq.gz
    ├── 24599cc86f506866fecfd299708d6f0f6b3ee31f.nq.gz
    ├── 246712cac9df84b5456761b95993ef45050cb76f.nq.gz
    ├── 262f1b3a5a5d0f09220d7e9b6dac26c1b9c2c483.nq.gz
    ├── 26bd3fba9295a94aaca7d63c17ab16704a3ccaf5.nq.gz
    ├── 273e90597587dbad302b815383d375b25566a483.nq.gz
    ├── 2900be8cef0dde5743ee2a6bd8e2b0186a2f7a8c.nq.gz
    ├── 2986a0f898ddebb8748a126428184351392dbaf6.nq.gz
    ├── 29f7955bbbe9d458e47d940ebe1c41aa71e266ae.nq.gz
    ├── 2a00e21d103beddb529f496004136d0bfd8eeb50.nq.gz
    ├── 2a1cc15d6185388fa634593ee715bb34729901fc.nq.gz
    ├── 2a8c221d3a6f526bb3fe01afd0254688825d0347.nq.gz
    ├── 2be0af9cb0e841cbc92b6a17de4f943e159da007.nq.gz
    ├── 2c48489862097b0ce70d5a864f61e1356cd21979.nq.gz
    ├── 2d1ad15fc58d9d1a99948a80ecabaa5884000bf0.nq.gz
    ├── 2d8f3d70da066f3f76056f968873dacb79baf6dd.nq.gz
    ├── 2de25480dc820ad1bb2c3def3ad018ceb829cc9a.nq.gz
    ├── 2e34de9238441393febaf84a3d50f37d9d5d6284.nq.gz
    ├── 2ea3c64411c65b63bb8012d109987540bfb535f6.nq.gz
    ├── 2ed31f254a08a2444adc1a8bb7c5687d53e554e4.nq.gz
    ├── 2fa291fb392c6eac00149b507ce1bc086d37a241.nq.gz
    ├── 2fdf7bd21d6b45c191648d9058113b7cae3d7ca0.nq.gz
    ├── 30451bb04843e1790048b3f5caee083306002fef.nq.gz
    ├── 306c9c59d88626acd349edcdb47d616f4cf804c9.nq.gz
    ├── 307bb331c6d17e95f8160e621799656e8ec7996a.nq.gz
    ├── 30f96810f9cc87124abab2489876952c6040c53a.nq.gz
    ├── 314ba38899a2046a92e3a1f9485187cff10f9478.nq.gz
    ├── 3247ed0f961271445702ce383f0fc5fd93582fd9.nq.gz
    ├── 32aa478b35d620191d33cc8620107486b77d3d72.nq.gz
    ├── 345bc70f90b99d9f4911497a25dd1abab9c705c8.nq.gz
    ├── 35a0abb89589971b44338705c5bb26b0639aafde.nq.gz
    ├── 35ad9f32e87835e08332ada37edb8aea13e67a97.nq.gz
    ├── 35d5628dd1296f89cd76aaaeab62516125dc669a.nq.gz
    ├── 360074f792aa848dc8c1d8d06172011deded1f1d.nq.gz
    ├── 367de51e12d8d10109df4426d32e159eded47f57.nq.gz
    ├── 36f525196458a09ab8ecc1804373d160b80fde6d.nq.gz
    ├── 36f9ec828392e5707bcf6f1c023a60162ff5d204.nq.gz
    ├── 37719a461358477ed73f1a82570e3af9443b6974.nq.gz
    ├── 37c5b79a847077e27fb7da11c942cc56a529d139.nq.gz
    ├── 37d77aa863248b3a74975f52a1cc5d2d5e504373.nq.gz
    ├── 384d75298ec19c37286c46c5166261424eaaed50.nq.gz
    ├── 39bca2aeb17f260a6e89440f12be568f38ac71c7.nq.gz
    ├── 39c89c122dec160237d1b31672625238281879e5.nq.gz
    ├── 3a227b5a85329dd19afb21f1201ac6921f1f5cee.nq.gz
    ├── 3a5af336410c199124df324e3eacf6d8543a1957.nq.gz
    ├── 3b1076d1ed50b451b992261158d439501da81006.nq.gz
    ├── 3b14e788cd785fa4cfe9f1a47897d6e1980825a8.nq.gz
    ├── 3b271f929322217c0ad0fcccb02849254073a484.nq.gz
    ├── 3b886670a5e9d9ec7b5e93dc09f8ae0bfa40d783.nq.gz
    ├── 3bb6cffa319565fd1daeece80604ce20ebba3585.nq.gz
    ├── 3bd3f41316a143371c4e936ee4f5e36803dd474e.nq.gz
    ├── 3d6be24303e3e2a8c6bf536bab825fbc92b693d1.nq.gz
    ├── 3e4a343b3026aa7dbf31fdaf813378ea47f55d00.nq.gz
    ├── 3eaaea21fa2f82839da96158068720a3bd48a90b.nq.gz
    ├── 3f0c85febca31fcc6bfb77e156212dd4a2b329a0.nq.gz
    ├── 3f3a9969fd053ae1b5217e5cdce117413875e36f.nq.gz
    ├── 3faeda4f4f3acee7da1324cc8fec3f1f376f29a5.nq.gz
    ├── 404297fec3519e6923d0d68d3527ece3bf24b6c1.nq.gz
    ├── 40b89044dc52a6c5f62620d24382f9bf77974d11.nq.gz
    ├── 40e07e1565c33c99764b1302c4d00f7a8a80d14a.nq.gz
    ├── 418a56dd6a03a0751f6ac406de6dfcea375a0bf1.nq.gz
    ├── 41e72b82a671f14a50ffac9a751ee18f84453eed.nq.gz
    ├── 41eceb7b4e569840251dbbacc68bbed962c958db.nq.gz
    ├── 42fb908263d3de39a572ea08834d52a96066ce5b.nq.gz
    ├── 43264b61a35c8257c65ade57836590e6bcd80351.nq.gz
    ├── 4389229fc732803de4f887238ef66640874550d8.nq.gz
    ├── 43ad35be57d5644b67c11efd2449835ce843eec6.nq.gz
    ├── 43d0432980120562f97922cf6da95e9ebc589040.nq.gz
    ├── 43e0ffe0abe1147b3b233f99c18c8bb1962f8008.nq.gz
    ├── 44043ed5ea2fb36eaae80ff638d0f2f34044bbe8.nq.gz
    ├── 4450fe83c01b0517b994caab10599a7d2355b4ee.nq.gz
    ├── 446867c1aa5b67992da38b54c548ca0aa53f146b.nq.gz
    ├── 4520f2dff52465077c5b811458717bd091b1d2bf.nq.gz
    ├── 4523ee8568f807cba96347457037a7cfaf8fd613.nq.gz
    ├── 4595f50315a8388dfe70dd98c277298d4138f595.nq.gz
    ├── 46947fc629e634bafc2ce8d794414c64a0a84c94.nq.gz
    ├── 46bdfdf732ea59c36d9ad92475fc61d2f7851ff8.nq.gz
    ├── 477878bc1d49dafba65cb70bc1b326a7f9fb5004.nq.gz
    ├── 479757b7bdc66016c2f05b400b45da2d98096802.nq.gz
    ├── 4812c4b332e11f5fff98d558a3dfaee8f19a56ee.nq.gz
    ├── 48f8a2d007c2f069073b2476ccad705d588a7c74.nq.gz
    ├── 4a2d08b12f870dd9685d6d829c555c3f6c6a743e.nq.gz
    ├── 4abc4e84ec450ef134668d14ccbc514e7a2d5f7f.nq.gz
    ├── 4bb852d36859f604a69bed6cff73cfc3cf0c289e.nq.gz
    ├── 4c4a30e9185c393ba6f01137db3241d2ffad7f4c.nq.gz
    ├── 4cac393d7b884524ea2f9883dcfb62baa6347cc1.nq.gz
    ├── 4df3117b66b7b8459b4b2c15ae4b6cd24a7b4024.nq.gz
    ├── 4ebf9cc9609c8ca5f8f5fed75a64ebe262d2e6a8.nq.gz
    ├── 4f052261499b60cdeacc3cc0fc848d5a1042f45a.nq.gz
    ├── 4f23f36a13dc794bd73aea88ef10f6dcab2a76cd.nq.gz
    ├── 5018880242a2a57b62791598f3e2ef6d3f37cffb.nq.gz
    ├── 504733f57fe962b371c3d9e49b59db5984e0a0a5.nq.gz
    ├── 5069a782556e6cb21a44ec1313696715cbf5ee3f.nq.gz
    ├── 514d66285624f0c2643687573b0cb1b347c8a8dd.nq.gz
    ├── 51988e5a778136bfcfd08138bfe0b12b7c2a3ea7.nq.gz
    ├── 520ae302c2d8b6a21bd5720b1b4ba2a00cb8e38a.nq.gz
    ├── 521175752bcf8fb278dd4ff48b7e302005ce166f.nq.gz
    ├── 52dcd398ee643f9f640d88d153601615157a6b24.nq.gz
    ├── 53b2a481a2a84568db4328f095161a729544df06.nq.gz
    ├── 5445549ff166456753a0a387cd292c620d9a4599.nq.gz
    ├── 553bb9689b0911d4c889ae891996c88544cf58ee.nq.gz
    ├── 558832accb0c9c8469eca38b9af0c632d7a8d265.nq.gz
    ├── 55e2113ad6bf2fc052705a3ebb523d16297aca04.nq.gz
    ├── 55f0cacdf3733aa86314edb3335b0bd290e01281.nq.gz
    ├── 5602af495569e122936bc226c22690d089a871fc.nq.gz
    ├── 57b348b24a8c276f77fc6f5a30d73552a4cd35ce.nq.gz
    ├── 58e3573e02e3a4e24ca602bc7a21fb9340ef4e6a.nq.gz
    ├── 593911e2fd9a40182eb1be968114749bf2a20064.nq.gz
    ├── 59b45eef09b35d03d9e04e4d0e17e119a5a98db8.nq.gz
    ├── 5a70d21daf2743ffc612b1b2e1cd672793625d86.nq.gz
    ├── 5abff49d5ab8438edf1c84dd7a97cb1db97243f0.nq.gz
    ├── 5b9a5e45c265aed36703df64c8a98f998d0d2884.nq.gz
    ├── 5bb383f5e6a984b56645146ed1be9c388fc46ec3.nq.gz
    ├── 5bb575c8863ea97d471ae133430a5b37b474fa8b.nq.gz
    ├── 5bc6a03447f7c12df5cb69faba684224bee22591.nq.gz
    ├── 5c27d9642760b315c2ab22fb7bcab0c39f15e99f.nq.gz
    ├── 5c3ef00abc5aaf988db73ce7dde0cba77067e823.nq.gz
    ├── 5c8cbfa8046ca3b063051e9fcd0b216f9cbba35c.nq.gz
    └── 5c9e291b03a78974345f4505ad490afb63a740b2.nq.gz

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

[allenai/ToyBlocks](https://github.com/allenai/ToyBlocks)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
