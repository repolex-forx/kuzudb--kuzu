# Repolex Knowledge Graph of kuzudb/kuzu

RDF knowledge graph data for [kuzudb/kuzu](https://github.com/kuzudb/kuzu), parsed by [repolex](https://repolex.ai).

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
rlex download kuzudb/kuzu
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 89f0263cc7a1fd9c396d2c4953747a013556a7f9
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 89f0263cc7a1fd9c396d2c4953747a013556a7f9
│           └── chunk-001.nq.gz
└── blob
    ├── 003b26ea14951b5781eab96d8425cdfda0f54553.nq.gz
    ├── 00a15ab7c209503d4dcd7ecaf09fb65acb92965c.nq.gz
    ├── 0121127fa3cb6c1ff71686ef6d26e99ae3cda754.nq.gz
    ├── 01856b28fae5aaf63d57341f18692204455717f4.nq.gz
    ├── 01e113d53a8eb40a9f73bef3ac0058f99ded3d98.nq.gz
    ├── 0248dc1edbf1cb8b620669c0615efc97e57908d9.nq.gz
    ├── 024d6eaef58619ddd0a4494402d36c15a344cc04.nq.gz
    ├── 029cb6528ae83b991b1a6d9a8641997507d7d4cb.nq.gz
    ├── 02c1ec0caded61ded7947d16eb9932a6191a53f9.nq.gz
    ├── 03d568745640470891fe33080b74fe75d6d25d85.nq.gz
    ├── 04390579f50bef7d5e1284165b3da0bd9d766134.nq.gz
    ├── 04dbb2278cfdb86a5a01273fdc85e61d2cf82599.nq.gz
    ├── 04ea5726b3c709275780c8692dadfc6284ddef33.nq.gz
    ├── 05f20355ee7bc2b881ea1c3b7fc829fec0931d5d.nq.gz
    ├── 0697a078850cf46714ee3d1061aef3470b2d0f09.nq.gz
    ├── 06d8c475b156bea8d93045b46989c9413e336ba6.nq.gz
    ├── 06fcb923cd4e7e0c5361abe8db054603b0819088.nq.gz
    ├── 07cc4a5e95e89dbd00c6069c6eb4a5afc1cc0942.nq.gz
    ├── 08066081461245a7de964f5bad0bd675257b1c0d.nq.gz
    ├── 0848ccc7f5a5805bc556bc11814477e84cf27025.nq.gz
    ├── 08814912b82864670aa0e56078c2c5891f06ce05.nq.gz
    ├── 095ad56fa70e9af562495b1e8e2fb880e503f236.nq.gz
    ├── 098ee2713fbf24264d7ed343a3f564befbe5a718.nq.gz
    ├── 09d64a96d14b70203eba64aec225f236ad3c4821.nq.gz
    ├── 0a3e8272887433d43d597956be2d186732d316d5.nq.gz
    ├── 0aacc427cafc1d6c91973af9bceab8edcbf5f480.nq.gz
    ├── 0ab85c3471f6b8f23413ecf514002c800a58303f.nq.gz
    ├── 0bffe66073c688d194527025398b94d73e7fbd0e.nq.gz
    ├── 0c8cfc429f4af9f10432c753d65087bc3013722c.nq.gz
    ├── 0cbe8b30201db989046aec419b205f27504b027b.nq.gz
    ├── 0d0c2c3707b40d36598d72368000e47163c14aaf.nq.gz
    ├── 0d93dfe42910346c3cf682cfc3e5d2340b1a6c97.nq.gz
    ├── 0dc1fa6945be129fa66f1cf69fba3aea1b9f25f7.nq.gz
    ├── 0e9b08af738a5be5d4cd53a0184e3ff2db6a0bf3.nq.gz
    ├── 0fafff5e9af35aff576021b57b47682be310463a.nq.gz
    ├── 1052de119c4a66d3c2150fceb7163133472b05a5.nq.gz
    ├── 108d20f0d7724f4049d02a052e14dc49ef5090af.nq.gz
    ├── 10bd5b6e5624b2227061e1a80d1559e6e8bf9133.nq.gz
    ├── 112d1cd61c69e22a48995e85cdfc05e9c674a3b5.nq.gz
    ├── 11944078406a2ab27495bd9b0d7b16b715b359d6.nq.gz
    ├── 120a6d818c2009e89a55e912e94d068cf0843f9d.nq.gz
    ├── 12724c0b65737699305628f155f52ee4b2856b88.nq.gz
    ├── 128da19db01cd9361b1b5b476279566c764dc002.nq.gz
    ├── 12faefab48dbc4ece2bdb9ed6ab1b868512df098.nq.gz
    ├── 13417927f566815b0879e50fa9314598175ae421.nq.gz
    ├── 1344160592942525c1142e33f1028f6a93e7a139.nq.gz
    ├── 13bfb6996548b0d0751aa250157e496372451eec.nq.gz
    ├── 141c098bd8c3104ec6c529de3c35240a303a68de.nq.gz
    ├── 147f2606a6e09cd718966a43558c069fdb35045c.nq.gz
    ├── 14aed7c82986076420b3119dc5c4cafb90a94c54.nq.gz
    ├── 16c43c8b52588aecb2f4c98fb040025b3d298aa1.nq.gz
    ├── 1772909db89fe9e3b339628769d2539270401729.nq.gz
    ├── 181641b50c1c0785409480f5d36b0d8b7ec5806f.nq.gz
    ├── 189850cfe357ec49500d3770f1659ad5c9c6d6b1.nq.gz
    ├── 18a5a5d1035f1c61447b18c886fad638ee0c1ed2.nq.gz
    ├── 19b0508ad25707d6d93c5791757422eedc491a1c.nq.gz
    ├── 1a5d2955d8b5f66f136a372aed47ed5aac908d74.nq.gz
    ├── 1b5e05057cba0c014b9623a8d955e854163b7950.nq.gz
    ├── 1bb51bdc6127e3c7ec82d425a179e122e2af08d6.nq.gz
    ├── 1c5ca6f2ff1181dbeb3152e6d09b4ba8b3809f98.nq.gz
    ├── 1d5b0b96febdc2e48606f6efdb5a4464e3af7a48.nq.gz
    ├── 1d9d487c350c387be32f5b23e4605c4a6177cea6.nq.gz
    ├── 1e0061bf65e013a57c2008f409bc32fdd0eb4ef8.nq.gz
    ├── 1e6cf4c584581c6b6a2ba05d0543fe32de56044e.nq.gz
    ├── 1ea7c5bc5c989ffda22d2bf7de5fa4761538d3ae.nq.gz
    ├── 1f53fea6a70fba28361d7aa069187e5afb7f8198.nq.gz
    ├── 1fbba27c8364b0c05af62c379ae901d91b9365de.nq.gz
    ├── 1fc324cb50b691fc1b658ba16d3f8dc8ff2bdbf1.nq.gz
    ├── 20e8731d11e9f1afbfe2c44303c957665e17fe09.nq.gz
    ├── 210284ca7f30af07a622931bb6f17bbaebe71b6c.nq.gz
    ├── 210b346f6276b21fab61bac893b4d470f47605e7.nq.gz
    ├── 21d21ecaa14ec2f311fe722248674f6c15ef24a3.nq.gz
    ├── 21dba7ff1eeac2459fe8999b08eb190f7e8bca74.nq.gz
    ├── 22383be9d2a1261999575ce1eec0c685081c65d4.nq.gz
    ├── 2246962873d4aeda8f6711c1072ec1e4f50eddc5.nq.gz
    ├── 237967048e3faec4563c2b7c9d52e78393c9a32e.nq.gz
    ├── 23ecc26f8ec80ec8dc4f2ea46632adff1459dccb.nq.gz
    ├── 245a132be90605e5e038c666704ca0e20be01999.nq.gz
    ├── 246006a1c596ab847a72cf12df8cbba7a87c91c1.nq.gz
    ├── 249e5832f090a2944b7473328c07c9755baa3196.nq.gz
    ├── 25a680a4894acb080fe58a603fe116bb972ac287.nq.gz
    ├── 25f7d0a42cd9d7ffbc6db5cf22a7dabe52d9c40a.nq.gz
    ├── 261374a51a94a727643751222a93efac323cd838.nq.gz
    ├── 264f5564b2abb3bbef4629e21603776ffa315b6a.nq.gz
    ├── 26cdedd7ac31bf2112c6266a8d2353db6efd98c7.nq.gz
    ├── 26f157e6ef97763fa1ea05fc328b5bf5de83d108.nq.gz
    ├── 2724909a183e947b6434041de8c87663442e17c1.nq.gz
    ├── 28140548ea28c5f1534eab8811ed343587e39db5.nq.gz
    ├── 2854bfae7ac48931fb003d03140d1d8168d6b8ab.nq.gz
    ├── 2999869cb249c13d8c15fba3715f1a707c9874ce.nq.gz
    ├── 29b656888987cbe9415e4dbeced47aa14f2f8caf.nq.gz
    ├── 29ed29c16754205eeaeef34996cc49dc1e1fe64f.nq.gz
    ├── 2a1d8d2628b66f08a4d666a887511371d5aaabf2.nq.gz
    ├── 2a5dd985cd5dc77923a2801ee7b45b2316974c0b.nq.gz
    ├── 2b075add4abbbf2e40abfb56212b099d2f1aa721.nq.gz
    ├── 2b3d6c87d86b482a15803e1352f1910b412ad346.nq.gz
    ├── 2bbc632bc71d111e5961f09f6120f5d17e8cb2b6.nq.gz
    ├── 2c320d1ba7703a56ecbba0d745338a61ce520aca.nq.gz
    ├── 2c5f31ad2110d69fa30e87fab7ad6fa37f074047.nq.gz
    ├── 2c94e00a78e9f198f17ffcc5e490c49ac0f07aaa.nq.gz
    ├── 2d69142549d06a4a36a55d4c9b36c117e84add38.nq.gz
    ├── 2dd07e650730cadf785c890150a0a60c5b23e72b.nq.gz
    ├── 2e96b3d0903ba74c51b59231d8224c5ef3eab630.nq.gz
    ├── 2ecfae4faa47729aa267c03c059fbf38f53cb8dd.nq.gz
    ├── 2f01d5d58132b6cc6046b8e3976b69b7123652a2.nq.gz
    ├── 2f6e86c3774941658a262ec4f26426fce9fa26da.nq.gz
    ├── 2ff735bb4c2e4152033b776f0b3b73f4676ce2a0.nq.gz
    ├── 308a9a27152f18aff30b8a122720f826cad264b7.nq.gz
    ├── 312411df16b9b4cdb35f081f989d3d886de1a371.nq.gz
    ├── 3180c246c22a1b8931d38579f2671525c19cf84b.nq.gz
    ├── 32f1bde201c00c7b1170203aa1a38ee2c628d56d.nq.gz
    ├── 33114da913e0fed159820093501ebdab6f707c18.nq.gz
    ├── 3322d9a614373102735933c0f44fe89a5858fae2.nq.gz
    ├── 33245b9acb376d75126132f1eef9bb52c584c89b.nq.gz
    ├── 33b107e5862a97fe28e5f2d7dc66a92e91df8837.nq.gz
    ├── 34f85a2cbd5936d03932ea220db6008059a3d975.nq.gz
    ├── 35420289e5540f4bd2e961c586d75800cabb4f94.nq.gz
    ├── 35557703c54cdfb3b827e1c8a1a5e8ac0bb71802.nq.gz
    ├── 3579c1f20d768c85015eae1e6737777cece19bea.nq.gz
    ├── 367845aab0438e44b023b45ba5df3753b12fb448.nq.gz
    ├── 36cf49bf8b7d6e290219d6837cc5c8ab6394e260.nq.gz
    ├── 3832d91573dc85c08c0ed0e377bb11b29964d978.nq.gz
    ├── 38b102edf836ae70d189f44f4dedf0813897c41e.nq.gz
    ├── 3980a17186277afaaf6b6a93e742917e6413c597.nq.gz
    ├── 39eb2f169f79b32ada797af81c4b1ab7ded4d13a.nq.gz
    ├── 3acfb762a73b3fae700cbac1b95f9f18dfc7113b.nq.gz
    ├── 3afcd488b36b5454bdcf06da8b6a84d206ede6b4.nq.gz
    ├── 3b67c12e1cd22627cf5dbeb772edb5e309c575d2.nq.gz
    ├── 3cd0ef033001c531a55d455a00566d59a457b56e.nq.gz
    ├── 3d5ba50a8244977dcc33e176a0c7daee825a00f2.nq.gz
    ├── 3e5cc755126a3fc3154146f933702ec0694b1dbd.nq.gz
    ├── 3e5ec2f7b19eaf6d988e02574e875c3ad5a6dafd.nq.gz
    ├── 3f4bdd644b32eaf286a0535a16e96d0804687374.nq.gz
    ├── 3f8f715515db577c84046f7463085de7f0683f5e.nq.gz
    ├── 4145fe934e8eec5e7279270ffda7a1ed8131b135.nq.gz
    ├── 41c5bdd54b6621a08e2cd5221aade8028717e79b.nq.gz
    ├── 4206516f71f7d999a634499539d64a5ce630b431.nq.gz
    ├── 42909c49f2560537fd9c860da8bf91e206d2d47e.nq.gz
    ├── 42f8812e0678dc36dff6c066b72239319df94802.nq.gz
    ├── 432aa91c567269dd5676f76fca23baa0be4f9141.nq.gz
    ├── 43364e09b6b3c2d421effa82b8186dfdcd55bf58.nq.gz
    ├── 43918558fb0ead884b3fd725e8a21a7a32fa3c69.nq.gz
    ├── 441b3eb8d2df43a0b9e030cdfc1645e1f2b43aa2.nq.gz
    ├── 445f0ffa5a2c6535a802fd4427dd047878017341.nq.gz
    ├── 44ca69055189237f3dbb5ed2ceb9fe3580b50542.nq.gz
    ├── 4500208cf444ea73a803e6f2c13c8fc37569022a.nq.gz
    ├── 4515ddf65b96aefdf947276e762c26f28fd670f8.nq.gz
    ├── 454b849ab2d910796648c1f15d3ebde14868b456.nq.gz
    ├── 47abe214f9c1267965beb957514a216b8ceec67a.nq.gz
    ├── 47fda1c549241a8698f516800eb5cf5f44a8dd80.nq.gz
    ├── 482113bfac35ca4a29e1769a2faa3f65e99ec67f.nq.gz
    ├── 486e8878a38326b9ce9298334cc3d4dbcb6ff374.nq.gz
    ├── 48ef8b039066ca6c93ed1e99ded0e9e3f4d766df.nq.gz
    ├── 4938ad133490236e8996fb7c74f31db877fad082.nq.gz
    ├── 494343042c791dbf226f478b3183079e34f75d93.nq.gz
    ├── 498f529a64502f3e1fee7d86ac50cc1fc8292fd7.nq.gz
    ├── 49c4bbe5720f721dd5ef4646e9deff3ef5986d76.nq.gz
    ├── 4a272e1b30c451dc99f4621fabe9158f844b3ee4.nq.gz
    ├── 4b590e694073bd5329642a74275a9869e1a51730.nq.gz
    ├── 4ba8cc900034b2982a470ce0a944617f8925a8db.nq.gz
    ├── 4bf614e9941a3a25e7fc83540cd49bffd072aa53.nq.gz
    ├── 4c73ffb986a5600642e8c03515cb3dc5cf144e85.nq.gz
    ├── 4cbbf42517ba8315c3985f25dcf9865119877cc2.nq.gz
    ├── 4d22c1aef24ae6b116608b54ef428ca2dfa04e98.nq.gz
    ├── 4d4cb78b6168dc718e30cabfdf76eac35cc2b7ef.nq.gz
    ├── 4de831402d71e827b7f35bfe83f75ac3243b42b4.nq.gz
    ├── 4f0e8561b60ca7c41efc6a28d09b31c759426ad2.nq.gz
    ├── 4f6ed77f7d6cccd87ec538a436630bd033fca2f7.nq.gz
    ├── 501ec4adab8736590c230e429c2749bf3b490648.nq.gz
    ├── 50239f9e16b83b0cac6733a992cb1bd8eff92f9c.nq.gz
    ├── 50dab95a3a0e9407e320d989ee328ef13678c02f.nq.gz
    ├── 5151d7af2f9b49909601f660d0b08ec98301418a.nq.gz
    ├── 5164f51e658037d2a638332908dbf9dd0dcfd935.nq.gz
    ├── 51a0f2e0ceb0c38df3a176c94357ea310fbcc7d7.nq.gz
    ├── 524e44ecc8adfad2cbb0affd99a729b785932a52.nq.gz
    ├── 52b891148a59a8f98f8ed0ee102b9455ecf03496.nq.gz
    ├── 5302c6709e025fa94c8afe7f24ace5bf89ac18d2.nq.gz
    ├── 53541e4eaf9a7cada9cc12cd537ec4e4b18d64e3.nq.gz
    ├── 538b1ebd8bea9181164afa52b047f5f6568a130c.nq.gz
    ├── 53ef56705b1b3b3c72b92d93282332b6ab03d878.nq.gz
    ├── 54d274e001fe81d3c6fbf7d0cad598a556d67181.nq.gz
    ├── 555eb81877db594be571c64c37d0fc18ee913399.nq.gz
    ├── 557360dfe55eebb28e3ca2e95b3c74f306d782f5.nq.gz
    ├── 55d5efbe32e153624913ad634aeb64172d98b34a.nq.gz
    ├── 563f123f3c966be126fcd0cb051d527b0c175f14.nq.gz
    ├── 5711ac6b7ff39a042c5020fb74b345523b1c86ae.nq.gz
    ├── 574d1abf47b587cd0ee801923dd905d0a21c09bc.nq.gz
    ├── 5952a5b7df4f976bf02eace210e3b4f3cd4e72f5.nq.gz
    ├── 5990ecbcae4d6dfd66cc517feaa3939d37e719ed.nq.gz
    ├── 59ef3ad3d9606b651ec98c39976599b2c75bed8c.nq.gz
    ├── 5acfa0d8939f1655f3fe527d6e991d0be20a2fae.nq.gz
    ├── 5b00478d4690e06f5bd002bf7da21d67509f4108.nq.gz
    ├── 5b204a6c0d9e106ba1e9510ff7474dd6a5554ce5.nq.gz
    ├── 5b4cbc74d5ed0df2ce5f169e48df90980975c698.nq.gz
    ├── 5c300067c4e4151838b94d5647772f9a7aa6f49e.nq.gz
    ├── 5c3ee868b296f82b36fbd02bc3e31593a5de7c37.nq.gz
    ├── 5cd87243f02c7b33471b93f35ef6b59482863ba3.nq.gz
    └── 5d0d37658e9461760378518f2b8d97797dee061a.nq.gz

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

[kuzudb/kuzu](https://github.com/kuzudb/kuzu)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
