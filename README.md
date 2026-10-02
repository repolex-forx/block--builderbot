# Repolex Knowledge Graph of block/builderbot

RDF knowledge graph data for [block/builderbot](https://github.com/block/builderbot), parsed by [repolex](https://repolex.ai).

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
rlex download block/builderbot
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 68208726c78839c9cd5f266f1400ae211567f199
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 68208726c78839c9cd5f266f1400ae211567f199.nq.gz
│   └── repolex
│       └── 68208726c78839c9cd5f266f1400ae211567f199
│           └── chunk-001.nq.gz
└── blob
    ├── 008d32ea89ac1deceedd54d0ab63a043654154a6.nq.gz
    ├── 00dd1feb1d72d52dee1326795213b3e30676ed6f.nq.gz
    ├── 00e86391aea40ec73230730c67a984831ad764be.nq.gz
    ├── 011e061b2bfee467b84a4c8cf983f1e7824ea479.nq.gz
    ├── 0133e56a348ed0f76fffc0779c56e7d5970a7b3e.nq.gz
    ├── 013893b4aae3fa49132b22868c12b6af623c8403.nq.gz
    ├── 014d2150f760767dcb342aed9277f7676a1fc581.nq.gz
    ├── 01572e2701701d2b287a300aad3c6161740e64d4.nq.gz
    ├── 01817831714bf119e6003edbc99bae7f54643052.nq.gz
    ├── 01b8882a47eb035ec008d201f84f12559d62fe55.nq.gz
    ├── 0226708322b6547abe58760026ba57a1475b8fd3.nq.gz
    ├── 02ab00b78337bdbc751d417a364c5ae232d028e5.nq.gz
    ├── 02f5f63a55c91cb549e61b20ffe126e46379d764.nq.gz
    ├── 0333b24554f366db4450e74659b7ef73c7b3a54e.nq.gz
    ├── 034cb377c9724b8120b16b4c0d20d7019e653772.nq.gz
    ├── 0367d2331a2cbfb3dadb43da08affe106a235c28.nq.gz
    ├── 03adfc2b9238d5d4985e3fdd021b70f5027326ba.nq.gz
    ├── 044c6a9db6888a7dcc51eaa85fd284085fe8962c.nq.gz
    ├── 04a052a0a8f4512ff09931586d513d666d37fdc1.nq.gz
    ├── 04ceec8d7fea85d02dd340536d32417caf0320a6.nq.gz
    ├── 04f0113cd661d3445fc1c4fc06bebf1f00da17cd.nq.gz
    ├── 05361b472d121cec92b70600d780cbc08dcadb56.nq.gz
    ├── 05d6e58588aa62cf7d864c8a4b57724527229690.nq.gz
    ├── 05dde3bbb1728e6dabe899ff094ea1d07fe47759.nq.gz
    ├── 060d42c945314d17826883e6eebba8487c532c06.nq.gz
    ├── 06135ebe6e0d852cdd923ac9d5a3ac4ebbafc099.nq.gz
    ├── 06b5000bba47bb0bfd4f2ecfa9b929d44de49f83.nq.gz
    ├── 06dfcb9df0df1abafe7102ed11b8d1c9477b0f4b.nq.gz
    ├── 06f602dbd0841bf04f6d0901e4b274ab111aad18.nq.gz
    ├── 07098a61502701ff618974bcca6c49698d1a44ca.nq.gz
    ├── 0721f886d0c3097afe5ab19d97bbd238a9081448.nq.gz
    ├── 0800bf06f5776810f7ac2951d2749b331d38f845.nq.gz
    ├── 081cbe83449cf8e625a3e2e79b6b35415c4e1503.nq.gz
    ├── 087fe064fbdc73266ecaad4b5160dab302a6187e.nq.gz
    ├── 0888f0e06772347ef2a5b2d73a874d6acbbacef4.nq.gz
    ├── 09274984c310d609c70a35b8ade3cb1b970e14e7.nq.gz
    ├── 0960b273c68293ae577836d6c1336a47b0643335.nq.gz
    ├── 09931dcfbfbde85a395d45b60e5d3befd2f8d3d3.nq.gz
    ├── 09c0ac58e17b930eb9122c53b5c75ff7fe8ed9af.nq.gz
    ├── 09fab1d1eb2e17b1ad605a613b8e1e11b8332281.nq.gz
    ├── 0a3d7d39bd7908b21567a096f82b8a34b7f1e9d7.nq.gz
    ├── 0a887df6036da678b2651d024536bd0d1bf8dd03.nq.gz
    ├── 0ae18b3f5c4158c15654b6712d7ca5e73504e0cc.nq.gz
    ├── 0b155a2cfb180ee0c664c4ee34f0a09234d8c0b1.nq.gz
    ├── 0b48e38ab8725da7e7b5dd841cf7165c54d37650.nq.gz
    ├── 0b5f8f8429ee473d3984d5df1b7e9e150864bacd.nq.gz
    ├── 0ba70c9b6cece28c1de5899271ab2f8c73c6c071.nq.gz
    ├── 0ba9db25329d0b336e39ca8cde8470c5b7bc45eb.nq.gz
    ├── 0bad5f55dbdaecfe665d7cb9ccd1e23a8c25e6b9.nq.gz
    ├── 0bcf7c9d06b7390b77362679a7f29ba7bb7783be.nq.gz
    ├── 0c2d6b1917ce2f3ad4ae7d8a0a085c07d7a6dabf.nq.gz
    ├── 0c602fb2eeaf0334496a750e5d18fd8988d5fb12.nq.gz
    ├── 0c6bf9d35c0fd78b232c798e9990dd0fa3bb87e3.nq.gz
    ├── 0c73857bb357bdeb817029a7ca31b5ec831ec168.nq.gz
    ├── 0d25079dc1a2629d21f4a9d78beccb518e3ef4ef.nq.gz
    ├── 0d48514836e9156c02986f5b2260de1aabc68974.nq.gz
    ├── 0dd948f8c0c7a3c3d3f846bbe8658bf8daf8aad9.nq.gz
    ├── 0dfd22a4dfb5889dc007710e4950ff1fc5ec9aaf.nq.gz
    ├── 0e01d861f0e09a10f06beb4162fe98fb10cde198.nq.gz
    ├── 0eca70d87dc542b7ac29a9c4f4f195bea8562a07.nq.gz
    ├── 0f0f0a9e213c3768626d3a9171472e8bed76b15a.nq.gz
    ├── 0f16e7b2dea1419d9237226bea419dfd2c53fc8c.nq.gz
    ├── 0fba687f9cdd87d8da552740803dd79cc7b9b000.nq.gz
    ├── 0fe2fa7d1396fbf9527965ec81113966893493dc.nq.gz
    ├── 0ff706c2440a7d88a7518f1e134ed18d614c4fa6.nq.gz
    ├── 108200dafe1517404d588ac97556a93a7a17d631.nq.gz
    ├── 10a56f8b8424ea87efa8ed1f663af9320a00cc42.nq.gz
    ├── 10a662a30ed00e4411a41f8761de2a75ca9414de.nq.gz
    ├── 1100fbb8f4924e195125b067a6834491ebe40d26.nq.gz
    ├── 113a80b9a088007b6469e2be2eee5b6ea8939a04.nq.gz
    ├── 11e7dce90568b41c831c7d6ff22ef0fb396714ab.nq.gz
    ├── 12342e38413618140444e21818754eadda7a574d.nq.gz
    ├── 124ba4676dc1b978aa4629cf230c4cc67cc03585.nq.gz
    ├── 12e9e3a998777bac8428d76d0542b46509ad052e.nq.gz
    ├── 12f27120607b5663f3317dc69eb410b9b7eced7d.nq.gz
    ├── 130c20f79bc32997f8840a3a51c2647e1b06204c.nq.gz
    ├── 130f4833f57961dc4071dadcbab2eebf8a790b4e.nq.gz
    ├── 135167ed50c31d31442764c0edc2282f99f3f04c.nq.gz
    ├── 13d9ccb2e1c33a9fbfc56561a5f8b0331ec0087a.nq.gz
    ├── 13ef4e290a323d3213f1bfd8d034734b00d1bd1a.nq.gz
    ├── 1490e62f2f3620bb709b833f2e10fa2289de8952.nq.gz
    ├── 14a3d870668f6d8f490999aa2d312d42df1f9188.nq.gz
    ├── 14bf655497c7683c9188f1385ec63b67af1f0e5f.nq.gz
    ├── 14cf41e7ad03e153b3d3f7bc997eafc202f08df3.nq.gz
    ├── 1516f85f1aefcb532eb57d865bc345c9fe6daacc.nq.gz
    ├── 152122738cefecc86d508f4692751f62fcb5b563.nq.gz
    ├── 156189d9bbe2526cdaf0b4a76bab38efc38a9024.nq.gz
    ├── 16477ff3ff483f77ae9d510eceb2dff76328ce22.nq.gz
    ├── 16ca640c65f9799f4d72b67ef5265245d52ec34d.nq.gz
    ├── 171b29659575119ddfe64319fa3573afe5d51663.nq.gz
    ├── 17675f75f914d2ccaea33d411a3a0841ad5da001.nq.gz
    ├── 177793d69c0fb39ad6af8601f6efebb326955fb5.nq.gz
    ├── 17a64de4508f9d9b54a1f06662bcf6bdf9c72c0c.nq.gz
    ├── 1825185b40b7b0afd689420f075b706ad6189325.nq.gz
    ├── 19f694bb5c9e404cb2aa62497df5b59ad1878bca.nq.gz
    ├── 1a6f047caec2238e33c10ff593d9b9fdf159534a.nq.gz
    ├── 1a79756ced5535ccd06bb28e504796c222dc80a0.nq.gz
    ├── 1b4a7e1e64c8bdb65af5c3afc65674b926ac08eb.nq.gz
    ├── 1bcb4c898ea679b4bd26f3f9cf6898c61aec03bf.nq.gz
    ├── 1bd53f63106ba44f4ad7af02c3b7db9211329258.nq.gz
    ├── 1c2f57dab62e79ffea0037c400d3cac5bf2b3edb.nq.gz
    ├── 1cb2c828748ebfe1c628746959998f026f48c4e2.nq.gz
    ├── 1cbc6aeb816703228b4c071c338be4769aa83532.nq.gz
    ├── 1ce10b3d5c4d40b36768998a548e3833c7429f0c.nq.gz
    ├── 1ceefaa3fe698a19b2573e7e3f863b43512561f0.nq.gz
    ├── 1d264789a8e9df3241bfe540d7b899008ba56e08.nq.gz
    ├── 1d77b0c6165ec54701f0bda77c0650beb6ea2a14.nq.gz
    ├── 1dc6b17f97f6e78912a5d2008e20b05fff6c40e1.nq.gz
    ├── 1de9575c880bfb565aa050b85852af052f84b337.nq.gz
    ├── 1e033483a4c74d5efb9ac7b9c99af70954b35e68.nq.gz
    ├── 1e13161e5967547b16fe78fbbaf80a7b4ec82cc5.nq.gz
    ├── 1e1956647856fa5d776c2fbe48a768ea18fd0e60.nq.gz
    ├── 1e272e5c9a2e0fe3736fd14f3520381e7dfa5ba5.nq.gz
    ├── 1e3e37b427953d6b1b567a8cacb74ece22b4c4e5.nq.gz
    ├── 1ee14528f32f46806226c40a0e8ff5e1f8f1fee8.nq.gz
    ├── 1f33888478908bd166f1fdcf1cd5f90da022da83.nq.gz
    ├── 1f3c96d03e90435b62afd445e7903504ec135118.nq.gz
    ├── 1f7d1390304cc9e60a53a3b45eeb95bbc93cb42a.nq.gz
    ├── 1fbdfd9848f9697ee84a6e308fbd6c5cbe25af20.nq.gz
    ├── 20b8286641f4af5947bc5cb7379076bfe1d0b06b.nq.gz
    ├── 20c4846442c07836417a59d1b5d450c080480db5.nq.gz
    ├── 20f3647d60b5e48b72df2c5e0c99136be1815018.nq.gz
    ├── 20f7699cdf22592cb767bac94b2c08aeceb403ec.nq.gz
    ├── 210f0e4cac51bbea16c37b5b87efcf8bf8fd0792.nq.gz
    ├── 211d387c2a44b4ec8756d21828698e21b7b6cd27.nq.gz
    ├── 21463e48057fdc4386294198037d8e1754f4c9b2.nq.gz
    ├── 215544016e8f1609a3be224f1f19729edc35d90c.nq.gz
    ├── 21a7087e8b1f8c6b3f408976779c6c31c1cebfc2.nq.gz
    ├── 22eded8e93a068ca871eee65180f8e0acc3951fc.nq.gz
    ├── 234766e85de201c242c49c3dab149235596c4cea.nq.gz
    ├── 235c0c5494d7ab60424e1788d0cb282cfc093a97.nq.gz
    ├── 236ef4e1ef667b73e15ee64c0ccc063545bade13.nq.gz
    ├── 23cde89cfde579e54f85a6b8fec1f1f401938a12.nq.gz
    ├── 23d47848349fa66a56e97ea6aa875db207e04a94.nq.gz
    ├── 246d825615e05d93167e19ae30e47aa185d6d7b9.nq.gz
    ├── 247cd4ecb242146f237d3e238885ca1c7e19ff44.nq.gz
    ├── 248403c12d255177e0df9422d51ed1000ffd76d1.nq.gz
    ├── 24e11c50df391a5fb4ff94a9b5c84279426bb720.nq.gz
    ├── 252f5d2aeca614a31505688bcf757ef65273533e.nq.gz
    ├── 25f0bc5ed80683a81f46e6bfd1cf8ea0b56c6807.nq.gz
    ├── 264998ef93dbc66f41691ba92a870596e5e2a52d.nq.gz
    ├── 26fda21e2b65a3ef7cfe3996b587fdde816c4192.nq.gz
    ├── 27258814335a660687dad6bc7d7fa85731a20151.nq.gz
    ├── 272d88f4093d765d8b98fa3669e028afcf004862.nq.gz
    ├── 27340324b290ff271e2fe1f9ebe828630f683527.nq.gz
    ├── 27440616e241a7ef7c69e3c9b06408a5cb094e79.nq.gz
    ├── 27487e7dda84cd0f003a7b4fac061baf34632f84.nq.gz
    ├── 2834f8a0c06de7cd02e4abe714b11544b56fb35f.nq.gz
    ├── 283eba70e32e5927ab27e2b30e3ca2be2e1dc6db.nq.gz
    ├── 285b8f686f5edfcc67b723458e234834f0524410.nq.gz
    ├── 286e4bfc9edb3075828447349a99571cd13495cc.nq.gz
    ├── 2897cc0b4c33f0bbf830880dfb9ce6527965b62c.nq.gz
    ├── 28a390d5c5045ab7cd342caf988e6bb09df2af13.nq.gz
    ├── 29105436bf689118520193d719254c8d48afa7d8.nq.gz
    ├── 2920ee114e34b7e3bd6177f78e3e5c0b00065c8e.nq.gz
    ├── 2942b2f8a538c7ff1e7cab8da406ca5b662d46a6.nq.gz
    ├── 2948d838c6982bd4e19e90645b642c56daf40332.nq.gz
    ├── 29983f64b4072d82ee45be555de1f65151f7cdc9.nq.gz
    ├── 299c891f56d94dc53497cce4bba4889cb86cb4fc.nq.gz
    ├── 29bb134985a5f1030cb9efcf72c3a53d9ce23cc4.nq.gz
    ├── 29dcaaaddab5669a7df72e4a1817d437c270678e.nq.gz
    ├── 2aa4db5b87d10338fecd4d660b383c3764ac3a66.nq.gz
    ├── 2ac59127207adea2bd513c14ca67b54c3c9fc6ee.nq.gz
    ├── 2ac5cb43639b44f1f278f1efcb6550e93fe3f6ff.nq.gz
    ├── 2ad822a790c14b2f4ae4a49e2cf65fbb2b834d28.nq.gz
    ├── 2adca32258befa7f430bdad3ed332143f6860d44.nq.gz
    ├── 2b3a7a3b3f20bb6b9184503723ad58f0b859c58f.nq.gz
    ├── 2c24a1bce7a7f0e8b2ebe08d27b78ac05139c376.nq.gz
    ├── 2c3cc0cc3d3d0effa4d91e179f120a80e214cbb7.nq.gz
    ├── 2ca9615632c160d5eb3b2ccc596427f32fff24dc.nq.gz
    ├── 2d9e86c1f43495c114e75890ec433a4f7aa5ec8e.nq.gz
    ├── 2e0b8a692f173d425faa00173678eb875c259a73.nq.gz
    ├── 2e4806ebbeb95090bdcf8751bae5a5b7164cdc21.nq.gz
    ├── 2ec902317cf6504fa172266dd9b8f34b7674d8b4.nq.gz
    ├── 2eebb7cfcccc6b77acf1e390bd804cbb08ded6d8.nq.gz
    ├── 2ef08851b6fb7c691516135655896d07fc9940ee.nq.gz
    ├── 2ef96cc0a5aa639615966283f8cd730ef68244f1.nq.gz
    ├── 2f313f6f63527904b271ce4c546b55100e4e95b6.nq.gz
    ├── 2f3e4acdb7e4c908648fc1706f9e9ca9c9623b13.nq.gz
    ├── 2fb50dd93be1a000e3fa972afc57e4e348c99564.nq.gz
    ├── 2ff65c4056f4e7d08cef7c1a6ca7a67af4c3b214.nq.gz
    ├── 2ffbf24b68988bd935f5c695a59753fcb1a5de0e.nq.gz
    ├── 2ffd02982c9e98078a03a42016df02661ab2f6a8.nq.gz
    ├── 309a6fe8519ea969cda38c2b421ad8b0c1c2923b.nq.gz
    ├── 31559b7d115e3c105b328cce9b9dcd9774025061.nq.gz
    ├── 315e7c06cb4d4a7c8c07975103bf7d793044a6c1.nq.gz
    ├── 31c0a9ffdb8fa7a4e1b253428424c89c97a11b3b.nq.gz
    ├── 31cded2dc1139793832c645afea1c5334aa1b5e2.nq.gz
    ├── 31dde60d90612b44b0a3a7fe0b8a28e97e9dfe1e.nq.gz
    ├── 322b143a3dcba7a5c8ca21eb3a365c64a971a7f8.nq.gz
    ├── 33910f20c6539a825a9abfa399bd11c1406ecda7.nq.gz
    ├── 33aa304d8af9ba6d3f8e871d85f5044942680692.nq.gz
    ├── 3409f8d89bd2ce62bf4ebc07e13da193aa70ebdc.nq.gz
    ├── 34c0a0986c408f7d03ed8ece97ec062035d8610f.nq.gz
    ├── 35bcd1182752cdfb45a9a0880a0dcac012fa1e37.nq.gz
    ├── 36ab5177264cf1a750572dc88c1e1a8c24ba8052.nq.gz
    └── 36fb393d409a85b887eba649ea77e5e7059d75f7.nq.gz

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
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[block/builderbot](https://github.com/block/builderbot)

---
*Parsed on 2026-10-02 by [repolex](https://repolex.ai)*
