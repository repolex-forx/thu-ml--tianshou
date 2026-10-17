# Repolex Knowledge Graph of thu-ml/tianshou

RDF knowledge graph data for [thu-ml/tianshou](https://github.com/thu-ml/tianshou), parsed by [repolex](https://repolex.ai).

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
rlex download thu-ml/tianshou
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f2402056b03acafeedf2518a5088db55add004ab
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f2402056b03acafeedf2518a5088db55add004ab
│           └── chunk-001.nq.gz
└── blob
    ├── 00b2560f23ee4a6080475f68b15e8915024928b7.nq.gz
    ├── 015146b2712ede2c71a03bfb343eeb86075712e2.nq.gz
    ├── 045cb15875babd289c0d72db34e6fd5a35b95530.nq.gz
    ├── 049bd81f4ecd48de671eb3c15ca57c33c1fe5b35.nq.gz
    ├── 04e5e706a2fbbef6b104f9faf67c9553f3786468.nq.gz
    ├── 0609fddf8beaef9301d0aee8cc224ebe4dedb818.nq.gz
    ├── 064545434318ad2005258f71f80aa43b990ec519.nq.gz
    ├── 07aef747df18eecbdee6f640b0d704b48f8194ef.nq.gz
    ├── 0819aed6c68f0796fcffac814a2c07024eedbfe9.nq.gz
    ├── 0869ea972124ddda0f05ba04b1d1fa98fd7538ce.nq.gz
    ├── 0878d23840a76aeda9cec1319d1be598730d5a20.nq.gz
    ├── 08b32641a2d7861f4ba42db2d89366f97d5ff8f0.nq.gz
    ├── 097d0dff9ffeb7bb703b9ff0e1452631d656a80a.nq.gz
    ├── 0a5b1fb664ad3f5b63e4ce9134381631fac5b344.nq.gz
    ├── 0a9886182d97c0451c0ca408b003e3d0e7e94aac.nq.gz
    ├── 0ca8c263bd044bad80bc4150f3b7c8d69f753de1.nq.gz
    ├── 0df154a84caab03d29cfdd5aab2978bcff39e96e.nq.gz
    ├── 0f0c237c8104faf1055f8730521c3b403b9d7476.nq.gz
    ├── 0f75fb71915fb024cfd9f0e32032b64c4cbddffd.nq.gz
    ├── 104d8bb29cf85fdf5a8d755fc6d3a9ad89a533b9.nq.gz
    ├── 10bcdfd1e566fa51faaf1f721ebeb38d9b3e711b.nq.gz
    ├── 122db6040b54422fc0e781e02ceb2207f90204ac.nq.gz
    ├── 1302a35fb35f4b5a6d6e31079ce0cff15d16c3c8.nq.gz
    ├── 13645e866e3c2b193559d0b2040d8d17832e8931.nq.gz
    ├── 13fd9e21abbc64378f2e0735068d77fb367f1133.nq.gz
    ├── 143164ad66dda2cd69d0e03c195fc28c0cb1ccf1.nq.gz
    ├── 158517164307d5f8ea120962609107ec78409bbc.nq.gz
    ├── 16ce28e2bf4609f576aef4cdc50209da2c062bbe.nq.gz
    ├── 16f532cb3772e51e93185553576de521920c68dd.nq.gz
    ├── 18893594f0e8467f91f113b3a50334d40a8b0ac1.nq.gz
    ├── 1913a1e76b560869c832497fabaca2a54bc33178.nq.gz
    ├── 199525fa2b3909c1c27491359d623c51c1128821.nq.gz
    ├── 1a344a65b3b6f5fa84bb7a13873d4f4316ebd83c.nq.gz
    ├── 1aba38f67a2211cf5b09466d7b411206cb7223bf.nq.gz
    ├── 1ad54bf60f2120d64856613df987a663e6646aa3.nq.gz
    ├── 1b0be34d09b5a51461ef5902aa9c570a3662fab6.nq.gz
    ├── 1b3b2dceb640b67473d4b0e278bd8beb762d5cdd.nq.gz
    ├── 1c38d3602051c216cf872bf2c02f7fd5be2bc7e0.nq.gz
    ├── 1c7431e0289190a4582574d8b5075ff5b2c5fd12.nq.gz
    ├── 1d649f15e92172910be613c5d9723b68f552c55c.nq.gz
    ├── 1e2b00dd28119e18ed5a9ba2cbb75fa8aba0fbf9.nq.gz
    ├── 1fd1c51be3c0f7e07f02bee355ca521c2ec4d70b.nq.gz
    ├── 2119ec176d1ed6680514233d4e0c2df5259a4164.nq.gz
    ├── 21e7fa141bb8a538cdb94e7bc7c42f3426f4e3f4.nq.gz
    ├── 21f936b94bf563826af15b5bca4bb87874c72911.nq.gz
    ├── 23cbb0cb28462dc11f5ec4306da8752ce5de5ca8.nq.gz
    ├── 2520fd8d12fe6962f358cfbdf92aec016d2e6022.nq.gz
    ├── 254d0848c10b31c7035ccc4ccdf092651912599b.nq.gz
    ├── 26a0959581ef880099af9c639fa8be10c8401869.nq.gz
    ├── 26e478c1fb22c13ac907e83f5c0743c2d0ab3508.nq.gz
    ├── 27631ae93352e5078a848a9597b290c2cee6214d.nq.gz
    ├── 27dcc4a971248118fb2190b3839e1040f55bf192.nq.gz
    ├── 286a56896729b3d7f27ccb3df64f968239bb2357.nq.gz
    ├── 2920a70f737a5d9b364fe039bf08ddafd9b9d593.nq.gz
    ├── 294f05e459536c2b57809cfbaf22fe41016dd7bf.nq.gz
    ├── 2bb92149fef6259f2301803b780b42a4d8f26265.nq.gz
    ├── 2d66040fa237b584e11eebcf2cc2eac9fac2fc46.nq.gz
    ├── 2d86406cabf9b5bd8956eaa3707c8e2978d0d7ad.nq.gz
    ├── 2e6c279da8b45d9e7bf04164f000e56243c5cacf.nq.gz
    ├── 31615113bc6d9514305b4945598b93a750a7827b.nq.gz
    ├── 32289bfec6015c32c68f54e0d28d23ea4316e62f.nq.gz
    ├── 322a77c33dd5800d19ad169626e446de6ad58863.nq.gz
    ├── 324187fe2f483a19ab0e05da82b5aa98f0e42aca.nq.gz
    ├── 341f16bffac8fcb9d0fdd308af669d6b4e8985c4.nq.gz
    ├── 3489d0dea70876d328417b41036f60b84391da32.nq.gz
    ├── 35127b71410d2c2989a69ae495413878a5f5097f.nq.gz
    ├── 358600a8057719827f5951d00992b6c6e147cc69.nq.gz
    ├── 35ccc04f9e6bcf06b3c29cf855452349bbf1f455.nq.gz
    ├── 364f896495db7ec712614f6473dcbd4e5688002c.nq.gz
    ├── 36f1d2d3a17ff871aaf4731a879bc3bf57fd774a.nq.gz
    ├── 3731e93273628dc9249bdbb1bb10c89d4ca1e13c.nq.gz
    ├── 3777ce98c1a38bf5ddeef9fd8c6c0eeeee0e9fdb.nq.gz
    ├── 37a2aa71b56534905c0b7d073aac20712dbed13b.nq.gz
    ├── 38364476ff5696a6d353699d9ad9ac1d7c1b4c03.nq.gz
    ├── 386de1f3930857dbcaa10f39348341fd2b56fe16.nq.gz
    ├── 38aa3b4a94143d2f13486e649b14ecb7d209b902.nq.gz
    ├── 38f7cfb6ced5451c6eed3612cc9cc154def6c1c5.nq.gz
    ├── 3b05e5f1aae024f88fc29a69e9cd989b823213bf.nq.gz
    ├── 3b6f9d3f01813112fbc26660f8a766cdeca9f10d.nq.gz
    ├── 3bd40f4add50dcc5f5d7f89d878092a5f58472be.nq.gz
    ├── 3c917b1fbda67eb666af560b58b5cef14ef1f67f.nq.gz
    ├── 3ddffcc4bc1c14faac887da9bee3c51521f65aed.nq.gz
    ├── 3e4582c7bcdfcedef83bc8a30fc3adc78e7a7673.nq.gz
    ├── 3e47690189e01f347a46b51a5158f9c300ec09f5.nq.gz
    ├── 3e9a9fb6393578b84e408409181852cf12701c96.nq.gz
    ├── 3f8e8eeb1b63c6eca4f5f7a4debe50bb9bcd6240.nq.gz
    ├── 3fafa0a234643ffe0d48f0519e0cb6273de72fd7.nq.gz
    ├── 402424e173c3a89098ecf498048484676e868a00.nq.gz
    ├── 40ce4a2990b785738fb32969691404a033a056cf.nq.gz
    ├── 43ecdea635b23b8ae711460da5e00218fe09deca.nq.gz
    ├── 44f167eff8fc498457cd8d97f1456c153c693d6c.nq.gz
    ├── 452232d081bfc4827c8bde05c993f6b56a0421cf.nq.gz
    ├── 45f9df671f69ba37512204deb42a8b1b3580d79b.nq.gz
    ├── 463928470176a603dcc5cb718586e42a6618f717.nq.gz
    ├── 4655a7a0944bbd2fce82a20c60a5e00916033953.nq.gz
    ├── 46dab163a23d869cb8bbd6e25b984cf047d7c958.nq.gz
    ├── 47332f0b17f69d6a1ade97c08aca9c126d8cc8fe.nq.gz
    ├── 4757e6926beb4dcc778561aa0b6d05239d7d1d6c.nq.gz
    ├── 4792c090dcc349159d2cfbb290d5fe2bc70c4707.nq.gz
    ├── 49db9bff12ecbe89c3c9ea749e81cdbeda4a0de0.nq.gz
    ├── 4a2f4cc5bcf3aeebfd0c89b1756ec500c9dc6529.nq.gz
    ├── 4bf48a3ae53f36160b27b2565c509c993a1d1d57.nq.gz
    ├── 4c1c81dad2821c16d0c01889ded24c81a46cec46.nq.gz
    ├── 4c273cc6312f2fa91222d61f1b56f0ce16b47a1a.nq.gz
    ├── 4deab84ab3c28fee84f18aa58f7e0adeaeb718ce.nq.gz
    ├── 4deda628f8c544d8f054239a769b25662b5ba4c6.nq.gz
    ├── 4e2ea27afd2fb4e344785ec2c4bb8056f2ffa473.nq.gz
    ├── 4e3827b2651026da74a233154441eaa8b4b1190f.nq.gz
    ├── 4e3f24ecec605cfd16102bec66c4ba84aec404f2.nq.gz
    ├── 4f79f755743aa5e4d1fc1c71025a592d685a9a81.nq.gz
    ├── 4ffd1dfb186e40e5b04b3369772469c339db6fb2.nq.gz
    ├── 51034a24a1f0d987f479f8825d6d5ea0d4daae9f.nq.gz
    ├── 51e965193dcc5059a2c06994055440cef1a05c8c.nq.gz
    ├── 536443860d42b8ce1a9fecbdd638afb5665f0b3d.nq.gz
    ├── 54596be128a87d1109888a1bbe75cec25e97161e.nq.gz
    ├── 549774e528eb5ddc945c55c38d442b19fbe860a8.nq.gz
    ├── 56775f36aeb30353a489050bafcc6b9e9d468fa3.nq.gz
    ├── 5747eeb12e5b7739ff074d8ad7f28c7fe11c977c.nq.gz
    ├── 579a792faa5f511b1732458bf77be231f52b4e9b.nq.gz
    ├── 57ef0645f123aeba2b6d001b3c73b785077ad47b.nq.gz
    ├── 59d6699445614242a909676eb85f7395d12b6cee.nq.gz
    ├── 5bfcfcfad69e7f0c0e49dd320e9c3a429b899c70.nq.gz
    ├── 5cad9f83ad79b42e7cc27d6d0e1b71733075e4c4.nq.gz
    ├── 5ccbbe0fb9b500bb774517dbd7e9b6f74acdc6d7.nq.gz
    ├── 5d5074e48d65550134f7807eb3f1876bbd3d0318.nq.gz
    ├── 5fdb0b2942b218a3e65c0361237b64bc246ebf1e.nq.gz
    ├── 609621ae48f93b73a3a3faf382aca6e0a09a10b3.nq.gz
    ├── 60fc91cae71d734a33c2c90d576292c34896d107.nq.gz
    ├── 61c86cf2485ddef44b1e6082f61d86636450727c.nq.gz
    ├── 61f4a232bdc44749bb93ba9b0c04ef6299c75c73.nq.gz
    ├── 620b97882250556d88b97beb5600f9a7a50a34f6.nq.gz
    ├── 625854dcf6e6b19b04540418f3c4fdddcf4bcf7c.nq.gz
    ├── 62bc6ae7dd0c4343eb62b8304981dc5c6bc81413.nq.gz
    ├── 637850031e85ab0ea368e0c61e986499fc852c00.nq.gz
    ├── 648358d2ccfe9056f1ee34889b5a9bfc74a15e4b.nq.gz
    ├── 64eeb424762cbb8b508219aea1a270b3085bb540.nq.gz
    ├── 67165382e69070aae2c5ed69deb584ad83af3878.nq.gz
    ├── 67a5714b0a606e6f16b9f673b77bf45c1efb8bae.nq.gz
    ├── 685d5db67434082ffa0a3c23b6efc7272f429446.nq.gz
    ├── 6943e4f11c5c44bfe41da56e7c6be275ace885e0.nq.gz
    ├── 698715cd4d8ed7682345fcae68dfd907628e8787.nq.gz
    ├── 69c6f690d86a551076235af48320ef7b5042b16e.nq.gz
    ├── 6ba0a2259886e5b1225ba5a0b08960a36baa1fca.nq.gz
    ├── 6c1766d3e9a3e041c27d821a84f5ec012a816e85.nq.gz
    ├── 6c7a6e1749a38f4b000f8d4ded48939803fc879d.nq.gz
    ├── 6ce54f60b31bed4a8f484f03f8c39e677f3f4c35.nq.gz
    ├── 6dfda1681060f393f6a1c134f9456eeea29ed50a.nq.gz
    ├── 6e0cbddf3e8cb7be862ca54655f1db60d22d7847.nq.gz
    ├── 70da6584462550d36ce12a8be8959da060c7b396.nq.gz
    ├── 71e1a9f37e4af864e4afbe29206211ab076e3df6.nq.gz
    ├── 72762477f39ff6c4e979de8d8ea7b9dd728c2024.nq.gz
    ├── 72a3beedfe4b5f63d614f28ca21578ef8cdf129e.nq.gz
    ├── 7385cb8a67e0f409c2d4e0f9f74f6213da6e2a97.nq.gz
    ├── 753f86629b288bfbcf80b2eba63d065b61825ea9.nq.gz
    ├── 75d39380fa295e9646cd20bdb6c9f8a340259430.nq.gz
    ├── 7857037bc5bb50aa5de32b248c604fbeff45143e.nq.gz
    ├── 786db84d960a8af359c7b6839aec04ea60be30ea.nq.gz
    ├── 7a964ee10cf0348c2b0b959b1f6192c7bf345aa7.nq.gz
    ├── 7abf43b5eaab744015bbf6ebe76fc5c9dfed4010.nq.gz
    ├── 7b70b6e1ff4fb488413c40f037a60deb76a31787.nq.gz
    ├── 7d684655b1793457c070e1aae57bfee8efdea655.nq.gz
    ├── 7e9698dd0ac91003445de5f1aeb0728ed384204b.nq.gz
    ├── 80f12122adce974b1bed50639865b47f1f51a7d8.nq.gz
    ├── 81693fdc0274c2fb0e34fdf4eeb37c7fbd8def72.nq.gz
    ├── 81c4c5ab4cc472db6eb77aef868d498dba5b025e.nq.gz
    ├── 82ef17814924de853773307e3b435b1cd389c7a0.nq.gz
    ├── 837f4c4641ddadb62c2bccf28e0b5ddb93d82eaa.nq.gz
    ├── 8643069562316760decb2dd548dce7183865aec5.nq.gz
    ├── 8749a86a0908b132d8ec6ca842170a32e1e3ba2d.nq.gz
    ├── 87b4100b417ed2f0ba19081298fde98e7cde43ad.nq.gz
    ├── 87d318a038f6a7725f1e74501700d2f6ce0559b9.nq.gz
    ├── 87e586247a55b5f90e2ad1d89f2400e7463b6222.nq.gz
    ├── 88035ba40b0724df674ff69c04b1d365208e8add.nq.gz
    ├── 89c27ccf6b65339f5bccc1c1045d8ce98e967075.nq.gz
    ├── 8a5ec1ecf16f900484377dee01cc828e226d87b8.nq.gz
    ├── 8b137891791fe96927ad78e64b0aad7bded08bdc.nq.gz
    ├── 8bd00852e39680e6b1f0ef2e4f5b701ad5d39977.nq.gz
    ├── 8ca11f37d4069646d13b76d11b81911d55de75a0.nq.gz
    ├── 8ca39440ba36d5d6b5da70dfb2fad3dbed38652d.nq.gz
    ├── 8cb765980319b34342e918aafd33542d03f9b5e5.nq.gz
    ├── 8ebc6fa935d0e157b7536036d84f25ca475d80da.nq.gz
    ├── 8f7d7798c082453f6f7773146942f9cef1908d77.nq.gz
    ├── 8fbbb6b5092232c18945e8d8369bf3c3fe7bded0.nq.gz
    ├── 91e77632d32bb9711d81a1736e5290e7e7b7f0ae.nq.gz
    ├── 92938ce501fc9c78fdac92ba6b28bae097a7ce1b.nq.gz
    ├── 9297ddebbaaa67e8cbe7f63a94b0b36a85ec3e2f.nq.gz
    ├── 93ac1b3c76d25554aed818e93e537091ccb1386a.nq.gz
    ├── 93c5ccec38f2f1dd83d616d77744e0bc0bdb4cb7.nq.gz
    ├── 93e2a0954e28fc9635a7b29f3831c1afda4b30f4.nq.gz
    ├── 95e7ecc7733ebdf1d1ccf223ddf01a831d0fdb0e.nq.gz
    ├── 960adbded084040f880825a73eacde36ca0abdce.nq.gz
    ├── 96b9a38adfb0b2eedf88fd15304f293acf69bf03.nq.gz
    ├── 975d5952c080d8a87d2911a61a20b0f534373ca4.nq.gz
    ├── 979a03e7f616f9651bffa1e9727c804381ecd67b.nq.gz
    ├── 98f90c26ca9bac4e38c5c45f6fae2a596b08f286.nq.gz
    ├── 99cf2c01c51b42298487bf4df700dba1e8f838ee.nq.gz
    ├── 9a3ade5426e13221d233a772a22bc41ef22abf6b.nq.gz
    └── 9ab9b34c3fcfcf7f3278d5798432bc7bf2c88d88.nq.gz

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

[thu-ml/tianshou](https://github.com/thu-ml/tianshou)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
