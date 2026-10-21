# Repolex Knowledge Graph of scverse/anndataR

RDF knowledge graph data for [scverse/anndataR](https://github.com/scverse/anndataR), parsed by [repolex](https://repolex.ai).

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
rlex download scverse/anndataR
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 24f52ce320b3dad9d15bad7c11c6803efd93a285
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 24f52ce320b3dad9d15bad7c11c6803efd93a285
│           └── chunk-001.nq.gz
├── blob
│   ├── 0010834cce0936300e030152182dd8c2305ae8a3.nq.gz
│   ├── 01a6712f7f4ace731808e523ab4fe1d19ce78389.nq.gz
│   ├── 01c8143fd03de4428a4cda62b6e31458bb9a7531.nq.gz
│   ├── 04c55859903c1a7db8ce30f4a37f144795cce7c4.nq.gz
│   ├── 052278d751ae547779d77b82c54e84141f3b7822.nq.gz
│   ├── 055d65c3486a8cc6021d7a18b7f2c024bc42a946.nq.gz
│   ├── 061accca2ef8c68bad09e7cc016c12e8cb3a4437.nq.gz
│   ├── 06f90385616ea36d942fa3dbeb2eb3692c942e17.nq.gz
│   ├── 08d67672948660b6647afa42fbb051f875629b61.nq.gz
│   ├── 097b241637da023174b0f2e3715bd0291d9ded37.nq.gz
│   ├── 0d55c53a86dbd5019cd079484dc003d56aadb599.nq.gz
│   ├── 0dc87d1c8f39df9a6a458c5fcbd39fb8ecb62691.nq.gz
│   ├── 0e0d01efe5a64415ab41eff3278a9189ddd3d2d1.nq.gz
│   ├── 0f1f46689f5493d0b43e99d96c86d29e2e9115b1.nq.gz
│   ├── 0f3a750f7c77eca83a49c4eab910de1ddc4895f5.nq.gz
│   ├── 1058923b86ec50741c17d2dff6885cefce507cf0.nq.gz
│   ├── 123014908bebbfb7ecfa1d15daaceb272fabe05b.nq.gz
│   ├── 1712645b78355022848e6e7261eb4094d2b7604a.nq.gz
│   ├── 1ad7f69b7ccf0274a459c8642de7d430f2b465b9.nq.gz
│   ├── 1c2c5fccef1b308a1556a062b0796bd92fa6b486.nq.gz
│   ├── 1f412320dec0f8679df4a37eb745edf726403da2.nq.gz
│   ├── 1f9bd2f1440a502a175ea565f241c5d6ddeec9cb.nq.gz
│   ├── 210f2d4169f853b18c66d7d765ef641d71a13c1d.nq.gz
│   ├── 23aaeae6365f2b96490092453652b2bc05139b47.nq.gz
│   ├── 23bbadfbd51f3dc66e331c762fd98657151560d4.nq.gz
│   ├── 261d136da0b44e57ba7b8178405afcc4f6397718.nq.gz
│   ├── 2647c9b8f0aa0fedf76ed6a34ef7a03e7e431412.nq.gz
│   ├── 28528d84a00f532fa8ff8e52b22efc130154d022.nq.gz
│   ├── 2909eddb66a298c775d286a16e19c41f0911c15e.nq.gz
│   ├── 29a2c354ba9cef847699858304fc50b47a8e7f2d.nq.gz
│   ├── 2a01f5d575e9049dcb453fd948b34babec95f39d.nq.gz
│   ├── 2bf5c8ffd0abc875a3428a69ea9ecdc9c6aa2c81.nq.gz
│   ├── 2c1d90207a37bc6062c03e62a9ddf193d93f8310.nq.gz
│   ├── 2ca10ca71fc2d5b9b553da6d905dc8e26e047dbf.nq.gz
│   ├── 2d19fc766d98a08d9d1437896bfb008a7b15f340.nq.gz
│   ├── 2e31bc05c60ba317bb5c6c92a8a8da70534b505d.nq.gz
│   ├── 2e81503f5a44c239ac5801ed64a5b655f46a28c8.nq.gz
│   ├── 30ec5e54987e178e12f47e888b217bf313905541.nq.gz
│   ├── 328d350f889a01a5b07f9f6ca334fbe2fa3be233.nq.gz
│   ├── 3317969cbc3bbe253789167401b6b8a46e40ddac.nq.gz
│   ├── 34df106819f88c9785b5f545ba7f9710d399b5fd.nq.gz
│   ├── 3576785b71fac8ee7d965362de639badcecaf012.nq.gz
│   ├── 35eaa36103a20e81caf9c585663d107af3b54306.nq.gz
│   ├── 3689c21a71100ca2ab70dffda40dbe260c618cd8.nq.gz
│   ├── 36d4502a52130618685f680a89d1ae92c3cdb303.nq.gz
│   ├── 37b1ed984adfa7f6a75947efbc1d71c1dabeba33.nq.gz
│   ├── 3873be4c19597ecde25f6366e7410adbcf1319a2.nq.gz
│   ├── 3b472a3f3e0ef4462c690d8b226b14cf76f0337b.nq.gz
│   ├── 3ce8135aa98ac1fcc04814368cb6cb4f6ddf52c9.nq.gz
│   ├── 3d441ecd88ec16a566768894873e0762b84cb839.nq.gz
│   ├── 3f3554cc8e9b11ea6205ad4cd92587af07331225.nq.gz
│   ├── 40126588f2a6f522c4d523df272a90cbb5ce0f78.nq.gz
│   ├── 40f657c7c915705a23394b1e60332445f2663371.nq.gz
│   ├── 42a401aa89931fbb3e3b9efb97f7e1a25b150c30.nq.gz
│   ├── 4524995bf917c0006b2bb76cf6e91e5f3eb5f0cd.nq.gz
│   ├── 454ef067520779866239c59e26213b3c50f824ed.nq.gz
│   ├── 4618d3fdba5fbd5f7e924a50de198fa9f7fa0737.nq.gz
│   ├── 4826532ec47b6e226e1c98ba7d69b7bb29f336b8.nq.gz
│   ├── 48d8bbd5f9f957dae9e8b3918f02bd539a3956b5.nq.gz
│   ├── 4b79606d94d88a5573306aaa085ea8a87c477586.nq.gz
│   ├── 4e3eacd7c6942121ca04d804a1aa857a177f4928.nq.gz
│   ├── 50320cd4e91530acedcfe60417b34f42c2459d62.nq.gz
│   ├── 516c3348eeae6f825a97a60c1ca3bd255ab99581.nq.gz
│   ├── 51e34853078cef66ac4d309df6066504fef8eec5.nq.gz
│   ├── 5393ddd73ed51793c9749b425a1a0827a147c51a.nq.gz
│   ├── 54d15f0d756a5bd8fa6ad3b6521d20d0ae8cc69b.nq.gz
│   ├── 558762174ae49844d27127b0353b31f07e5e84a9.nq.gz
│   ├── 5726a1c6a7859b4d7b12c2406f674fe38a5d0b02.nq.gz
│   ├── 59c537b8b6300e6fb5544663efa0718943df3acd.nq.gz
│   ├── 5c997ee0c74abe34e3d45469f68ffcb615bbdd43.nq.gz
│   ├── 5d88fc2c65cd0f2f966623598ba3a1f4374b39d7.nq.gz
│   ├── 5d9f60fe8db79792fe518cce80028838d6d9ae28.nq.gz
│   ├── 5e08e9c50bd390cbbdcb2af785974b64e08e6644.nq.gz
│   ├── 5e80c73f759a49d875a678017482b35016c340e4.nq.gz
│   ├── 5f3c5f9e1a7b224c9fbade59791f297e69a5c41b.nq.gz
│   ├── 5fd6bab5ca58f4fa96154d5f09c76ffda798d38c.nq.gz
│   ├── 600eff0bb7eb952b3cc6a36d16e4368de6c8e12f.nq.gz
│   ├── 62da2f3a16f9b7ee6134908065c8105b603a44e6.nq.gz
│   ├── 6444192701e34fe26fd3faa4f10feabff850361f.nq.gz
│   ├── 66cf89fa7211e69eb4ffdeed91d552adbff674e0.nq.gz
│   ├── 6768354e21388f6877692cf5785ad6421af98288.nq.gz
│   ├── 689bfd995711ef105a8acddc8245b4ca624e5d34.nq.gz
│   ├── 6a92b9ff30c3ac335e085ed3e21d647b37fd0dc1.nq.gz
│   ├── 6b3eb27d2596b96b89e5b262714f538e4237257d.nq.gz
│   ├── 75508d644a3e1969418d923d4e666887ae075223.nq.gz
│   ├── 777846dcbe14655cc0079a415a087f79796981ce.nq.gz
│   ├── 785e8c892fca7c95da7cfa644e704da009d4be86.nq.gz
│   ├── 78d1bd0252d2bd05c9eb48e2cfefaf718198b592.nq.gz
│   ├── 7967d2a14938c4b6951761427f885ed0916461d9.nq.gz
│   ├── 79f1300785606facd76014a96dd8e80805e11d8f.nq.gz
│   ├── 7aa4a18407d3799f6eed156208c2c13fd4d441d9.nq.gz
│   ├── 7ab8a1abd4b2c80cead63ee246cb56fae207e297.nq.gz
│   ├── 7b031c87bfea0d41b047d9c6cdd98822494dcd37.nq.gz
│   ├── 7c08eae4381d199c5209b7e81c9af1881dda4fe5.nq.gz
│   ├── 7ca729b9c9e3634b932b010cd12c8579f37d7ab9.nq.gz
│   ├── 7d64d8d6eba1c19621caf9a609efec466da1bfaa.nq.gz
│   ├── 7db06e4fb50b175d4f7babf9de1b388335841623.nq.gz
│   ├── 7e14d57808c4c869dd67a1dbefb4ba7236ed372d.nq.gz
│   ├── 818778b04fe70d04056b2637beaa568a8976c270.nq.gz
│   ├── 823c8a99f3bc0d01c29a4e9b840c8206073567eb.nq.gz
│   ├── 82c553de143821640f192d807a76e37e851aaa88.nq.gz
│   ├── 83a43199bd6e798749594428142966a76b3e0248.nq.gz
│   ├── 84e89d1fb5641c2dd6f71152e63068658d07bf4b.nq.gz
│   ├── 858e9442d344da0e61883badc8dd13d86487fb26.nq.gz
│   ├── 8d17bc6377235d328ca78ae37c338cd523cd6652.nq.gz
│   ├── 8e2a6358a8b859c66898fdbc9827b4959ff80233.nq.gz
│   ├── 91b813322a2eb12ccc4d3ca6d3db5a29ad2ef734.nq.gz
│   ├── 91dfb64c48766de4014cd4441b9c08a5fbb703a9.nq.gz
│   ├── 92a07082739b8acb6ae8958395a8a48c54022c3c.nq.gz
│   ├── 92e4d67894997fe793df97e81985d817a50b7fa5.nq.gz
│   ├── 93309f7d0e50cb23342ff15d6f4eb7d4b0b53377.nq.gz
│   ├── 9397aa9550897b3d267738198b5d19977d597830.nq.gz
│   ├── 946baa81e2308c1f563a9c88da52e12ff800bf03.nq.gz
│   ├── 948af6756b67fb14f88cc3e42de041d80b5515c2.nq.gz
│   ├── 94d16334d72159196772e9cb8f9ebca0a3c30842.nq.gz
│   ├── 96ed5ffc4e6bed4c541a7b7e4ede9e5c0845c4d6.nq.gz
│   ├── 97362f5ae176d69a2b9f1d78f04823bcfc49afdc.nq.gz
│   ├── 9bf21e76bcb43085a6daefe65def015bc6313df4.nq.gz
│   ├── 9cb4fdd6c5e5512b03da12911b9eb56b7e2ff388.nq.gz
│   ├── a1836cceeaa7af67d119a13d84428b74311913c8.nq.gz
│   ├── a454c09074c12673aaf9cd449996b5097762f964.nq.gz
│   ├── a6770036b222ffc4e5309e2fef868c0f6d0af7a3.nq.gz
│   ├── a6bc30004ff5017849f4876111ad3bc393178279.nq.gz
│   ├── aaaf31813f33259614c1609d811fe7aba2d1257b.nq.gz
│   ├── ac6935c441e568f8a30fe2bede5fe9f2cbeaf9a5.nq.gz
│   ├── ae4392ba40e325022e380e0fc3e45339ba278130.nq.gz
│   ├── af10dcc505e41ce2c604a36ecb24fc01a59e65b0.nq.gz
│   ├── b1e89e7f70127535d5c6d14e4cfeb62f956161c3.nq.gz
│   ├── b36c4aa287cb624c1a3ebd4bb99e69797a8c1bfe.nq.gz
│   ├── b4a5416fe3e076398bf02495b5530398fb4cf0dc.nq.gz
│   ├── b61c57c3f9c1d4838e0c310a36a8dc029d610c60.nq.gz
│   ├── b82deca85439ef37aba773078cdab9655da2aea1.nq.gz
│   ├── b9782648cb52798180e8334517e94095ec07c5c4.nq.gz
│   ├── bc6dcc6b7dfdf09b140b9712de872dbca7e44698.nq.gz
│   ├── c01e1547570bd64d72abaa3daed113fdf44866d9.nq.gz
│   ├── c09d145b11380f86126c925d5b32a53e783c02c3.nq.gz
│   ├── c1b97257d208a0bc42cf8bbf6cd386dbab87fab5.nq.gz
│   ├── c2dd22bb8d2d24239a4dd540716ac308d50bdd89.nq.gz
│   ├── c325f4eafb7991d90cceacac84a8dadbbfab8bc1.nq.gz
│   ├── c3faab0d7154c8c7a0108d2c08d3bbaf2bf74960.nq.gz
│   ├── c4d5fa5474550a291fda21c914db96f84164399e.nq.gz
│   ├── c525918ca31c9f0ee3cbd9e3486b899fcedac328.nq.gz
│   ├── c9fd78d0b27da9770449da948e77f02976ad13ee.nq.gz
│   ├── cbd040bbfe9642fc515b4b17b82a0d2c09e898bb.nq.gz
│   ├── cd47a008e53fdb22ce6e4692bdfaa5424a84e612.nq.gz
│   ├── cd7b861b66ae3e7914f0586cf9ff6d63f7804fb1.nq.gz
│   ├── ce9769397a1f9bd1810538467b8dc0704d090c39.nq.gz
│   ├── d4c1da18ebfc83b48241b4a78f9287689d18e3cc.nq.gz
│   ├── d4df1a2f5875b965d141f1666cc93f561484ae42.nq.gz
│   ├── d60e024c22e8afd5226822ba2a1abbad9827abaa.nq.gz
│   ├── d648eb3367c176fc1b05b99eee6edc70f56e3b0a.nq.gz
│   ├── d7900a39a39605b175ffd06250ec8d60245850c8.nq.gz
│   ├── d798117dded5136b04ac2875df4c55e76ab33080.nq.gz
│   ├── db8d757f7043f0cdc02c74bd9e722be59f4d5caf.nq.gz
│   ├── dc454b32a69de796a436695b634ca940f1d74e93.nq.gz
│   ├── df3cb3d268c1b8bce9af2160bebdf27d7a736b77.nq.gz
│   ├── e1acfddfc4c071f3c2e4045fa581f2e5e1593c4f.nq.gz
│   ├── e51ce35fe8ac4bd5ae6f4c360ed948a9448ec418.nq.gz
│   ├── e73f2e3d62b1106b2bb7d6d714c5e2e2304671c0.nq.gz
│   ├── e8a4485dc781ae34e91bdbbd256f9e7599ebc3b7.nq.gz
│   ├── e9df5ef0244698245ea121f6a9731d904c5bc4f8.nq.gz
│   ├── ec440df3196a2a34d3b02cc51377055e5fa5b343.nq.gz
│   ├── f2862876b36d3e711b277389872d0dbb29689c63.nq.gz
│   ├── f3b920d58b014c5f382b1dc005cd27e64800c65f.nq.gz
│   ├── f4d51b048d50d1b996ee8d55c65f6e47832ed825.nq.gz
│   ├── f58ffa6a275a3439884fe1e342b22b968b4f8eef.nq.gz
│   ├── f5f0d3f8b0287c184f77a80aaa28b1b0c2080093.nq.gz
│   ├── f7aa1fa5263733d32d8a6e3e6bab643f8ab22115.nq.gz
│   ├── f8696795cb63dd713a5fd5f0ae7ed42dcff89798.nq.gz
│   ├── f92471f25df016e41feed121485b91d5ea7475f1.nq.gz
│   ├── fbe2008ab9d2570d4e36c78f5a784444432b6f8b.nq.gz
│   ├── ff0c1b93748b8e2a2d8ef567db5cdb3f0854faf8.nq.gz
│   └── ff826fe5d0dfd1ab3f4e66e678003b93b94b7083.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 24f52ce320b3dad9d15bad7c11c6803efd93a285.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 181 files
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

[scverse/anndataR](https://github.com/scverse/anndataR)

---
*Parsed on 2026-10-21 by [repolex](https://repolex.ai)*
