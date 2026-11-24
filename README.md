# Repolex Knowledge Graph of RustCrypto/utils

RDF knowledge graph data for [RustCrypto/utils](https://github.com/RustCrypto/utils), parsed by [repolex](https://repolex.ai).

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
rlex download RustCrypto/utils
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0b715735a660a8566ccd240bf42489fe2ed98efb
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 0b715735a660a8566ccd240bf42489fe2ed98efb.nq.gz
│   └── repolex
│       └── 0b715735a660a8566ccd240bf42489fe2ed98efb
│           └── chunk-001.nq.gz
├── blob
│   ├── 001980535da9565a61b5ce3f5aa7dcec775e4597.nq.gz
│   ├── 0204e8797486267128d0815c36cad516ba83cae5.nq.gz
│   ├── 026cbe90da4ffc1f6e8b16271ce79593da0d000a.nq.gz
│   ├── 0272a4c9e530ea62c04689600884d410dba733a5.nq.gz
│   ├── 03bc756faa8a8f2682d9e634fcfa36b32340b50f.nq.gz
│   ├── 064917d5f0d3d6f02677eb0a1a7de9f9ef18f4b2.nq.gz
│   ├── 090e95ed1de9c8e5071c605b45f6f6159607a379.nq.gz
│   ├── 0958999ee61b34b162d69a162463ac28b30f1f82.nq.gz
│   ├── 0b050d7ebc2dd2a015a2f115381430dd888bc010.nq.gz
│   ├── 0b701f78f53812784eee7bbddde03abb3ad20731.nq.gz
│   ├── 0bc5ec984b4a87d0ba9d039e4cc5d1db005eee74.nq.gz
│   ├── 0cd648f76b488a00f8fa6bf50b3120c7e1d8464b.nq.gz
│   ├── 126fdd7bf3ac9332fc3ac9b9f26c412189bfbfb4.nq.gz
│   ├── 1454f772b9d3e40d4bb83cdda20937b5071a1c7a.nq.gz
│   ├── 1513398e630d8d8e6d2190721f4533794d971c23.nq.gz
│   ├── 15b11b0a8e11098321a1fb781454c73900b059f8.nq.gz
│   ├── 1638e31a2fafbc5326b36e60351b925add7a5a30.nq.gz
│   ├── 1a82000d95fdec629f19b834fef486d0f3e94cbd.nq.gz
│   ├── 1adf9aeb7fb3094ad6e3479288a62066de445b60.nq.gz
│   ├── 1bd016e21a6110f5fe7ed10d0119c23f6d44b14b.nq.gz
│   ├── 1d52ab0e32e70b8b1a2518759e51b7c9ffdd96dc.nq.gz
│   ├── 1d9033a7613a715461297f5a5bff08e10b657cfb.nq.gz
│   ├── 1dd80b9305211fbcb378b59af58dafcd13837d07.nq.gz
│   ├── 2166f7f7e2b81511413015e48554ecda3841db6b.nq.gz
│   ├── 2329694829d0e6b416bac075deb72be6319bca54.nq.gz
│   ├── 268cc148aee880b5f4277f23674298288b302cd9.nq.gz
│   ├── 288ee16872f30dda98ae3eada1ecaf2ce0200ada.nq.gz
│   ├── 292f95554e26e1f5d0e3229d8571d8bf1355a382.nq.gz
│   ├── 2b1faca4e79a8bc6ba900e495ba59de9429dadee.nq.gz
│   ├── 2ca00b1f5d0370c7027fde6105f9c7586c68137e.nq.gz
│   ├── 2e06d1584ec649d78d9a7f9de165908b287b0bf2.nq.gz
│   ├── 2e40990cff804b0632fd56463b444318b9fc44e5.nq.gz
│   ├── 2e6542c013d74f5d7b80e6d8a887b985378e0795.nq.gz
│   ├── 2ec893610756d9cbcc6398fe542b27a05197671a.nq.gz
│   ├── 2efdfc595d78a491153aeaf0b79838659e1178b0.nq.gz
│   ├── 31f9cbecc16599ffef0d6a88124703a48e2b7366.nq.gz
│   ├── 32889bbc6ca04cc7c3c228c18dfb113fed79dc20.nq.gz
│   ├── 32f4742820674829e8d415fd1db4ef5c59009f34.nq.gz
│   ├── 332bd2ed781b9afb15d537bf30e67fa0049c6c05.nq.gz
│   ├── 36fc8c0586a34739186c57a88d47877bec03664a.nq.gz
│   ├── 397bdaa4f10fcf70786ab3afd305ad233b86fed0.nq.gz
│   ├── 39b2563902350657c0a4766a43da0e6121abbef9.nq.gz
│   ├── 39de4a4f585df03f12dd84a68ff72813b55e5cee.nq.gz
│   ├── 3cd1ff74127d9d95dbd87645da1bc3cc3b59475d.nq.gz
│   ├── 3d59414796ef40227399d0486162111094e18f93.nq.gz
│   ├── 3db1bb94dcc16815a530bccada69a3c67ddc6620.nq.gz
│   ├── 3e04d2066f4672ddc3e2f7d071eecf32584e0cbe.nq.gz
│   ├── 4198c3c2c52a886cb92499c427b8597490f468c0.nq.gz
│   ├── 41a61233140c1afb6c3625534c5c7fa3e8f2005d.nq.gz
│   ├── 42bc79a5b796f6ec9e6e998ea6ef0b89258cca16.nq.gz
│   ├── 42f3158271d5f9108061b0e1c1c9b5e745638524.nq.gz
│   ├── 43228bd660ed89a075bf7157e3668b1816ccb4fa.nq.gz
│   ├── 4697b3e7232acbc15eec8a1618b414f987535a23.nq.gz
│   ├── 46cad9d65e640223ab5a03eddf05faf20daf51c6.nq.gz
│   ├── 4758a3d80084f7273182986033deb23fe8f8d622.nq.gz
│   ├── 478f8dc70df9d1fc17c34e2fa2a5e63af8e6c3ba.nq.gz
│   ├── 49ac81169fcd31e7d22382c4dc5b776808d6ba60.nq.gz
│   ├── 4b851c6a87cedf3534f9c946e6024a7180ea3d19.nq.gz
│   ├── 4be27d1f5cec50e250a23fcbe747b8b549f90a4f.nq.gz
│   ├── 4ce5dba094b0a1a8042fe920851fd53bc58c8f81.nq.gz
│   ├── 4ef2b5c3b905b74a69a3f4843ee9f38fda874d77.nq.gz
│   ├── 5442e84cb2febbc80312695a25703809a43a1494.nq.gz
│   ├── 54e48a06190fd9dd1f0cd28c3d1fda88e4c76a6c.nq.gz
│   ├── 564787d99789740ad729774a1f19dc3245a1947c.nq.gz
│   ├── 5869922448b9f932d2680c4dea45ca7a8f7e03ea.nq.gz
│   ├── 5a1b24dcabfaca442aa880e7d36b0599bdd33b0f.nq.gz
│   ├── 5ab50df31dcf851bd016a4174c58a0a7c7c59eca.nq.gz
│   ├── 5b37ba5c5e0d974fd58a330848dc1a53ff2d2f9a.nq.gz
│   ├── 5bd8324742844352ba7f1c0d35bd00709e0c4547.nq.gz
│   ├── 5d0f81e861d92b2964e4174f5b35f0378f577290.nq.gz
│   ├── 5dbdd715c97d230ae42888063e93b8301fa84969.nq.gz
│   ├── 5f5ee29092e494e33cd1a9d88a0431e3d2cdaf1b.nq.gz
│   ├── 6589bb0bfb2fb22f9544c0e0ed9027a9c3077d7f.nq.gz
│   ├── 68c5998050f3882a3dced77491c630c53488434d.nq.gz
│   ├── 6a0480988be886948c0ffbde2e8bb6437963602e.nq.gz
│   ├── 6e1a3a5ed5c594cf73cb64cf52e51acfb73dfca8.nq.gz
│   ├── 6f0a303e51f3eaa06952da633d8b83ce8b3e8c20.nq.gz
│   ├── 725866bc50dd4629415c0f5a3e1c5929be766b09.nq.gz
│   ├── 73286a85756ed589b0527cc4b4edabe67ecee0c0.nq.gz
│   ├── 7403afc6636bea21700a8880238507a918d6308d.nq.gz
│   ├── 74d3cf92c9249dd2435301860985e7befb3c1b74.nq.gz
│   ├── 7628b5304028ae6f66aaf9807a5619e10f8ae68f.nq.gz
│   ├── 78173fa2e753d614bb0aa5ad125ddbbe70b282c4.nq.gz
│   ├── 7a08991ff7e6c9b4b98d0fd3f546c7fd21ba6771.nq.gz
│   ├── 7cb8c8e28dbcca392edec86ee2300a206a35f372.nq.gz
│   ├── 7dea4f35e160e783f8b2b18e8f745cde293dbed9.nq.gz
│   ├── 7e995b0e0aabb9c743de3ead53801a5bf62109a8.nq.gz
│   ├── 80869246d58cda1142c50db0d37fe82af5eb3f90.nq.gz
│   ├── 827d68db807c9c7f11b14d43882225afa6c1a927.nq.gz
│   ├── 82a58781ef2a98758607ff9d6427249c7abda0f5.nq.gz
│   ├── 8331746f37980f97273711504d8da27c9e747948.nq.gz
│   ├── 851db876fe25c1330bc534db20b32ccbbc578ab0.nq.gz
│   ├── 86c244864ea200e22da03ffa8c4d2e3323e33b4f.nq.gz
│   ├── 874c03dfb9efdfa64c9cd70d93812e9352fa79c4.nq.gz
│   ├── 8778cf0074d7343789e4cbe10934fd1afc3168c0.nq.gz
│   ├── 8b1692b269223d262932db42d3b69f36ded32102.nq.gz
│   ├── 8b80d24101f5f6ff5d9b18124a8cb510bb737634.nq.gz
│   ├── 8dcbbefe1d3f962083d797e5454448f7f001e49c.nq.gz
│   ├── 8dff21c13efb0c12ab3e9509f17c42917f0c3003.nq.gz
│   ├── 8eb4afa2aaba1b2d0047e25bb62d18ed09e8e3c4.nq.gz
│   ├── 91a6c4ec7f361c665bce024226833f92f449b52b.nq.gz
│   ├── 94ed9c0e50bedcd5745b774a8ba7b8ee42442f94.nq.gz
│   ├── 998b9792934b9ac38da45fcdb6f84827b44e489a.nq.gz
│   ├── 9b767f9aa9d7dfaf7672b908de9c5229050a7bb3.nq.gz
│   ├── 9db4ccaacab14ee946510db59e3e1077f2d4393b.nq.gz
│   ├── 9f6d8afe48856c46280e2b213bbc23a9d8bf9035.nq.gz
│   ├── a061d1b7599eb3c716fd6e8945cf590ac4fc7eeb.nq.gz
│   ├── a5b1ea9603090443d06ad35838a77e66202aab76.nq.gz
│   ├── a674e4162acfa8f5db4e90040b69c22c32ae07de.nq.gz
│   ├── a7c35e26b53221ca37100cdcdbe1c084de208409.nq.gz
│   ├── a9e52d9aaa951cfa2a19276d5b409b4dc61b2765.nq.gz
│   ├── aac100582874d89d57e854111dff97b76b613703.nq.gz
│   ├── ab42a20b3b1b32ec092a2754612913fc2f516e9b.nq.gz
│   ├── ac76b39add249f1dc6bea65baafa8431a565bfbd.nq.gz
│   ├── ad3d06d3a92e0c881637f6c5ee8cb1350aa4cd68.nq.gz
│   ├── ae54ad91573a0abe0893408f5db3f428b5f3d439.nq.gz
│   ├── b3a407080cbb213ca417c4cd14239511cba9aa05.nq.gz
│   ├── b42e049fcf0a18650b6e9c0ebf0294504abd6599.nq.gz
│   ├── b7bcfce85abe1d6953b1beaec32d3bf535ea1621.nq.gz
│   ├── b9c8336ea8a62713a108ada3bfd8a827db11f729.nq.gz
│   ├── bb13775e0cbfe2b11d894d689c2697bb81848658.nq.gz
│   ├── bb9554184f72488b888dd889205dba7ce952a046.nq.gz
│   ├── bc8d36a2904ab958824fae16fec17aeefa31dd3e.nq.gz
│   ├── bd255388354126d26c014e18e3d82b2ffddf7450.nq.gz
│   ├── bdfc6d2d436c36d44555118ab6e29a1e9c1fd009.nq.gz
│   ├── be8bcc22b24af3b1213bfb6ee113c6201a90fefd.nq.gz
│   ├── bfe4e3fba1d8e24ddc25a67dbf481e0839c091eb.nq.gz
│   ├── c0d6884de64644042c18c76e0aa126b569150e08.nq.gz
│   ├── c7a61da3f1d630599db01b649085790a0a3bdb7e.nq.gz
│   ├── c86724f7c85b51d96b8a138517d3e3b12ef34152.nq.gz
│   ├── c97aa010b6f8c3d3e74a43c9285b96c7b9cab595.nq.gz
│   ├── cd055805a30a5fe193706efe8e79d6de55d2c4d2.nq.gz
│   ├── cd4875ca75a65a1347432b9ca730d9c1eb9be3dc.nq.gz
│   ├── cf9859bb6babb260994787595a7d5414976d036c.nq.gz
│   ├── d3d95840fec47a237e8dd7abfb31d50202957d67.nq.gz
│   ├── d44c898b5785c708da37b6643a307df89df412c0.nq.gz
│   ├── d49c41b5249f880c3f38b991b999ac6992c7488a.nq.gz
│   ├── d51b757210f8c3c1040dbadab0113071aece9f16.nq.gz
│   ├── d5371dadd1eb66682637feed2d802c04fa2fe41f.nq.gz
│   ├── d61abc5a15a5a2b13394472cdfeb5094c1e455d2.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── d7357e0a8b51745f26ef4c28e5ab7a148d428fe2.nq.gz
│   ├── d737edaf6ed67fe97f24853f8dc7750bacd0f688.nq.gz
│   ├── da5a1ef0a48169f8370d0cc7589e55c26217f72b.nq.gz
│   ├── dc83f2fd83dd84e4a205450d56bd21a6bab36829.nq.gz
│   ├── dcace64bd3a1870d7bb9c50554f80d56ee75dbe0.nq.gz
│   ├── dcd8a607d5f6657bce17f1453745fb077a867a32.nq.gz
│   ├── decaf158e86e627f62749ba42f905200622d4e73.nq.gz
│   ├── df49ad431dec33351fab98cd092a5bdda4ef3bed.nq.gz
│   ├── df5399ee7d6f607dbf4d36401ff203c64c69ea88.nq.gz
│   ├── df55f037c99d3ee0d148240240ac989f3a753949.nq.gz
│   ├── e17f4cd832d842da1b0f8c988397915582e34c30.nq.gz
│   ├── e3155387484679a83902f1f9244d907bd6296d13.nq.gz
│   ├── e5637fe1bb69b969d49b8b37335ce8c1a3e74aa5.nq.gz
│   ├── e920cecb3a5b76a56562db57ff549db51e4090fe.nq.gz
│   ├── eb5a316cbd195d26e3f768c7dd8e1b47299e17f8.nq.gz
│   ├── ecb2ee5c51fa3e8a38e4d5e86228aa3fd0145da8.nq.gz
│   ├── ed240f054d4b87d938ee67e96d8b5ac8b0c1e0a0.nq.gz
│   ├── ee45de8b6ddb9f5c35860416bda50c98e09c64a3.nq.gz
│   ├── f220f04733b78c9c934e7e9cc5b88c403fe24999.nq.gz
│   ├── f30b8f060d03d87b6768d3cc7ce574cf926c5d60.nq.gz
│   ├── f7b928e443c3ca769c5eb75d5b6a64cd3af72dc7.nq.gz
│   ├── f84f8eb7046261382c852977b57aef99fe3b987b.nq.gz
│   ├── f93014d2c00c7560598e628d2dd4035310c4808a.nq.gz
│   ├── f9d910e2f08624b76f81b98fba092673fb486ebb.nq.gz
│   ├── fa3e88b0bba11bc21916e7ae5c1128129295bcca.nq.gz
│   ├── fb17a03cf85eab4a25554790192399a13ea2c233.nq.gz
│   └── fed1753743583c949d419e6e4a9e32180f52574b.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 0b715735a660a8566ccd240bf42489fe2ed98efb.nq.gz
├── filetree
│   └── 0b715735a660a8566ccd240bf42489fe2ed98efb.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 178 files
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

[RustCrypto/utils](https://github.com/RustCrypto/utils)

---
*Parsed on 2026-11-24 by [repolex](https://repolex.ai)*
