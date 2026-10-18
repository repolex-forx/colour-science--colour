# Repolex Knowledge Graph of colour-science/colour

RDF knowledge graph data for [colour-science/colour](https://github.com/colour-science/colour), parsed by [repolex](https://repolex.ai).

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
rlex download colour-science/colour
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 248121e33fcae458e62190ac872f3e16ab2044bf
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 248121e33fcae458e62190ac872f3e16ab2044bf
│           └── chunk-001.nq.gz
└── blob
    ├── 00ef548492767381b873652fd3add44899659813.nq.gz
    ├── 01a57f30d50aa0ea17b6bb14c5182962fdb332ff.nq.gz
    ├── 01a6ed626a358ae7efd677a15d017d60089bea84.nq.gz
    ├── 01bca9233470e2733c4e1c608d49f9f061924bca.nq.gz
    ├── 01e25eb133b38f8c34db951d9b11904448cdf9b4.nq.gz
    ├── 01e2eb4bd5c4f68cb849ad7ed4dd9e559e27a3a2.nq.gz
    ├── 024dfef019c10d5b0f5b934efa16b61c3a104d0c.nq.gz
    ├── 0266c96d47df417797893dc78a5c0fc389e21b1c.nq.gz
    ├── 02a297d572cc895832441387fab5902ffa02b71a.nq.gz
    ├── 02c1250cefc30c2985e55186dd70e11f01154d2b.nq.gz
    ├── 030c46dfdc6522a61a875357d97977354b7d5f0f.nq.gz
    ├── 046ec552a879ec834d6d2c0b4d0f17d35b521b30.nq.gz
    ├── 05a13a294b265a50e98698e2540d198dba08318a.nq.gz
    ├── 05ca55db18875ce221a332079be260793e322406.nq.gz
    ├── 060ff2882f8d25ed9d5c9629e7dc2b808c84b06d.nq.gz
    ├── 062f54f83dc8cdbc85afbe3d78e6f8c63f0723fe.nq.gz
    ├── 0649b3f0861a3a7d6b8aabeff76e3a6878a12275.nq.gz
    ├── 067fe41cb168d272b06740c9c491d4ccc5d48a52.nq.gz
    ├── 06b1e70ccfbf90ef3c2306f171aa6f29b2888041.nq.gz
    ├── 06ced132e08c1507391cc329b013ded3dbc8bf01.nq.gz
    ├── 06e663afae7edb7a4c0242a7304cae0f2579d648.nq.gz
    ├── 07069f5d02748cdc90a60cc768dbfee0cdf585af.nq.gz
    ├── 07094330e184e7c44da23015fe7d7ded55a64971.nq.gz
    ├── 0735ccf067d145c07cdb6bc840c358dbeff35f1b.nq.gz
    ├── 07cef22a7097c192865569c5e641a1ce673f7ce3.nq.gz
    ├── 07e2fd4e074839c0471eb08615f4d23b93906035.nq.gz
    ├── 09708db5c229a9fa7695a326e744c9b4529ea2c6.nq.gz
    ├── 09b1ef93fb414db8745a7a1e33d5bcb399735fdb.nq.gz
    ├── 09ff88433f455882150f4db05339cf1903a9d683.nq.gz
    ├── 0a2e20874f3d81b30fce411c3e5048ff04df5694.nq.gz
    ├── 0a4db1ac4a20b70658aa33a6be05b5a9c6ee364b.nq.gz
    ├── 0b1da5dad6d670b9656f83ce9df8daf7c33fde16.nq.gz
    ├── 0be8f3e8b2bc6060e9d92af20c010db1f28be713.nq.gz
    ├── 0c9cd3806d0c399e71c2a8a233f2bbdd4aaf31e5.nq.gz
    ├── 0dd6830b0aaae87db8ee2f9184bda6c80f33f476.nq.gz
    ├── 0dd9d99a5ddef9819cad482393d0dc24d1c30dec.nq.gz
    ├── 0eafae8854efaf01b3694aaf741934295d6e9eb8.nq.gz
    ├── 0ecc4a43cbfe99ef9ceb347343de59b31256cb09.nq.gz
    ├── 0f07ca7969e357f493af72481a52acf3d3574f3a.nq.gz
    ├── 10235c5192f16e0336cba20a7bdbec827192fb4d.nq.gz
    ├── 10757fe3ce956c76d8f62983f0bfaf0a6b7d9c1c.nq.gz
    ├── 10b21ab1d81d507d000d7d1d06105291449dd585.nq.gz
    ├── 10dfeabfb976ff4869f22e234e8ba83e12940e64.nq.gz
    ├── 1124820869b626c80ff5cad7a3b7d0f95c6fc61d.nq.gz
    ├── 118379a12823a57ed37cebb2cee0b4ee30c9db6d.nq.gz
    ├── 12347eaa8f56fdf86ed595ce121e88af55e24fa7.nq.gz
    ├── 127d200304d15fc5ba063c82e9e6a13aa8f21298.nq.gz
    ├── 12d4cb1a79aef1f3d8c9c8b7aba2974c4f3e08c1.nq.gz
    ├── 12d74f310992cf645dcd4d6f347f9b3d3f3e658e.nq.gz
    ├── 130afc162f3780bd6fe4159513050bb247de4f22.nq.gz
    ├── 1350cc0416f93a4726dfa1dc3ffa2ec8edd2d55c.nq.gz
    ├── 1389e5837316a2d3e4107bc4e21f36ca2485be76.nq.gz
    ├── 1398fd13bd968bd7f79debdbfe989705614b2023.nq.gz
    ├── 140269eb3c002a83aaf51a0bf164657e9c570cdd.nq.gz
    ├── 14d3f1cf21435d78a0ccce5e352d82d223d9737f.nq.gz
    ├── 150e024bd5bf85e59bb3e3123a4bb287aa57c791.nq.gz
    ├── 16754f8f7b08f055f921ee4f529ec68b80e4d0a8.nq.gz
    ├── 17150d31036bb520cb27debf1dae74e885667ee9.nq.gz
    ├── 172fb46aa4a7bceec4c05d4295919aadc444b5cf.nq.gz
    ├── 193e436f8729690e95c875214253cd78f7058778.nq.gz
    ├── 196c932ba30e1f59fe4eaf02f16d1a3c2a32ef3a.nq.gz
    ├── 1973b9bdb4c7bf8e144fd733f1d35440a235ceb2.nq.gz
    ├── 19e28ed1d136e2c2fddbeb5b92a41363162232e0.nq.gz
    ├── 1a955cb945cfa22ea3e99f6f2a0f175f600506c7.nq.gz
    ├── 1b958bdbf943f06414fb91f8dff7df9b21aa1062.nq.gz
    ├── 1bc5f7208d53ba81df5ceb0dae544823997ade64.nq.gz
    ├── 1c12bfdfc8c0e3dcfb83dfa016d65c6d73936c2f.nq.gz
    ├── 1c3018f4ff3d8192d074f681d29e3c6fffe9fbaf.nq.gz
    ├── 1c49e834542b97458f79700a1b9dd2686c0ad97e.nq.gz
    ├── 1ca1fd12af45465232a96006dd3f501b8c0be600.nq.gz
    ├── 1d1922bbaca24f152185a37031342fa0f17039ff.nq.gz
    ├── 1eeec6a755293ddc1c2db6fe75b9a7fcb45d5598.nq.gz
    ├── 1f5b59585232bc909130fd04d5120bfe8c403641.nq.gz
    ├── 1f8ab0809e6783079c2c4ebfd5ff9ee8a3db1020.nq.gz
    ├── 1fb841496c0ad3534a81b74a8624952e22aeffbf.nq.gz
    ├── 201f588527d3459862b4d3710e4cdff2d1b2812e.nq.gz
    ├── 21004f41cbf060130f8a8744b785db7f9300c594.nq.gz
    ├── 21259aca15bce79e629ed47d6ccda40ad2994666.nq.gz
    ├── 21c025e5dc65fe5f46459e972db59cba76b1de43.nq.gz
    ├── 21da43996261e5e51debd83a7eef202865d2bcfa.nq.gz
    ├── 221522e2afb307e94d602bc4afe47afa1173e1b8.nq.gz
    ├── 2235fdc5d6e3d5f7013b890da382ab918f5c583e.nq.gz
    ├── 22658a275197267c0292f3059c9a338e55f9fdf7.nq.gz
    ├── 22b684f43fe491275b31a30a65d4d43de387e72c.nq.gz
    ├── 24203c9250e5de9250e8354a4ff77629d94733a4.nq.gz
    ├── 243f5d5fa63761ee3147bdea5742be8f6733d3d8.nq.gz
    ├── 244754817e1f2ef3aa7b65531bc98b2a54183f52.nq.gz
    ├── 244dd66dff6ecd84d71056189117f2deae2ddc67.nq.gz
    ├── 2469643b3fbc4ca2eb54cef98068cb1e08d99cc2.nq.gz
    ├── 24a485a6fc212623d0daa5cde476c8bc7a5c7842.nq.gz
    ├── 24dcf4e914a0254626ae0b3b4209cb02531f36fb.nq.gz
    ├── 25613f22feac6e4bbe45bc02aa594df7b128a8fe.nq.gz
    ├── 259c7362a5470390d1e6ca3ae2ea4533087ee2ee.nq.gz
    ├── 25fb97166187a5ac32d0f50377926d5d92ffc2ec.nq.gz
    ├── 269c11f57f62a74bc743e0ec880300cef9bc23c8.nq.gz
    ├── 26d9491defccf7398a0b0b9bb549053f92bac8d1.nq.gz
    ├── 27581a1d96f37c9ca64f63dde0c1cb4c299c4bf1.nq.gz
    ├── 2764db10c8ebf0ec543bf8b94ef804e3e363ba40.nq.gz
    ├── 276a447ad9564c537aa040b947c9aeeac5441acd.nq.gz
    ├── 27aa95f604b5ff3a49b8e03b9cf6a2cf3bd60584.nq.gz
    ├── 27c43b2c5a39ea8238e3d34dd38b5419c95657a0.nq.gz
    ├── 27fd8687476152031b115e18d776eb7369214647.nq.gz
    ├── 286050d195015441971dfab54e2e76e4ae923dbf.nq.gz
    ├── 28a5e39164f3172885e9e4e27fe91a3e35d26df6.nq.gz
    ├── 29025e7f492d0f4e2875a18f791bae44ba2129c2.nq.gz
    ├── 298e8658769183b80bdc7bdea470c66a87e80ae6.nq.gz
    ├── 2a724b1121c48dd61eb57baab63f466c9d08f5ca.nq.gz
    ├── 2aa7d7c8db388f80b30e17b9abdcb62e3d6781ca.nq.gz
    ├── 2cd1089b2832f9423467d0f3661648d898f623be.nq.gz
    ├── 2d61aa68fd38b22609e9643cead516d24ec50643.nq.gz
    ├── 2e6956cba34de3bf0b6b18e809a596ccd5b88569.nq.gz
    ├── 2ee97fa374d98ffe9a5aed2cbc01263b6d12cbfe.nq.gz
    ├── 2fba5b02b550fac49c48ea7c7b2eb0aedc52fa98.nq.gz
    ├── 2ff70ecb100122de752e9edb80f14c93eeb9f798.nq.gz
    ├── 300ba2c7794b03797cce17452e5a9586b92aa9e4.nq.gz
    ├── 317ffb87d61b21eb6551fb6b05ec24d97b163f05.nq.gz
    ├── 31b82e858590fd5002a036d5ceff05f7dbc89281.nq.gz
    ├── 32ae2f0c4fcf7c5562ba63ad722c4594fb189708.nq.gz
    ├── 32e9c091bba6fa15523b246bc4b9a8c2ad066b6f.nq.gz
    ├── 32f18730f5735aa22852bbc2a61e5a89775fb8eb.nq.gz
    ├── 38108dede5e0483608cdd8f90c230979356dae6a.nq.gz
    ├── 386007ea0b676de10e23e127813f74bfbb7d0f7b.nq.gz
    ├── 39734bad9dea85b6b62db6b012b62f03853205d7.nq.gz
    ├── 39777940bb09e318115e1dbe1c0b075d72432a7f.nq.gz
    ├── 398b69873d0b97de2738a50ed7f2dd4384e80b31.nq.gz
    ├── 39f3bd42e36880b7e0638982579725420bcb7beb.nq.gz
    ├── 3bfacbb32bf6042d891fd5b2714578b1e03460c5.nq.gz
    ├── 3c955e647314cc8f142a4b9fa089f1096adef00f.nq.gz
    ├── 3d408350790adf4f28c3e8ee7165879601d4e6a1.nq.gz
    ├── 3d49443e8798d16ae50a660710ecd83197621f1c.nq.gz
    ├── 3d5f50e1c71f215e915acaf838cc2ee711ea00e3.nq.gz
    ├── 3da85d2a34b7c1b0c28ad7b5ae95751ddda4e805.nq.gz
    ├── 3e250ba93962fb59a02985517365177c8cea44cf.nq.gz
    ├── 3f53c69883af4302378c411169eb773f36b67f5c.nq.gz
    ├── 4010192dbe4a51c64f53d09e9325f2d5a64f8be7.nq.gz
    ├── 40714c7366475fe76bab454af01a8156d0c9c5a5.nq.gz
    ├── 422086cc4c4e1552374ce0bd503864fdf4c4baa1.nq.gz
    ├── 429fd9340d0741e8cc3519c94af1bc1ac35783d8.nq.gz
    ├── 42b6247ae0be74056dbef74733f79f3594114400.nq.gz
    ├── 42f9216550f7bb0e06db6e0d95899d06778b9abc.nq.gz
    ├── 43aeb2743326f5fa87033c6c48137a080aef7e60.nq.gz
    ├── 43f48ebabb7ca01990f9a6546240465e7de968ca.nq.gz
    ├── 446623e36ee4d755a53c817196fae8a6dfe30653.nq.gz
    ├── 45ae87e641ce494b8261f441076888aaf0e0ec8a.nq.gz
    ├── 4662e9d5b01084f85d0d4a6a5a809a6848e70ede.nq.gz
    ├── 471886bbb7553748fcd7bbf24e419007de60698b.nq.gz
    ├── 47e652eb8ac0a255ff4f4fe4546e2d631e0aa944.nq.gz
    ├── 4814110fc385f3084721b392c40078a826869408.nq.gz
    ├── 48637180a278c006268e478e31f5f99b1e197ced.nq.gz
    ├── 486ff6e898848c4f5adfea3ad52c4e742b99cb4e.nq.gz
    ├── 48ea9984949c9801fb4b48ee88726661d7f56cd8.nq.gz
    ├── 493cf54511e719fc815a7c9194f85a8b710fd788.nq.gz
    ├── 49dd27ae7d9d9476c16a2963c4881d21707c20cb.nq.gz
    ├── 4a93244eed1b1958105d92bee52546ae35a105f4.nq.gz
    ├── 4aa7229bf94270b626dcdf228d19999ccc5777e1.nq.gz
    ├── 4c1b17639ee8f76f0b87fda226901424828498f3.nq.gz
    ├── 4c1f1b86508b3f9e7fb423d52fbb760237933e8c.nq.gz
    ├── 4c3b808b9bc32b0374c2f93419037d5ba9a8e847.nq.gz
    ├── 4c4fa60337ba355121e29e826addbaebbc4738c5.nq.gz
    ├── 4cb4f25a351754fedcc93eff5e69d1576b2c2401.nq.gz
    ├── 4d1039f58671d665309d85fca11dbcac1ef3c1a1.nq.gz
    ├── 4e84b3db9830cf9f471186d33267c81b7eafc2e8.nq.gz
    ├── 4eb3e6ea4e16588cd1b1fd7acc343b8009f824e1.nq.gz
    ├── 500b2025a67f80fa1975221ddd591d200c55b8d5.nq.gz
    ├── 503954e23df5d93f7ea88f4a8210883f393df7e2.nq.gz
    ├── 517be82c3c0eaeb862857cb3994325843028fea9.nq.gz
    ├── 518521598a8942993a091b4ebb115e3b738e844b.nq.gz
    ├── 5256d62fef42bbae4854f42bccbb999e821f4a15.nq.gz
    ├── 525748a57019324aea4bb9d0ef13ca79978abbbb.nq.gz
    ├── 5278ec1148db6c63b3b7093c2c414e25ab829ab4.nq.gz
    ├── 52854917cf2a6668751e8e4d55cf789cbdd39714.nq.gz
    ├── 53186f7f57624b5646e06172cb112a5e3f973c63.nq.gz
    ├── 5326592dc7e183977ae98e41c47841f9ad8bd318.nq.gz
    ├── 541dd56faf950f60c573a269c8fa382a0c53d092.nq.gz
    ├── 5431758e5fc67d8c4df7835ba8c9335c00a2c802.nq.gz
    ├── 550dfbe09486db8fd5bf498f36df1340f31f7df8.nq.gz
    ├── 561c5774f32ca97a5f3a039aaf047c1869831077.nq.gz
    ├── 565fa32fb14eec0c9e5de3018877184456712110.nq.gz
    ├── 56682f32e352b01ab17ef89c430f050dcaaaf638.nq.gz
    ├── 56ad376fc31e3893c628ae9b125a2deb801f58e9.nq.gz
    ├── 56c045dd8491623bea975df2c7c60d6094f9a36d.nq.gz
    ├── 57007c90cf6cd259d8cf382ce4dac46545573b87.nq.gz
    ├── 573c8e85b50c7ecb65ee2c777b7d0c0c97fe94f5.nq.gz
    ├── 579577452ef9c3b543c9b6c7b69fd2d9fd119581.nq.gz
    ├── 57cd1611fbb4872c65547a301a6ac960e221195f.nq.gz
    ├── 57f630c0d26ca2c2e0208d470655370b37e14252.nq.gz
    ├── 580ec2ed4719ff1fede3776b817ff59e6851c6df.nq.gz
    ├── 58315b78e4bf934cd968b02fed7ada6fa4349f24.nq.gz
    ├── 58ec1de5353bad7c7697baa59300d26fb069f300.nq.gz
    ├── 59bd36c1bde4ec00282621a02aae27bd47ae3d3f.nq.gz
    ├── 59e1ba078356607c02b1420818ffadfff7c1746c.nq.gz
    ├── 5a049694b85de31521b7e8093d28b1ca16779c44.nq.gz
    ├── 5aea7be5dffecfac89f10422acc35f431ef55ad0.nq.gz
    ├── 5aeca0b0e5b5c0ec39f826100a825728859d85af.nq.gz
    ├── 5beffa61be246b20deb764ed1105e77fc8d7110c.nq.gz
    ├── 5d0c7a2a2687cdb590a1022a219251b74ae0d91d.nq.gz
    ├── 5d1fc0d246a621ba541070e075ae2605a2ed866d.nq.gz
    └── 5dc208872eeff5cfc286e17011457ee662d26644.nq.gz

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

[colour-science/colour](https://github.com/colour-science/colour)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
