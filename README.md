# Repolex Knowledge Graph of deedy5/primp

RDF knowledge graph data for [deedy5/primp](https://github.com/deedy5/primp), parsed by [repolex](https://repolex.ai).

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
rlex download deedy5/primp
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 84c1c45d614d2085192826409517e813ecf461f1
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 84c1c45d614d2085192826409517e813ecf461f1
│           └── chunk-001.nq.gz
└── blob
    ├── 003efd8e60506ad4bc4930ccd521da9834d1a18c.nq.gz
    ├── 02d265061ce68046e40dbccf7f010ab74c77bc7e.nq.gz
    ├── 03795049e5385459e0c2cefff67bf74fa0e34b01.nq.gz
    ├── 03aa775d69ccc6b1c9d24eee8bab765ac3be0e99.nq.gz
    ├── 03acf1bd2c44c9c10429d0ee4d05ee1e92f9e3f9.nq.gz
    ├── 04a2428dd1b241426110ecd5aa0d7ecc260f5cac.nq.gz
    ├── 04f8dddaf3ad036c23e1aa1d3ce2ad0104e837fe.nq.gz
    ├── 06462bddb60d32ae44d8da3c934a2f017a605e27.nq.gz
    ├── 072d248a9b29a6fee1ead6ca3c2166ae473b8246.nq.gz
    ├── 08532aa6ebd50a4b818883bed18c56633e4ebf59.nq.gz
    ├── 086226a4a3e1bea958345692fa320a7098404737.nq.gz
    ├── 099367f95284854f0b8008fa3aab2c29be981057.nq.gz
    ├── 0a709f16e982ba03fe4b0948a3ccb55ff6b703f6.nq.gz
    ├── 0b1f2743bfdab34ebacd3e17caa5fd77acb330fa.nq.gz
    ├── 0b28bab5f44b46b1ec71e0d6ee5018066dc46f85.nq.gz
    ├── 0b4758fcd896d15d2dfa18a49c6ebec86fead5dc.nq.gz
    ├── 0b8a298e8366f5b8882486142a95812b12d51ace.nq.gz
    ├── 0c5c01500a39f6070a7be07129421e7afceb4c76.nq.gz
    ├── 0d15068e0cdf13771d4a57003ec26d935a513093.nq.gz
    ├── 0e4fddce1cb8a4eed45ca3d22ddf5910f529daeb.nq.gz
    ├── 0e7123a090fd204c58704f091fb3fbb2573af62f.nq.gz
    ├── 0e7d2901909b17479954d83619cc9d6c748fb5cf.nq.gz
    ├── 0eda0ba7c65711fce379750b0d87c5523d2ec66d.nq.gz
    ├── 0f1449ea9258a2c6b3cfc8f9214b6a8f201c4bf7.nq.gz
    ├── 0ffcccfea04f60970b2fe7f2312580483e004c78.nq.gz
    ├── 101987342f385e24b65a10c3f8341ff05a3d008b.nq.gz
    ├── 10ce78759a583c88089c0b610d1bad6e3f50b491.nq.gz
    ├── 11ae757ea92952028e4040d1a0a32f6dfa6ccaff.nq.gz
    ├── 11dd98990f48ea97f16c0bc64b03f1b5cc17f8a4.nq.gz
    ├── 1230fd14231574ed36d5cbfc09c57a46fa720030.nq.gz
    ├── 129a638da9b298388ca02a2a78b579d6a666d0a3.nq.gz
    ├── 12b53a6c93a55ca54104cb648a6e0a6d2cc32f42.nq.gz
    ├── 1360f776986cae6d8d8fc40836537cf6c11975b5.nq.gz
    ├── 13e6ca2ae98de1e4befe6ca0497bddb4736ce6f7.nq.gz
    ├── 1489a630df5b980a54feacbea1e5d380e8f25e14.nq.gz
    ├── 15a60bcbb978eb8f3f7273c714d8b272220803c3.nq.gz
    ├── 15bdc3f8013b94addeea66470bf7217fe2a114b5.nq.gz
    ├── 1623c3746b8e5bab75e55e353907291f2dae5b53.nq.gz
    ├── 1683fb6c6e76c114c5e8d1365fba087233b42f07.nq.gz
    ├── 16e546952e854e7c7aed06eb3eb1f4e14be98943.nq.gz
    ├── 16fe87b06e802f094b3fbb0894b137bca2b16ef1.nq.gz
    ├── 1760bdd4b3aca74e1dc7c219abcc52ae1ba6682a.nq.gz
    ├── 185258bad9af3e173a806bfebdd0269355837830.nq.gz
    ├── 18fb67ba8bafa58bbf94e7514cb8f619bc0a2b14.nq.gz
    ├── 190f2c7c65e67d4e3b2235e30928c7c89e257104.nq.gz
    ├── 19187549671fcb899c2f946e62131c6266f88683.nq.gz
    ├── 197536b0e5935fe8317a4f2c98819f14257c22d3.nq.gz
    ├── 19e9b4cd1c86b008ba1095ea877810e51a43e688.nq.gz
    ├── 1a822a51a37798f4227f35e458d33da6954a731d.nq.gz
    ├── 1a8f12fc5d987e56fa34613f93fc236173ef343e.nq.gz
    ├── 1a9e713f963b052a1a99600ec0111fe95f23fbfd.nq.gz
    ├── 1aea258c2c897c10c13a52d73b205b1860ecc9d6.nq.gz
    ├── 1af16133e9270bb974977a989d1223aafc6bf3e9.nq.gz
    ├── 1beeb8896b443dc85990790ac53ca907f6185572.nq.gz
    ├── 1bf0fb8b27e3c5f45709c196e61477a91a0d34f3.nq.gz
    ├── 1c47947337eff9fc9db9d6e6967e953597385e07.nq.gz
    ├── 1c6a7b98bd0f2cdff15f742d787a4b23e56bf2e6.nq.gz
    ├── 1ca30bee0d2ddb6e1c36f56d75d9a3e9f795614e.nq.gz
    ├── 1cc52ed9e15b2178d64452814f13c354f82f4866.nq.gz
    ├── 1d14efd50b2fe7f02f4be93b2e7db53a72204e42.nq.gz
    ├── 1dfb0e70faadbce1e2af09df6a528e061e25c471.nq.gz
    ├── 1e4c812bff4b40c0bc6de39ed880e6636d66b488.nq.gz
    ├── 1e7af32f57f82bc92a0134ce8d8c7dc650df1f20.nq.gz
    ├── 1e927a7afe06c270670d6bc25c4d465db2e0a7e8.nq.gz
    ├── 20352daeb436dbadb962b7462a23338cfc793010.nq.gz
    ├── 20693e9b7b58deaddd87d98fff773a0c1ccf223b.nq.gz
    ├── 20efd0a8d746c4c9128475d6e0857c6c12aea57f.nq.gz
    ├── 2132c7acf3f9edf2bf95424dfca56fb97b897a85.nq.gz
    ├── 214dad4e0f89216a3b28ed1c166bb95523fa9fa4.nq.gz
    ├── 220dc536395121b2738dd52fc1e38b615aaf1d1a.nq.gz
    ├── 2266d036ff32881a6410812f5ca5ac57f8d1770e.nq.gz
    ├── 22dfb976974fb9856c11c6bbabd8bd68a7b330bb.nq.gz
    ├── 23593863d38327ace3ada31bde61df5a683969c3.nq.gz
    ├── 237578e008c664b02ded4a420e57c594ba249de5.nq.gz
    ├── 2386d583d723275f4d1977b191e236490afba639.nq.gz
    ├── 23a5c7bc5cd04bc65f4b2f319211f595bfea492e.nq.gz
    ├── 23a6491ac378e5f997221c1116cd6f149b1d4548.nq.gz
    ├── 240343770bf1dc6ca4dad25ff7316708c2e6e642.nq.gz
    ├── 241d06ea176f8965f5db711ae6bebb8fdb0ce9f3.nq.gz
    ├── 242455e764f61fbe9bbaa8b46191099a1cbb9d08.nq.gz
    ├── 24da485769ac721477770dbf482b58fa2e98a293.nq.gz
    ├── 25b46c315408ae99bb3f113d07cb3c8b583b3e72.nq.gz
    ├── 26c157542a5ddb08a34ab6934e2d8ab0892716db.nq.gz
    ├── 297a6d744d45fe836aa2fcdd1ad8aa20678daa01.nq.gz
    ├── 2a00360ae6fd43b62b2379a732155e91a3a5aca5.nq.gz
    ├── 2a412cdb354114113732bcd16ae375b2714dcde2.nq.gz
    ├── 2a653b81ce57f947b4c4f73a3ff11ab6f3f97532.nq.gz
    ├── 2b74cfd6bfd8865795a1250c15692e374f21b405.nq.gz
    ├── 2bb1ecb71c08f8140b406cc08e7e4859a1b2a9ab.nq.gz
    ├── 2e1cdfdb94ab281fd7aa8889fac10d6a05cc28db.nq.gz
    ├── 2e6032598dd9009e3de6af876190989ab33d2fd4.nq.gz
    ├── 2e61a33fc52f0a219c2f7340f17eb7a7a4607ef7.nq.gz
    ├── 2e7cc0f6f9d5f2a68058d3ba41d654feb445cff5.nq.gz
    ├── 2f0fd204d98ebef9431eca5ba0ca1502efa12a6b.nq.gz
    ├── 2f4f61cbf3f924e847abe134943014412440558a.nq.gz
    ├── 2fdb57e5232477307aa71ef69e4c81fd60c46582.nq.gz
    ├── 316257c56a72db64b88cb1b7641de3c2f17154f3.nq.gz
    ├── 354a33f0a9012b785efbd75d173efeafdbaa57ee.nq.gz
    ├── 354bfe09461ad8acec53ef754cca0b3b342ca9c9.nq.gz
    ├── 366430009bb73814837ec3bb68c9d75b22081673.nq.gz
    ├── 36a08a4af65909824365838a46f035972e7e2bdf.nq.gz
    ├── 3785d45074778f4a0a70fdb0d1b2a9f0b4867919.nq.gz
    ├── 3861aa2d34d77ed60958bb1328891b7ac9b7f978.nq.gz
    ├── 38be2f6973b1ea8e50f3b077110ea48392a49fe9.nq.gz
    ├── 39f6ac20229c91bb031c3e25a0dbb95a2aee1f20.nq.gz
    ├── 3a55977d42bd8651d6879c8c778632b6ff09c08d.nq.gz
    ├── 3ab89e9413bd1fadb388257f0c1ac9b28cc15905.nq.gz
    ├── 3ad2015262e6b2262bf1911f5e84f517a92f47cd.nq.gz
    ├── 3aea6c1b080733d86fc4bea1bad35c842d6aacc8.nq.gz
    ├── 3b0a00658d9d2e6de937ffa1da35563a12d25213.nq.gz
    ├── 3b2debb7e51462c914bba879a82148964c081623.nq.gz
    ├── 3b49dadd20449b5a58cff7051fbbdcc83fa2f17a.nq.gz
    ├── 3bcd132058eca94e4dc997c2cfc2cabb7bedf32a.nq.gz
    ├── 3cfb68a5e02956abe9fb5786c74328233a616611.nq.gz
    ├── 3d1933f50b07b78dbe6ecffbad3b8058e807f5e3.nq.gz
    ├── 3d4ab41cbc8deb242968fbd9c0f0deadd57967f9.nq.gz
    ├── 3d5de869c39a3b9c148d26843a91b20f36966a14.nq.gz
    ├── 3da778acf4db350cb34da8c62fec49619f0c23a9.nq.gz
    ├── 3ed5be9187d62541a14f1d6663940e180db94bde.nq.gz
    ├── 3ed8cad56a6d63b632cc6e91e1cafddaff026b61.nq.gz
    ├── 3f9348ee70db1aeb400ebce5b65f85e8c4296fbc.nq.gz
    ├── 4093c9f0d095b4a64ea3fbb80831c1e51a31bfec.nq.gz
    ├── 41a1250da86b2b304d36aa6c0338d51a9214935a.nq.gz
    ├── 41f0caf890d0baa4d610393058fcf741860ea2be.nq.gz
    ├── 4204714d891012485d63aa5358d105e0d3ae0510.nq.gz
    ├── 4225d134623f5c710f7755ba503c65850c178e45.nq.gz
    ├── 4283875999e214230f1dc66874f6bf80811c1cf4.nq.gz
    ├── 4338143fd2f732fb874f35cc7b31eb4dfab751f8.nq.gz
    ├── 434bfe6691844a45070dce47a1ebfd966e8dda39.nq.gz
    ├── 43899bcedcf9b760d3d34a043cdd3fef1add9c2f.nq.gz
    ├── 43d5ac6fb4af5cf183e09b61be35a14f96e26421.nq.gz
    ├── 44fab6f05c198fd84eaa19094716f9a2199ac07f.nq.gz
    ├── 4626270d2c4a6b9cc00155fecb293e5d1370429f.nq.gz
    ├── 4668ef01287a13bca3b79041fe9f179a03514a65.nq.gz
    ├── 46731548ad74be1860d669df320774afabf302e0.nq.gz
    ├── 46b00185907564f787392b4c13ebe5c2ebc140d5.nq.gz
    ├── 4739075ea074d8f77a9e40d6e20549f5614cc208.nq.gz
    ├── 4740b1da7af2cdf9d5fb3240c28004ff2da321ae.nq.gz
    ├── 479b19e3e498e9efd1dae043dc69bf49a1c7af68.nq.gz
    ├── 48674831531ce0cb61da4a374922e6bd15a436cd.nq.gz
    ├── 489d16daf789228edc093317f78665f53370230a.nq.gz
    ├── 493cb13f3cc50b9afda2854e732af4c8af6707f3.nq.gz
    ├── 49f072549d2d5848ac5bccf1a2872443c6330b0a.nq.gz
    ├── 4a2dc02014cac9e92d4e06a167245ef61ca5a0f2.nq.gz
    ├── 4a598c24d90da0bbb8188a1edfb68d97b6d5cd40.nq.gz
    ├── 4acdf99ae1ec6c7af73a29c0214758ed4566e48c.nq.gz
    ├── 4b669f42253f9886044cb600be4b49680f21a47f.nq.gz
    ├── 4b86db3b56edd64fed5864d618eee96969a3eca0.nq.gz
    ├── 4c8f92766753be7c4efb465e053a03db02ec526b.nq.gz
    ├── 4c92da6172ae35780fd2f5a85e8b212bc0e2b7ed.nq.gz
    ├── 4d601e1c5d00ab2e519bb5afd933811139e92775.nq.gz
    ├── 4dc36fa28d5503c7365821becb0b0a3d78acedce.nq.gz
    ├── 4ee4a3c65cec70784114d9f2bdd2adf8c02833c9.nq.gz
    ├── 4f9e1bd2f55b2e53a29da01def0c68160763fe61.nq.gz
    ├── 5055b8c7e351f8a1078cedb9d75e8e6989c2e7f0.nq.gz
    ├── 506a22e7dc250cb62eec5287cff080d8617660fa.nq.gz
    ├── 5120f70da568534ce0c48545e9050b55c0497caa.nq.gz
    ├── 52228c009ea4efaaa74e8c8c0781b0c88dbf19c3.nq.gz
    ├── 53040e7da09759fc0270ddf2640b2bca86ed7c2c.nq.gz
    ├── 53b8a513964f450941621860a27da6d762e2a76d.nq.gz
    ├── 53f68aba0745cc285ff52cb7417c41fdcae87ade.nq.gz
    ├── 54ce87bdc645985aa9120b004bed22efdb734660.nq.gz
    ├── 566ea61de1893153d77084a4ad6340a7ea51380b.nq.gz
    ├── 5670c3d455db63a61bd71961e927965c48dba801.nq.gz
    ├── 5690b661e573a71bbdb67a10060675a791978da8.nq.gz
    ├── 57551822e40e63d3e9dff134e85a8ffd84d95851.nq.gz
    ├── 5798ceb5bd31dda54f21d7c5905cb41c2ffe82b7.nq.gz
    ├── 59366fff02d41e90d1397594d8799b06c36207ee.nq.gz
    ├── 5980e32738daad8d00e4bfd3fdbd02384c829c49.nq.gz
    ├── 5a6ed6cbbcafa70db745197e8c49f049051b0d42.nq.gz
    ├── 5a95f837c8348b990fd16b8451f5d0027dba3bd8.nq.gz
    ├── 5b8709bf3427d8a677e5fa24fc05f66cce83c3e2.nq.gz
    ├── 5bc2926000bd3ce732b7ed669108ed22119d43f6.nq.gz
    ├── 5c04f3f6064a55c0160bebfa7ec62d259a476722.nq.gz
    ├── 5c18e175f50cbf6d7eaed4130ea7c8b0e8256f13.nq.gz
    ├── 5c347f7a5cd324be3a9a225af5bca423d75517cb.nq.gz
    ├── 5ca03a746d47979a2d18c680d1c14b8384c40c79.nq.gz
    ├── 5cdc2c043499b7aee49f8e49643ebf2f0840f811.nq.gz
    ├── 5cfb5dedf3430a8bfeebacdf38501b3f7ee6639e.nq.gz
    ├── 5d23af3b8364245cfd886d03c13af7e8487606ae.nq.gz
    ├── 5d259787cc968b98f7c6685fe95864eb4a6d03e8.nq.gz
    ├── 5e3b4f40a382caf1afeb07e16f1b9e2e0b2aafdf.nq.gz
    ├── 5e4cf6eb6291799ebc4a597f1636c3337a041d7e.nq.gz
    ├── 5e72c424caa9c59596444b8d72b71c6d4743f0e4.nq.gz
    ├── 6085ba950d8205b9727fe7486e95b967282cdf68.nq.gz
    ├── 60fd92897d59cc6768628f1d999b4f43f68f0f2b.nq.gz
    ├── 6126fb8382c11036410fbf4327670fc801497df8.nq.gz
    ├── 618bd9566ab3531d3c0995bdfa47ae7051041616.nq.gz
    ├── 61ed06580d4baffe9e0aaebf0e53d4b744b3ac2e.nq.gz
    ├── 62029f87f13dc9513b7ca2c03baf1713b97f9d40.nq.gz
    ├── 626afb3a1865ed079169824c6494a6e8ef083a39.nq.gz
    ├── 62dc4f82b333876d05574854c177b86935e099e8.nq.gz
    ├── 62ecaa439bd55331c688bd26dc4132d4fa6ba439.nq.gz
    ├── 6313964c68b8863bd34be70128707d505197ed6c.nq.gz
    ├── 652299fdbde4836f697060f20bf5e2c449e16082.nq.gz
    ├── 6526e09f95931204a2efac05ee84e17c32ef0e66.nq.gz
    ├── 655dba99ee0e10d4bef9282815664995de6e273d.nq.gz
    └── 658e8ba567f90fa709d9e1307b0e558778580be1.nq.gz

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

[deedy5/primp](https://github.com/deedy5/primp)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
