# Repolex Knowledge Graph of facebookresearch/hydra

RDF knowledge graph data for [facebookresearch/hydra](https://github.com/facebookresearch/hydra), parsed by [repolex](https://repolex.ai).

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
rlex download facebookresearch/hydra
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9b521d9a9d1e0b6dd41146d5aa64d844dacc2691
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 9b521d9a9d1e0b6dd41146d5aa64d844dacc2691
│           └── chunk-001.nq.gz
└── blob
    ├── 00e70d3508377466dd10004a5cec0330558f74b3.nq.gz
    ├── 0118989050c55f7157ea62d89ec0ad2aeaf417b9.nq.gz
    ├── 01556e5eb01266d50a1b2f15e07b9ed17f170071.nq.gz
    ├── 0174576e9c33b0d9c04c093e96f4b87415c19094.nq.gz
    ├── 01a31c5c0694f681a186d71b953009774dc3bcd0.nq.gz
    ├── 01d8a8cb6e17d4a932d4e000bdb884725b3abf2d.nq.gz
    ├── 01f3ede5c202b8356dcdf68612a89b3e60d139d3.nq.gz
    ├── 022d26985143d2906eb771d589612c1635b145a0.nq.gz
    ├── 0242d18087560baa23fb11d7d45cc4e4060f8851.nq.gz
    ├── 02480b8a6d60601ac44e9f0632786f37421916f7.nq.gz
    ├── 02a3d41d5ac715412eb576ef861640b02ffe0a87.nq.gz
    ├── 037619898955c60bc9c56c136ef01d529048170f.nq.gz
    ├── 042ce4297d4e6b665a16321959639df1c85b37a6.nq.gz
    ├── 062129187403aeaa26b748a495ef6ae991a36d2c.nq.gz
    ├── 06ff1436ffa1e72428983cdf9a2c3c4cfd29ccdc.nq.gz
    ├── 0776bb5ffc1ca068cc1d7cc44442f77395f939b8.nq.gz
    ├── 084b33998f7c26417d5a07c5a5b18c628b667e53.nq.gz
    ├── 08801aa5e357a8741f90e885f5c7727d9d47c213.nq.gz
    ├── 09644f1d3d7dd026ad7669a928264717640d423d.nq.gz
    ├── 0a459f061647803a4950a25aa0f67ca9b1b68493.nq.gz
    ├── 0a4df44c2baedc482cebba3f2f616cf257259cfa.nq.gz
    ├── 0b2549e4a1f62d6c69bc1d21a254a711a3ec3b2f.nq.gz
    ├── 0b26c3881e6e8068e1c9d2bbab11d73e7b0f390c.nq.gz
    ├── 0bc706033522e32260de049f1de33e18c6f3de61.nq.gz
    ├── 0c2125a802a62241dd4bffc5fa7773801a13ffaf.nq.gz
    ├── 0c40195ae06d562d07c3639daa2242d3b1cbaed5.nq.gz
    ├── 0c7edc28cd61d55a4e5fbbe1e969d3d50480b963.nq.gz
    ├── 0caefd3707854a9170fac58f1809aced3e89a2c8.nq.gz
    ├── 0cfdfb1d84d0b21dc75bc5ac3cf02137dd091f1d.nq.gz
    ├── 0d93e8cb1eefe857f84892ef0b0ed3754db0f22a.nq.gz
    ├── 0dcf91b83b7471267b62eed1fb8e428070fd0f7d.nq.gz
    ├── 0e179b7c33c7d33ed71e968dd50b34030e52111f.nq.gz
    ├── 0e5cff7263d38b0699bd5e5fc179e2e22182cfb4.nq.gz
    ├── 0e6ca43e3488c01fdc198f0570f9a3cd368c03c8.nq.gz
    ├── 0ea654f666ae71a184b07b31a3cf44a91088f40c.nq.gz
    ├── 0eeae2cb939c195af162429569be7332e7e99b66.nq.gz
    ├── 0fe94e5f5f2def8a211adb009db33458c78fb273.nq.gz
    ├── 10fd4a8732ddf873cd986bb63d9c9dd458d880a7.nq.gz
    ├── 1148851f0153d411414e4776adb590a07ebd5fd8.nq.gz
    ├── 139d4a3b473125f5c801f7f2847f3bc41a253b7b.nq.gz
    ├── 13c471d8194ca2917f2358c62c79f6eb6c38f01f.nq.gz
    ├── 13e4dbf45f8dd4643dcce819416eda8a441dba51.nq.gz
    ├── 14282eb048bb2bbe7062ba7b0f7890e041c7b3c1.nq.gz
    ├── 1452b6cb8083c4d6c37aeb0dc54cd5e58c841831.nq.gz
    ├── 14c6257c86e58e80eafd49d9bd6cc8adb5793d7b.nq.gz
    ├── 15d537215e7bc5207b6ede6648792e36834b3045.nq.gz
    ├── 168f9979a4623806934b0ff1102ac166704e7dec.nq.gz
    ├── 16b8b0629e490ef87f0dbcba26aae0f5d71c34c3.nq.gz
    ├── 17e3443282541b9543df3ea6c87a2e09aaa1dc4e.nq.gz
    ├── 17e7463502b510dab7913e32a4b830f9026343ea.nq.gz
    ├── 18912daa5f6460dd38b1d7f6df959949ba4c90f6.nq.gz
    ├── 18dbabe7496168eb28cc8072075e12909fa1b42a.nq.gz
    ├── 18f8daf727e6aa4a12d4711fb1bbc954e17ac524.nq.gz
    ├── 19230f66332a10160963706a28820173fb513c99.nq.gz
    ├── 19467634b98ce5582fe177edab0a4076984c2ec9.nq.gz
    ├── 1aa1f73397e141fd58e6de449b253bad7958532c.nq.gz
    ├── 1aaf0455489b67078845f82a0ee0bac6b2949675.nq.gz
    ├── 1ae0f2a514468b1067ef9ef91be793a77996d249.nq.gz
    ├── 1b15ba99f97e13796d0b7402e740f03188225376.nq.gz
    ├── 1ba5cc849a5bac9f2395dfca90654ce2706d14d3.nq.gz
    ├── 1c24e31afd477bb85f76d013d7f40f08a64bc75f.nq.gz
    ├── 1c8e2add1e47609b908f0e70f5e0f85f5815580c.nq.gz
    ├── 1e76bf008c928e4f4c783c76d060b8a6b8e70d7e.nq.gz
    ├── 1e78044ed86ed1047f5d88eca48c5b30b0055004.nq.gz
    ├── 1ebeab142008cf48758ecd8856835b57f53ea3a7.nq.gz
    ├── 1fc5c173d084da3569f026b92172a135f2d4726a.nq.gz
    ├── 20d50b344dc167d95b14e753451cc7bc33132f08.nq.gz
    ├── 20e9ff3feaa8ede30f707e5f1b4356e3c02bb7ec.nq.gz
    ├── 211cb011edb16d0b5106628f831989012b0fb60f.nq.gz
    ├── 2217b3fb363e077980ef73b2154470f0748ddf7d.nq.gz
    ├── 22934bdb3e70eb2fa2d8c9ad5b876b978e84325d.nq.gz
    ├── 229aa6d7e560c5cd72598a180c857ce6599248eb.nq.gz
    ├── 246e9889c7aa5a5840c22641024160075f58f3fe.nq.gz
    ├── 24fae3f03584888a5222b6ef532cd51cec1298ea.nq.gz
    ├── 24ff83b6edd36dfeec0703e6920e5e112c68e2a6.nq.gz
    ├── 250790fd1d6665472edd3c64afe401b0a0c754d3.nq.gz
    ├── 25168de34634c384632ce3c3e4fab26761e128e8.nq.gz
    ├── 271da520d6631d6201863182d5dcc27c6555a5cf.nq.gz
    ├── 28bc82c1b77699ed384899284f2cb946d1a81f90.nq.gz
    ├── 28d8ba5d22ae7323873e10776d42a0383b3077f2.nq.gz
    ├── 290dc1e4e80a016daca79023fb6d00435b5f4b4b.nq.gz
    ├── 292fc352076d4ab4b23acc0a42b2de4676738106.nq.gz
    ├── 29f0b3fd5eaea87ba166f64c46b3b48f11ae46b1.nq.gz
    ├── 2a05160d2d1d9d28930194d3cebb5e0a1abdbcb4.nq.gz
    ├── 2a8f613b85e1b2af11e861ee9b0d083abba5c99f.nq.gz
    ├── 2bdd02dd17894310967dbeb7533acb41ded3be8e.nq.gz
    ├── 2c4bba2a57a9de1bdaba1e9ba0cef5baddd52f78.nq.gz
    ├── 2d122eaf2a8eb7b11294176cfe7696af4e1a9a30.nq.gz
    ├── 2d616efb0e82ff0092b7c0bbc97d4461ca721e7b.nq.gz
    ├── 2e4a40670386ef0277fb3398d887187bbadab1e3.nq.gz
    ├── 2f9a183a2e3be551efc4bbe055724f17aba12b4c.nq.gz
    ├── 2fd2240242304a0ac125ef295899db695f0bcb76.nq.gz
    ├── 2fff82707dc1845944a0be60dd252e443ac9fe13.nq.gz
    ├── 3103f73b0b2145fffda8da568c3c821800968f28.nq.gz
    ├── 311a855dacecf95b590520318958ee2b6ec96509.nq.gz
    ├── 311d5c25d0d98e1bea39034b5ebfe91d866bf140.nq.gz
    ├── 327c481c7d5d8ec819b3524b7f8306b0da6ff29a.nq.gz
    ├── 32b7656122354edec55004f95d6b9d58d3c142c5.nq.gz
    ├── 32e5a752c302bceb3698640c2548a5d3aba5af3b.nq.gz
    ├── 3338d113aa6a17b2b1c13fa440fce5c95c97b247.nq.gz
    ├── 335687ed445a57d14526d9a4e9a99d72d1a1a2fe.nq.gz
    ├── 34229c3c82b0509fc06e4e7a8f8c1566646edd9b.nq.gz
    ├── 3491c05e544050cd3d0eddb03dedac68550fb604.nq.gz
    ├── 34ae3b96876854cd88ab1beefdca6c781a79b04b.nq.gz
    ├── 353330fe9bc8381743cfa78946ff42b46f50dbd8.nq.gz
    ├── 356176c0a1c9fa4c1ac37f9562412a37428d8596.nq.gz
    ├── 36067445f429d8790f98afe0fe1855ab8840ea44.nq.gz
    ├── 36573151f7710e7725e91b0fe34d94cfacbb391d.nq.gz
    ├── 36717712413483fe2d08c0beea80108c0af8a3c3.nq.gz
    ├── 387a7acc6c8a5df0f1f2fe0f7129fc6a175124d3.nq.gz
    ├── 3a22797a3ec2df661d7a182870576f55ce884778.nq.gz
    ├── 3a5d0ade8a1b58b02a5a01640c589d6be91b6f42.nq.gz
    ├── 3a8bdda26288cce8c541451bc53adff7f4a9a7e2.nq.gz
    ├── 3c4e393178828c68ffd6af0bed2a7d343a74c69c.nq.gz
    ├── 3d0b5a3284c95b18d441e440b9e39ea480698e3a.nq.gz
    ├── 3e20617f17230191ae38b05020fd03843ae082ae.nq.gz
    ├── 3f47f86f3798651bca296e03edbe8ec0fe0e463c.nq.gz
    ├── 3f947b783b22c0280c1321e6cecedda92b1c2157.nq.gz
    ├── 3f97ef706ba620c0cf78690b2d2b3c79cfa6db32.nq.gz
    ├── 3fb463114aab9f5470e5ed7f0052e37d82925c6c.nq.gz
    ├── 407e41e53557016b7d9cac4aa37703ea8afbddcd.nq.gz
    ├── 40ecdc0319d70f44c907632804ecf1aab066e9ba.nq.gz
    ├── 41b11b963b131e57aa1c9672f70390870d829ac5.nq.gz
    ├── 4216dd79cd3134b2e7124bec8cc6fbfd72261e3b.nq.gz
    ├── 4217824d32f1668c54cb1ec7dc6dc932bdd00491.nq.gz
    ├── 43148de1a84b6761e6ae27afad1d8057b02d56ca.nq.gz
    ├── 437e677e77c24c07896808832a67649a365b122a.nq.gz
    ├── 453ce039469a987e76a525ddf7c351805c07a8b0.nq.gz
    ├── 453dfca00f4a13a26442a11d1e3459be0223ac00.nq.gz
    ├── 4585f3a42292072107edf69232d1f0bf213aca0a.nq.gz
    ├── 4617ba2d6d2e368f57576cc92734dfc380bb6906.nq.gz
    ├── 46dc8354e14c39a08ef600dd58d8a1287eddb0d8.nq.gz
    ├── 47da31676db05c16deebc85d615b89f4aa5d55fa.nq.gz
    ├── 48325d54e6be4c1053cf90b93adfaa2388310697.nq.gz
    ├── 493051b4d4d42f5019b5b33d73e44b0e0f1d58b5.nq.gz
    ├── 495fb0ab9f3e25665fbd46ea47ce8b7b76862679.nq.gz
    ├── 4a07c8410e4fd9cbcd23a1fe9fbe65267600bd39.nq.gz
    ├── 4b8cbf47050fe8fa4b20a0ab1fff33c877b26722.nq.gz
    ├── 4bbd69bfb55764d4508cd49d051fc29a6d730ee2.nq.gz
    ├── 4bc24fe1cf92822bf18e154c4b23cc077dca9c80.nq.gz
    ├── 4bcabd050cfb7954c5dcc56486ced9c1abf70cd3.nq.gz
    ├── 4ca261d3dce24f2206484692d4cf2b5152a86b68.nq.gz
    ├── 4cdfd3ddc67be7b6b85970a0faba34a81181d8e0.nq.gz
    ├── 4d6e2217525a80fac584801eed5b2a80e587efa2.nq.gz
    ├── 4e73c9c9cd8db0f011560b296916333215978a0a.nq.gz
    ├── 4f5835bee067062db986dcd40ff3797cd5dfb6b0.nq.gz
    ├── 4f67965f9bc2adf1349ad7db6061fae48fbd27a2.nq.gz
    ├── 5039bdd55883f2bec98daa7a2fcc301f0cb8e546.nq.gz
    ├── 513b2a83c28188d77d267e84ee9187872e026ac2.nq.gz
    ├── 51e63dea74f720a0cc40f94c5686ff65554421a7.nq.gz
    ├── 520a109bbeb5d1e7d2918ce46326ec0c48509439.nq.gz
    ├── 52d4bebd558fd216076a083e69c14ac7ab2fc2e2.nq.gz
    ├── 538d825650313cf1da1b1bce33ef74cd880aa653.nq.gz
    ├── 5418f7aece9a107e495d8e1bac47eb0c3facf013.nq.gz
    ├── 54d8f1a12af267075787b20afa845b72aacaa66d.nq.gz
    ├── 5561308c3f313e10cd28f665bec913f4d17b73d1.nq.gz
    ├── 56971db55b50be647064f562872eb5b55578509a.nq.gz
    ├── 56a0e7e55c5f39a21be2af26bdf01ee5d34ec70f.nq.gz
    ├── 5734ab528dd352a3ea65c91f0478907b4dbc9dc7.nq.gz
    ├── 57dd537ae0637267b16c014bc1d74415fe686181.nq.gz
    ├── 580709b13498a13fdb9edb2f2db0e857220fdee7.nq.gz
    ├── 5846f787e663aa149e347d8d66790687c1d800bb.nq.gz
    ├── 58c9e8c955764166af83704b90a1a51982a7e0ea.nq.gz
    ├── 590028a14facf10e59fb61f948716a9f9f75307f.nq.gz
    ├── 5aae025cda6e5bba4a4e0a1d525029a0011da56b.nq.gz
    ├── 5ad115909fcba180427c324d460027666dcdd6ed.nq.gz
    ├── 5aef3824a973ffc85a1950dd295882e21d840dd8.nq.gz
    ├── 5af4c654ac59c5af374813cdfdbdb700e4518906.nq.gz
    ├── 5af96947adc22aeacd2a14fd3cd41be8c6cc2c13.nq.gz
    ├── 5b281fb2f98f4d93e656cce9df0d2e5e6d2bd539.nq.gz
    ├── 5b5bbc3287edd945476bdc23d78055896d985bc2.nq.gz
    ├── 5c49f05e7f8ede62701dc417051a3dda9df788b4.nq.gz
    ├── 5cfcfd562c6f31c6ff36724192c03425de6a657e.nq.gz
    ├── 5d13821dc9db15cafcb3e2fab2f785fe73f076f1.nq.gz
    ├── 5e04211ffd70be95fbcb74f1c0168afbad0fb91d.nq.gz
    ├── 5e6adbab22fa1d991e8df111c005ab5ea1f7f48a.nq.gz
    ├── 5f0da7fa23b4e30926f14157b405d81e126f6fe7.nq.gz
    ├── 5f6448f35a166e86740f9a611686cb666f3c51e6.nq.gz
    ├── 5f7a169ccbc2d80b6f8ccc8416a0d5d0212245db.nq.gz
    ├── 6020df6d3d118feeb6929f52f006b3aa5ab6831a.nq.gz
    ├── 607eb237554f279f65ab76d6af89267daecfb2bf.nq.gz
    ├── 60bacddbb1e714897c6a99ae42e7764b4f93473b.nq.gz
    ├── 60ee17d064611f6bf772e3386f9b5aba927003e6.nq.gz
    ├── 61e29c03f0620d1c34924803ca2303dd461326bd.nq.gz
    ├── 62d4136cff0779a478ed9e4eabe67404f2800f7d.nq.gz
    ├── 62fc9834bd9a320200db407fd2c055fffe75cf73.nq.gz
    ├── 63fdc8af6a521d3489e6af9a52602b0b6a462ee7.nq.gz
    ├── 641f38754359032cafc0116195816be64fb1151d.nq.gz
    ├── 64346f6236c8f83db4c2cd1b39b46ea883169d45.nq.gz
    ├── 649faf0d761dfef01c39b960b4dcd9c1134f4deb.nq.gz
    ├── 6598636e38b9d0153207162b837add4b4d4ef42b.nq.gz
    ├── 65dde5c45a76a8a7c9f3d37d7a9372cf08f1bb31.nq.gz
    ├── 65dee745014b031c4d5bb9a276304fd20eac63ff.nq.gz
    ├── 668a277d6e3d54cfab42ae99dcb7aa3169cea4b4.nq.gz
    ├── 66a8de0e8d27ef3953dbabffad88409d03d6828e.nq.gz
    ├── 66c9576d52c4bdbec72ecaeacfa08c51f7bc43e7.nq.gz
    ├── 6845727c2c6cbe52e054d727a30d32c026296dcc.nq.gz
    └── 68a5bf72773ffa1c18a9880e25ceb2d81dbb320c.nq.gz

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

[facebookresearch/hydra](https://github.com/facebookresearch/hydra)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
