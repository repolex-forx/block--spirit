# Repolex Knowledge Graph of block/spirit

RDF knowledge graph data for [block/spirit](https://github.com/block/spirit), parsed by [repolex](https://repolex.ai).

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
rlex download block/spirit
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a0a8e82817bd12285696207fcfa65f75a84a89f2
│   │       ├── chunk-001.nq.gz
│   │       └── chunk-002.nq.gz
│   └── repolex
│       └── a0a8e82817bd12285696207fcfa65f75a84a89f2
│           └── chunk-001.nq.gz
└── blob
    ├── 000f174ed68290c22423c1726be83d2d43fd0441.nq.gz
    ├── 00c2b7f40d16d8ea37d100a492473c7499f0f5fd.nq.gz
    ├── 01141ac0d286bb6d51bd42cb8b4fb05b18017d3b.nq.gz
    ├── 0189ec621dd2eff5baf55407ce231c2a4d9efa3e.nq.gz
    ├── 01e97eabd927249b223b898ca2f0a73b300181e1.nq.gz
    ├── 01ff2f3430ee2379a6f206d029b66bee42e6000e.nq.gz
    ├── 022296e7d074b7a4327cce67fbed0e1a689db9a1.nq.gz
    ├── 02a934e20300a77016e165ce453303c78998110e.nq.gz
    ├── 02b122022518f733ef8fb3e0b8f8640ccded3c1a.nq.gz
    ├── 02d757fd9a435326344d0aa449015691f7dc9f59.nq.gz
    ├── 06dc5d0c0f27945fb7729ded2910e632cafe4f94.nq.gz
    ├── 06ffc9e0c7b186dd774c5b067e73b9acc30f6467.nq.gz
    ├── 070e0c2852e5f062badd46c21d1363e9a38ff101.nq.gz
    ├── 077a892d30e91e32b195387f14172d0b46b07f04.nq.gz
    ├── 0784eb085b265ccfacdadc94c5797d4c17b9d654.nq.gz
    ├── 07dfa446ebd28a3d2bf0880909661da9fe86b641.nq.gz
    ├── 083c97b54767c80294ea9fd9942feb6855509f2c.nq.gz
    ├── 08619e647ade76c48c022f78ad7c11735e652a21.nq.gz
    ├── 08e53bb1b6f88537c66953c5efa3121af42e8546.nq.gz
    ├── 09381ef3ae80cc512f4115214824b502d700360b.nq.gz
    ├── 09f2aee8d938ffd5f33dfbff94a61e105fc1437b.nq.gz
    ├── 0a3e2a61042a0f2744647d59eedab012275335f4.nq.gz
    ├── 0ad5d95fcd30291f5529adccd17258686b2067a7.nq.gz
    ├── 0ae9f6278802f98ebee840db3b331bf77fdabddc.nq.gz
    ├── 0b4dbaa7891035012cae2db518992b6c965830a5.nq.gz
    ├── 0bafcd5f5d50f7e0300baa84219dcb307ddeac7c.nq.gz
    ├── 0bedcd79db8e06ef0846fd46082b6ff1ba405d24.nq.gz
    ├── 0c0f8f5b18546f0a28147fa6c6ebb80855797235.nq.gz
    ├── 0cd7f0899b4b0919688c96be53a793d3c2e585c6.nq.gz
    ├── 0d631bf41756cf98180b0c1b17e708838e096046.nq.gz
    ├── 0dba4729b294694e2f6e11d63afc02334aaf3936.nq.gz
    ├── 0e11cc613d5b341311f34f7c1abd0369a4b27333.nq.gz
    ├── 0ea1de47ac73f29c56fd743a71a5c312fd5903ef.nq.gz
    ├── 0f22e437e9e94b6af03c86c0e8514295ff17b52f.nq.gz
    ├── 0f4dcb9f5dc6a6ed778a1cadb0582d938f108dfa.nq.gz
    ├── 0f9712665d3f86261800e7ebad2ef591c0bec119.nq.gz
    ├── 0fc9f2d633f3e9f4c13a3909e19e6b9c86793684.nq.gz
    ├── 1048d9d90fb9d81bb65f4a46e78969f8eb96ebb5.nq.gz
    ├── 10df0715253a132c28404f2d5e63a1dc508bcac7.nq.gz
    ├── 10e345c1ec4cc8abb9313f01ded6e5476092d06b.nq.gz
    ├── 11b91bca4d36f73a38672e07b0201ec8c3bb6da6.nq.gz
    ├── 11cb1157e4c3f64af1dcf4edbf79662a332380c3.nq.gz
    ├── 11ecc36312b59b9a3e5b54993ef317b221a5511a.nq.gz
    ├── 11eecc02700d48786e0818afce47c5a287eb619a.nq.gz
    ├── 12a9f491efe96f2da1126caff6eccfb307038b79.nq.gz
    ├── 131509ea259c425c047456b95fa9888b7caa78fa.nq.gz
    ├── 1357ed4ba11cf08109c5950fae3302ae5ca7f0b6.nq.gz
    ├── 1438785dae1cffead4b6b6cec7fafc3bc3823ce6.nq.gz
    ├── 14a33bf0d17b62cdcf5e138af1b1095a62b103d6.nq.gz
    ├── 14a70a733cff1a59414fdc2100ff326e7ff18695.nq.gz
    ├── 158d5da5adb16976965121d5e667e388280a5669.nq.gz
    ├── 160c163e275caefa187c00a6ae9a19efe173ff6c.nq.gz
    ├── 16aeb6a56f0dd1f72bdaacd85d8c04996dec93a7.nq.gz
    ├── 17e9da12796971b295c3918487627db114b0b823.nq.gz
    ├── 185a65cb709282c15e364cfcdaba4cea36fcc2a5.nq.gz
    ├── 188fd90364765ca988a04c16ef718b9e1f7b8017.nq.gz
    ├── 18933e12b04333233f4b015a365d09798b608208.nq.gz
    ├── 18f5c3df8e4758fbab88e6d9ff3df6d4ae3e3074.nq.gz
    ├── 195e5cc7f75b0179386a8fe1c50d316b025d9acc.nq.gz
    ├── 1a4cb2eb5889358ab0e97e46af80efc4abca8abf.nq.gz
    ├── 1a7a1edb77d984054a69dfc76d63ec50b9accb79.nq.gz
    ├── 1ab503a5e9e51cee5239d239982068d0d5e31d79.nq.gz
    ├── 1ace8b561ba7f009cfcdbfeaa2525a1663f7c6ed.nq.gz
    ├── 1bd496f684782b598867c3223a46b58c8df7afce.nq.gz
    ├── 1c7ed8bdb3a84c0d5b393c947101fb4e8cded88b.nq.gz
    ├── 1cba9e0ff83d4a0fbb7e62b8cd7604990ce84499.nq.gz
    ├── 1cc7dce749786953dc0eaf645d0376e805ed6aab.nq.gz
    ├── 1d5b13e79a64bda94a009bff49f01c6b83b9ee8e.nq.gz
    ├── 1e3bdeefd618a750a4ee0b875f92a7e2ab611ba2.nq.gz
    ├── 1e6b9d325b33200f02dd7d5359b709035a12bf3f.nq.gz
    ├── 1eb571cc0d2729d95aca600571798c724881ad0c.nq.gz
    ├── 1fbef253883562b54de386bc04495cc55f7fab44.nq.gz
    ├── 200d301ab7d792e3cc4fdaf3033b06c33bc28f23.nq.gz
    ├── 20e3975dab7afa2cd0420b523a453aa81a2e858c.nq.gz
    ├── 21863775733835ba04d023817f41706c679f3016.nq.gz
    ├── 219dbf4cd6bcbef229b7fb005f9953e195d97ceb.nq.gz
    ├── 21b41d502e91275bdfab5f6abf4a8b2aca8aeeae.nq.gz
    ├── 21fdbacb762f702f755f58b06c6675bee1d2a383.nq.gz
    ├── 22c2580dc37d00cac71d9e3ec437ced61957b41d.nq.gz
    ├── 232ff46727872210c30c52264a0bee074edbcd19.nq.gz
    ├── 238ea405778bde2c4f3b1a0c74aae3f83e6aaa4a.nq.gz
    ├── 23b01d534b882e7ddb775ecbfcc6b0cdd496223a.nq.gz
    ├── 23b81e44662642e58ab15e8d018712129710bb32.nq.gz
    ├── 243b1776d7bf02760d677b25368200caa213c915.nq.gz
    ├── 24f88518263322d11159fcaebefba2397f99e17d.nq.gz
    ├── 253e6dedc98b512af48dd4aecefeea59143679c8.nq.gz
    ├── 25bd2fa46ac4be807e15928de074963cbe950daf.nq.gz
    ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
    ├── 26d64191d9d828df68ebc623b4eb08ed0b1f78f4.nq.gz
    ├── 27afdea29b77da8f436b402138185c5bd6c0a21d.nq.gz
    ├── 282cb05b8f128483cf5849c4375dad9828629284.nq.gz
    ├── 284a3def726da464ac711716832765c0dc0a10eb.nq.gz
    ├── 28869f9a37d3315fee15bc9cb83df021b7ee199e.nq.gz
    ├── 28e9369de75298c24b25866c3980b2642ea9ef4d.nq.gz
    ├── 29b54420d4424ff50446e314ea37f8f7c65f2e78.nq.gz
    ├── 29f1dffe48d0bfec26551c83f0d593fab891923e.nq.gz
    ├── 2ac3634820d695c05e4b7474cbf08b35ac1df469.nq.gz
    ├── 2b0b1fbba22f587f0a98a44fc624ac8400616ca0.nq.gz
    ├── 2d1720111809a3d2c8cf6b03ea895f9c29e49dd2.nq.gz
    ├── 2d4c5ee2f6e75df6785fdf617ff6a41ed93c983c.nq.gz
    ├── 2e07a901e3798eaef1164a9a57bfc4af81aa8404.nq.gz
    ├── 30302df8e17bb1b50e49ea28b518bc06c854353b.nq.gz
    ├── 30b256cb69bfd9ab6ffcedec21fa3559c21a96ae.nq.gz
    ├── 319566b91b459ea1f6ad8253362c9c1abb968a0c.nq.gz
    ├── 31c22257edb7f1f66d26c3db5da6435191af164e.nq.gz
    ├── 31e8efce82e721f31d09f9ad9cb9e8a8b33477e4.nq.gz
    ├── 3290e58ab11e5285030d48fda1358bbc014e7e9f.nq.gz
    ├── 32e54903735ee518470a00f87b0bf156f30cd27f.nq.gz
    ├── 340b1c7a31686ae53dfc8fa7550da9bbec49eeda.nq.gz
    ├── 3422f0853e3142c4192b99ab7edda7c47d18d51d.nq.gz
    ├── 34d8d6cf2b4fc4633e89c641dee92ea0d2674203.nq.gz
    ├── 34e402739b2179a1ef00a43c966c1693a50068f9.nq.gz
    ├── 3524547266cc127d9db7e6b4e6f3e7c8401469f7.nq.gz
    ├── 352cb0de084a50c2b332567dbf2222e9fb810d28.nq.gz
    ├── 353736d58b0f9de16e7396fc8d0c1639f9ef50b2.nq.gz
    ├── 35eb12cc9e4ddbadaeb4f37e8df7050469420a24.nq.gz
    ├── 3632598588ba78b594f369425710987345eab27d.nq.gz
    ├── 3647f489f33338aef51e14906360169eaea73d10.nq.gz
    ├── 367baee8e3140cb3cccddc95b06b521df7bdbd46.nq.gz
    ├── 37afefbafba7049a35845432b8e4d00f1c2dbfc1.nq.gz
    ├── 37bba7d43447fa725d64cb3e39913fd5c103f2ca.nq.gz
    ├── 37bca98bce9acd3c729f9d5c186ab02a46219998.nq.gz
    ├── 37e687b9b91b78b9d2ffbdcf75668c6b1e2b5ee8.nq.gz
    ├── 38381931b498edb9451329ab5dfe8077602e7e61.nq.gz
    ├── 3a2e16503d9822dbb2bda98e1e9c05d8669db904.nq.gz
    ├── 3af276224c34b6c8dff6c51a5ae4f12bfb5479b8.nq.gz
    ├── 3b9e6120829a661e874b66b3064ab7dcfcb92c13.nq.gz
    ├── 3ba97b2153bec2843e2a494e959b96a92123c4f1.nq.gz
    ├── 3bb158c58d19e402386d6efebf249ba7713d5134.nq.gz
    ├── 3c43e6c83323e6e39e1f62fb5d2d74843ee83cf0.nq.gz
    ├── 3c76841af516e2d3609f79e7f160f86f36fdd3c1.nq.gz
    ├── 3c9e805cb2704a7185dcf3e4a839e372168b72fa.nq.gz
    ├── 3cb44f7f9ee9dbe19d9a1669976274597c8d7714.nq.gz
    ├── 3cb5839b1dffd33ca8b51955903b97821ea321c3.nq.gz
    ├── 3e9d44870abb8b44520f07e906cafd841820a880.nq.gz
    ├── 3f3c19b4b13e7d7376b10cd92f2e3dd320da48f9.nq.gz
    ├── 3f62da26ac4e031707a749e7d5af85b9dba5e74c.nq.gz
    ├── 411cbe26b3d966a5b8398813ef790823e35889b8.nq.gz
    ├── 421a373ee5bfdd2139cfa8ecad514519165a79ea.nq.gz
    ├── 432d9d50a39d47431551b015e468c0f1330e62a4.nq.gz
    ├── 434cf48a78adc621f2d7216314544feb38f9a1cc.nq.gz
    ├── 447f9d8885b42be6cb2b126b3bd262b4cbfe9139.nq.gz
    ├── 455926e6f4da9276f94434964d29798fe7dd41cf.nq.gz
    ├── 47b2fece7d63132f6bb3e2a554345a0533ca0f47.nq.gz
    ├── 496838aaa5b72050cd13d7dc2c122597da25d8de.nq.gz
    ├── 49e695bd4d1ce1e1f738a8faab73110db1add1b7.nq.gz
    ├── 4afd2a8c07ac4adbf14f8efd677a1fe6a45cddf5.nq.gz
    ├── 4bb2e7d3e2462eae216827b6f401af42b95643f4.nq.gz
    ├── 4bc4174681b395882f791b60c0313611d474d625.nq.gz
    ├── 4c3cba2f94c47f5afe0731b19b31a1ed63728fad.nq.gz
    ├── 4c7ec8b2b0a159e2f65b02667ae85a3a47a7bc81.nq.gz
    ├── 4d0ddcd79ad1042195c060fd654720f4f0374567.nq.gz
    ├── 4d7587644840ba447ef8d71820f7758c24c1659b.nq.gz
    ├── 4d92dc5d6af591ad464493f654e9efc5c342e999.nq.gz
    ├── 4db0ef859d0fa587ef445d055c0819f30bb513a0.nq.gz
    ├── 4e1cfa63a9bb50847124e5e1ad80d03895474487.nq.gz
    ├── 507dd76480b1151730c97828d070443896dd1800.nq.gz
    ├── 5099c134defb32f695f82f515ca569034417a132.nq.gz
    ├── 50fc5056359753867935b2c1200b8a73ae7ad10d.nq.gz
    ├── 512c5fd7c504683708996fb48d87ca79588a117e.nq.gz
    ├── 528a09e8d181c72f70eeaaf1d930376f5bd4fa11.nq.gz
    ├── 529637499f39abddf19762af31acebf5f754cd1f.nq.gz
    ├── 5384e22aa41bedd7511c4724819abad87c9d0090.nq.gz
    ├── 538afb98e6b9a529947b1076b6699ec605309d67.nq.gz
    ├── 54620076e6d8985776ccf4b40fe56cfddd9b5827.nq.gz
    ├── 547a98181ef3380cd9092fa139fff892b3860bae.nq.gz
    ├── 54dc3ce6c6e58ee51c05d20875cf22b33ffa0f1a.nq.gz
    ├── 552e4ce204723328f9107906c62ae8de5896b6a1.nq.gz
    ├── 553d2f905d3d10a5cdae2e4f7c702bf463e12821.nq.gz
    ├── 578bf7e1e11803c01a88e36a61a59861d0ba7919.nq.gz
    ├── 5790e614d779087029c1331a64290040dea3c35f.nq.gz
    ├── 57a39f76b19ab31255e29a14e279f99a0f99f4b9.nq.gz
    ├── 57c9e63176708367f1a8ceaa4626a6862e36fd7b.nq.gz
    ├── 58be863fbddc83a112a1059d180b61124e0d67e5.nq.gz
    ├── 5a250ba6e0df5f25e5a9269167f2ca15b22d494e.nq.gz
    ├── 5a753ceb4aca8ecee12d2496c13ace80e4f5ac4c.nq.gz
    ├── 5a81d9f88368f160844850a0ed88259ed7b6c97d.nq.gz
    ├── 5a8fe00cc3ff3a6c350ae7ce4571cca9eb6311ba.nq.gz
    ├── 5ad64672096b8949b4d9a1e94f6cc2096018edef.nq.gz
    ├── 5b61b89d2ae1cbf7fe5ab12450867592c63ce04e.nq.gz
    ├── 5bbfe6cb7368af4ee2eb5cdc6a2f5076743c80cc.nq.gz
    ├── 5bc1fffc666501dca35d0562a6a9d3d2c4746c9f.nq.gz
    ├── 5be79fddbd84d5d1ee0df7addc91d8f81b3d5698.nq.gz
    ├── 5c5d8d664722804f74e31840694a0a8b57254883.nq.gz
    ├── 5caea4aef432f8282d8273eb2fcf8cc6004a62c1.nq.gz
    ├── 5d003012c1ddfd68b7f1b92c1983db5aba12beb3.nq.gz
    ├── 5e5c2d709b899f51c9a0c7e2c36bc547ccee5238.nq.gz
    ├── 5e6041c75c3854bcbd053812a0df39f288d0481f.nq.gz
    ├── 5e7dac87a7994d811863d9a102a453a01e996993.nq.gz
    ├── 5e8aa1ae54ea2103201e0030d8cfdb4af61ef84f.nq.gz
    ├── 5f3e9cc4aeccafdf7a052bf99c02472539efe400.nq.gz
    ├── 5f93e1ea731a457acf9283962dbd54851f39f963.nq.gz
    ├── 5fb922196b77f7f37a644472f21507b6b7eac4df.nq.gz
    ├── 601a95cefed1bf3fcc4609f97c29c3036535afe7.nq.gz
    ├── 6033f188169664406f488ae14816102e6d5c3e4e.nq.gz
    ├── 6046e22640401d4c68d21a06e3a8d0f2341daf7a.nq.gz
    └── 62921e4722eabd5640203e49157f7cc6738d80f5.nq.gz

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

[block/spirit](https://github.com/block/spirit)

---
*Parsed on 2026-11-09 by [repolex](https://repolex.ai)*
