# Repolex Knowledge Graph of NousResearch/autoreason

RDF knowledge graph data for [NousResearch/autoreason](https://github.com/NousResearch/autoreason), parsed by [repolex](https://repolex.ai).

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
rlex download NousResearch/autoreason
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 538f8817550e7c76c92355a967c5363d55ef9659
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 538f8817550e7c76c92355a967c5363d55ef9659
│           └── chunk-001.nq.gz
└── blob
    ├── 0038c8b333596256fec2a4f84f6fb5eaa253e810.nq.gz
    ├── 007d557e6b28f208ef871e70c42b07bde3b59234.nq.gz
    ├── 009983eb9e72bbbe3015ee2ae1b9906f1344a5ba.nq.gz
    ├── 00bd55446dfdf907343ac9e90ecd0e7f471f6b14.nq.gz
    ├── 023174c33205414a42d4db0454ec023932e1d9ef.nq.gz
    ├── 02a2e859be65a9ba8b1c89f0f84dda3b51270096.nq.gz
    ├── 02dd98793638925d33378cd1fc821514074287e1.nq.gz
    ├── 02e05d7b90889a6f8d01840124cb88a0b2b27a93.nq.gz
    ├── 03085d82fcded18042d070618bdf0f083dc850dc.nq.gz
    ├── 03ed60994450b93c45a92ddd25b95f23b3a4395f.nq.gz
    ├── 048f427c7c9f6f60789e6a00411677e26bb998aa.nq.gz
    ├── 04c821d86e1f02cfd68cec2270e72260cfe9f40e.nq.gz
    ├── 050fc4939874152b83707fc1b5f131034523724f.nq.gz
    ├── 0576bfc0051019afab618576ad86b131b2cd45aa.nq.gz
    ├── 058d1e699ea68bfa000a0eaa0a683af362b8787e.nq.gz
    ├── 06f571bdb9cbb8f5a5a59fa237a7e79e1ce97560.nq.gz
    ├── 073d5de385e23bd81191cf67d52adabb67cf64f0.nq.gz
    ├── 08b454be049d7bea6de119230b29bf0fb2482b05.nq.gz
    ├── 08bd6709d0b863c5e603cb9377317690ee982cd6.nq.gz
    ├── 08ecec4d957e30895fbeebe6129dc829c6c64477.nq.gz
    ├── 0959add073dd3c62cc37ae1814e091ded1f5f8fa.nq.gz
    ├── 09613be5f3646f4e52f004ca3d82abdad31114d2.nq.gz
    ├── 09ca144f7c129a51e6e619e98a065c44bc08ab1b.nq.gz
    ├── 09ea17cdf0e50117aee5a6bf91700c997ec348bf.nq.gz
    ├── 0aba2b0d2b7d7497255c1cd24e2aa6131ca0ad06.nq.gz
    ├── 0b4dceae35354d51aaa717e6c58b0aa33b144548.nq.gz
    ├── 0bbfcb18295cef03a5f4dd01bffb8242c5f60535.nq.gz
    ├── 0bdfa6b33b96ff868653b2f30e318f2e8bbb5aa3.nq.gz
    ├── 0c20b8c21d47e63a2bb4afbbcf7bacaa3f4d977e.nq.gz
    ├── 0c8ba670048d6d97424c7dba0a8ce2871996e49a.nq.gz
    ├── 0ca9b9ec79a8d0aa1063832978efdfec5ead6866.nq.gz
    ├── 0cc139f05dc91e41368c3eead8ed97b65d5f3e71.nq.gz
    ├── 0ce1eef0a616c6afaea50f6c0aa8e9d64f7a2488.nq.gz
    ├── 0dc093637732c2d63367bbf9a0ad00b4503f7422.nq.gz
    ├── 0de28726fe834d19f371b501c49b55154853cf4d.nq.gz
    ├── 0e23d19ff2fb73bcd2a2db2f374e2c93a07cd7b9.nq.gz
    ├── 0f46c3d98912bc88e7f534094ed420815d3e4a59.nq.gz
    ├── 10053f24e52f70507e7c3396a56c74d2f15f7d7b.nq.gz
    ├── 102c514c5c3d1f35d0fa2486b649d69384342ed7.nq.gz
    ├── 103b8cf85b5bc57001074335e069f539086eac30.nq.gz
    ├── 10caf3aa28d7501ef3ae97f6bd31fac4a80173a0.nq.gz
    ├── 10e3fbef05c129f4e0b1097e6cd74952487d346e.nq.gz
    ├── 10e563ed9336d3e0a823f223de415ba5b9b98b11.nq.gz
    ├── 10ed870853e221f78fb0adb9170e160a7c14a3ae.nq.gz
    ├── 11228779d9f82d85fddfe0d6b096081d5512304c.nq.gz
    ├── 114ae8c76058be82723319d4788486794782c40c.nq.gz
    ├── 1192d02da6f05160941fd516c579eb83077243bd.nq.gz
    ├── 11af0e073cf2fb18647f89b7fe9f852409ed9d44.nq.gz
    ├── 134f70eb69e9dee4594a7a374c939bab7b367904.nq.gz
    ├── 135948c285bfcbe6603e4cff73124065885d36fb.nq.gz
    ├── 13bdf668559b153d11599551fbb8a30612fd0802.nq.gz
    ├── 14919aad733ff840ef9f344b6c742b442c579a28.nq.gz
    ├── 1565525d92c431301ac86d9900e0bc61d3f76d2b.nq.gz
    ├── 15b4fe604532ff2a067989bc32edfa6015ec25a3.nq.gz
    ├── 162c28dbce827e3aa12b375b898d63a228d74a34.nq.gz
    ├── 16533b6d4abfc32d4603d9e7438024aa450661f2.nq.gz
    ├── 176aa5c0c04cf1f68ff5cf42fd34123181a835c3.nq.gz
    ├── 179fe0fe9c66d822c891c6e4502b698b5cc33b7e.nq.gz
    ├── 1a8a4fb9e23041d6fee5b06258cddce1faf365a8.nq.gz
    ├── 1c5a89cd8e67890ad7eda1b70a08e13b1e50a32f.nq.gz
    ├── 1c60a29597a5e3108da8140f4dfe15a6365a1b2f.nq.gz
    ├── 1c7da5267b006261d9d860f302122ca7b06fa61c.nq.gz
    ├── 1cebfa72b3d4597285f7c3624312bcbb5c73488f.nq.gz
    ├── 1d31d3a2ee5b80e78d9d9961e5998829c3ea2690.nq.gz
    ├── 1d54749c1fd54a9e327ed73ef0b1a36a254e8a67.nq.gz
    ├── 1d5ad57c5bbfeaff340271974a53324309a3b8d5.nq.gz
    ├── 1e2bbaeb423e2c5cd2aa7dd1b66298548e52c48b.nq.gz
    ├── 1e915c906ea5dbf9f9bba46d5ebfb51d4a652ad9.nq.gz
    ├── 1eec8c68908666ef6cb7a534ac8f32cec4ee955d.nq.gz
    ├── 1f26169187384e54d887b2c065e11f66d9749b19.nq.gz
    ├── 1fd8fa9735f3451b4be3c4352e92d6dae29fd5b8.nq.gz
    ├── 1feea694cfcf06068f06efa32a2612da96670fbc.nq.gz
    ├── 1ff8566e15722087d26fd404ff36d06afdf0313a.nq.gz
    ├── 20c399eed795eb6c21861ed19bedb70ebf42e17c.nq.gz
    ├── 20eb82c05e605374310cda0856e65f53826fd1c9.nq.gz
    ├── 210ed1b68652202a5b8727872f4e9449847fb71d.nq.gz
    ├── 219d2178723b328c0200629c8bfc9de2335e4a7b.nq.gz
    ├── 21c204ae6f6f00147486afc2bdf0d57bb986758b.nq.gz
    ├── 222c22af64b380d5870acaca6cd70477a01919ca.nq.gz
    ├── 228299eb25369b4ddc1edb041e53e1a86bf01b89.nq.gz
    ├── 229cb1e537a055269dccaca6ba9f424b986e304e.nq.gz
    ├── 22be83c100279a68aec230f34b5ae7361fb0aa48.nq.gz
    ├── 23dce3e40511ad86da674c737ed8ba1b9dbb4150.nq.gz
    ├── 23f948b115ac149208323d39ce1d90281fef2f34.nq.gz
    ├── 2425e098e24e5c1fed484092eb69cefa2afa444f.nq.gz
    ├── 246ed3e164a1671c90534d59c92e6674aebf5608.nq.gz
    ├── 25883d903e184eb48d2a826da3f3bb83ca495f23.nq.gz
    ├── 25e69594328cd5e8efa020c062e6ccfebced115f.nq.gz
    ├── 25f7056077811d71fb321453c70989ce57896032.nq.gz
    ├── 2676d370516d3a412a80a67a2531a8543b0ed414.nq.gz
    ├── 26a0e62be3398c61f19991cdf8aef2c22d46d0b3.nq.gz
    ├── 26d88a2af2db2e719289ca70d2688b7c178990e0.nq.gz
    ├── 26f7cbddd13d8c99d587742c7812bde7980022ad.nq.gz
    ├── 270ff50fa3c5583f03b64896e0167dad1caa8eea.nq.gz
    ├── 277367f8ecbbf48e8d695e4443b461baeb8ceffe.nq.gz
    ├── 27f2ab15f699bec7cb6aa36e637554817ea0a274.nq.gz
    ├── 2878d21854699dddc39cc4a2da158c847ce719ef.nq.gz
    ├── 29755caebed34cded9598a380584f880c57ddbbf.nq.gz
    ├── 298b89c885e922e5fc100bd18f49fcbf3c6353d2.nq.gz
    ├── 2a33fa5cd82cf5b981530cfcc150a90b5a05d446.nq.gz
    ├── 2a51c39f3a6cb6edf9061819b874a2d694889c60.nq.gz
    ├── 2a71156fddd2f663748067d4f4dcfc8e96ac8048.nq.gz
    ├── 2b155ebcad124896b0953001ee937683bb759ed8.nq.gz
    ├── 2b4cbfb07933ac51234cbfe30881f3b355647c5c.nq.gz
    ├── 2bf71c77a64fec98ebe69e7bff39c2ee370babea.nq.gz
    ├── 2d76ad0b364c9f7a2cec53675457e78d6b837095.nq.gz
    ├── 2eb5eea92534fb1008bb25b4c0a8ad41a0555303.nq.gz
    ├── 2fa9f932642ba26daa252a906ad3fb52be29bc21.nq.gz
    ├── 2fed3fd5e86ddb6a244bf0b62d28300d46282ae7.nq.gz
    ├── 3043e8ecc7db8c445a90896e400d1fc8488dd110.nq.gz
    ├── 30dcb6053015697c94ce48e3b35d8894caba1731.nq.gz
    ├── 30ee734f597f9f79b7c1323d251e9707caefe8fb.nq.gz
    ├── 30fccb982791091a9b28b4459e588643e7435e77.nq.gz
    ├── 3125cd127ee70d0ca93373596497005bed6274b8.nq.gz
    ├── 3139943e676598a7547e27b98333ecbfa7bd7013.nq.gz
    ├── 31bcbf7dea6b107ca9a15aaba0c56638d94bba16.nq.gz
    ├── 32647bb700715f05d1dfcbd346d86959107ee477.nq.gz
    ├── 328dc3a37e17cbdfdfdc40fb984c97754cd64aa4.nq.gz
    ├── 32a19fc59cc2b2d45af9bf36a35953f9a3b39504.nq.gz
    ├── 32b09e91e194a949575218d715876f128362a9e1.nq.gz
    ├── 335f3bd091177319c28dbc6ef680a231c334c7b4.nq.gz
    ├── 3465dbefd06b2eca28df6ae1190ff4052ce2202e.nq.gz
    ├── 34a20d1cdc7428325d657e99b54a5eddd043b487.nq.gz
    ├── 34b2b22f5139f2709ca2fc4b307abe71e4d3d79a.nq.gz
    ├── 34cbe4690ac449d6dff2d66ee98927512e9f131b.nq.gz
    ├── 3512f65bc25c70e660289176b37020d8fe7a7bc9.nq.gz
    ├── 35174066977d925d45ff5445e3d09123083ff6fc.nq.gz
    ├── 362a3602235f93e67011f08c40b5fbb9d89da22e.nq.gz
    ├── 3704bae8db99fda41ed21fe10123162ccba45555.nq.gz
    ├── 3775edeabad88431dcb6e87a8ef5ea7241e04e61.nq.gz
    ├── 37ee821ba569458aafad4d6d8b0dd5800568b908.nq.gz
    ├── 382063bf9c6da5e9d48cbc211ae43808f0831083.nq.gz
    ├── 38b319efcb7844823eadc359de22b52483cdf025.nq.gz
    ├── 38cfd63ff092ec849f7b6705478941cf89668505.nq.gz
    ├── 3902763be7f7d0ab80f044f002a35f36f6d41d05.nq.gz
    ├── 399b597bc384a334a2c543c555bbefb0c26a6262.nq.gz
    ├── 39d7e1c795d3e08a78c16fdfc5362634acf134b2.nq.gz
    ├── 3a149ddd783b66c92026a3530376277a041e5b4c.nq.gz
    ├── 3bc745acfae6097c6729248ddc5e1d73755c2ef6.nq.gz
    ├── 3c669803768369d134e6b070123d3be878088867.nq.gz
    ├── 3cd558e8f9fd1947046ce3a990bd992f8713202c.nq.gz
    ├── 3cf1e4a95d5dc9b402dc06dea3a25d02587ef278.nq.gz
    ├── 3d34f84528d4efab33d40ed8a3f0b25088bbc0f2.nq.gz
    ├── 3d8e8e089df4a4851a1ee15265a3bda1c0b2011e.nq.gz
    ├── 3e97e82a52aa117d385fe31efadb7a55d68fb2f0.nq.gz
    ├── 3f0eb2d9c0a863922f5ab32bc003fa0e112b13e6.nq.gz
    ├── 3f1402dc9c2301db85cff8c7c51d7557ed7963fd.nq.gz
    ├── 404328c265b8a16ba3593ad79c6806d4eeb24870.nq.gz
    ├── 409752a628e9ef78196d53867218d6793f18b29e.nq.gz
    ├── 41259b845bab1f829083ac395ad409b8bdbfb8e7.nq.gz
    ├── 4175af771a8bd9264f2da34d43b0ab302b11756d.nq.gz
    ├── 41ee3aceb124c0b78fa5cc240afc6ea0c9e10004.nq.gz
    ├── 42653b25c2133938ef6e698639881da8ae7cb2fa.nq.gz
    ├── 43030ea5787fbb7fa3207bef3e3d7ac40300542e.nq.gz
    ├── 4327fef07ae0f41e18258c96e2963bf4d6c9a0ef.nq.gz
    ├── 443a001b6900f3239918425563908d06517150ee.nq.gz
    ├── 445010fc53e29c69d490b2bea95f789eb39da123.nq.gz
    ├── 44a05e26099a49b683e4483473f4d091c81e8d16.nq.gz
    ├── 44dfc8807b09d02c19879799a92f131bc76bb6a1.nq.gz
    ├── 4693fe208cfb19c9b803fd319d5435a4d869f2bc.nq.gz
    ├── 47881484229e0bd5fceeae3ac4faff9b35cd83fe.nq.gz
    ├── 478c10cf9db4b5ccadd6f7f349bd4d716a6878aa.nq.gz
    ├── 47adca6566e1c476ff89fb294b33cb98b29c77cd.nq.gz
    ├── 4914b419ebafc97a029f507e29549d9de94badf4.nq.gz
    ├── 4a275e8c7ca542099770cc5948357409191f3e1b.nq.gz
    ├── 4a3abf354eadec389cce94f15e37dddd8cb26556.nq.gz
    ├── 4a85c3a5230ca0b98fc30beb2db081748f629b5e.nq.gz
    ├── 4b47bc9fd2541be2ea9ab3eb8e2f98bd11d44430.nq.gz
    ├── 4bd2ceb60147bf3818938b52172425ef95708858.nq.gz
    ├── 4c31e6540b7c505e9c07ca3e3c260c1b89742b6e.nq.gz
    ├── 4ca26b868951e18d29f89a43bf8f8dc04ebc8ce7.nq.gz
    ├── 4caa1db13e54a2d510b1116c31394f0b56dea359.nq.gz
    ├── 4d82e5345f0bb8b915276b876ec8712ba149c365.nq.gz
    ├── 4da27423b25860cb81d1025925e1821f6730ff10.nq.gz
    ├── 4dba2ac1554dd6751f71b16d0d523422b8f0bbdb.nq.gz
    ├── 4e07e73c12e8dd04c65e86c4cdd812c56e213fd5.nq.gz
    ├── 4fc35a84a0fbb77b08519eea726d9794c1fefe82.nq.gz
    ├── 5104a16684bbaffbdde99ba6868810c2ab14bd54.nq.gz
    ├── 51617a731c7ebefa97e87cea3b1e84d514ff32a6.nq.gz
    ├── 5234cf3c64958448ef401c1a7ce2d4e1cf59d099.nq.gz
    ├── 539153fef659e7f46b16857abd347a89de9048a0.nq.gz
    ├── 542e454ddc54f71b65bd6473cc45dc04f8e61c98.nq.gz
    ├── 54661397b28871147c00df74df6e9c55f4ffb534.nq.gz
    ├── 5480f53a06318863348564e3822c561dab6e9efe.nq.gz
    ├── 54ef1d379b54db265b16dd9cabb08bbfdd0b6bc4.nq.gz
    ├── 56883362b8d18ec202c03b88edd029365a2cde3a.nq.gz
    ├── 56a57060bba903bcf9d9eec378df0baf5615dd87.nq.gz
    ├── 5715c3dd5cddccfffd6ca2bad17e8dd46d9daf73.nq.gz
    ├── 5738e49bbe2ecdf642096437be886ea8fc1a9bdd.nq.gz
    ├── 57717421e24c19a18448e33c179661340b0d25a8.nq.gz
    ├── 580416890ef0113da1039fff61a1d8aeb2520e6b.nq.gz
    ├── 584009a0d8f060eed5811144be68b86430eece01.nq.gz
    ├── 586488e084bb4f27e3c1e77e507d0d110f7618fa.nq.gz
    ├── 593bb0707ffd22228fa4e785314c89bae8b11e0e.nq.gz
    ├── 596a8ac1f5567223dc7e1fa05af14001aeb6d26f.nq.gz
    ├── 59f8e6e81be04ffd9e14dfe4ded5c30b81a276b5.nq.gz
    ├── 5a12f69813b0a3992ed783005f175622aa2fe2b5.nq.gz
    └── 5a1f881bbe826c5b39dfd7f538f37145b23ff7a2.nq.gz

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

[NousResearch/autoreason](https://github.com/NousResearch/autoreason)

---
*Parsed on 2026-10-09 by [repolex](https://repolex.ai)*
