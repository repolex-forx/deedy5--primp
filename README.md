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
│   │   ├── 3c843c473a940782173d59b1d0bb4bd67387eae8
│   │   │   └── chunk-001.nq.gz
│   │   ├── 73baffb5d48174ec050d247a50a92eb9c1230ba2
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 84c1c45d614d2085192826409517e813ecf461f1
│   │   │   └── chunk-001.nq.gz
│   │   ├── 91a70d99784a98ddadba10611058389599a340e2
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 9ed6e67f7d04facbab6c468f4bbede58b4804491
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── a1dd8d4290b7cd0d9ecaa7685d32b8b155bb514a
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   └── b548effe3b7123ce5d943212bf15d1182b072188
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 3c843c473a940782173d59b1d0bb4bd67387eae8.nq.gz
│   │   ├── 73baffb5d48174ec050d247a50a92eb9c1230ba2.nq.gz
│   │   ├── 91a70d99784a98ddadba10611058389599a340e2.nq.gz
│   │   ├── 9ed6e67f7d04facbab6c468f4bbede58b4804491.nq.gz
│   │   ├── a1dd8d4290b7cd0d9ecaa7685d32b8b155bb514a.nq.gz
│   │   └── b548effe3b7123ce5d943212bf15d1182b072188.nq.gz
│   └── repolex
│       ├── 3c843c473a940782173d59b1d0bb4bd67387eae8
│       │   └── chunk-001.nq.gz
│       └── 84c1c45d614d2085192826409517e813ecf461f1
│           └── chunk-001.nq.gz
└── blob
    ├── 003efd8e60506ad4bc4930ccd521da9834d1a18c.nq.gz
    ├── 0141195c553128fdeea4180e8e8fc14666dcad69.nq.gz
    ├── 01634e4577356d1d3461de3b919f923764fc71e9.nq.gz
    ├── 020d00afe60717d0d007d84d0463a985dbff423c.nq.gz
    ├── 023559aa10928e16c4d367977c890ed6e4c1c476.nq.gz
    ├── 024cdf1f48245397c7fac6c61a033ceef83b6ba0.nq.gz
    ├── 027e2ece308682603973f8070f1eaabaf0654c52.nq.gz
    ├── 02d265061ce68046e40dbccf7f010ab74c77bc7e.nq.gz
    ├── 0340e328251177168bead1a5c63cdb665764578f.nq.gz
    ├── 0351088b32a8b057b7e26b686e9f57ad16d41cef.nq.gz
    ├── 03795049e5385459e0c2cefff67bf74fa0e34b01.nq.gz
    ├── 03aa775d69ccc6b1c9d24eee8bab765ac3be0e99.nq.gz
    ├── 03acf1bd2c44c9c10429d0ee4d05ee1e92f9e3f9.nq.gz
    ├── 03fd874bd289e52cd78dd16a795d082f7c952a82.nq.gz
    ├── 0412aa775c23593664bc3c4575cf84dd3604f13d.nq.gz
    ├── 0437465e44866b216c7cb450e6cfd69f351fc8b4.nq.gz
    ├── 0452109c3c7a2932a278e43711d7a4f6e4678b2d.nq.gz
    ├── 04627cdc910e817e639377491f03371c84303b58.nq.gz
    ├── 04a2428dd1b241426110ecd5aa0d7ecc260f5cac.nq.gz
    ├── 04f8dddaf3ad036c23e1aa1d3ce2ad0104e837fe.nq.gz
    ├── 052f798ef2c678921b69d110bd06c3514a1e8dee.nq.gz
    ├── 060f0f77937bb71a6a628588f0625156d8f293ae.nq.gz
    ├── 06462bddb60d32ae44d8da3c934a2f017a605e27.nq.gz
    ├── 06b1a9a81ac9e9656c62f349f35f6b6af265e8f2.nq.gz
    ├── 072d248a9b29a6fee1ead6ca3c2166ae473b8246.nq.gz
    ├── 081d6c2a84996fc421b866e843cea4b96486b045.nq.gz
    ├── 08532aa6ebd50a4b818883bed18c56633e4ebf59.nq.gz
    ├── 086226a4a3e1bea958345692fa320a7098404737.nq.gz
    ├── 088ba6ba7d345b76aa2b8dc021dd25e1323189b3.nq.gz
    ├── 0896bccf287bfb5052c63a9265a8bdf3cde3ccb2.nq.gz
    ├── 089784f17720d267f176b9393728e3931162d8a4.nq.gz
    ├── 08a463ab788ff999dfd4b088f095a7e39f313100.nq.gz
    ├── 0926116566d76793a79f4a9e7812a0fe2f135ea4.nq.gz
    ├── 099367f95284854f0b8008fa3aab2c29be981057.nq.gz
    ├── 09946039cc404210b9a3f36c90836ab2d92f01dd.nq.gz
    ├── 09e738875759920a470331531ad862bb3e81fa76.nq.gz
    ├── 0a09cb72d48b6ca4d32033048f49d0cb41fe35da.nq.gz
    ├── 0a116fab9b0f93bfa3c0bf08f9bd605120f25d63.nq.gz
    ├── 0a3ecefd1d929e8f538df8d485f15713d7f682f1.nq.gz
    ├── 0a709f16e982ba03fe4b0948a3ccb55ff6b703f6.nq.gz
    ├── 0af623b1bf915b5f87f3ae56d2747eeb0146d4d5.nq.gz
    ├── 0af6cc573b745cfaa1f84f0135f9912bf50d7b2c.nq.gz
    ├── 0b1f2743bfdab34ebacd3e17caa5fd77acb330fa.nq.gz
    ├── 0b28bab5f44b46b1ec71e0d6ee5018066dc46f85.nq.gz
    ├── 0b3d3d3a69533d44cca43553c1baad17231457db.nq.gz
    ├── 0b4758fcd896d15d2dfa18a49c6ebec86fead5dc.nq.gz
    ├── 0b8a298e8366f5b8882486142a95812b12d51ace.nq.gz
    ├── 0c49936c6ecc79e2db17e07414ab14b67ad24030.nq.gz
    ├── 0c5c01500a39f6070a7be07129421e7afceb4c76.nq.gz
    ├── 0c874abf9225ba07d874774503e15e12e2fb7692.nq.gz
    ├── 0d1167aeb71418a7b7aa12db245d0e7c1276c58d.nq.gz
    ├── 0d15068e0cdf13771d4a57003ec26d935a513093.nq.gz
    ├── 0d7051fd6c6445ea3934c3b483309629e6a83034.nq.gz
    ├── 0d91f0eac82464933f543f190c58668dbc88b980.nq.gz
    ├── 0daf4ecd33c3a839c255e7d53133a22bb6359641.nq.gz
    ├── 0e4fddce1cb8a4eed45ca3d22ddf5910f529daeb.nq.gz
    ├── 0e701a8a3670deeb2c8662ce46835fdbee993e1f.nq.gz
    ├── 0e7123a090fd204c58704f091fb3fbb2573af62f.nq.gz
    ├── 0e7d2901909b17479954d83619cc9d6c748fb5cf.nq.gz
    ├── 0e82d479f422324433fc9787c2b55f3f5a019147.nq.gz
    ├── 0eae06ab1ebb489f0414289963c052fba4967ae2.nq.gz
    ├── 0eb266974f7b3324a02317676f633eeeed07e091.nq.gz
    ├── 0eda0ba7c65711fce379750b0d87c5523d2ec66d.nq.gz
    ├── 0ef650aaff82759f28e1155fb35a6ea90c87c1f0.nq.gz
    ├── 0f1449ea9258a2c6b3cfc8f9214b6a8f201c4bf7.nq.gz
    ├── 0f427dfb491b632bbcf18d49f46780f1252319fe.nq.gz
    ├── 0fc5acee04ed77a4de6cbe1d9b4d662e82f0fed3.nq.gz
    ├── 0ffcccfea04f60970b2fe7f2312580483e004c78.nq.gz
    ├── 101987342f385e24b65a10c3f8341ff05a3d008b.nq.gz
    ├── 1028ebfade7bfa0689fbb1b54f70df6ad246d31d.nq.gz
    ├── 108e8693aecb5ba270b246327862d00c3b6c7664.nq.gz
    ├── 10c438d4d2d7492f0ccbb44d4aba34d5736b8859.nq.gz
    ├── 10ce78759a583c88089c0b610d1bad6e3f50b491.nq.gz
    ├── 10f1201201bd33604c5b4af05add316e1a3d4a83.nq.gz
    ├── 11239dd1c157a353a2402fc66a1f5e7596d88c76.nq.gz
    ├── 1128d633e57d6f7f614c331be1cf86f06ea7f548.nq.gz
    ├── 1147b646e44d41921ebc1b03446fa808c7472063.nq.gz
    ├── 118a2f02a0a37ef2448732a07fde24582652cee6.nq.gz
    ├── 11a9822ecec6ab58c797a72a2b481cdf8f1792ef.nq.gz
    ├── 11ae757ea92952028e4040d1a0a32f6dfa6ccaff.nq.gz
    ├── 11dd98990f48ea97f16c0bc64b03f1b5cc17f8a4.nq.gz
    ├── 1230fd14231574ed36d5cbfc09c57a46fa720030.nq.gz
    ├── 126d458d6571e221f6b1959637ec162f5c02ce1f.nq.gz
    ├── 127bb76e66c42cc572c305e0dc4bd9f1a9addca6.nq.gz
    ├── 129a638da9b298388ca02a2a78b579d6a666d0a3.nq.gz
    ├── 12b53a6c93a55ca54104cb648a6e0a6d2cc32f42.nq.gz
    ├── 12c75d553588e30f955430a568c9053651c7634e.nq.gz
    ├── 1360f776986cae6d8d8fc40836537cf6c11975b5.nq.gz
    ├── 13e6ca2ae98de1e4befe6ca0497bddb4736ce6f7.nq.gz
    ├── 144349e5d7c193dd97da10060c0820c594e01588.nq.gz
    ├── 147c363075bbd71ec89146372fe8b04d4cf7f53f.nq.gz
    ├── 1489a630df5b980a54feacbea1e5d380e8f25e14.nq.gz
    ├── 14ffbb5aa296458110011b0d68a213126c2f1d74.nq.gz
    ├── 15098d082c1a5371f271029dcbb291269106268a.nq.gz
    ├── 1595ee88953140ae25b465cdb4299d0bdf293ccb.nq.gz
    ├── 15a60bcbb978eb8f3f7273c714d8b272220803c3.nq.gz
    ├── 15bdc3f8013b94addeea66470bf7217fe2a114b5.nq.gz
    ├── 1623c3746b8e5bab75e55e353907291f2dae5b53.nq.gz
    ├── 16425e7fd4e3d399e74237dd7a8a6039a2d565ab.nq.gz
    ├── 1649ae7ea0fe024162c2aefb53463df7b5111b92.nq.gz
    ├── 1674e26bc6bc3081d49e70c7da9478738a4b0e64.nq.gz
    ├── 167abace0a2f2a606285dcaf3647efa1a0f863bc.nq.gz
    ├── 1683fb6c6e76c114c5e8d1365fba087233b42f07.nq.gz
    ├── 16e546952e854e7c7aed06eb3eb1f4e14be98943.nq.gz
    ├── 16fe87b06e802f094b3fbb0894b137bca2b16ef1.nq.gz
    ├── 173bacbd21bc219168a61fcaae34c3619fbc5fc1.nq.gz
    ├── 1760bdd4b3aca74e1dc7c219abcc52ae1ba6682a.nq.gz
    ├── 179c7578c3875d1a3a7597d9434fe306e592b9cf.nq.gz
    ├── 17b3309885e4fabd35a8b7eec7c2c0e0349e1773.nq.gz
    ├── 1822d62987488120e6be9ba3c381a7c60ab16907.nq.gz
    ├── 185258bad9af3e173a806bfebdd0269355837830.nq.gz
    ├── 1899c76c9c6d9fcaa0d27c1a3fa08b920bd38f0e.nq.gz
    ├── 18bedd7e1081b9e609842c083986486c08b088b8.nq.gz
    ├── 18d2158e27d2b46956eaf7625f6e2b74376184d3.nq.gz
    ├── 18fb67ba8bafa58bbf94e7514cb8f619bc0a2b14.nq.gz
    ├── 190f2c7c65e67d4e3b2235e30928c7c89e257104.nq.gz
    ├── 19187549671fcb899c2f946e62131c6266f88683.nq.gz
    ├── 193370f22f91b15b0c185b75c3ac8c01ba6dc34c.nq.gz
    ├── 1956e155c7cb049a3d44be2b5f8c6eb8b862c20e.nq.gz
    ├── 197536b0e5935fe8317a4f2c98819f14257c22d3.nq.gz
    ├── 19ceb5ebb44dc94dfb4ef017e34be594c4b04bfc.nq.gz
    ├── 19e9b4cd1c86b008ba1095ea877810e51a43e688.nq.gz
    ├── 19fb7fe203fbd86266ad6592a4476a28cb4398ea.nq.gz
    ├── 1a822a51a37798f4227f35e458d33da6954a731d.nq.gz
    ├── 1a8f12fc5d987e56fa34613f93fc236173ef343e.nq.gz
    ├── 1a9e713f963b052a1a99600ec0111fe95f23fbfd.nq.gz
    ├── 1ac46f62ed79244e71da6af9f237263b7b59f620.nq.gz
    ├── 1aea258c2c897c10c13a52d73b205b1860ecc9d6.nq.gz
    ├── 1af16133e9270bb974977a989d1223aafc6bf3e9.nq.gz
    ├── 1ba5ed9b4d91b63bd2256735b7a4ca98d70b8bc9.nq.gz
    ├── 1beeb8896b443dc85990790ac53ca907f6185572.nq.gz
    ├── 1bf0fb8b27e3c5f45709c196e61477a91a0d34f3.nq.gz
    ├── 1c47947337eff9fc9db9d6e6967e953597385e07.nq.gz
    ├── 1c607641eb460df03600061c0e4ec9322bdcdfec.nq.gz
    ├── 1c6a7b98bd0f2cdff15f742d787a4b23e56bf2e6.nq.gz
    ├── 1ca30bee0d2ddb6e1c36f56d75d9a3e9f795614e.nq.gz
    ├── 1cc52ed9e15b2178d64452814f13c354f82f4866.nq.gz
    ├── 1ccc8c61f48dd9124b2b9d407434224f29fa9665.nq.gz
    ├── 1d14efd50b2fe7f02f4be93b2e7db53a72204e42.nq.gz
    ├── 1d4d2e4c8597f8c324b087bcef2e201e7d2fedbb.nq.gz
    ├── 1db47ff01e46a8ac8d9c868becd327f3282b13cd.nq.gz
    ├── 1dc88a8b878f39e0501c209d12aa273c234bf88b.nq.gz
    ├── 1dd57de319ebb0e51e1b560536bc413f390c72f5.nq.gz
    ├── 1ddc0e73cd3005ee70dda2bce53130f6a464f540.nq.gz
    ├── 1dfb0e70faadbce1e2af09df6a528e061e25c471.nq.gz
    ├── 1e07b7bb626f38ac5062b8843d3cb2574c838bbc.nq.gz
    ├── 1e4c812bff4b40c0bc6de39ed880e6636d66b488.nq.gz
    ├── 1e7af32f57f82bc92a0134ce8d8c7dc650df1f20.nq.gz
    ├── 1e927a7afe06c270670d6bc25c4d465db2e0a7e8.nq.gz
    ├── 20352daeb436dbadb962b7462a23338cfc793010.nq.gz
    ├── 203a759e41512a86da191244158d0d297faebd10.nq.gz
    ├── 205f18c0bcd06ed33c287c2c2c87248f78f4a813.nq.gz
    ├── 20693e9b7b58deaddd87d98fff773a0c1ccf223b.nq.gz
    ├── 20ab69ec49537612040fa811e20c5d8c2f1ec71d.nq.gz
    ├── 20efd0a8d746c4c9128475d6e0857c6c12aea57f.nq.gz
    ├── 20f255b6c0311adef18bb0684cf430f9c3956e6c.nq.gz
    ├── 2132c7acf3f9edf2bf95424dfca56fb97b897a85.nq.gz
    ├── 214dad4e0f89216a3b28ed1c166bb95523fa9fa4.nq.gz
    ├── 21f11da9aa0462f3594f52e2b90c3e959a8dc035.nq.gz
    ├── 21fa6123c9d186682413318d9dcfe6f5d47b5f56.nq.gz
    ├── 220dc536395121b2738dd52fc1e38b615aaf1d1a.nq.gz
    ├── 2217209f875117ac82c9a8d0937dda162c29c1a6.nq.gz
    ├── 2237f5b8713bc23c63191d8aa978c0177e19c941.nq.gz
    ├── 223e0ed3e1e85e556fd591efd787afa87d704fb4.nq.gz
    ├── 2266d036ff32881a6410812f5ca5ac57f8d1770e.nq.gz
    ├── 22dfb976974fb9856c11c6bbabd8bd68a7b330bb.nq.gz
    ├── 23593863d38327ace3ada31bde61df5a683969c3.nq.gz
    ├── 237578e008c664b02ded4a420e57c594ba249de5.nq.gz
    ├── 2386d583d723275f4d1977b191e236490afba639.nq.gz
    ├── 23a5c7bc5cd04bc65f4b2f319211f595bfea492e.nq.gz
    ├── 23a6491ac378e5f997221c1116cd6f149b1d4548.nq.gz
    ├── 23aa0a260d8763cf645904a8d60b072feed14ee3.nq.gz
    ├── 23e7aa7477ea12a5c35277ebade516a06ae77de5.nq.gz
    ├── 240343770bf1dc6ca4dad25ff7316708c2e6e642.nq.gz
    ├── 241d06ea176f8965f5db711ae6bebb8fdb0ce9f3.nq.gz
    ├── 242455e764f61fbe9bbaa8b46191099a1cbb9d08.nq.gz
    ├── 242ea48f1d3919a92c94e8d9d65fcd5c511dd133.nq.gz
    ├── 247926f1f84c5b282712df706bdc26813d6890c6.nq.gz
    ├── 24960a1ef9fe54c71d64c00d81da677bcf938f1f.nq.gz
    ├── 24da485769ac721477770dbf482b58fa2e98a293.nq.gz
    └── 24e9557830f59f4a4ad34994ab8c878e45579950.nq.gz

15 directories, 200 files
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
*Parsed on 2026-11-24 by [repolex](https://repolex.ai)*
