# Repolex Knowledge Graph of canonical/mysql-operators

RDF knowledge graph data for [canonical/mysql-operators](https://github.com/canonical/mysql-operators), parsed by [repolex](https://repolex.ai).

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
rlex download canonical/mysql-operators
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 268e6159c250b1ace7115a44cb8599983ccc472a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 268e6159c250b1ace7115a44cb8599983ccc472a
│           └── chunk-001.nq.gz
└── blob
    ├── 0332222b5c8b58bce7d3a5dd6d05aeb5fdacf876.nq.gz
    ├── 04cc5dd0e48a7185282d56932201e165aa141c70.nq.gz
    ├── 0605cc45b1cac09e8836889580d80d5b4ed256e1.nq.gz
    ├── 06ada066f36e5b323ce9ab87737d92117addbef4.nq.gz
    ├── 0790bd477c0dc1de5e1da841881793551c7b4130.nq.gz
    ├── 0796be0562dda5cadb4f1088b8af1e30091f468a.nq.gz
    ├── 07e0b48cbd1569fbf0e610fa77b6a4e96330574f.nq.gz
    ├── 0900bb33a59d555adc9816328fa6394964e5e03b.nq.gz
    ├── 096918629019ad243714dfecf2af3fcc483d7600.nq.gz
    ├── 09cb7feb881f9d3c3a07c54fb9d62189791b37d4.nq.gz
    ├── 0a7628433a12b5fe311d9066c86eddde83003016.nq.gz
    ├── 0b1663b31cc8115b4f9dd99e287506409b6350f4.nq.gz
    ├── 0b5ac6609f4f961fd4d57c22184815d983c9c01f.nq.gz
    ├── 0b6c58e078f1e1c6f03de3702c00b8a681530cf5.nq.gz
    ├── 0c2341e50e7168291d406b40225e06d4dcb23296.nq.gz
    ├── 0f8d2b78cb739a6e60061ef3fec02df5116cc3c9.nq.gz
    ├── 0fb53e79745a64b61a51938d6b720f0c778f9720.nq.gz
    ├── 1214431b9561e2356f25da771b4108fb76376222.nq.gz
    ├── 121eb99d0840d346c79514b57d8c6959d339f1c7.nq.gz
    ├── 12587fa8206ee47030b19424800485f3e71eeaf8.nq.gz
    ├── 12d1444f08b18a8b1e24b728d2c27bed91264b1b.nq.gz
    ├── 1314b7e4292af33e7607248c05d327319be8ccee.nq.gz
    ├── 13602cb08e7af6ae96472a2421a9b3dcd2e2b054.nq.gz
    ├── 1420dbe56bfd26863bf0787789b807cd25776d34.nq.gz
    ├── 14c376a32845be6843a0830bebad8cbee7cc3934.nq.gz
    ├── 14f3f2bcefe45c16bc61ba56b067d1d4bb675ca3.nq.gz
    ├── 15a78cc947068237f94cfd374a6ba7cda9d4e798.nq.gz
    ├── 16277ef16bfe9016bd59a14f39c2a9976320f6ff.nq.gz
    ├── 165c0616dcac2457a353b3fa05ccbdcb93ef9e43.nq.gz
    ├── 168de93801407ff062cd5936cdb93f3de74b60d1.nq.gz
    ├── 16b10e14c9d810c748d63fe3a6d5419261997b2d.nq.gz
    ├── 1750cfca4c9edb91da0e83a04d1d004dd53aef41.nq.gz
    ├── 176f8ce79e77736f12c7681f0a7042520e1aae1a.nq.gz
    ├── 1818ad4d183aaaca7f14a62491368c588c7065ff.nq.gz
    ├── 190206971a215e891435e81ee5af0785606bfcbb.nq.gz
    ├── 1940944ec1bbc77138808a09f435f0cdd55e10b0.nq.gz
    ├── 1943e16b9034055ee9268070ae7f6d69a7a633de.nq.gz
    ├── 197d7b4c1c42eb7dea0468ce50f9bb0ccaf02eb3.nq.gz
    ├── 1aa630ab098f8d980b099356ec17ef9d7687f722.nq.gz
    ├── 1b52f070e24b6d8cc2fa7900781db34cea1e5156.nq.gz
    ├── 1b5d797d978faa6f06b185af664b42918b618dae.nq.gz
    ├── 1c07177c3f40dc2364a350e3fce0414edc969e1a.nq.gz
    ├── 1c2e279892bd6a79b7c7d2ae7d1b81c574209e49.nq.gz
    ├── 1c34bae0cba3795acd454d0ac9ace1e7374ed534.nq.gz
    ├── 1d46aad793a0de3aa8168143217ee1a284de685c.nq.gz
    ├── 1d87c06d974259a1be963e4595b6e69c59d1d496.nq.gz
    ├── 1dd679fa184635a9b6ce56a6ba2435a3a6cd1655.nq.gz
    ├── 1decbdbbe3bfdf5e8d7426050d59495bc592a0fc.nq.gz
    ├── 1df903fc15b05760d8263c1b3eb9506e6f70fef9.nq.gz
    ├── 1e9b8d43ec080bfd573e338afde448cd7ea8ff24.nq.gz
    ├── 1ec774db07cefcb3f14754b7e94f83f1b8d0a190.nq.gz
    ├── 1f2ce92d5f8b6531ed1f2f0e34b9212a3f95d9fa.nq.gz
    ├── 20484c333c2a3352f2c25d00d9a51da50524458b.nq.gz
    ├── 212ff299b82c833394b1067a7751fc197a357386.nq.gz
    ├── 223877f4d995086ab1a5260a44eb5d715340c93b.nq.gz
    ├── 2283876aabff40d2eac8045b304abf90d71e48af.nq.gz
    ├── 22daad6503decb99225b0d9199c0fab528500f3f.nq.gz
    ├── 232007ac2887c2cdd8fc262d4dbc920e120d8c03.nq.gz
    ├── 237db2adceb42fabe49bdbffb69c19436b14960e.nq.gz
    ├── 24ae28eb64290d15d180c3a0e3a2f4985a8aec3b.nq.gz
    ├── 25438fd13d599da81e2087aba3764d05e4e303c1.nq.gz
    ├── 25d82259aba9bbc77d898cae4253c617247d7a59.nq.gz
    ├── 26815274aeab1fd69d4c0f6f54e3b12c0c8358a5.nq.gz
    ├── 27a233b13a79431e53fed3053198d580294cb8f9.nq.gz
    ├── 28bcabd30680a071cdeed7cf5745f0c6a7913a91.nq.gz
    ├── 29ede242ff455a64fa253000d80487a0bb723248.nq.gz
    ├── 2a07e2416b5b14cc3d6a7814d1a803182099c04a.nq.gz
    ├── 2b09555fa487b99dce09c5e656ca5eb0362376f7.nq.gz
    ├── 2b72cbfd0053dd5647193506bd94c7efa4a6bd54.nq.gz
    ├── 2b73cb730a352a6ea764c779df081d9bce853b01.nq.gz
    ├── 2bae6aa5ccfb6eac832b3cf7ff09ab81cea92cb4.nq.gz
    ├── 2bb2dd08cad233c91908beee6bb3607163752ffc.nq.gz
    ├── 2d82d0f846e87541f144cb998f37c61db64924a2.nq.gz
    ├── 2ed5ea2263353e292fb85d8328466b550060ae62.nq.gz
    ├── 2f925fc954d1742c6f1e589473337a50c4582538.nq.gz
    ├── 2f9e0934763b4b50a1b60242b422d5ae63f9ee81.nq.gz
    ├── 2fef88b85831f78fca1ba1f06f4b06da923bf866.nq.gz
    ├── 3006f13e199b573708dde2114878ca4fa8071aeb.nq.gz
    ├── 3024fb2fb8fdd486bc19235befc71565e63dba57.nq.gz
    ├── 3153c64e65874cf47b9e47c914833759fc7757be.nq.gz
    ├── 328f12a1a0129f284cfe7b3dad86f59a8e0461ee.nq.gz
    ├── 32bd9eb9ac5e17dc6903c270e5f226740af06b60.nq.gz
    ├── 32c3bab632e8d2b0b00e1da1e65237667e8aafd2.nq.gz
    ├── 3362e4bd537f9f7fc659ab4c940aff76db356266.nq.gz
    ├── 33be128e75b565300c471f5977ab206d4cb7698a.nq.gz
    ├── 3423fe1c406135b0b9e74abe76f3cee6b48892a1.nq.gz
    ├── 34c7c1ec1a724fd00de437fd9ca3f56701922051.nq.gz
    ├── 34ead76c98cf4a15f0777512ac0f1bed60dd0d47.nq.gz
    ├── 350f2c037428a493622efd0c2548c3572bfc58b0.nq.gz
    ├── 359c3e4decb980aee75473346ff8bd7a5d4b81f3.nq.gz
    ├── 36356ef6ee9923097d74bb1ef817840dc9bfda71.nq.gz
    ├── 36c1916082e8145abfbf3f3303611edda0263c04.nq.gz
    ├── 36ec3bd8d429305d44a087d179193ded038a7cbb.nq.gz
    ├── 36f8d0df0968b2f23466846e77061c0a2f3a34bc.nq.gz
    ├── 37f5732ca6e6738cae474b2c0da7071f8bc7d9cf.nq.gz
    ├── 38516fa446c5541094ff3b6d44757d6c5b8b9a9b.nq.gz
    ├── 3878f3d25a345103214ea9e9f90d2dca39d98cb7.nq.gz
    ├── 3924479e4dc6b927f54285f9bf14b6e1a5250151.nq.gz
    ├── 3934f1535c8bccee8e23cb7b7df69c3f9421d0d9.nq.gz
    ├── 39cb964643e1b7127528ecabb8812f32ed451e7e.nq.gz
    ├── 3a3c1d7529856a0f36f92a7cccf7821d1dea90d7.nq.gz
    ├── 3a436794e5bf6fc70f86d077a9e205ad6c04b4ef.nq.gz
    ├── 3a501279e8e1a0e03022f905b7e2db1237012e8b.nq.gz
    ├── 3ab2c4ebc51cc527d92f431ecb45c090d382d5c7.nq.gz
    ├── 3b4355d6d01e3f28c2dba35e08f5a26c697402af.nq.gz
    ├── 3b83a872d0431b4e740b4fc9bcab578f114e2a88.nq.gz
    ├── 3c110467866a38f24c86ce5646afeb27678d6422.nq.gz
    ├── 3d542ad9fd7cad788c05d38d780c6843c379e626.nq.gz
    ├── 3e0197ead002f4bf402caab1df956b2f6b7a8c01.nq.gz
    ├── 3e7c15394ea904a19c702621e6e7ba2faceb4add.nq.gz
    ├── 3f50c1fc315319ef3d9de8c34efa1ba54d3e12f0.nq.gz
    ├── 40cf4c07598a88af86b720027d3c932c2f2c06c7.nq.gz
    ├── 4126d08e1ce51e3cc5a2a9bd5f8bfd4b26e48aa3.nq.gz
    ├── 41b66904a8ce92807e301bbd617c3f93e6e0b93e.nq.gz
    ├── 439064c32bcefdbcbae4a3e463fd4fced91846d8.nq.gz
    ├── 43eb91e9afad12c2d1d3ab60b2ccdeaca4cfc693.nq.gz
    ├── 440d09fbba855f8cd3c73d77b8b34692e5f3ca4d.nq.gz
    ├── 44bca01748fd8f4ad31660811b39edcb87f6b748.nq.gz
    ├── 454c9389b433c54a5fa18f9770a9ae7b3df4df84.nq.gz
    ├── 45696ac366c480b879b4abb1608029fc080c5474.nq.gz
    ├── 457782c517da7e8d81f1faf39e3e071c29efb789.nq.gz
    ├── 4586404424e3d07893bc3c5da0ae943897ce300c.nq.gz
    ├── 45b708a20c9ff6959eaaef485bbb3f82d5757038.nq.gz
    ├── 464205426df2aff2a2871cb29414d90443c0e07c.nq.gz
    ├── 468abf08567ec52a46c5f601e560ed7a0ec648cc.nq.gz
    ├── 4714e3304c2bb3982fb415927308d0878e92b154.nq.gz
    ├── 4788cda93fde023b000d20c0edd92ea25a2ed895.nq.gz
    ├── 47eae891052cde709512893dbc0299eea0b0745e.nq.gz
    ├── 484129e130e956ac099f9ed3bef7984dd62cd175.nq.gz
    ├── 494af9d9d63f22e7422960bc910a1f64d51953af.nq.gz
    ├── 4a23baffea7bf25040b580441809c31d2abd200c.nq.gz
    ├── 4a30fb181826b8ad932ab9b21e3ee8c75548178f.nq.gz
    ├── 4a52142026170d754c50ba4caaab8cc9253d0816.nq.gz
    ├── 4a9b36defa64cc38284fcc80aa19a763adfdc474.nq.gz
    ├── 4ae014e2ccf0a23f246827db13ebe71a2e8da995.nq.gz
    ├── 4b2ac03809836e0ca22da0eea5001e194a9a453b.nq.gz
    ├── 4bafd3710476d800f3fff6029e09df6374e2fef9.nq.gz
    ├── 4bb03e1d8f4aa300b7574ec0aaf093ad82be6bf3.nq.gz
    ├── 4d90d1875baaa5261c56b7106bdbc074bf555d94.nq.gz
    ├── 4dac6d1d944b72ec718aa9a8225e089f9a857609.nq.gz
    ├── 4df04ddaedd976523b5ff9b9087011cfbd241d4a.nq.gz
    ├── 4f6d958650e5026d7960a3019c9cc8e30ea7678f.nq.gz
    ├── 4fd87c9d67b01a6fa30b6f47d5dec911dffea441.nq.gz
    ├── 50c658b514bf559351303cd1c3005656edf5b6d4.nq.gz
    ├── 510f9c7064f990e7060d86dd6e3b17ebf7af0a62.nq.gz
    ├── 51a547664ff982de045864ec5a61fa67a0017406.nq.gz
    ├── 525a36900fbd85247300c0cd6a5b15257850f7bf.nq.gz
    ├── 532edace101d3ee1e97792d3e0f097f6d8838151.nq.gz
    ├── 543e70bbbc21d362100320d8af53b82e6ca988f7.nq.gz
    ├── 54622586059a4ec8dc278545c794330f5511a3da.nq.gz
    ├── 548be6714efc090168111bdc100385190cd05fc5.nq.gz
    ├── 549bc776cec58d972752e0fb9b8cb2e86ee36334.nq.gz
    ├── 54e6d2cf9ed5a119ee792ee513c5e585657af4b6.nq.gz
    ├── 5512b12fd9d14b07ffa904031038e25b69deda5e.nq.gz
    ├── 554d06d1500bcad59ce9d4c7d9d87d908b3bfbbf.nq.gz
    ├── 565c6b0e982f5fa3dd4e40756d5daae92f27dffa.nq.gz
    ├── 57498aae55fd274510a3b32bdbf5f84de35e5971.nq.gz
    ├── 574bf43e390092eee62f72c0ddd25e4ccd47df50.nq.gz
    ├── 57c19cd3d2e481085153b6419631589b815b3e77.nq.gz
    ├── 58a2d6424ccc998fc2710848b7863dd1e44bbf94.nq.gz
    ├── 5acdc68474409ae607d3aa68d6386ce795a7eb53.nq.gz
    ├── 5d60a82826d914c081b3bc8005f2d1a22ea12c53.nq.gz
    ├── 5f10d654f36b4ce6309c952d97d15eba755e7c70.nq.gz
    ├── 62347a50ffe861065134d249c99407816bb9a761.nq.gz
    ├── 62900735905bf01e55633f54cbd520530c92161e.nq.gz
    ├── 62a9238a806a03b0e108950e8c305ba66b81997b.nq.gz
    ├── 6340aa080ef787dcb49eeda1af4f2cba56785281.nq.gz
    ├── 6360f822855827fd3d87ea8e171a1d3166a6c6b3.nq.gz
    ├── 65f733231b603c203bc542a6b3847868d053b6a5.nq.gz
    ├── 65fcaac6dea55051e61b18413606d3d3e7357d1d.nq.gz
    ├── 66126436a58d27ba80a718c0104a077fe8e6ce95.nq.gz
    ├── 6709bc81bd9e2e6dc220d8024ff7d36563673e57.nq.gz
    ├── 67280c6cdf46212c455487eb912364a092cbb480.nq.gz
    ├── 67ec3971a56b2d3c103b67e4f798379547bb79f9.nq.gz
    ├── 690df95a09afec0043776bc92c3a502523014ba2.nq.gz
    ├── 699ae071b16ea7f07f3a58c27efbae0005be1ad9.nq.gz
    ├── 6a64c5f0d4380c3f7137168d099a7154212739ca.nq.gz
    ├── 6be80faf05eb98e9baded4e316beacb3d4c060b1.nq.gz
    ├── 6ca820d5c5130e4136a2913030fa8912bf6c2a50.nq.gz
    ├── 6cca9c1485d4685a6d17294bca547adc69d68644.nq.gz
    ├── 6d8dca486828bc44309593831b1d56e56f901cec.nq.gz
    ├── 6d96cbea13d9ceeb851548ca8086e736ba2fcd79.nq.gz
    ├── 6db0f4db6b50368ab98a87437c8c0bb66d211bc9.nq.gz
    ├── 6ddd81b73bd7ab5d84edf7ad4933e692d1f9c269.nq.gz
    ├── 6eaf294bdff6d996bc261f585ad7d1eb951916ee.nq.gz
    ├── 6f000bc945a39f2702d41501c024248471b289ee.nq.gz
    ├── 6f09144829799f6feb8ccbe02fd99f22d41b6ba0.nq.gz
    ├── 6f1f13303d4a172cf9df89fd952d82f42ce21003.nq.gz
    ├── 6f4d8bc1c7ac3da53d328bd950a896cf21c3943b.nq.gz
    ├── 6f94cded4fec60283aa42d48789f2f779e32bb9a.nq.gz
    ├── 6fb0178cd6e7e11794920f45a0e23e7c2f833c57.nq.gz
    ├── 6fb68b6a3523fb82f0c91bc2d985e47e1770e2a4.nq.gz
    ├── 702078687eb41db1f02e6f1d30a9f676b0153e7a.nq.gz
    ├── 704a13c77330dd656cf14605edb58c6112bf7d32.nq.gz
    ├── 70695457980fe9b7c5b0d68afc5d836fc055f687.nq.gz
    ├── 707049fb613a403bbd4fd31a8a189b30bb8c4253.nq.gz
    ├── 70829676634e809375784f72cfc6848f08e0521f.nq.gz
    └── 7292da78cb6e79f16f657f6c5521ad857aac1c64.nq.gz

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

[canonical/mysql-operators](https://github.com/canonical/mysql-operators)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
