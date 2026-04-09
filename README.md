# Repolex Knowledge Graph of PyAV-Org/PyAV

RDF knowledge graph data for [PyAV-Org/PyAV](https://github.com/PyAV-Org/PyAV), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download PyAV-Org/PyAV
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1f2b3ad8268b2bbf116567e2f60ac3570d041d92
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 1f2b3ad8268b2bbf116567e2f60ac3570d041d92.nq.gz
│   └── repolex
│       └── 1f2b3ad8268b2bbf116567e2f60ac3570d041d92
│           └── chunk-001.nq.gz
└── blob
    ├── 0045b5c858c247b1f244092e36dff0866623a5d7.nq.gz
    ├── 0093fabd098d30c317e659c4b9dceb1067223965.nq.gz
    ├── 012792a4aacb8e3c4a91dfb2114a92a6c0a380e8.nq.gz
    ├── 0155bdae406214a85703be6809d96a6445ac22bd.nq.gz
    ├── 018c6ac310d484151af018455a1a0fb2a9f4db75.nq.gz
    ├── 01b8d9d41746f61aee48481796e3a9ec20f7a38f.nq.gz
    ├── 01c8fbf1f02e14f78d51f9c903132e98f010e2d0.nq.gz
    ├── 031b59a421978dfa21091ffa19d97dec91f1dec5.nq.gz
    ├── 044dfd9070820bd89f889d1906c336b96bbcf6bd.nq.gz
    ├── 04981a9388e93b712fc314c2ad31c8c96c387f1c.nq.gz
    ├── 04f519a3530fbaebcb7a5b8e8adebc4d0b521dbd.nq.gz
    ├── 05a5402a8df67600d82d868083925511b5a8b221.nq.gz
    ├── 0786483258c6c7c0c6810f68b58958c80ff7029c.nq.gz
    ├── 07ae34ae512fff2cfbc2dab7dd1222fe6946bd03.nq.gz
    ├── 085ed4bba1039b77675da29e26ef9ccbd539c8e1.nq.gz
    ├── 08771362bd8ce1e1cf52085bffaf966b3f8196d7.nq.gz
    ├── 088c0b0c0e7f4ec1d381aab6d1a71e7fdc614982.nq.gz
    ├── 08d24761e27d6e32f0943751b3c59c24f007e962.nq.gz
    ├── 092aba3ae47775bd48ad940ec28f5f8018e4bf11.nq.gz
    ├── 099ac4a14d3a77d08de6e0c99320e27d896602e2.nq.gz
    ├── 09ab06b13dca5673551e572b06c51e3ce4471d22.nq.gz
    ├── 0a33cf9f6e12ef3fcc0ec33222f97157df62da92.nq.gz
    ├── 0a4f1523c50fad747b44679daf8846437514d217.nq.gz
    ├── 0a7cd41a017000361aaffdc774261e67c5a3138b.nq.gz
    ├── 0ace5e4b1ec84daaeb09f27f6f9689a56d026912.nq.gz
    ├── 0be991ab6b17c5ef7050abcb69f55387f003a48d.nq.gz
    ├── 0c943de819b6c5f12a386fdefc833f5eec4c971b.nq.gz
    ├── 0d13a2a1841a82f22ccca92998ee48887eadbe56.nq.gz
    ├── 0e00f98732cb996f3d42356a874386f60802964c.nq.gz
    ├── 0ed7eb8622ff7a77487c9df082e4bcddbbb9c027.nq.gz
    ├── 0ee0a562677bdb1c4a98c52722af95e0a4f08d00.nq.gz
    ├── 0ff969475425b2c3c45bc28cbe872f5fbccd2326.nq.gz
    ├── 1067b678db42887e40f1840eb1ef3e673b4aa7e4.nq.gz
    ├── 1069c8f1dd5f0aba996cbe92691122b84ea39dbe.nq.gz
    ├── 114551fcce2a2fed7cfbeb6c9a7c3f997453c8f8.nq.gz
    ├── 115c15b133e8cfc221bc067e56861648be5dc38a.nq.gz
    ├── 1169c153adfa26b32599dac3cccf9c2a7ca3886d.nq.gz
    ├── 1173a586544a7315c8daa456600bc9d847f6f08e.nq.gz
    ├── 12a85182bd5138fe2fed247827f54ce373d2cf36.nq.gz
    ├── 136af619b7b4275bdece814b4284d6426a376a4c.nq.gz
    ├── 1459fbd22b64319e060e9035f5739b65c893bc0e.nq.gz
    ├── 14c520bebee54588029dc700fdcb80771209d46c.nq.gz
    ├── 14c8563ceb202db02e48c201d56ddde99ff7837d.nq.gz
    ├── 173f0ef182497e359b35f8ebfba0cf41dd84edac.nq.gz
    ├── 17432c926b48722f4bc47d98d145fa3e62802c71.nq.gz
    ├── 178ed5106d23822248448266ad6ac911c21daece.nq.gz
    ├── 17c37f609f16bcc5dbee4b1666387c6c4170c6ed.nq.gz
    ├── 17d977f3eff4b02ebfc299a2801fc318c8ccf976.nq.gz
    ├── 1894ce7abee46529aebb80a4640b08c6cdd5a12e.nq.gz
    ├── 198c96fa89cee62bbe5453929d80678e0a7c46c4.nq.gz
    ├── 199d2cc8b630ca6d9d03fc7fa17296417508e6ba.nq.gz
    ├── 19d75621c930e542ee5ae80bdf80b8ea03424b77.nq.gz
    ├── 1bdb7fab7a4ce99f25064a64c1e1e87fa559d0b3.nq.gz
    ├── 1d68e08b1bcf9bcde64e4fcaf1d8c5c3f3094d9e.nq.gz
    ├── 1de247b853fb779522ff265964ce565debe39ce5.nq.gz
    ├── 1e0cbb317aeca853a57eec3eba2dc54f268a3bf1.nq.gz
    ├── 1e2e0c0f426d412be8e0cee2061f8e63cc0c0a18.nq.gz
    ├── 1f345d36580104b261da347c1a77e35984f335ec.nq.gz
    ├── 2066bfea89d6214dcaaee80ee0c54773ccb05976.nq.gz
    ├── 207d6e15ecb23fb7f64d93dae7b862c4070fca6c.nq.gz
    ├── 20b74186ed1e80fcb879f5f341a7e10e6846825b.nq.gz
    ├── 20cd1a7872a0e796bda663277c699a768593ef7a.nq.gz
    ├── 221872c3367c42c291b5518c2866964ab160fae4.nq.gz
    ├── 2350019f3aae5f3c7e554e56f3c0a5903528d56c.nq.gz
    ├── 244d3ad7d045dc8e571b81781a9868fe3528538f.nq.gz
    ├── 247771a3bb6ca550fbfe0a11bf68998b9ba2f0fe.nq.gz
    ├── 24b8f0829367054e959a74f92f58d22a0d3dfbe2.nq.gz
    ├── 24f945bf2f71a82ceb43f99691f64761be54d18f.nq.gz
    ├── 25135c27af3fdee36ef2f55da504a79112106285.nq.gz
    ├── 25b2d27d01093810e9ca80220977866d51586cba.nq.gz
    ├── 27112d19fa77b04d88cdc962194774cac1151666.nq.gz
    ├── 2729dd8be0e2d4d53d64c5348f4cf909f161be2c.nq.gz
    ├── 277d47780e1023ad236054d4fc226af203d2d0ca.nq.gz
    ├── 2896519de0f175a3c18dbb0197ba7a95f86eaafc.nq.gz
    ├── 29f6e93ab61c2007f4acb3fba1720d2a56d0a8a5.nq.gz
    ├── 2a321a28d242e28bfd5895cea16e0422110ee108.nq.gz
    ├── 2ae69d84b2ded7fda06678638ebb3a6b51d3d7a8.nq.gz
    ├── 2b169f9cc2bcb33c566d310b57204f5ab0cb8590.nq.gz
    ├── 2c63232948489820cc2216c3d9eef65478fb6311.nq.gz
    ├── 2ca547028ca78fbc03c01c25e5455962836c2685.nq.gz
    ├── 2d313cb3ff480179ccf425a7f5bb1512cc578166.nq.gz
    ├── 2e52bd6ec3a67992dc0f2a40bbd5da8e5ed41fda.nq.gz
    ├── 2e71c06bce142c405f41f2a27be02e823e7e135f.nq.gz
    ├── 2f22bb0be036e91a8ee2e4e777b7d7c2ff8219e3.nq.gz
    ├── 2fa7562c9c6820cfbcbf361cbca51574234cb66f.nq.gz
    ├── 300d315f23d98a56b0051ed1d27a0e612f8b7ef3.nq.gz
    ├── 304fe3e3f2a6adb8325a75c84aa355a23ee07b71.nq.gz
    ├── 315d08345cfffa36811379848dda7104b1da57cc.nq.gz
    ├── 316c84031c3da5b35135132227133b9ee5694bab.nq.gz
    ├── 321b29d1e7ec3e6b458437fe9a6281cf5d9ad0d7.nq.gz
    ├── 321b65e6d3aaa34152d7deb74aac14c3c3a5404a.nq.gz
    ├── 3277dd776c030711f9d0945e5285f78d08b61821.nq.gz
    ├── 32baafdafe96e3970071b2c9612d726955ba4c15.nq.gz
    ├── 32cb6bfa1725152483fc7d83f9afc3d6966088b5.nq.gz
    ├── 32ee7d6d315a42bb0d93559dffb0d4e5223b23d5.nq.gz
    ├── 3324ce0bc23ef33ab9e6af5b02e6d166b78b9fc8.nq.gz
    ├── 333815d80140814ddf76fcb2e01d496732f52037.nq.gz
    ├── 339b4474eb9c229a7cd086a70603ce340575a491.nq.gz
    ├── 33c55699445b2f6f6bb239125bf584db674e45d3.nq.gz
    ├── 33c64727e6ee4ee91fba478359a144d609bb8330.nq.gz
    ├── 35ba4c160539055e26e27242485e8da33c1465b7.nq.gz
    ├── 35d0e2f334d95ffafdeb7f985b291dd998fb9569.nq.gz
    ├── 3717ddc811fe2cc90d595ec65ba3d5930b120737.nq.gz
    ├── 372821666019782d4cdfd574b9e4e0688d310aeb.nq.gz
    ├── 37a5718831e1dd014f92a4ffc58b98a0356e72b1.nq.gz
    ├── 386e819bdbff976ce65eb3e30eb84050d14ebf04.nq.gz
    ├── 398d76d33ea1173e31a5e13809ba3910385572b3.nq.gz
    ├── 399189a6b0e52862f0e936ba5eeb481b8522f6ca.nq.gz
    ├── 3a0af39effded2dc7345b6a8b982febb71cb3e96.nq.gz
    ├── 3ad995fb9aba3356005b2ff52f88c5774b81af60.nq.gz
    ├── 3b7f88bc10c990f8ab8dc6c8734bb314c797fcda.nq.gz
    ├── 3c0bff1bda5ff94d11aa5d37881aab47ca88b9b9.nq.gz
    ├── 3c69185b2cf8a84d94b3ed7ab16220012422862f.nq.gz
    ├── 3ea3a0c6d56338e2aeabb03728afa6a5b3491791.nq.gz
    ├── 3ee78d2f5410fe6272664c8d1d1ea3d9ac756893.nq.gz
    ├── 3f82f4ec2e2820e1c5f6ce4d969d64b33a301650.nq.gz
    ├── 404f646afce60e3703814c4ae6c493dc8757b5c9.nq.gz
    ├── 4109f325c19d9e4f6bbbd9f804e16e991a2a161e.nq.gz
    ├── 4184c10f76563f9fa97da8fb55c3fc9b8ac4c770.nq.gz
    ├── 41e0e1d1f473734949d75c29615b88129db20787.nq.gz
    ├── 42141aa4f80e00ad81dd88841cd1b9457d49c231.nq.gz
    ├── 43bedb9c73948c629217d1490fc33e48bb792828.nq.gz
    ├── 43d1e716d2f1699b472eb9d2919c8170d162903e.nq.gz
    ├── 43f1eca9fc9bd9f18f251d21bee53cd6382f9ddc.nq.gz
    ├── 471b6ebc42d9947cad52be15ef1408fab94331f7.nq.gz
    ├── 477c65f2d2356b2f9fd160d24af5b10cfae39c7f.nq.gz
    ├── 48163b09f1adfca72af7e55a2bc84a14dc5e6810.nq.gz
    ├── 49c97367e351aa5f16aee697787ebc7d37964f06.nq.gz
    ├── 49ff05ac87601ea49fee94430a0406e163469dd1.nq.gz
    ├── 4a25d88376662b42451db9fe11a704f642f94744.nq.gz
    ├── 4a3cab48887b20f74d2cece23a470da037914796.nq.gz
    ├── 4aa2144a32ee36b69a3f859b97447699a70f443d.nq.gz
    ├── 4b7eaed08ab1173e963d0df167c7e452e23ade31.nq.gz
    ├── 4bbbcf369315bffa1a4449038508fe81d13ed518.nq.gz
    ├── 4c8eaffbff61f814942b2afa82a74cceb48df032.nq.gz
    ├── 4dab1bde5d7e20a3c9a1cbe50d8fa847fc7e8207.nq.gz
    ├── 4e2c4995e366bae92b9df299efd8c4b17686e5e6.nq.gz
    ├── 4ed2223d428a8900774df8d3316d84ff24d09584.nq.gz
    ├── 4f85567421d014bd877c248d3ee2c812dc8730ba.nq.gz
    ├── 4fe78b54ac7cb9e2017a0067d22b4ec68b03f6e8.nq.gz
    ├── 4fffaf697ccbb37c6972502aa0ff5d07ca305dec.nq.gz
    ├── 504da957626b74ac5bd43e6eafa3bad6b5f0f898.nq.gz
    ├── 5090f68867306f61b1f0dc290d7fe7915212d519.nq.gz
    ├── 50e6bfffd12a2835f722ee12fb7f8f00ccb8739e.nq.gz
    ├── 50fe0aa59439664c35f5d57787d4cc57cba47abe.nq.gz
    ├── 51d3f308edcec45b301ed55f9d85bc5cf77d505d.nq.gz
    ├── 525440e9db97876251b543d318f47d9b92809a07.nq.gz
    ├── 552af82841053e67073fbdebca5e7b985d2a132a.nq.gz
    ├── 557ab188e4bfbaa55cd91145a4b70293d4b0e3cf.nq.gz
    ├── 55ad15e9f0404d2b77810682774fd25ab434fadb.nq.gz
    ├── 55d969999f4986a02938d897661c12207f424bea.nq.gz
    ├── 576c659b46939204543b2313f33de1d6ae3ac2dd.nq.gz
    ├── 57cd288f493d079473329339ee65aa8f404f075d.nq.gz
    ├── 58a19a63fbfcb54ed33028383ac368ada7ef27d3.nq.gz
    ├── 58b3c38110db30f20fd1dc23e4904828a3387eaa.nq.gz
    ├── 58ca547e278732b39e4d698b714a570225602e82.nq.gz
    ├── 5954a9c98370d8424c9becce2cd6010b03700688.nq.gz
    ├── 59e291c74cdb9dd9140a22dfc0d96b200ce89788.nq.gz
    ├── 5a0a423e3531c6c7be5fbbd0589bfc0a1f762687.nq.gz
    ├── 5a97817e31cfaac4d71a7525c6c4eb217b0f2a5d.nq.gz
    ├── 5b179f322810f171becc3b569a4b184afbd5fbf2.nq.gz
    ├── 5b9a299c3e7995d400d4b5d1023aeb4d89bb14bf.nq.gz
    ├── 5be1326c99efab97108a8dba6887cda669b6996a.nq.gz
    ├── 5ccac3ffbba5f06619205a8f74c3c2187f828030.nq.gz
    ├── 5d1bf74cc69d030ec45cf7725ebd3600a8afd31d.nq.gz
    ├── 5d2368a2f4993a5d66c2f81bdc42cbb8481aa35d.nq.gz
    ├── 5d4eb7871b62b31c86fb052f21617309a35150a7.nq.gz
    ├── 5e47b1db8eaf57518e980a7fc4b2975a8d4bab7d.nq.gz
    ├── 5eb11ecc207ba864ad653f77e6b2f9a5c9ee9530.nq.gz
    ├── 5f7e322edc85d831b5b6cc9979fd4dfca4b994c1.nq.gz
    ├── 5fdcec4f76fe4c94ee73a70b08de1245396b19c4.nq.gz
    ├── 60279e513e3592b55bdddad7cd799957d28e461a.nq.gz
    ├── 605ee18417222c259e52ccac7e77920c159fdc95.nq.gz
    ├── 60c8c953d5234aec6d054a84d97cf52e797741ff.nq.gz
    ├── 61b9ca0fcba957ac641a2c0822665c310b522098.nq.gz
    ├── 621ac8f18bc9f011c745497da4a76a5070a48c04.nq.gz
    ├── 62ad3ee97ecda3916e3a22f6ffb1b7ea5457eb67.nq.gz
    ├── 62c3e5c164ed148206ea7deb1adbde7abf5265f3.nq.gz
    ├── 62e6ff8bcb053a4b6628c8ec57e27d3bfe9ca588.nq.gz
    ├── 63220889c522b0a91c4f5e24852cfc5cd73153e1.nq.gz
    ├── 642a1c2c647c32f72a8304d27edf3c6230b57ec2.nq.gz
    ├── 64524dcdb5170ebfbee5aaafff86f37f9a476444.nq.gz
    ├── 64ac00c9957fd92a740d64d4f393e274a845aa78.nq.gz
    ├── 64c13e198bb361d2eb0deb6df0544c5740cdb0cb.nq.gz
    ├── 65a1e540ec5afbbbdd4ca20a2fbd7e5292385b48.nq.gz
    ├── 6654f106204f5b0364d6a767f799c2b93c833ab1.nq.gz
    ├── 669c8e55add99259b603068cbc60366e49aae6ea.nq.gz
    ├── 6842efefc8ad2e6271d39e79af0f4af1d9f32f4c.nq.gz
    ├── 68a6cca0facd44cccb39850d06e091eb493420a5.nq.gz
    ├── 698242c512d46a13f8b4e9d60e96bf5e4716d239.nq.gz
    ├── 699838c38f8db99e66aed2ef2b0df40983d4a0e0.nq.gz
    ├── 69b356cb595153f7f19a49b3b31691a7d2b39a5b.nq.gz
    ├── 6a20af14f7cd37ba7f2dcf51784472a6903c7e49.nq.gz
    ├── 6a3add3e1a4d86a619a80e34ca9a9f0dae1f1ab1.nq.gz
    ├── 6a68de73b18b9d4e9d3890b3ae64aa6fbb72aebd.nq.gz
    ├── 6ad38df5b20593cba9e59047bd9ef33249560934.nq.gz
    └── 6aeb86b4d27487dd44b6a8bd91f9998462c56af9.nq.gz

8 directories, 200 files
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

## Source repository

[PyAV-Org/PyAV](https://github.com/PyAV-Org/PyAV)

---
*Parsed on 2026-04-09 by [repolex](https://repolex.ai)*
