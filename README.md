# Repolex Knowledge Graph of rayon-rs/rayon

RDF knowledge graph data for [rayon-rs/rayon](https://github.com/rayon-rs/rayon), parsed by [repolex](https://repolex.ai).

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
lexq download rayon-rs/rayon
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 7af20d7692d5decbcb4adcaa079cd607e3e50814
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 7af20d7692d5decbcb4adcaa079cd607e3e50814.nq.gz
│   └── repolex
│       └── 7af20d7692d5decbcb4adcaa079cd607e3e50814
│           └── chunk-001.nq.gz
└── blob
    ├── 00ab4ad7fe41f8b42038f928ae9a1d2923e0145c.nq.gz
    ├── 0100518be847a710770b508636312f0835804683.nq.gz
    ├── 020589c29a84994cf9d0ab4bbb1aaf5ac4402714.nq.gz
    ├── 032ccbbb6f866a2bb1286ef1479ac21698b46a35.nq.gz
    ├── 0367512670e9ca68ef99ad2c14adf53d63e4621a.nq.gz
    ├── 03f4ab4478d40bee6aaba2e2b4307a4159abf67c.nq.gz
    ├── 08f1120b799aaf51d7ab23b58c58b387836f836c.nq.gz
    ├── 0eb5ae3dff321371b4ba42c7c9fd9957b3e87064.nq.gz
    ├── 0ec4f22dd99e5508a7c4ac98fe042a210358a421.nq.gz
    ├── 0ef5fa7729f45f49c5fb280d00689c48dba292f3.nq.gz
    ├── 10060c1a191620a28be1c95d770ae3bb279feb08.nq.gz
    ├── 13209a40d0310ae402ea3da77bac5e216d939c75.nq.gz
    ├── 1479b671550703f5c87819abffdc0a105846d47f.nq.gz
    ├── 15915304ddccc9608e192b1165b00c5eb84dd08f.nq.gz
    ├── 16f39137bb87380e711bfde575ef7d0b52df68a6.nq.gz
    ├── 16fbf3b824d35793d2b0d1b23a0f4d6654507142.nq.gz
    ├── 16fe87b06e802f094b3fbb0894b137bca2b16ef1.nq.gz
    ├── 17434d72b2194d38a521edd129162e4d2fe1f4c8.nq.gz
    ├── 17526e34344e146c34af06342db669c847cc8609.nq.gz
    ├── 17fec02892c96d08111b7ec2ffbac0fe68110806.nq.gz
    ├── 1af9ad8baddb5741630bc929b3356bcdbcfef0fb.nq.gz
    ├── 1be04d4c17d51e9b703696d56918279c2fe5e506.nq.gz
    ├── 1c07391d18f8849751ed54bb059b2d4a7f1c986e.nq.gz
    ├── 1c2c2627e9db90abe8b14281fd1e9c898447fb74.nq.gz
    ├── 1e55ecb20e0ec58e54bd4e0a6a0e090b3a4f544e.nq.gz
    ├── 2008bff840ee128374e99de42b0ac140183ab4b2.nq.gz
    ├── 22d00dec4071e5e2ee9247b19dbad555ccf22c26.nq.gz
    ├── 231c8d1bb3056ddcb7d9e3fd18bdacd323b90845.nq.gz
    ├── 25489a2ef6e4b6af1f6febf01f140519f9755800.nq.gz
    ├── 25597d5838fa4cd7ff5c3c2bb1d1b4c3731eda7f.nq.gz
    ├── 2564482a47e5d2587e53dffb3da153aea77094bd.nq.gz
    ├── 2642fcf99134f6ab1256fd55e1884696124e80da.nq.gz
    ├── 274bf181a037dc7a2594cf95efb82417a07c7ce7.nq.gz
    ├── 298093094ccd8e1a86ec0ea191758c5e3b1a60a9.nq.gz
    ├── 2a6e3319302f4da9c3280df20428b6f92280e5dc.nq.gz
    ├── 2cea2e7bb820fb215772d4033a3dcdb9d98e089d.nq.gz
    ├── 31a158ff6539b2daf96a698a7930f2bc4695f73f.nq.gz
    ├── 321b5dd8648aba5fdf1d670879b2b5a91af7cc40.nq.gz
    ├── 35583625d671fe081bae3df8a032bab4589cc089.nq.gz
    ├── 35a724c94f7dd0e23ad023e9e9480bb14174d3e8.nq.gz
    ├── 360b40ce01cd9d22b25cdd831530ad2ecaf1526c.nq.gz
    ├── 3741b60adabb073b030b17be950918cc8d20ede4.nq.gz
    ├── 374507632436a27a3eef4704fc71dcbf5163606f.nq.gz
    ├── 381b12f3726feda08172006173f057190c2e9b66.nq.gz
    ├── 385c1320e8bac9b2bf2bf65063e00c0eb05e8ebe.nq.gz
    ├── 3870e457f6f50ab01e8056cb667f05b9b9abd499.nq.gz
    ├── 3a48ef143d47585be556966544ff8206be430e14.nq.gz
    ├── 3a6cedc737b61807d861bbe069fca2698064ed98.nq.gz
    ├── 3b77bebe1bcc30b3f197db65e5131f98cd64cb89.nq.gz
    ├── 3c1ad251c7e02fe232d7742c08aa4ae03f6bbedb.nq.gz
    ├── 3d19d9d8022c255e9808fefee0f0443671e3d6f3.nq.gz
    ├── 3dce0645dc8c058ebb55ab875036921ac61d97d6.nq.gz
    ├── 3dde3071e096243ab853177cf63881ae86cbeb0a.nq.gz
    ├── 3e44dc5cdd281b456b737cfaaa6d34754a0914ca.nq.gz
    ├── 3e881420e3c005e788c238b6be1de01865928f0b.nq.gz
    ├── 3ecd97f7f0a3b7e8a63612a5fe37376137e4be58.nq.gz
    ├── 401d352b7da1a457f7c01a2a5b519c90e35d3558.nq.gz
    ├── 40dd142e5836ddb7518ee4f8059ad337280ca90c.nq.gz
    ├── 41a6547a3fd6e5e8d32c42a24e6b7c845381a2de.nq.gz
    ├── 42d22effe97392b2baa150a73a543b0df8774a92.nq.gz
    ├── 431e829705da46163b0e93dd8b352c78aafa7c71.nq.gz
    ├── 448a4b1022376d97c1eda62d224d897a919e0370.nq.gz
    ├── 4642c9f14185d38d688c2a77c2ff9396f9f69f04.nq.gz
    ├── 466003da28ebc4d0bf25189e4ce5ca382cab9f83.nq.gz
    ├── 4664d3d5f3cd03c5646ece56e5064050592c6c81.nq.gz
    ├── 48238b42f9ed5693db82a4f1e7bac85e78b9c176.nq.gz
    ├── 493fdafdc804b2322c9d17a7be66cc33ca620328.nq.gz
    ├── 49f8b9fd82b0cfe3b5f393b7c707f4781479f98b.nq.gz
    ├── 4ab24a96bc1a725b1eb7f2dd8d1f71cee04ba439.nq.gz
    ├── 4c06c0b8c9c141dae79d1487c455b0d5ba87f221.nq.gz
    ├── 4c7458792e5e0488767bcefc6a2be6a102699211.nq.gz
    ├── 5101a637137192d730eb16bf0ebf83047da8d4fc.nq.gz
    ├── 510f1337526158942fd9761874170d2aca99468f.nq.gz
    ├── 51d38421bb94a2648944f5d5808a8a615d3fef55.nq.gz
    ├── 52fc01fe1debefaa45912a9ee3aeb61c0203a4cd.nq.gz
    ├── 54fd50de1d26d8106d1e7370f1bbe3ed6b11eaa6.nq.gz
    ├── 5615033895a001c53f1dedc0796a357fead07667.nq.gz
    ├── 5664bb385f70e169594fe950479592f7488ed02a.nq.gz
    ├── 568a00e57a269cbaf63fe1edcbe6f59cf5a24cbc.nq.gz
    ├── 56ed4b554499b5a7d3cdbe7d08965a8bbadec2f7.nq.gz
    ├── 57f6c6209208c3eb54cf161c8c32815fb011a6d4.nq.gz
    ├── 586a8b7d92b54978dcf7346514699902e275d653.nq.gz
    ├── 58f2c9233d36529e714f735104c0a117e50c9e75.nq.gz
    ├── 59a8f874098e7930b4a9e9ffb754a6a71cb5f167.nq.gz
    ├── 5a2335822a201bc68774727c7eefe14b874c4175.nq.gz
    ├── 5a41b1af6229b18cfbd7d1e8ec1b7545123f028d.nq.gz
    ├── 5aec80c9bb178acb9e39fb6bac0b526ce14a5d1d.nq.gz
    ├── 5b3ab2e25c2cd624ba8866b56dc3e772ba73e3d4.nq.gz
    ├── 5f34e257bdae41b24dfbd79dd0b13a362bac88b9.nq.gz
    ├── 613564438ed72fb291468e718d076f381c0c2aa7.nq.gz
    ├── 61eb8be665bf950f087be11d1a95244198cbd3ec.nq.gz
    ├── 627df8f96b90ef32ab6c6b0bcccc22c0b7ac7690.nq.gz
    ├── 65f0c12bba7637b6ca1c6fe125b0644c56ba860c.nq.gz
    ├── 663ee1ef0086bde3d2c8b703f257357bf8d68280.nq.gz
    ├── 6a84c18dbfd62af734ed08e3d647598e8d3c9825.nq.gz
    ├── 6b3ff200d76fcf8538854c0c0569accca98e37b4.nq.gz
    ├── 6b66f038b04edac469aec2cdd6b88eb85f2f0beb.nq.gz
    ├── 6bc1343d86406a9f64f14dfd7991b18131150f28.nq.gz
    ├── 6e15b792d2a7196dde2b550a339518119b19495a.nq.gz
    ├── 6e2804f40c363d8ebb9ddbcf39e2b7399423fb95.nq.gz
    ├── 6eaca06c1b7101c64bcaabdb30e12b9f85a176f9.nq.gz
    ├── 6ee62cffaf600e4453cd4eb065c6c832e3ae9296.nq.gz
    ├── 717d4ead735e6184995bc638c09a27e62b078a96.nq.gz
    ├── 74f2331ac53b6c632b2a51d43992a9d0e25dc00d.nq.gz
    ├── 7573c0346f3aecf73f72f00a100bc38f16dd3d25.nq.gz
    ├── 75cf8d93cde45e4429fa769ffbf7ff99ba5be22d.nq.gz
    ├── 75e4c5ca6c0d502a0616dbf099bb466f63b46ce1.nq.gz
    ├── 7616f672cbe19ef4e8414b7a365b2b2816ff4aba.nq.gz
    ├── 76f505aa26fc614e66ce57bcc424227b15a6e12b.nq.gz
    ├── 7dcde43c420a519b09c393ee2f22a17439d524d1.nq.gz
    ├── 7eb4b96dddd298db0b1c29206b7dba764c8b99cf.nq.gz
    ├── 809976a0818ec936d70b23c22f59abc2a7c5d2b5.nq.gz
    ├── 8125fbe0bce89d650e03acd320f8f5307c975c5f.nq.gz
    ├── 81333495e34009648407140201f8738fb28060c6.nq.gz
    ├── 8327a07ecd5db12c529ff7a8430b4643ae4f9f3c.nq.gz
    ├── 835e2e27f8b5900498487433c21dd54c757d08cf.nq.gz
    ├── 83e2b9c4772f0cbb01e31742bf40e918025c6c79.nq.gz
    ├── 84f9ba95f21ea6f2493fb847adc6dea086ef9b1f.nq.gz
    ├── 84fdcd4999d060720297a4aeb389fa48e57fbbdd.nq.gz
    ├── 86b8df59d42ea3e6c5031585b577675875e44821.nq.gz
    ├── 874ac3178d060a895aef826d9b8faeec1da2764f.nq.gz
    ├── 8771b63fcf373e44cabafee77b5036ea279b39fc.nq.gz
    ├── 89c1e1d9f856a03307352841485893f49a86c571.nq.gz
    ├── 8a87b5ae1bd844e5a97dd64a251cf9d67f4df4e6.nq.gz
    ├── 8b66c837b574faae7463ffe13379e6db415e1ecb.nq.gz
    ├── 8d08f35ba547ec1d92e59a158746b67e3d22c621.nq.gz
    ├── 8e14082d45393f68ed8a74cbb438950039f39cc7.nq.gz
    ├── 904ce90554ab6625457d9410f06987fffdf48be8.nq.gz
    ├── 91e69f9a3c1b0087d3742c6da7404de59a4e22f9.nq.gz
    ├── 932147179f5c597ce8eb24fb7f25d3218ff885bd.nq.gz
    ├── 93e3a603849a1e58ec172abef023ee0e0994e2f6.nq.gz
    ├── 9585c45193f06389c526e741d231dd984e66d8d2.nq.gz
    ├── 9671fa57821476cc2edc93146872e194b65c60d2.nq.gz
    ├── 97ef081520dc3f26831e017bf741f00622690285.nq.gz
    ├── 98a1cf96ef7511b969cd899f5e0fb483ddb19825.nq.gz
    ├── 9a99e5bdb827188d0e8ad397f7be8018d15004fe.nq.gz
    ├── 9aef862a857f8fb4bbb478ba3e13dffcdaf8a533.nq.gz
    ├── 9b02b39b56f353dafde7c413b0431a18e376bae8.nq.gz
    ├── 9c6d47ccd4e73fe7381d8cea63e6f463d39ded27.nq.gz
    ├── 9d0953fe6aa39b56ae819eb4d63f363c69c85849.nq.gz
    ├── 9d88133bc5b6986834a9d02b21c9c00e39d12f5c.nq.gz
    ├── a016f8d9420cb3c21b73926367f32ab2f7682490.nq.gz
    ├── a19ce539987c1e79e26bdca10bed49efcc030c5b.nq.gz
    ├── a35e98303c196651d8429c4df2cf26914f859932.nq.gz
    ├── a40b671c72dbefb6ee9733204c4aeb2783899256.nq.gz
    ├── a5632058992ddd45270c087788172e0cae8267d4.nq.gz
    ├── a8bc3942291f7a9b3ab337c257cc85daf8b15341.nq.gz
    ├── a97c786c2f8859b763340daa49e540eef1ce7bae.nq.gz
    ├── aaa5b6530dfcf4b3be114519b7ba6cf622a5ad8e.nq.gz
    ├── ab6a32f10265bd800ded393b3440122e69ee59f4.nq.gz
    ├── aca63e7ace47ef7f21bb420c0dc8cec814a77e45.nq.gz
    ├── acd67dffa7115119a938e4ebc900848680694bd8.nq.gz
    ├── ad011894b70923a4db1ae533319454d6dfc6ef64.nq.gz
    ├── ad19ab8130ba80448445282f2997f9ab244ca3c2.nq.gz
    ├── aef4ea1156987f22e0a39b144de216a46993fa80.nq.gz
    ├── b096e02301c4f417e816d85d5e6e2424da855c2c.nq.gz
    ├── b0c2f166d116fb30acc468f28e839db706d50cf2.nq.gz
    ├── b13c41a605ea485e327bdfb93a8ddef900b9cbe1.nq.gz
    ├── b16ee8446637a53964516385d7422577b1940274.nq.gz
    ├── b382783068850728a87f35aad57c0db43e5cbd42.nq.gz
    ├── b8b60a207c641f9334620defe0fedd57333bd3de.nq.gz
    ├── ba678f056c3dc533116359ad481415ddaaa9dde2.nq.gz
    ├── ba7b1f469054777f707e069a8cce8cb7b0c8517c.nq.gz
    ├── bb62ce02f540b2a63d25a12a572c41d3ae9b5f5f.nq.gz
    ├── bbe13164a8876f47b8bdcde4d8ae8f55eb843598.nq.gz
    ├── bcc112fa54c7f578af70367f2488af821b727525.nq.gz
    ├── c29f299b795e866a5be40c7edb6ee13c82229add.nq.gz
    ├── c509c9bb303c969f0f01f776f1087a6e8d455a95.nq.gz
    ├── c62a8dbdaf87eb1d1ec2d84cc1b77435ea292e08.nq.gz
    ├── c85e77b9cbb738766078938db208fb0c1b943519.nq.gz
    ├── c942e9ffe651e9e3e512f2d92c4d33d3d1d97979.nq.gz
    ├── c9af7e6e3ad482f36d424d52a6cc9b3752b55629.nq.gz
    ├── cc982cf1f4b67a2ab904ee4598b072bee298c776.nq.gz
    ├── cd7c83e2725595ee60801d01b3a85cbbd0c3d590.nq.gz
    ├── d01a3e7b12393e29866f98dd63e284aba4773310.nq.gz
    ├── d58e59b84d1eba3685d39d5f8b2f9a3239b31837.nq.gz
    ├── d6f2e64bdff8feb8bb041f36132177573858fcad.nq.gz
    ├── d8aebcfcbf24bd51ef6bc572e68c20f574b91f3b.nq.gz
    ├── d94ff8fdde49c622a0f3b77489b81eb73129396a.nq.gz
    ├── d9ad50f0e2d86e9a6396478dbe48b54175ac52df.nq.gz
    ├── da03b8f61a97dfc19bc59891bfb7eb63403b9a59.nq.gz
    ├── ddae810f95156a7a7718a775e74bdebd219ec58d.nq.gz
    ├── de3ef08fa03a6230a5622a93d52f6cdf3f348eec.nq.gz
    ├── e070f57ecf9003f258cef30440681bb194aa85fb.nq.gz
    ├── e081be06bdae4e4056138c82807f84f577382e18.nq.gz
    ├── e33e066b44cd188bd1144877bda06c0be06c0eb4.nq.gz
    ├── e3dfe51d359b1717de1027ceacdf6c6346e76d3f.nq.gz
    ├── e4675e49b3a4bf42f4a1b56f26f2c5e63871d12f.nq.gz
    ├── e66185ccac34704fd24a61cc2cf407b854166df6.nq.gz
    ├── e67cb274c639d060743689abcdec58f6e9b5581b.nq.gz
    ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
    ├── e88b6f882d3f4296e03c082fc5514133f191359d.nq.gz
    ├── ea5bc1f652f9e39070c7cabb2809778b5cac86c0.nq.gz
    ├── ea81fc6b51064bd05cab386db255ca7065865cc8.nq.gz
    ├── eb9a417e37aa93f10d3991c0f0c7f2133a99e987.nq.gz
    ├── ec08a4df858c90c5e575f392ae90af861943d33c.nq.gz
    └── ed05342733f27313e21b7be73a07ae7941a9ebce.nq.gz

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

[rayon-rs/rayon](https://github.com/rayon-rs/rayon)

---
*Parsed on 2026-04-22 by [repolex](https://repolex.ai)*
