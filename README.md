# Repolex Knowledge Graph of GhostPack/Seatbelt

RDF knowledge graph data for [GhostPack/Seatbelt](https://github.com/GhostPack/Seatbelt), parsed by [repolex](https://repolex.ai).

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
rlex download GhostPack/Seatbelt
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 392171df84472591d4eae7ebd5b1cdc96ba91377
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 392171df84472591d4eae7ebd5b1cdc96ba91377
│           └── chunk-001.nq.gz
├── blob
│   ├── 0268fd6d8579d548d8e0b6a566716f5f48b790d4.nq.gz
│   ├── 02e1219a987964ed8c7d2ee2f2e03ce2ff080b1b.nq.gz
│   ├── 03e9c5a897e0493cb0b3153fb2a705c6da111bd8.nq.gz
│   ├── 047ab127788f40d8c2740b9bf730f1be240010ec.nq.gz
│   ├── 0958e69f4eac374dc725d801aff260a901b7d816.nq.gz
│   ├── 0a01560cfeb30058ca9953d22f40cc582f006a9b.nq.gz
│   ├── 0e7ac50636f742b24c43af0b61a4446615f098a5.nq.gz
│   ├── 0f1829ed0f6aaf0894ab070989d5d2f7331691b1.nq.gz
│   ├── 11401903eb53351d06a254319bc99d7cdba01b9f.nq.gz
│   ├── 13a2d100262207680c6194100a3160270226e8ea.nq.gz
│   ├── 13ebd2976bb91d650650377291659fce32440912.nq.gz
│   ├── 151328cb99441241bba07c83c4408444b5d720f2.nq.gz
│   ├── 175f2cce41326f3f57d915bcddd96ef6424c31ec.nq.gz
│   ├── 19ae32e12fc7444b0722771bb28bf6cf9e173d19.nq.gz
│   ├── 1b8abd1a9a67bf55e20f3cef809843df7bd65cd9.nq.gz
│   ├── 1c00bea5e0f843c4b4812411c94aea1ad345cb42.nq.gz
│   ├── 1ce845075d9fa23bd47f31f591d27725ab1a276d.nq.gz
│   ├── 1f073d470ce1befc9d291db211712885fc54edaf.nq.gz
│   ├── 1f8c1dcd5aace67d3e4cfbb1558fedfa74c3012d.nq.gz
│   ├── 215c55005b084b278e2d4015fb6fd79d3b9452eb.nq.gz
│   ├── 22e4fe21b0309b0f5cd9725a4d93ba4219955755.nq.gz
│   ├── 238bfc2bd863aa7d03b9ad8543ac697c4cb6dc13.nq.gz
│   ├── 24a354c6baa30ac3a7f3562512ca72099b1f86ea.nq.gz
│   ├── 24ae14b965f424c5a21a44cb8c3942d7caf2a1c2.nq.gz
│   ├── 258649165cf76c7375e47ab60e1c9c5278941493.nq.gz
│   ├── 261a33eb79c2ef058affc3445d42f19beafa8dc6.nq.gz
│   ├── 288b1e7e0f79743625edcc5536f941d54c5e795f.nq.gz
│   ├── 29d4385dac572a34fe0f35bb8d545bf972910393.nq.gz
│   ├── 2b2015c767aff4e78f3a682fb4e3405a5b261f43.nq.gz
│   ├── 2b2f38c82b7752b196f3a36ca6f9b79a69a6a19c.nq.gz
│   ├── 2d218ee6b5e3aa2e64fa79330574a1ff5759e1b8.nq.gz
│   ├── 2d9cdd63eb82854f7c3000bd8b4bdf4b3bcb5e46.nq.gz
│   ├── 2dc73d2aaee7d35047a808f2e3607ab64cb47ab7.nq.gz
│   ├── 2e70ad9604acae0744dd7c652365c7a7193b9931.nq.gz
│   ├── 2f4ca9aae354d8dac8c7a68e6e902e7d72a25313.nq.gz
│   ├── 2fdd61d2f0cc3de7f32e1cb0babf9418705f70b7.nq.gz
│   ├── 309e7cf3785ae708ec834524a1c19bb0696c67f2.nq.gz
│   ├── 3139edcb253e0a77c5881ffc569249609f4e04ae.nq.gz
│   ├── 324760f164829d4026f778ad35e0f416757c2c0b.nq.gz
│   ├── 3484ade94470ef2ef44b7ec3f5f1fd1158a79049.nq.gz
│   ├── 34d35c50ac665e0c8e898a3703e7e7e775e3ffcc.nq.gz
│   ├── 357b6a82b18f85b0f6953314044475e8114c876e.nq.gz
│   ├── 366d5524902ff7f4824bc53ad3bd0f2002946e20.nq.gz
│   ├── 36ed935ef6941663716b656290d069bfaf4ddb0e.nq.gz
│   ├── 3818d2875102c563e89086a4b045a150a6a01347.nq.gz
│   ├── 386897c5e62ee15870a216f7e3c0319dd6579f81.nq.gz
│   ├── 3a62a2f0e66f43d633f9528f2c2e6ad8925c5da5.nq.gz
│   ├── 3a6f400e8526bee02ed9a16e3af86802deaa7303.nq.gz
│   ├── 3af82754eb15b9355b1549a14a097738a48c6422.nq.gz
│   ├── 3d085e4f69ccf55f88361c6164989c476edd198e.nq.gz
│   ├── 3e6ca1d9356177f4b8c3cea28d797a041071c72d.nq.gz
│   ├── 3f2c39ab47eb9846269479eccc7f20e0b8298e47.nq.gz
│   ├── 428388cbbab6d0f0cb0fdd5ba816710960c50836.nq.gz
│   ├── 43d51bbfe75dfa15e62eff8a7c397f801f9e6dc8.nq.gz
│   ├── 446f1f652ac2561453cc556fa3e17d0c5359475b.nq.gz
│   ├── 45a8cc221adbe3451154e1402dfc87654d3b8d79.nq.gz
│   ├── 45b60b445ae65a67d08215ad9ab48426dd59739f.nq.gz
│   ├── 4c0ca7cefe3c0122a687b838a3a6eff8581e9868.nq.gz
│   ├── 4d5a232df89bc729d604915098594ef8d9c891ca.nq.gz
│   ├── 502dbc35b7f4f118831143fccb2580f99ce41ad9.nq.gz
│   ├── 503e046db32642e0c44fa50bdda19da9d9e8db1f.nq.gz
│   ├── 52f7c2598ccd990fee9f389b98a0a6398195b6ed.nq.gz
│   ├── 5327aa8fbd1f6f3a528dcc7973a8f4cf062d4fb6.nq.gz
│   ├── 5515179e8a9d1d8f0bbd66a567f490f8e433c1ef.nq.gz
│   ├── 556ec279c26d76c540aaf4c41100a8d2f5e502c8.nq.gz
│   ├── 55d9fab56c300fd8b74c26b8e7fb005e82d7e41d.nq.gz
│   ├── 56202cd6303ecd2313124f615e8d09e486027297.nq.gz
│   ├── 56b4834213787272c4a8d8712590602dd2d69e38.nq.gz
│   ├── 56c82fbf1eaec36f3d4aad22f2ad2b2441492c79.nq.gz
│   ├── 576f8af51a848db129029e9bf4d7ec19b40a8d8f.nq.gz
│   ├── 5ba1580dc890de507343165a0560defbad3248a2.nq.gz
│   ├── 5c1ff6795eae5ec2798eb0816b0a9b372042a05c.nq.gz
│   ├── 5cb3dd2aa3ae846318a242c8125a55ce046044e0.nq.gz
│   ├── 5d30c635eece01c31a08ac86ee991de0e490d7c8.nq.gz
│   ├── 5e5acf80ee1884ac384294b0d4c05680a8ca159d.nq.gz
│   ├── 60a9f5dd07929439203d8e16fed4127a78201f1e.nq.gz
│   ├── 6119de709afdeaca01cb144b337f650dd3803766.nq.gz
│   ├── 645630b1238e194f308bf573aa7493d0f765c3fb.nq.gz
│   ├── 64b4b47d168b9a7b6a92c9a87703a197191fce4f.nq.gz
│   ├── 657ba4812afd2125af26b56d700a68a3c33ae2e3.nq.gz
│   ├── 65dab38f57bfe92e2c0d005df762eddd9d4663da.nq.gz
│   ├── 6761f62230191b2620ad50f63251b07bb1acae0b.nq.gz
│   ├── 6a7b5e42a23932a80d65b2e3c8c2d9f3eebdb5ab.nq.gz
│   ├── 6b7f2f706bd9b2810081996533fd45f29efaa6cf.nq.gz
│   ├── 6c7f6ef2ac6d55187fd1a7204fdbb87d875ab55e.nq.gz
│   ├── 6d6be2f1857bb58d8dddf33f0be8b1c2c8c4c16e.nq.gz
│   ├── 718472a4f176ccddb43af0b5c3ddf8921182393e.nq.gz
│   ├── 72da7159b7b3450fe4ecac87f8e9819ecb156ba1.nq.gz
│   ├── 76d4ae854e0cccc43d14e5ae69a91b6fbfef63c9.nq.gz
│   ├── 783aacc2be27a6831d3183c6b85d14c6c8f1212b.nq.gz
│   ├── 7e14b04097a4fbfa89f1b1c4ba6adc66ca1a50ac.nq.gz
│   ├── 82bbbc7c78bcf19801c409a39c09e3148061d2ba.nq.gz
│   ├── 82fdd262ddaebca28c7e749b1858dce5894845f1.nq.gz
│   ├── 85d0d50dabb8b1c1c3d1750390df09d445dfe6c2.nq.gz
│   ├── 87b3b0fb29f8aeff0d05eb57225ec5951b576e83.nq.gz
│   ├── 8b3ba3f1279c7573f7b01db77580ccaf977b254d.nq.gz
│   ├── 8c07199070429319e6f44bad5b5d747edb22eeb8.nq.gz
│   ├── 8d27f323117e05372a1be6c4d69aadcc5f51a592.nq.gz
│   ├── 8fd35651bb4c94136cdc083b714385d5ea18b5fa.nq.gz
│   ├── 910d8fb0a8d972fa094d351b78b2d94620f0f1c7.nq.gz
│   ├── 91e448a61a55e5488bffef14ffd4d41f0006b9ce.nq.gz
│   ├── 93b47afaf4267ae5c9bf31cee54d6ae88aae60ba.nq.gz
│   ├── 944cd7d62dad0227c574f7d997e609ff058cf217.nq.gz
│   ├── 9474e7ad706579db94fdf54aabf5a1564144ecaa.nq.gz
│   ├── 95648667afb5adaa9e2ec3dc032ad00c882e9812.nq.gz
│   ├── 97339c27d2864099a871fe9cafafcac82d466db8.nq.gz
│   ├── 97c1702051189603d31dfb29bfc4f1879e0b7648.nq.gz
│   ├── 9859e8a2a72ccc64035b4875eb3a15767c42dcbb.nq.gz
│   ├── 98de47597b58e2abb405e2abac7ba887d4644264.nq.gz
│   ├── 993765416dd7009bff8c4280cb434605fc23f367.nq.gz
│   ├── 9a0f14638a111a7687dbdb81710e73941ef41e1e.nq.gz
│   ├── 9b6d6b8e4c71e563b068d083da73c2de8acf5e99.nq.gz
│   ├── 9ce399c5219b053b6052ef8761746a0761595784.nq.gz
│   ├── 9dcf452792af502ea289916dbe0142629b5d4fe4.nq.gz
│   ├── 9f60d2f3a8c9143cfc3c5256f0c5306787a0322b.nq.gz
│   ├── a09b97f801c6c4d059111e497cf1b38057dfad7a.nq.gz
│   ├── a3cf752c0370bfe80f727a79c59367cb12713421.nq.gz
│   ├── a4116fa121345581557e919f4ceb050daac037de.nq.gz
│   ├── a73b5655b68e9816dd8f435ea9f6db565ac3d472.nq.gz
│   ├── a804f9348bf0e6592bc53dd7181866969ae15c16.nq.gz
│   ├── a863cda59078f3b2cbbd2335fcdd6aefc6b2c509.nq.gz
│   ├── a88dd5a3544886687bd365e008d0e69f153a4dee.nq.gz
│   ├── a8f0064531495555d9e42985b2906458bbc461d9.nq.gz
│   ├── aa984b3e027d30af2c81192d5a56e600d873f307.nq.gz
│   ├── ade7105c255586ad270d7abc4cdd8b5d9bc6e4e3.nq.gz
│   ├── b1964e8fde20a99d4060cd51fa61c8ef8fa5ee1b.nq.gz
│   ├── b2cea99cf6394fa727a278cfb53b1a8f2caf1c0e.nq.gz
│   ├── b309ae3bae1d44d704c1d37eaa8939b6c5089864.nq.gz
│   ├── b325af11954e72671b9d3e964a52a87df42a805b.nq.gz
│   ├── b5e86b10ec796c15da963e41cbe68ef1bd272c86.nq.gz
│   ├── b76cfa5c2cee860ed3e13e985d0e46ac832959c9.nq.gz
│   ├── b8630063f9eba7c62b442fb8b3edba473b965391.nq.gz
│   ├── bba530bf5f0b5ed5620650d9206043ae3d88652d.nq.gz
│   ├── bc5f9a7fbcf0a32cb834e20cda81a457fdcca798.nq.gz
│   ├── bcbcc08f44d7b0f6396a10a17289f1a3f43454a8.nq.gz
│   ├── bedbf931005134b633b1b482b36d757e36c09727.nq.gz
│   ├── bfa96b24fe213d60e5d5f7a32645cdd89ec69506.nq.gz
│   ├── c1552729ea07cde2fe19468997761b18c296c889.nq.gz
│   ├── c233ea1a2774bd0fc8e2d9ca3ee0a5283f242953.nq.gz
│   ├── c36bf5d773f0846ea03503cd1d7d1e13bbe5ce17.nq.gz
│   ├── c71517de23b0fc4ba3114aa42694698d3dc1a6c6.nq.gz
│   ├── cbe072c11f270129dc29078877d45a993a2130a0.nq.gz
│   ├── ce2846c39e5fb86b91bebfc5c1ebaef22b31f962.nq.gz
│   ├── cf7e7ab70a4d28effc3e5b21d3f0b87e5c6655fc.nq.gz
│   ├── d0546dae344c3ddd053b979e8032a3571b02c042.nq.gz
│   ├── d0599878a33712aa74156e4339a50d2f5e581a03.nq.gz
│   ├── d0816a66d233153bf6bd3b1dd6eaeb4ae0e34820.nq.gz
│   ├── d13468f99c3504cc452af594f27e865b385af765.nq.gz
│   ├── d19bdf61b543f91836255c92b04a65ec2539765d.nq.gz
│   ├── d282c1653114c13a5a9b0a6077b88ab4d10a1ea8.nq.gz
│   ├── dc85e18982aa0d42a0024ae7cb4d14d2e1d15172.nq.gz
│   ├── deb3f03723a5d91cb3b56048c486b58af5c9cc4e.nq.gz
│   ├── e119111ef7856d7cc7546b48ecebba556e090762.nq.gz
│   ├── e3403d50cbb95c6ab899eb62f9db9e1ffe934092.nq.gz
│   ├── e3f2cf0da7761d3d4124375247eebe6a83176b73.nq.gz
│   ├── e8d0b51743c11e768458dab0f111e6fb1358ed4c.nq.gz
│   ├── eb77f20788c6d0234572d73f452b31ab37e6d2c0.nq.gz
│   ├── ec5fdbec96ef033115f803f72f9f99ee88ca225c.nq.gz
│   ├── ee18929cf297da900120af57edd5e3be21479408.nq.gz
│   ├── f1c9a39304d0d33287f02c2e4a0b512af2981462.nq.gz
│   ├── f3d0a1faa2ab664d78a1ca0497f0a26a5fe53b09.nq.gz
│   ├── f6280eec5c890c59111d578ed24fcf09029573ac.nq.gz
│   ├── f6a1427dff3cec1f913750e880c709bae9b829b6.nq.gz
│   ├── f6b16e41f18fc98c2bdfe0c5c4f26c9e761d6a8c.nq.gz
│   ├── f6c72fc5e2169379cc1a490b45e26b8b7d3ee340.nq.gz
│   ├── f7e4cbd66abfea574c9c1160e0a6f19e41be5a9e.nq.gz
│   ├── f861019cf079aa756db7a2f8ec3743681ada570a.nq.gz
│   ├── f93dc456f4c312095bec126dc9163e1d4f3f6608.nq.gz
│   ├── f9b4055cf7df56f6d78d3245974168335a2e3dbf.nq.gz
│   ├── fa1f8341c4ab0ffe17f0054fa462be8812b63b29.nq.gz
│   ├── fc21eae3842c1f3930cba8fd392b14c3bab560b8.nq.gz
│   └── fca00a5265e16b5371e96ca2724c8c42d0c73a6b.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 392171df84472591d4eae7ebd5b1cdc96ba91377.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 180 files
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

[GhostPack/Seatbelt](https://github.com/GhostPack/Seatbelt)

---
*Parsed on 2026-11-09 by [repolex](https://repolex.ai)*
