# Repolex Knowledge Graph of piccolo-orm/piccolo_admin

RDF knowledge graph data for [piccolo-orm/piccolo_admin](https://github.com/piccolo-orm/piccolo_admin), parsed by [repolex](https://repolex.ai).

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
rlex download piccolo-orm/piccolo_admin
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d6053adc9f6d2db49cba9bcce97914ac3b2b989a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d6053adc9f6d2db49cba9bcce97914ac3b2b989a
│           └── chunk-001.nq.gz
└── blob
    ├── 002d2298d5f91eb5ec97a657fab2ad21587e14da.nq.gz
    ├── 0146d43d9219a7a1addbef0f078f1074f8f38b0a.nq.gz
    ├── 07b2b0b9ac041f77589066ded75f2899bd8f78f8.nq.gz
    ├── 08a4051c59dcf622f3df81f2b74c8002f510b015.nq.gz
    ├── 0c9558bcf0f53c7c31a49c97b951311941a7349e.nq.gz
    ├── 0ce226b2b6a00f7d7d55ddaf9c6147b1269b840e.nq.gz
    ├── 0d50d20f5466f3d18503ad544bc5b3b3d6ac0d53.nq.gz
    ├── 0f0db739fe29fc84bb69d6c43e33e885234c4f7a.nq.gz
    ├── 11f02fe2a0061d6e6e1f271b21da95423b448b32.nq.gz
    ├── 149b87d989f552ef753f8aae1234b83da711cbc7.nq.gz
    ├── 16e0b160f12c6982a7a423c6be2ee173c50d91b9.nq.gz
    ├── 17b844924c6aaeb6e425cdad1e43dda800492c7f.nq.gz
    ├── 1827daa0a017710d0d7b6d65cf39d29df4be480a.nq.gz
    ├── 189752baf2543b7e5ff6573d2b024542bd6b212b.nq.gz
    ├── 18fbb66dfcebfe7901a8fd353ce2bcd3ece9e9c2.nq.gz
    ├── 1a4ef2a2220a8232f89cbc477f72accd6e263be6.nq.gz
    ├── 1a98a98c57754368a48c2b43b376a920859a8030.nq.gz
    ├── 1cac2048d0d025d973369bb7474d719e8b0623d7.nq.gz
    ├── 203c4a89c781a78753f19c841b14b1a592cc2607.nq.gz
    ├── 211dce9e0e92f21cf29fbb3ef8fe434a6067f564.nq.gz
    ├── 246c80c98ec7f5a10eb484e758a1372bc4001422.nq.gz
    ├── 25ee88ea391f343983e593caf622f92facd086a5.nq.gz
    ├── 260d315e2d95f848ea82ee4e2236558ee0a8a210.nq.gz
    ├── 26dfeaf66bbe0887e1c4e916363a0685b82117d8.nq.gz
    ├── 27f23d9a1cbac5d4ec10e4130b259b1e2c0d9d74.nq.gz
    ├── 28a6bdd31c5e424f674dbea7c0370d7a0905d5bc.nq.gz
    ├── 2988b1ef6a0736504065b37148b39f16ede2189d.nq.gz
    ├── 2bed1ed8ff5ef9733f601097d05de2e70ca8eb44.nq.gz
    ├── 2da7ac9e72cb110874728c183238d3705e86479f.nq.gz
    ├── 2e284b3bd572918caa271035f93bd1d3c3b94fd6.nq.gz
    ├── 2f86548403248f982d2787a0db943ef0271912e7.nq.gz
    ├── 3063682eb7ade0387a2da0ae9c2359f1d9f1bdd8.nq.gz
    ├── 3183c74c930e2372cc7fce9d485e7455a96c46c5.nq.gz
    ├── 32c4bf7cd7917a23ffdae96536d510f5302aa8af.nq.gz
    ├── 3304d079d27c190e890a27cc7477747986be4f4e.nq.gz
    ├── 359227aaa75996bd47c2e0f67e42d5dfb458cce4.nq.gz
    ├── 372ab4875b2b1ba9331720fb5e9129d2a2231468.nq.gz
    ├── 38c06e56391323c20ec22297bf135fd9281afd04.nq.gz
    ├── 39f995754e5bfc65c6710237f56d5850c7b26efe.nq.gz
    ├── 39fb28be0c78c607c1ec675c6bd34b5665a259dc.nq.gz
    ├── 3a37c167c0be7a341648ba83bb54f8c2df3c1e69.nq.gz
    ├── 3a6b00ab9dcf67d3167a8c7c5ac0b7576838b7bc.nq.gz
    ├── 3ac09b58ff7abd73b049c86019aafcb6be55b2b1.nq.gz
    ├── 3ad917285d346c0321bb36ce40d7d2fc1bdca667.nq.gz
    ├── 3b88b58292fa668f5f84089a7960dc9a826d96ff.nq.gz
    ├── 3bd8f1b9ce1da45ac1a92b915efed6dd85d4155a.nq.gz
    ├── 3c5f8ce44c861b4dc45369a05975250c91e08df0.nq.gz
    ├── 3d5feee8467bd01af7c8ba1ec873abc49bf0e488.nq.gz
    ├── 3d9cbf6957a61ae8282cf4fde40a5f134f885d1b.nq.gz
    ├── 3e85ead6a19039e6aca127715d3cf7d5c4da55b8.nq.gz
    ├── 3ec2fb1e411b6499cd79f3d4a38aae8f6a1cadaa.nq.gz
    ├── 3f5fecf7552c32e1cde3c113421d92e6eb461ef9.nq.gz
    ├── 43f63c5d2eb3c748a9c5003a0b15766a9ed29ab4.nq.gz
    ├── 44157030595b4234dd215bb0e024a110ad4380a5.nq.gz
    ├── 444c0a9045083c4313f456db684798f94e9e0f2c.nq.gz
    ├── 44ee05e1268e8b0bb37786e0c90ed0be815cf661.nq.gz
    ├── 45b2a85b6339b70f1557378eb1d65a2cb81f8f62.nq.gz
    ├── 45dce9c369a502170728e63529227182b5c1cea6.nq.gz
    ├── 460681dff842b23e094e533a9908adbae10847bd.nq.gz
    ├── 49429e27ee5443680d46c444ea19928bd24c3b77.nq.gz
    ├── 498debf5f8e0ca878f485e72777f44ff893dcfa2.nq.gz
    ├── 4b818d411a9c07ce8ac4798ba2b3f0690a43ed9e.nq.gz
    ├── 4c3f6d780001e3cccb4f64f367f8f5b27f3e62f1.nq.gz
    ├── 4dab1cacf1b64d82e10fa87763196cd34d1bd70d.nq.gz
    ├── 4de036208e902e8ef0d0a2c0cd04525945d3f278.nq.gz
    ├── 4e43d5acc8ac91559243b453d8b275e90aa0e487.nq.gz
    ├── 525b47cfb863ffa4d365bbe93a20317c5884554b.nq.gz
    ├── 534a73f54e3ea15229dc806555cdb2fb0839e116.nq.gz
    ├── 53f36a10d0e2a72e83d894f7acd80c2fe8b9eea0.nq.gz
    ├── 555ee53dace21d7fc0229ddec00a7121b6696a97.nq.gz
    ├── 559c6850ea2d8a3505e9c3c9e9ffe7f7c649e213.nq.gz
    ├── 5662ff8f36cda762fd84642bb52275f0c4a32c7a.nq.gz
    ├── 5a185e19c98b2c0d7ce758143a36b185e9245063.nq.gz
    ├── 5d8388f376209e147d588d0e58669e76a5942235.nq.gz
    ├── 60489e2ef63688326c1f25624680b4eb085c8ee1.nq.gz
    ├── 6107dc045cbab7865393603229af89b82fde6a25.nq.gz
    ├── 62ad783714edffba264839c1679a5a2d7abe0b3f.nq.gz
    ├── 6313b56c57848efce05faa7aa7e901ccfc2886ea.nq.gz
    ├── 63143da180aafed77b1bbaf8b1b8421d07da10d0.nq.gz
    ├── 6419de80d49a6c5f1c501ae5b6b15ec2d109edee.nq.gz
    ├── 651839ab7c8877883dd5f6bff3808b3d79818325.nq.gz
    ├── 662c32b1ca058096f5052f4b9e4fd014acc31540.nq.gz
    ├── 66af0910e98f4f1df63711dea266056734f683fb.nq.gz
    ├── 66b5e5703e83c352671ce094731e9e861ada6924.nq.gz
    ├── 67b8ec583f5d60bca72a292b2dccbf7ce2409985.nq.gz
    ├── 67f882623628e5792e89001acc11afd39380225f.nq.gz
    ├── 69fb78a852f9331383dd0d0bd92a50f5482ba65c.nq.gz
    ├── 6a2371bbe7345c6021870459f19be12338352e7a.nq.gz
    ├── 6c4935eb3f96b48a0830bbf54792f2e2a14b605b.nq.gz
    ├── 6c6791151e6a90a96873a3ce30150b6e77b9bdc6.nq.gz
    ├── 6cf310aedef6a75ca86f364de43b48df3fabd7fa.nq.gz
    ├── 6d729b6b60c33e3d95782020d98568711d69398b.nq.gz
    ├── 6dc49501fc52be1846b944115eb4d30e01a45374.nq.gz
    ├── 6eadb312c04d8743c2735aef730bbd29902947ba.nq.gz
    ├── 6edc1225dbcca7b7917c2c8c08c298ae29ad62b3.nq.gz
    ├── 71c90721cd98813a8c882dee4dd6de4c44f3231a.nq.gz
    ├── 74318628b08f99ef02543048e0d7e323e007715a.nq.gz
    ├── 75568b7cca5ba5dae470b25a95f0e7d5b896fc82.nq.gz
    ├── 76b7c9d57a5ce81a928216cea69aeea407b837b0.nq.gz
    ├── 77b4b5b2cd5d7a05654a716b3020548825d96363.nq.gz
    ├── 7855881dcbb4c3809bc368beb4ec19bd0ccaea9a.nq.gz
    ├── 78d64ea2f0f9e402a12da22ebbdf989687b8fd1d.nq.gz
    ├── 7c0e48674873776204e11939daa11aad95f3b456.nq.gz
    ├── 7c6943615d31b5076ef0ffc145522f250f077c61.nq.gz
    ├── 7c80b38bb88a5aea432efd66023f8108ea3112bb.nq.gz
    ├── 7d4c2f72bc3c7d3af9595c630659b6e8674bbfcd.nq.gz
    ├── 7e192d5cd630be188442fea0cc1d75fbe1651dff.nq.gz
    ├── 80e88d9d1ca2a2c65bd91de44b114d70db3a9837.nq.gz
    ├── 822272f712f265af349dd7a1bd8fcd7d4f53c34d.nq.gz
    ├── 83e5fe46510d8c7ab12fe9031f046d7abad5dda9.nq.gz
    ├── 8749b65f075fe462699b345819945a07e919568e.nq.gz
    ├── 88552f659064bae2ff08558a81886e6546d7f9ce.nq.gz
    ├── 88a7d78227851447da3c006bec27d2e472d035f5.nq.gz
    ├── 88d9e428ff690ba8e62ee4c6520e32d6361a9c01.nq.gz
    ├── 8a884875b334b567337074ba93317254c7183dd9.nq.gz
    ├── 8b4d663b47abd8a68457d2adf235ddcd673bdbcb.nq.gz
    ├── 8bdbdec3b34648a9cf1d718cd70af962913001e2.nq.gz
    ├── 8be6ed8e8a42766ddc8c3030a080ebf8ed3ee250.nq.gz
    ├── 8db118e9bc9cc9129c777594bb7aa8d92179a512.nq.gz
    ├── 8e2ec9e906830e3c42bee5f329e2b0d5c5d43d2d.nq.gz
    ├── 8e6589da35e016683284836e772a83c1ac36ab56.nq.gz
    ├── 8eaf45f81f0baef7568707d7beb9e2393652c8df.nq.gz
    ├── 8ee54e8d343e466a213c8c30aa04be77126b170d.nq.gz
    ├── 8f1d8da8a19a1bccb8cbd7a02effc21890df92bf.nq.gz
    ├── 8f6f4102637123d7e5696be9ff5776d810334a90.nq.gz
    ├── 8fdd954df9831dfd29ceec0d74829b02f3f5d8c3.nq.gz
    ├── 913b8f279fca6f23c1b6532660583d2ec4ccebab.nq.gz
    ├── 93499609859b64de2dc18d0bc6f27a54cdda4e81.nq.gz
    ├── 94aa8914e6fbe76828b38e20bb5472c4ecefa734.nq.gz
    ├── 956a971eb1f0317662dc9dfae7fcc554ee6b795a.nq.gz
    ├── 9725d593dfab3be9bb6048bb5a542a182273a7de.nq.gz
    ├── 976ba0294638950e865be3934cbeee3b6305ffd6.nq.gz
    ├── 9ab58f5018b52bcb9841598b107166e8c7285195.nq.gz
    ├── 9af3cd92f5dc13ff4b3904628982c939e5c3db91.nq.gz
    ├── 9f63d820b5332b9c709b9ddef8cd3908724344e0.nq.gz
    ├── a064067003c426257de7ad32b396ef68f4f1d6c8.nq.gz
    ├── a13324fef4d867a22609b080a1b53ab3c6ed1900.nq.gz
    ├── a13b99ded3ab3716e4cfd78cee74dc01e8a11ab7.nq.gz
    ├── a18316a39b47c27bc18d1c2262d410814ace9477.nq.gz
    ├── a185bc7cbc1f050a942edf09ce99402b88695b62.nq.gz
    ├── a25dce446bcda2f3fe9858a8f7ffa7a87c56cfa1.nq.gz
    ├── a4dac0cb532437487f4416298c8e2bff753cb9d9.nq.gz
    ├── a58fca7ad38b3c6f469221d58563e6b6c95af96e.nq.gz
    ├── a66583c2f0ef598ddd7f54e0f934aa253c01d1cb.nq.gz
    ├── a9a82887a625eba1add4fdbb0fb6797e6a2b9b70.nq.gz
    ├── abfd5792c29e4a4be0afed3129a90c43363eb2a5.nq.gz
    ├── adf6e25e570c84df15e597e62729cfe87b499914.nq.gz
    ├── aeb5efc44cb57376c9d3fe809bda04872b8c4b68.nq.gz
    ├── af3d7629999c33869ee2edfe578433952fb10699.nq.gz
    ├── b005cd56a05bbddc8b3d3e31cf874d7e1b2b80bf.nq.gz
    ├── b1f222c38e71825d85b89e0c2a600ebb4c92e571.nq.gz
    ├── b300323949a95d8d2528fb0be94163dc6668636c.nq.gz
    ├── b69dbf199c25f6795c122eac1bd7c9de0c065de3.nq.gz
    ├── b79e6f0d93ed980af03397f0e61353052a461c12.nq.gz
    ├── b8dfc6591f36a53a0f3d49fe114e533494f7db94.nq.gz
    ├── b96bdf1b57af8a6399791721a8feba74b692cae1.nq.gz
    ├── b9b1a2f1096fe493a8a0f0b753671708de11e043.nq.gz
    ├── ba91708d5a0768bde3604f3a5bff13cc3d3ae2e6.nq.gz
    ├── be14f3bbcdd12c957a1dc6d695630a122496f1ce.nq.gz
    ├── be842b930883be8490b4294a7334bd93a4ec397e.nq.gz
    ├── bf6ce3d82f8280c06afaa18cdb8795a588e1a1bb.nq.gz
    ├── c2f3c3fcbf9820a30e1b5cb456d3c59cc2072a35.nq.gz
    ├── c3de25ccfce4dc9867aa7f7530db35bfd39040dc.nq.gz
    ├── c7771bcc8f51e51e9cb9713ce1cd699000b1f068.nq.gz
    ├── c7a21436ff0c106cb6a9f451da305b5f8b153561.nq.gz
    ├── cae0e6b14ce313e4e72f6ab2dc2fe50bfe192b8a.nq.gz
    ├── cd99d386a8ddd0011ad38f1be24706c40fac3ba8.nq.gz
    ├── cfa95a7e0ffd93cfad1b80e2fc60a4f8535aee1c.nq.gz
    ├── d00b88ce6d7b29424d8e8904c4fd44455114e924.nq.gz
    ├── d0419bf9c50f28ce5014b2eb89454d045fb115e0.nq.gz
    ├── d0c3cbf1020d5c292abdedf27627c6abe25e2293.nq.gz
    ├── d2070311942146f853a6c07ddf539b88078e4fb8.nq.gz
    ├── d21265c936bb71470f3f54e05263739e237fab15.nq.gz
    ├── d31a77034f7166dd0dc967a6a6482d0f706a5d23.nq.gz
    ├── d3bf2c84472a35af88c84074ab250d9da441bc17.nq.gz
    ├── d3d55614c2351ac26619bc3932e6f0adc9ec5717.nq.gz
    ├── d4791ca276185c2cb1ed411b385ff3fc08f8a655.nq.gz
    ├── d4fd974eef7bff0c37ef11ec331668961d594740.nq.gz
    ├── d5457063e27ab482cfd522d4f694d401364091a4.nq.gz
    ├── d6471a38cc6e6e02345c1edce109312520a77d0d.nq.gz
    ├── d6c1430077ed70f15048abd24e8879af00e8a615.nq.gz
    ├── d93d6e791fe34fc2d01359b21e363bc5512f1b41.nq.gz
    ├── db693fe033ed92cf6143eaeede2d59f1b0bb149b.nq.gz
    ├── dcbbb510d8dbfe7b0ddbc0f68713f17f2ae0a407.nq.gz
    ├── dced374f242526c358e525d6e81785c44021e9bb.nq.gz
    ├── de80f807d3e9be58e17f3933a5ba63f8046a055e.nq.gz
    ├── e06ac8b4a3140cc6413466e700d517ce22b854c8.nq.gz
    ├── e07b7585b97db0cf96a45f365631c5a190e6e812.nq.gz
    ├── e0c7b7bc4f9ec9d9f85d156a151fce4e8859f180.nq.gz
    ├── e11d832b3ce5f2711655b8047780254081e5893f.nq.gz
    ├── e16b8cce0258aaf1119c0b908b22217f221f5e2c.nq.gz
    ├── e1f01f2e327fe22c2cda03312c2952a7d54a3775.nq.gz
    ├── e43357e9430577c00d2017d1453292fb8a524c82.nq.gz
    ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
    ├── e70731d783dc4746e759e62d146a8d516ed531ef.nq.gz
    ├── e777c4a74d0d67c77588aaa39ca73eec3dae3868.nq.gz
    ├── e8e7ed39af9c761315f0d64f97bb46dee98fb82f.nq.gz
    └── eb139237ff8556285dafc6ef69504139d3c31d43.nq.gz

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

[piccolo-orm/piccolo_admin](https://github.com/piccolo-orm/piccolo_admin)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
