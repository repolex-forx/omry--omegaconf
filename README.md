# Repolex Knowledge Graph of omry/omegaconf

RDF knowledge graph data for [omry/omegaconf](https://github.com/omry/omegaconf), parsed by [repolex](https://repolex.ai).

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
rlex download omry/omegaconf
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── bba6c5f1fe18ea4f31e2fc841b5743a9197d6384
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── bba6c5f1fe18ea4f31e2fc841b5743a9197d6384
│           └── chunk-001.nq.gz
└── blob
    ├── 01feb257e11bf17410002026367e5a35213b1db3.nq.gz
    ├── 034324c317f6d6487be548f6c48552974936ef36.nq.gz
    ├── 04aa34b08dc0ce3575100160293bca1c22d72b7e.nq.gz
    ├── 04e5ef98687fc4f170b66e107b1bae69cbd81a46.nq.gz
    ├── 06e3b99313d61edcb0ab42de4657dba98e184e1a.nq.gz
    ├── 07c556a03c208a56b7207405cf233a084d1db47e.nq.gz
    ├── 07d67a88d2864b51f4ae405225c20b283ad8cfcf.nq.gz
    ├── 084917e8037db07bc2b8ae730a992f7dcb7efbd3.nq.gz
    ├── 08dcbe05da13c5408206155bffb0178914da528b.nq.gz
    ├── 0981f9728957975c032257faf87f47eb31e3a94b.nq.gz
    ├── 09bf7d9d2e454579f3028cd8fbdefe6d3e0b28f9.nq.gz
    ├── 09f471657abc8327da12a734982a5631265a1e56.nq.gz
    ├── 0b05dbc19be24409b82d879611ecfbb8cb0a35fd.nq.gz
    ├── 0e2181e247c105bce4732816b13423c31d90911a.nq.gz
    ├── 0e51e9856d4fd89e5d7aba8ad636356d0164667e.nq.gz
    ├── 0e846b09017cb222ca2aa31e5c05b6b82723abc8.nq.gz
    ├── 0f2d60cabcb3b315c4640e5b9f3d1354d1346444.nq.gz
    ├── 0fb699d5387044c875ac89caa5f23c4bd8a6411e.nq.gz
    ├── 14066bd68c1a3cb5a3606b73b0f3cc2a6a6510b1.nq.gz
    ├── 1434aefb283bb01046e5fa6855d0d761f4a069d4.nq.gz
    ├── 152b7ae5c2ba75eebda3c363dba08107306c4cca.nq.gz
    ├── 168bb96afa7a33c42b9612d49c9c8a32b2a51f2a.nq.gz
    ├── 16b5c0a30e81539631370b1ecc6bd9c0b99edfc2.nq.gz
    ├── 171b9d9a6f1a748e8b109c80a6ded2a6496fbd24.nq.gz
    ├── 176a786174f6c378b68c3561d7bf7a4662d3833d.nq.gz
    ├── 18f7280d11773399e9d98642838716f5167d1cfb.nq.gz
    ├── 1a6ca89764c8586e52e4c402a765c07752a72754.nq.gz
    ├── 1ae8b2dccd18295dca94c63254915e250c527d35.nq.gz
    ├── 1b0bb71168722281af5ddecb46f79e36f63c71e4.nq.gz
    ├── 1b811b56a3913c2dd59450eb48230145d54842a3.nq.gz
    ├── 1c6e84d95dea79b111afd7ed83af66192fb9af38.nq.gz
    ├── 1c95f18446a0ed30c958e6f9b343cf2e66becedc.nq.gz
    ├── 1cdbeb75cc04e62d004abc21154eca431359f0fe.nq.gz
    ├── 1d3ea08dfd62bf34b182d6b29d2decf945432aa6.nq.gz
    ├── 20d0a2daa9b237f3a65e112c04eba1f77b14452b.nq.gz
    ├── 215cec77666c6e2c1a8842af73e8142911a54ad9.nq.gz
    ├── 2161ed3e4a9a386a46142ade8b611afaaf16a426.nq.gz
    ├── 27009a6c1bcc93334755aded2a84d48fff576ebd.nq.gz
    ├── 27d5d54d3c40cb2f482be71eedd0af956cc83819.nq.gz
    ├── 27f25e7dd3ed60083eadb738df4da5e85a0c2e8b.nq.gz
    ├── 28ff015d0d4ef8cb79307421f29f5834a343f151.nq.gz
    ├── 29e327ae7fac43952a7b4d279af75f6b51a8917e.nq.gz
    ├── 2b41a8e1ab07d3d19b04fdd605ef2278e07bb8eb.nq.gz
    ├── 2c7daae1404f700f831451ac49a92259cbcb14d4.nq.gz
    ├── 2cac145b2548b21768688b4fd8258d5e70404416.nq.gz
    ├── 2e2964612ebb4a83d0ad366e2fd168e3668d3887.nq.gz
    ├── 2e4a5780cc1a380c46396b7837ad1068f10c9934.nq.gz
    ├── 2f186cf99e195ac554bf633924ffcc698005dd5f.nq.gz
    ├── 2f7438c8ec8a1013b063146b0a8df5537a827b19.nq.gz
    ├── 2f9a183a2e3be551efc4bbe055724f17aba12b4c.nq.gz
    ├── 2fe6836453d3f535f0aba4fd85036d61c0e044eb.nq.gz
    ├── 310fedc21ffdb313785e95dbbd123710565ec56b.nq.gz
    ├── 334e3fd57b24e05d4e325b25106f932643508c45.nq.gz
    ├── 33d43acc55b765b8049de527d3eff4f3f38771c9.nq.gz
    ├── 3505c5c5a749ad9e3f742ef5843116a9eec2e4e2.nq.gz
    ├── 356b6be3f2aa482b30e754e95d5d5e6f0226752f.nq.gz
    ├── 370fdbeda9ae96bb32cdd67d3c6020f8bda2e175.nq.gz
    ├── 378eac25d311703f3f2cd456d8036da525cd0366.nq.gz
    ├── 37e39b41df9d8d9d5ef9b1574949858ccb61abb7.nq.gz
    ├── 3803576ad885b9304a811ec6cb73670a3dcfa947.nq.gz
    ├── 380f1ef17c2506436a0a9e8f39d30b76fbb212d9.nq.gz
    ├── 389bdd77ab45b5c4ae53973e7c0c51b00e12c1b6.nq.gz
    ├── 38ab8eb4707983cd724c996673da677f4125f906.nq.gz
    ├── 398eb4fb1baa5c0f5fe71fee7b32479b9ac0f5b1.nq.gz
    ├── 3a02148518068125ccb5aba3e8fe2cf0279a0b50.nq.gz
    ├── 3a07d337af36ff8e074e45a179519befc38d6d94.nq.gz
    ├── 3d742de5dac1ee394368e7dd096bdade09c27349.nq.gz
    ├── 3d8d23213da3dd4135075d0ab6988af7a4a43c04.nq.gz
    ├── 3dc3ce157b5de32df787e4925fd9251a65fa01d2.nq.gz
    ├── 3edb2e577d9faf12a8ada598b0bf669411df4dc3.nq.gz
    ├── 3f0b64b8e32d4e592f736282e55efe912284de77.nq.gz
    ├── 40ecdc0319d70f44c907632804ecf1aab066e9ba.nq.gz
    ├── 413dda5c198eb1b577ed4fc7c329e88e393de68e.nq.gz
    ├── 41622f4f4ff2b39f6bcfac8120c65782c1ccae1b.nq.gz
    ├── 429c53dda42cec7e89f42b8fae0e744930c4b455.nq.gz
    ├── 44570f7ff92001862e23b6a0b484f91a2314f7f0.nq.gz
    ├── 49bea25009853bffcacac0242f110a49969eb986.nq.gz
    ├── 4adc8ab61bb60cf88c14dae1ec3bd8472b5a09f4.nq.gz
    ├── 4afa1a1d3d6485933d57eba5752198d4e0cb5202.nq.gz
    ├── 4b23a3fe21dc13eb487b51be94660923da4ebaaa.nq.gz
    ├── 4b6708422ce838554eb86a22bbdf9168b152bab6.nq.gz
    ├── 4bca19307856c7b0f24b7b7027412d2f98db9c0a.nq.gz
    ├── 514a2f83b58cc1c120eb70dd0a6896d56041688f.nq.gz
    ├── 52536a89c5678055694cd849cbf622311055b199.nq.gz
    ├── 52643838f1aff84776708273480304f8e6c70607.nq.gz
    ├── 52d377616720d0e5bd76b427152765e9cdd5dc5e.nq.gz
    ├── 54c070d7a035ab0e9775324266bde7b74ef2baee.nq.gz
    ├── 56dc884330d802d6f8e49cf72591ea5fddf8aa16.nq.gz
    ├── 574f2711e39c99432f2d77e9d5afaa67487b00a2.nq.gz
    ├── 5751b0af769e7ecfe49a4f0c3750c09d64b6e14e.nq.gz
    ├── 58991356242620828f8908e42555d4bba4a2d618.nq.gz
    ├── 59688c6c37e87c180520d26e15728ef48a0a0251.nq.gz
    ├── 59f23964699bb306da94abdb14c7819f8ff2fdf9.nq.gz
    ├── 5a8fe50465eeb6e97a285abc2c44b21682db44c5.nq.gz
    ├── 5b1b7d428ea4c2ef27b1ee91f0595af6e51f23a5.nq.gz
    ├── 5bfa0db0461d2de7da1ccc66ef033b8e72679cae.nq.gz
    ├── 5c5623e3a22cf5eb9ad2ac6b47eb64a8f651789e.nq.gz
    ├── 5d276941558adc380d467a0a34ae92bbeb6e4fec.nq.gz
    ├── 5e6bf014a3305e510d85668c85a3367ef96b16c5.nq.gz
    ├── 5f4471e84475e78d55c438eeef05a3c2c071048c.nq.gz
    ├── 6066fd511dbbaca881cbaa299f4e2f10b9ba7ffc.nq.gz
    ├── 611818c9c9ddb57fc60bc4325e8bd0e839ea959e.nq.gz
    ├── 61805910173572abc85e192ce5bf2e1a1a48d3c9.nq.gz
    ├── 631af29e31cf296c0721f9ab418d70c9a3452525.nq.gz
    ├── 65e3cabb637a0b7f665e94cd5bcbcb597d52b17e.nq.gz
    ├── 66ed94af9258c3376a59791e6de54db241ae9f59.nq.gz
    ├── 671c3702a7541c1da6fb0056c1ca3c90efaa5a9c.nq.gz
    ├── 681d4ed8692f5e936a1c3db123895d59c2389787.nq.gz
    ├── 68424ee3f5fc462cb05d236b63026be0032b658e.nq.gz
    ├── 68812e183ff9ddadf67a08daeea36af6cdcb1078.nq.gz
    ├── 6949adce1d1f26b888051aa915e4798d1bdf9a97.nq.gz
    ├── 6bcc9f0e8122187dd3b3a63dfbc19a25b1274527.nq.gz
    ├── 6c03511008f6b93befb71d82ca38465b2e4868d8.nq.gz
    ├── 6e4b30b3c18ac334395a78e5a20f1891dbbc176e.nq.gz
    ├── 6ebc601a96014f71716142156529442c2ca9c145.nq.gz
    ├── 6f7cc61d3f0c87d3bbd8fcba9f7bc358ce3cdc3e.nq.gz
    ├── 74dd68d105454bbbed8e1c4946339b1bd018889a.nq.gz
    ├── 75b6107dba1306189f24204e9da40cc9a56c9d78.nq.gz
    ├── 75d2b43a61ae6702941ae7517e857fdf423f1ddd.nq.gz
    ├── 7642a3b82495be7729ff5ada7a1c311914de3d3d.nq.gz
    ├── 78611f2c1d0d937c11b975defd5870b9fba083f2.nq.gz
    ├── 78733db00c951c973a2a86197694a7eb650991e1.nq.gz
    ├── 78d3881f3cf75eaf00a3059bf208e73dabddab76.nq.gz
    ├── 793f104a9c917f446e74cafb7b36b7965e4fd8c3.nq.gz
    ├── 7bb15ac111b34e41637378bb4b6a74983183293e.nq.gz
    ├── 7c8b424abd9220f71dcf1b3fc60a31066ec89dee.nq.gz
    ├── 7d3369de6f617461d18bc620728ec8f4b4ec4ec1.nq.gz
    ├── 7d4cfe44a653e07ec45b1bae5e7d7ecd3aec06fa.nq.gz
    ├── 7da3946e67fd9f73cb1b1e3f1e818e5c027a52a4.nq.gz
    ├── 7e7ebb6ac668efef21e81eac644b094e080b9770.nq.gz
    ├── 7ef7dd25aa2293e1fe227edbf332bc096f51c561.nq.gz
    ├── 7f10a1d85566496caf397651e85ae326b9d92d28.nq.gz
    ├── 8003fc5a35278b3461e34a16ac66a34bfcb5ec3b.nq.gz
    ├── 804ed59d9ebe543bb361b9790eddd369de9b9b18.nq.gz
    ├── 80cefe67f85904d3f1ca785c07313ee19ccc965e.nq.gz
    ├── 81c2fdf683d9af020f69da08b34bbe6304028990.nq.gz
    ├── 81e4ba04ec48655de724d3581e79692c704698e8.nq.gz
    ├── 820c668c87b31da0c56d6519b8064ecd64dff56d.nq.gz
    ├── 8243bd55f9ce02fa0ea3e4c10e05f6820475be00.nq.gz
    ├── 83769267276c57fc9c1c156e71196033d209ced3.nq.gz
    ├── 852908a72535e72416b2b7cd2bb1da4e2513294f.nq.gz
    ├── 869c18da05779569af020f7429aee71bb2041774.nq.gz
    ├── 87d59d80d81b637631f67887720b12d3bdf8212f.nq.gz
    ├── 87d8a6299dd9418b1071479a2b81840ae86f8dd9.nq.gz
    ├── 8893dd409bd96d9a3f0328d55782610a6f259d0a.nq.gz
    ├── 88958a190ae1ad2669c9adf8b952f158879a583c.nq.gz
    ├── 8bb186d4502560ba2ea0cd580245b9368685de05.nq.gz
    ├── 8bdd8e6cab657623d5bbe041001265a843aadbcd.nq.gz
    ├── 8bf5dd378a74650d031e7165e6df6607755ce73f.nq.gz
    ├── 8c8e616ae1d07f319244f0a0b50abad0aedf9930.nq.gz
    ├── 8d5140b1c70190776a7e07a79f040dfd4aa6b5ab.nq.gz
    ├── 905a4943e146cda044eb2fd527b65f23d711f6ab.nq.gz
    ├── 91d1baa2f6ad2abea9922f58b63a2141c5382cdc.nq.gz
    ├── 92729e87a03ccb21e156c0b1cee44d36115c67cc.nq.gz
    ├── 930dbe5efaf6610c9b951d7f8fc29072e8e3a7ac.nq.gz
    ├── 94a169d05815bb962ea84595e497c5997e204190.nq.gz
    ├── 95fcdbda2b8d47d9c1a25820302801d7956e54f2.nq.gz
    ├── 98230592a5a78dbea2fbd38885ac3c1edf16a654.nq.gz
    ├── 983b4c719b6b1f9ff657c3754f299ff19623f76d.nq.gz
    ├── 98e8aeae69762b4c84d9d1e3db8bd7212d111f62.nq.gz
    ├── 9901356fa9071f1887adafb60f1717d13a9afd83.nq.gz
    ├── 99039df354f05de71fd2b2ce3d1fc4761ae6a07e.nq.gz
    ├── 99a162a88614204db68ed07b26188a7904352a08.nq.gz
    ├── 99aa9f9a0c0f2968b2b885881286b46712c5fca4.nq.gz
    ├── 9a84a3e8a230b445e4ae3d5afa4f34c3d419087c.nq.gz
    ├── 9ccb219733e78045e3616958b180662bad13c42b.nq.gz
    ├── 9d44a747e9e2f4381fc214fd917c57b47c27fa80.nq.gz
    ├── 9e59a31ec7a95246f1309521110580ada9784659.nq.gz
    ├── 9fbe9bac7d52cd3359cc21ca5c3075ce70f16187.nq.gz
    ├── a081a0674e6a8dac95aec228e48211a6aadf348e.nq.gz
    ├── a0cb1dbf531b3563acfa87959d0b06c749cd240a.nq.gz
    ├── a1eea2779e6faebbde7a20bf08d102a1e10a6eee.nq.gz
    ├── a27e6c785c92c82428b7e16c380ab933c0b446c6.nq.gz
    ├── a31a9d1564866049e36c2d62768cdfcd42549f3b.nq.gz
    ├── a322cfb392806e24d0fb6cdb6b34bf7fc401945c.nq.gz
    ├── a324f5b17651cc372927b7dfb4ed3e78793865fd.nq.gz
    ├── a3466625dbdfc36885f551ee74bc9fbffe81e59a.nq.gz
    ├── a447f28e8a64c0d4544824194efae49b077cc2a1.nq.gz
    ├── a45fd52cc5891570d6299fab38643103c3955474.nq.gz
    ├── a547133f5deb5ff147ea226368a68a714ba3b117.nq.gz
    ├── a6da6c9120793694d92e940affe48b2c0f7ae24d.nq.gz
    ├── a857da6bca7ada303b6de7d250788071548a3c22.nq.gz
    ├── ab055c07df822174bde432309abaad342866963e.nq.gz
    ├── ac133ff195ccace978ddf40f9ecc6b812f24505d.nq.gz
    ├── ac1668dfb23154400ddb1e182d3337555a52499c.nq.gz
    ├── acf95b528ba06126dd1230996d020160aad6825f.nq.gz
    ├── ad0d59d5fdb44a25b1b19e767261dad52b7da281.nq.gz
    ├── afee55f9dfcebca44d8cb7bedb43d2ee4b96bf65.nq.gz
    ├── b14ebde1ce542a0e03a0597303db93bc9356c5eb.nq.gz
    ├── b388ef1accfbf3079d9792d96711488804d6a625.nq.gz
    ├── b3a612d7bbcdd6ddada40986f19539e772a51edf.nq.gz
    ├── b51a82ce123baa71eb91847d3665b98d09c0198c.nq.gz
    ├── b5500403efefc52e76a3c2de644a99fa5a301053.nq.gz
    ├── b61e0b3e526fcf3790979489e3cca50b6985d742.nq.gz
    ├── b7bbf13e63eac7b79c549c69e0607f37573fbd6e.nq.gz
    ├── b7e478982ccf9ab1963c74e1084dfccb6e42c583.nq.gz
    ├── b99f777014990b51a9eafcd446719d39c800935e.nq.gz
    └── b9cfadb99e7b97fa52279f8ea63d7320d90aa3c6.nq.gz

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

[omry/omegaconf](https://github.com/omry/omegaconf)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
