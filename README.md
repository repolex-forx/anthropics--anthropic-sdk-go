# Repolex Knowledge Graph of anthropics/anthropic-sdk-go

RDF knowledge graph data for [anthropics/anthropic-sdk-go](https://github.com/anthropics/anthropic-sdk-go), parsed by [repolex](https://repolex.ai).

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
lexq download anthropics/anthropic-sdk-go
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f7e7e64a78ac7500f6a4ab6072332eef65a8781f
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── f7e7e64a78ac7500f6a4ab6072332eef65a8781f.nq.gz
│   └── repolex
│       └── f7e7e64a78ac7500f6a4ab6072332eef65a8781f
│           └── chunk-001.nq.gz
├── blob
│   ├── 01bfdf65e7d5e1834f392ccc89ac50a02ffd8874.nq.gz
│   ├── 01f9b50642af538e2031c89e2f0acddb342d4805.nq.gz
│   ├── 0232b84ae22c45bda992ecba40ef6e8f09639327.nq.gz
│   ├── 024227bd1ed777eba37ec799649d3d6f97673588.nq.gz
│   ├── 02a92a6cecb7e987a03e23062cfeca343c3ef85f.nq.gz
│   ├── 0435e58807bcadf85878e9c7c5fec08e526ac16e.nq.gz
│   ├── 09f8e623445b1c2275bde609e59d1b2a866577f4.nq.gz
│   ├── 0c27c1e32bf04f97d6a83a48f56787c89b9cf7e7.nq.gz
│   ├── 0d1698e6be61b12edfee227e216eb9b185953ce0.nq.gz
│   ├── 0d67013754b1c9dc550acc65c28e06a90fb1e020.nq.gz
│   ├── 0da82a5422fc38fb02c39d29fab36c1f194dbd65.nq.gz
│   ├── 0f379fa33ae487b7844dc1b75ea303be3a856206.nq.gz
│   ├── 0f69c6c243c99de78c13e81ebcf72f11c0e23f7f.nq.gz
│   ├── 0f92c3c81c681b266f307cdbbdbbd74b05c783c4.nq.gz
│   ├── 10acdc18c6b0b497fb5485db30b28a30163f0ad3.nq.gz
│   ├── 118906d3940fb67ff8665497add1cc44a3ab27d8.nq.gz
│   ├── 1194166076fcb4d1c362c1992218bb109ca3571c.nq.gz
│   ├── 1227adaa47421898f8038667ade1c0563002ac49.nq.gz
│   ├── 1348558b842e3b4aaccf92a955a445f11a5bb2bc.nq.gz
│   ├── 16207e5abdd0666938c0b2e88f0408e0c369c604.nq.gz
│   ├── 1b01434961c3f4f73aa8b86792c81c81a5c4fa3c.nq.gz
│   ├── 1b81fa987330312e22e226364479a0fbbf1a9f35.nq.gz
│   ├── 1bd9a518327e04106aeaa4a72cb180990a9fa18b.nq.gz
│   ├── 1c1714e4fcbc54d07b0ddf09d9c9d06004c3a5a8.nq.gz
│   ├── 1ce37ce3aad3613b2f090313d240820ab39a2363.nq.gz
│   ├── 1dd9dc9cda4c02a2183eefc3cd4a4871fa05109b.nq.gz
│   ├── 1e211ce0628a24e7c0ff46b22646a4811a2d96c3.nq.gz
│   ├── 1f84b12f7356b61215d32b059471b687be56b09d.nq.gz
│   ├── 2085d5a9d2bb3b97992e74206a35fb0c92253ecb.nq.gz
│   ├── 20ac0285d7e4aae5d6e4f4501a7cd8d8cb975793.nq.gz
│   ├── 21fbcbc6b31adcc543b438446cb6adb519bc5a41.nq.gz
│   ├── 2288fad63d314249bca939e7f1130e89ad20b205.nq.gz
│   ├── 22a415295b4085620941d993e6fd29427f41f054.nq.gz
│   ├── 22c19d683b45fc808220934efc18db1e0a6c005e.nq.gz
│   ├── 2450ae4551217234881cd053f431f0bb8333f3d8.nq.gz
│   ├── 26c71bcb3de65264604a285d61d8e54e853b3356.nq.gz
│   ├── 26d15b246c7836120a8cff43ec4e40fd6e9ce656.nq.gz
│   ├── 2853bf94898fa8775a4216f7732b678120ec1081.nq.gz
│   ├── 2a0c38b5b62a66c51cc273b033230ab5acf9d766.nq.gz
│   ├── 2a0f228c78891558ee0ece4d8d408b1e92b7c013.nq.gz
│   ├── 2a72eef124329fca01d6a23663fa1b8f6bfe0884.nq.gz
│   ├── 2af1baea554f6b04e0e70456ca1bf3cb7cb44160.nq.gz
│   ├── 2b2afcfe898189b7d76b0a10d356b8028e84735b.nq.gz
│   ├── 2b66fce7f11050c175f11661c0a3bb60e9450a01.nq.gz
│   ├── 2d6c4b051150cff7d0d76beb771443dbc9c1bd7d.nq.gz
│   ├── 2d8e3d08f3eab3899af11ca31a650b13384e0f6b.nq.gz
│   ├── 2deb07ef30cc9acca7becddb49483edd2ce0fca6.nq.gz
│   ├── 31103e9ed6f70629910892562bbe52c10768ddc4.nq.gz
│   ├── 34fe701a85988207931ff793da9ba79b73e58f78.nq.gz
│   ├── 374ea29197f3f46f5df5a498c648b19e3ba1807f.nq.gz
│   ├── 3755f4a04bce0e575176c611a235ca9cd0f4bc9d.nq.gz
│   ├── 379d75f4c7aeb98fa9bbb0de3f27e32f61cc669d.nq.gz
│   ├── 38746def11c581965f9e296d688826a7a876a5db.nq.gz
│   ├── 399051f27d0ebfe623bdb67ee7a8a0238cd64d29.nq.gz
│   ├── 39c9da33dc01e5e9241eebc5de411a133f206f5b.nq.gz
│   ├── 3d8b198b9340c0de7a532996b406558ead14486e.nq.gz
│   ├── 3db94be185c9da5ce5248fd71c8640fa948b0ced.nq.gz
│   ├── 49f2cc770a17a0263ed54c0a5b58ed460111167b.nq.gz
│   ├── 4a9ca4f4fd60269314ad2fbc524e84a7df5b2eb5.nq.gz
│   ├── 4e2d9224c70847d804e3c889781db5a3194b64b6.nq.gz
│   ├── 5114a081795f65e12bb58515b467e3a83e14af12.nq.gz
│   ├── 51f91395ee69726cc2501005252e1c57db0a8a99.nq.gz
│   ├── 53b576992639a63ea918ad59255233b0801af2da.nq.gz
│   ├── 5445116e99316cec5e84775ff84d98cf6a0dec68.nq.gz
│   ├── 5448ddb7b7f3f34053a197fec54ae6d9013ca841.nq.gz
│   ├── 5508c00728fbead2e050d94c53ee36176657875b.nq.gz
│   ├── 572c9ce26fc2ef3e17132717b5df5b8af552badb.nq.gz
│   ├── 577e34a4b34cd98803132e4c5d2e790079414948.nq.gz
│   ├── 5ab30665f805c0838d22e9fd50cbde55f3f304b8.nq.gz
│   ├── 5b32545260d6e12867a9c0a477ad9b3fe9440f29.nq.gz
│   ├── 5dea03d7c2897d3728edb931963d86e2c52bb659.nq.gz
│   ├── 5e2c99fdbefc565576f8c5f37b0b0a66d60f2015.nq.gz
│   ├── 5ef0998859d21ba7f6502a42480deb60a2e6ff61.nq.gz
│   ├── 607bbb36b88c17eb0992fe9f7ac7da464cb2b3c6.nq.gz
│   ├── 622624b50354bfe00cf47bcfdc6dcbca2fb58f31.nq.gz
│   ├── 643d50779d1bb4007fd154232b35a75c71d1f5d0.nq.gz
│   ├── 644d8bfec30980968389ad0c5e8a7bdd2839ab5f.nq.gz
│   ├── 66a65e5a386e8faecf06204d0de0482814944035.nq.gz
│   ├── 6764453047cf4e3169012a92f38678d805520fb9.nq.gz
│   ├── 6998723a1754f86870e0f882e1e76cf95678a7d9.nq.gz
│   ├── 6d1a6f936a81c34a2415af2535b0ae62ac798bc3.nq.gz
│   ├── 6f5df74e8d7a09c8500aa5c47632288e954d8c45.nq.gz
│   ├── 740955b52335ebe7a799f66a17d1c5f23387bed4.nq.gz
│   ├── 749cbcc861a299b9e8b573cc2a11809de6c11bf9.nq.gz
│   ├── 74be73155d2d8440cabb9f87449be88540279e94.nq.gz
│   ├── 74ece49af8982e768f3539f0f9bafbccb6967225.nq.gz
│   ├── 756571a6ab1c0728d8a667a628d1342c35ff033c.nq.gz
│   ├── 78ed921f8c69a6f31f1e25dcfe63094dfa01c3cf.nq.gz
│   ├── 79db052615c8fe453ac72f3d1d3f9997e08c3573.nq.gz
│   ├── 79fe056478c0a7c832b8870926ed1adfa0df6241.nq.gz
│   ├── 7a7a30e0be82a3b305242504f00211326ddf005d.nq.gz
│   ├── 7c91a88bd6308c0e6230ae7f0f3440badf8135df.nq.gz
│   ├── 807acb2ef3899c460134cda99f895022558402fb.nq.gz
│   ├── 83e27f5cb2fb9a39a19c434b943e722501ba626f.nq.gz
│   ├── 84f06e0a27c87aa80680e4e0ab0192529c43ef50.nq.gz
│   ├── 854d6dd78d77caec97b8dca68f50a48f4561bc5e.nq.gz
│   ├── 8554affe54c1d386886b7f45ab32714f6651b64b.nq.gz
│   ├── 85685fa174ecd010d268935183ad8c97c8f635b8.nq.gz
│   ├── 883f68e332036fcec0e4337352c84b2085239f50.nq.gz
│   ├── 889ae34727d9ee3946845c9968cd071b3bf466ee.nq.gz
│   ├── 8be1d974652e35079f7db6f415aa40e41668c89d.nq.gz
│   ├── 8c2fd503a17203fe448108b91c728850de792a8c.nq.gz
│   ├── 8c5f2ce22692c669b0bba1f1b0187ff06795c22b.nq.gz
│   ├── 8deb246f342d708630774f6ba37fb744b3567090.nq.gz
│   ├── 8ec9dd60bd6c94d631dd1bbc7c069b625754d833.nq.gz
│   ├── 8fde239bbebbf866c415e71abd6c1e0f7b2327ed.nq.gz
│   ├── 901ef808b864ea3ff8a7ac1352330a2b2970cc0a.nq.gz
│   ├── 92b371187ec1f328aec042b3a0e26b68ef1ad570.nq.gz
│   ├── 98c3dd4b58021255e5b47cbfa0e5e768f58b4dd1.nq.gz
│   ├── 9a3ece4da7ee45ae52af6bdf65e201c6449d8449.nq.gz
│   ├── 9a6f32791b2ab7e07a40cac91558965c7a0107f8.nq.gz
│   ├── 9b2a2e4f4fdb91535b36c12efb3415380bc17497.nq.gz
│   ├── 9bbb9269cf1b221297b2d30016d292c7fa355f8c.nq.gz
│   ├── 9e413ad82f04f05b88c22656cd15da8c61de73fc.nq.gz
│   ├── 9e61c5ca8c90a105f967fe2d4c9387fddeb8b577.nq.gz
│   ├── 9e9e38aa1df3f44c7dd38616c769468eacfc0927.nq.gz
│   ├── 9f7f307d1825796c156f29f22767153bad850dc9.nq.gz
│   ├── 9fb9beebceb8ae7445f7f9a2da04321b3da402ca.nq.gz
│   ├── a051f5415e1fa86d0ca3d17d6369dff08a87bd45.nq.gz
│   ├── a1626a574cc4be6150bfcc3ce9796b8d9eb1de75.nq.gz
│   ├── a18934b463b7de4efe80dea232ceb9aca14cede6.nq.gz
│   ├── a2aeed44c7e3da8aa7587bc4e553e856e922c9f1.nq.gz
│   ├── a57d62a2698086b24d516a3340a29b11f6dff88a.nq.gz
│   ├── a5a3e07d64d17be2d49e45ac45193f399532fef0.nq.gz
│   ├── a63ea3abfe495c05b919c4b1b57175d88cc113b0.nq.gz
│   ├── a858340f0a92da0c8ff915ad59337d5e0b2219ba.nq.gz
│   ├── a91bf4b110a51d4ec4d38ae36557904db5f439db.nq.gz
│   ├── aba8afefdde6adea806b55f639fb766f870ca875.nq.gz
│   ├── ac71a66cf790ec2b4cc699891aed7671a6233dd7.nq.gz
│   ├── ac7a1b4791b7febf4ec8fb478212900a7d2b6d79.nq.gz
│   ├── b06fc808825b311423cfb3c42fb4c7dea8153287.nq.gz
│   ├── b1e8a0c9e5ff1ca2a3c1d59bd22e1e026e9d4a3b.nq.gz
│   ├── b2a94acdb80f4a7bdfd2df4cadadf418f92b5ae0.nq.gz
│   ├── b40013c13ad1a79a30fc2fc191a7361b2071eaaa.nq.gz
│   ├── b490328f4c46e70aa85413ac5a4ee5a0190592e9.nq.gz
│   ├── b4e2ec29a829590d2e74a46b4e5997eba7c73099.nq.gz
│   ├── b636a52d0f1e5608f73c92049467f954641396a4.nq.gz
│   ├── b7d610ff19912b36247d5e3f5020986371331c4e.nq.gz
│   ├── b8c6b329cdd529c48a6faa387edc3854f8f8388a.nq.gz
│   ├── ba83aba75ae56294b533f79612d886cb4ef29aa2.nq.gz
│   ├── bb01f1ad8ccdfe580b64edc2e8fbefc23d0d47d5.nq.gz
│   ├── bb2d9e4414eb521f3b56509b4b6cb94dc3c73dbb.nq.gz
│   ├── bdeb0bd134708260d143a673badb668e8eb4f9e8.nq.gz
│   ├── bff104c83b551aa20e8efb0caeb01c65a134f91b.nq.gz
│   ├── c10ec40d6fe6f79e146adece84ad4165b727feed.nq.gz
│   ├── c15c4f8e1d5aeef1cfbd19ded24527c8e72ccb7c.nq.gz
│   ├── c25460de94a7335e5828dae6f99f3ec8d80309e7.nq.gz
│   ├── c3005c5adc4f0277d3f9dd8db13589b4a73616c3.nq.gz
│   ├── c3bfeb9aa685b49e4ff46e737511e7e150a19a60.nq.gz
│   ├── c4c671b52765a41c66fe6b055ded986c22b469c7.nq.gz
│   ├── c729e4a63853f32a016e100a613778cc1012ab03.nq.gz
│   ├── c7349fe02e5784cbcdb3b58d6e42d94f9e611049.nq.gz
│   ├── c8ac0322768c4fd6748b44eea8bc25e22e1b725d.nq.gz
│   ├── c8f0ad904af352612121efa125f47ee0a4c4e210.nq.gz
│   ├── c95d634529cf997cabb04465cd29f691f85d8cc7.nq.gz
│   ├── cf1aedcb816914dccf24be8a78cfd3c18ddd50f3.nq.gz
│   ├── cf6bd6a0d32ceae7b615fcae970f894baafbcf23.nq.gz
│   ├── d04379078697ebebe99b553c0cd9aff868e10ec7.nq.gz
│   ├── d0dd33a0b2ec8b5591f2d70840881b4d4f678116.nq.gz
│   ├── d222ef3614ebbc89fc69b5502dd63301d8a3a3a0.nq.gz
│   ├── d2df19a5d4f623d57d9e95cc76422c842fc1f613.nq.gz
│   ├── d2e94ad07fd4de7c8911912e0fe5ccf4cfa74bf0.nq.gz
│   ├── d30d54ba522b7fdf501a0b791a4c9aa08fc3e2fa.nq.gz
│   ├── d5ef3672ccfeaf946bb1ecec2c9cfeb555501d18.nq.gz
│   ├── d63018a69fc439ee7f13b92c60f681ffc4e947d8.nq.gz
│   ├── d76a534819cd4dee7f9f964f68d6638bd852d5ef.nq.gz
│   ├── d7c982631667669fbabf032579a0c62fdcf26b0c.nq.gz
│   ├── d8c73e937aeda0534b48d146e2816d5000f0680b.nq.gz
│   ├── da6ea2ac8f843f54279b509f5bf9786194b426d0.nq.gz
│   ├── dabce4f1554ac71a44173bf89a05a6e30b33882f.nq.gz
│   ├── db2a3fa29edfd4edf38f4153fd9417353563160b.nq.gz
│   ├── dff5ac85dfd60c82314889e03e94e799874c286d.nq.gz
│   ├── e2d9470bcc7fcaba1183b6aac565eadf3350a181.nq.gz
│   ├── e64ff1cba4f0b9b20ed59fb6efab1d8f57aa287a.nq.gz
│   ├── e735e4794c6ea561de5fdb69a8dbfe3229336fc4.nq.gz
│   ├── ef5b46ae0cc30477376fecaca4c29c878e26d37a.nq.gz
│   ├── efcaf8ca0d52dccf2db2bb6194278f840432390c.nq.gz
│   ├── f0c9d14cccf48c0ad2113ee7d6b56a6a27146a90.nq.gz
│   ├── f1c7ef53f6ba197b93a720dabe9198758190b24e.nq.gz
│   ├── f574704d1fd7d5f7fc0938090ec028c7779bceb2.nq.gz
│   ├── f6d6c1391f4c4cf98f2e4dc0daf52eb025c7a944.nq.gz
│   ├── f6f02d2e340aadfbc599a95a614c67bfa8ac4284.nq.gz
│   ├── f8e37643effbbbceb9816aa5ab6b3e9d1342edc4.nq.gz
│   ├── f90920629e3d2e4c83618babcdced65f950dad5d.nq.gz
│   ├── fae2b8dedacd11411087cd265d23c97187d1333c.nq.gz
│   ├── fc223c9f726dee41aee1a453717e6ce215347324.nq.gz
│   ├── fc645cdc7b0a6efd092c3d8521c769ca2ff33879.nq.gz
│   ├── fd089d7ffb53fd71d226536157785ed85f617878.nq.gz
│   ├── fd47ee15c933a3a11d1f244bc378f8a4c49a347f.nq.gz
│   ├── fdf3c5a48f781a0810b53c226b37cadd941fafc0.nq.gz
│   ├── fe9a71abebdd87ce661823c6aef59197fdf14f66.nq.gz
│   ├── ff1f1edc6dbfa0b17b7f467fbb42197da257132b.nq.gz
│   └── fff75606a77989d555069b849e7f6927e1005c3a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── f7e7e64a78ac7500f6a4ab6072332eef65a8781f.nq.gz
└── filetree
    └── f7e7e64a78ac7500f6a4ab6072332eef65a8781f.nq.gz

12 directories, 200 files
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

[anthropics/anthropic-sdk-go](https://github.com/anthropics/anthropic-sdk-go)

---
*Parsed on 2026-04-15 by [repolex](https://repolex.ai)*
