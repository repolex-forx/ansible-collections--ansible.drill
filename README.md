# Repolex Knowledge Graph of ansible-collections/ansible.drill

RDF knowledge graph data for [ansible-collections/ansible.drill](https://github.com/ansible-collections/ansible.drill), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/ansible.drill
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b4f8cb77d8d92b8ebfa5a60acd5be1bd8a9b69f7
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── b4f8cb77d8d92b8ebfa5a60acd5be1bd8a9b69f7
│           └── chunk-001.nq.gz
├── blob
│   ├── 013403fe1d7179d85212e4fb76e1c163014732f6.nq.gz
│   ├── 07faa2177626030f7a45d82ea31ddbae6911eb6d.nq.gz
│   ├── 085762ac5b0486409945b220e1199756c7ea2226.nq.gz
│   ├── 0972cd2e8e58d51f20c6b0d23d8f89154c7ac076.nq.gz
│   ├── 0b5f3eeb7930deeb9d5ad7031561f8d32e34a439.nq.gz
│   ├── 0b6905e1c988fe549f688c278c86e1c7dbb8f6f3.nq.gz
│   ├── 0ef3d73958d1b6c9a9e97efb51993c69bdc528bb.nq.gz
│   ├── 10926e87f113fb026c366866d6fa466061562870.nq.gz
│   ├── 1242b1d390c95692d0c82a504564a4beb6c55541.nq.gz
│   ├── 15530084d296fc7ed1deea10ce258242b29b6cf9.nq.gz
│   ├── 1683f99fc86bdb022d20de8a2c8d688391566d0a.nq.gz
│   ├── 17f14c2b5642d71a98b2600f3426bbbcb592defa.nq.gz
│   ├── 1c55b2856a60a5b8aae33d91d8c7b1992ae363e8.nq.gz
│   ├── 1f49cf69863c309fe4ee64e2880375ae1ca966c3.nq.gz
│   ├── 1fd693d77a9415a323b1b6967eae94e3581b180b.nq.gz
│   ├── 2234dee0a10a09a48106c7e7448938c473b3c613.nq.gz
│   ├── 242de9208c798eda7896d609aa63fc791a663601.nq.gz
│   ├── 24d0222865bb5b83aeb7a9c46b4192b710899aaa.nq.gz
│   ├── 252ee3d0ff97e67ac2878185fe73c8cbf00eb947.nq.gz
│   ├── 28e35c9e328db3520fbb6ab531cd3164d2755c50.nq.gz
│   ├── 294bfdeb1be0a41374e993fe0673114b803135ae.nq.gz
│   ├── 2a45b48c03cca393f9f8aa360ab69f6be34df3df.nq.gz
│   ├── 2ad4c0cfce7d87b7190e65ffaa2e4af971682ec8.nq.gz
│   ├── 2beb8ca2c75b5e836506749e0b750d3347f53690.nq.gz
│   ├── 2d8cfdda388894c77558aa014d115a5b6ce1b1e1.nq.gz
│   ├── 31939caffdc616b4e357c17fb84dbbd0c1f3898b.nq.gz
│   ├── 342d5280a7b6bbcaa92c006b8084629c690cdd07.nq.gz
│   ├── 39d9697e548d9a481c1448edc8e4b0342d4c7a18.nq.gz
│   ├── 3a56ac6675a658b4baa706735d002378ac5a4ac7.nq.gz
│   ├── 3b477d749a15ccbd241d4c785f5967a71fc6b408.nq.gz
│   ├── 3c95d81d251c8f1f83cee577571bc18869adc8ba.nq.gz
│   ├── 3cd437193bb9f111776a993f92cf4e080396e104.nq.gz
│   ├── 3e96db9b3ec01e9b8b8b0ddd9fb6d13bf5a64fc6.nq.gz
│   ├── 41fdca522046eb784d3026d9dcee526635976852.nq.gz
│   ├── 4270e896508b35e46897254ef05cdb5358366c08.nq.gz
│   ├── 43bbe4509687b509e7fe8a4d2125ad41ace6f1b3.nq.gz
│   ├── 4740452aa124e63c9847dae25fdc73dd8033813d.nq.gz
│   ├── 47e12a93cea5786bbd9fee5e60a7ab437721407e.nq.gz
│   ├── 4920b88ffade134dd788de7cdd294be143bae250.nq.gz
│   ├── 4b87e31f02d597a6984bb1341559a84c17715608.nq.gz
│   ├── 4d945469fb6722a2bb126d47e86fe63b994803fe.nq.gz
│   ├── 50248849f3d3a1e14f0b261762331ba25447ca9a.nq.gz
│   ├── 505a1342d1f9eb6b0a6f45677e02732a95bf792d.nq.gz
│   ├── 53133539c275e5db472a8544eddc13731864050b.nq.gz
│   ├── 538193533573fdbf938157f9aa3e1ca2ae10caea.nq.gz
│   ├── 5438ced5c30ae998cbd337fe217d86e970630166.nq.gz
│   ├── 58be0e8b689145c98eb39e885dca128e16cd7c15.nq.gz
│   ├── 5959a80593c22ba38d29e73047311cf5bcdc8c1e.nq.gz
│   ├── 59b0fb686a9f1b7b45fc28dddbaa2be112fbc195.nq.gz
│   ├── 5f63dd48607f898a3db2c3fbfe3368e23471ee1e.nq.gz
│   ├── 60c30cf31710baac85cc03a2161a39c8f5d3aef6.nq.gz
│   ├── 64d40e5af30d0d638b12c59b5eab59b6db6c7835.nq.gz
│   ├── 6632897fbd3373dc2038cd4a63d99270d10a2da3.nq.gz
│   ├── 68caa1f3e08bbdf19007b13be321a08d6641ff83.nq.gz
│   ├── 69e80e361f3785f92cb5cc8f97d88f4e308c7905.nq.gz
│   ├── 6c58961b69486bf7d2b8f49d31577bbde47e6492.nq.gz
│   ├── 6ddb77685452b41e26a1a4aeafd20688342eec77.nq.gz
│   ├── 6e7b726e3bd7a27b5dd36e2fcde0a5dccb73a82b.nq.gz
│   ├── 6eb5883724ffa4fe2a0c42aa10447f6522aab6ca.nq.gz
│   ├── 700ad3edcff119a856362985069b4c6a63f086f4.nq.gz
│   ├── 70752cf61ed41047d9f7aa3689d28aa3587f2d59.nq.gz
│   ├── 73086cc6a9729ea5cdfea0954a54d3312209648f.nq.gz
│   ├── 7608ebfaf32cb489cb6d4f6637ba741859fbb25e.nq.gz
│   ├── 7654cc6d77e3e02842826bc132fd14b8c69a10cb.nq.gz
│   ├── 7770ed483cd8f526aa6778a307761233a747a0a3.nq.gz
│   ├── 77e25783046f219692c73b44e2c10e78e425c139.nq.gz
│   ├── 78a451deedacea17c6a2cc0919f6d0e59e50eb4f.nq.gz
│   ├── 7b38d10c2a1cf4af72fc8db111522d3f1fb3d4fb.nq.gz
│   ├── 7c34db44288e14f09b84cc6efab65cf369c52b84.nq.gz
│   ├── 80ec6bc48ce80007aa70d02b810e80ffbb29d6d5.nq.gz
│   ├── 82458df43e1b65c8f412a331a5df6cc68b4869f1.nq.gz
│   ├── 828127b479aae3869bc1545dce9203cc18e4ce2f.nq.gz
│   ├── 82cf8c90dcac4f68bd9c92cff2ab696510dcb92c.nq.gz
│   ├── 8435735b67a4180a2fdc7f0057f8552c2cdeb985.nq.gz
│   ├── 84af28609547e1ea2b689a077b501c3ad51a4a3c.nq.gz
│   ├── 85f744a5968e6fcc6360af031409c1244036fdf2.nq.gz
│   ├── 8828391177b2ca4be665a62d15a711fb59e99e09.nq.gz
│   ├── 89e6b63dc4bdd567dc5213a70652392242dcd994.nq.gz
│   ├── 8bb65082f40eab869bc8e582a91c05638b5d080a.nq.gz
│   ├── 95259df37dc387378c5eecb2cd901345b77a37fb.nq.gz
│   ├── 9748fb3b0617a3d820d94a23580c2a7189f0c690.nq.gz
│   ├── 98f08ad6a8474fbcc3e338436bae46663d4aa4ae.nq.gz
│   ├── 9b227e075b16726af34c545f9f11da9b2a07c22a.nq.gz
│   ├── 9c12ee45bf9b5e6c47c72b8a36833052b4b4fd40.nq.gz
│   ├── 9cc2f966cbbad35a9a02ccf29b9156c14d6ef893.nq.gz
│   ├── a041534604c5d887015dbb3d07f3afce43b45551.nq.gz
│   ├── a2e3d6de7d3634ace3dd2cff9f17e5b51c4dfb2e.nq.gz
│   ├── a35ec4e98e102471fe08f47bcbbbcad616766d33.nq.gz
│   ├── a3b9509b546065a438084e68685bc8c0ed60f5e0.nq.gz
│   ├── a3c21dc0c18d1c89f41d45b8c63eb8774c1fb7d5.nq.gz
│   ├── a4c2d6d4debfe22ea5e1b3612f90d280a4e77ccf.nq.gz
│   ├── a4fbd6ccff3ad5d563a774e010d34fc39a994cea.nq.gz
│   ├── a5752b963c5ce61726faa555ad205cbb5756103b.nq.gz
│   ├── a69f38f8f1329af1e8fba62dc7bb7313dac0f1dc.nq.gz
│   ├── a6dafcf8cd8b039530128f336ff3a42ce1fd5fec.nq.gz
│   ├── a7e1d15ef2822f7bb499ef9a333f69f61d3e4221.nq.gz
│   ├── a9772bea1f6568ee5ddb0c318a980c20204d88ce.nq.gz
│   ├── aab5a37f6e2da4e5c38658d4f62b28f8f6b4a27b.nq.gz
│   ├── ac1aa03c6818d663f37739160b9d08cb24fff192.nq.gz
│   ├── ae2ac27c019619ae1ac5f4a0243b1786de8bd56f.nq.gz
│   ├── b089b140ddff10699da1be82f12af60f76a2dda6.nq.gz
│   ├── b7f7976960c8c6a4790c68b6076c81397eea644a.nq.gz
│   ├── b82b2e4d2c2d12267a4b32aac8b93bad6d0ac579.nq.gz
│   ├── bce5734060de274336fe7178908d2a30895f4ed8.nq.gz
│   ├── bce6b54d0a82292a13f7634213841ead1e00d12b.nq.gz
│   ├── c8532d37c554222c96f75288b4197eb6f8a5d2bf.nq.gz
│   ├── c8ed7312534106ae9d82ce1d7e653b04358db55b.nq.gz
│   ├── cc64eded709c256059c058861c18bf9b79cb6288.nq.gz
│   ├── cd09e118507cce01a55876cf87f90b35e60e51ae.nq.gz
│   ├── cd3014ccac732c65cfafb333eb032450e429f95c.nq.gz
│   ├── ce5107470ddb4317841afdc08f89ff8ae236acce.nq.gz
│   ├── d480f8af9ec2f9e2e26386a4e1964f9c94d0ad1a.nq.gz
│   ├── d672b1e463cd8a45c436034c9e07d94a9114531b.nq.gz
│   ├── d955f7b0d77f82e17a2bdaa959edc6eeb3ac26a1.nq.gz
│   ├── d99e298fdddaafc6d092ec1af7cf05f138cd3c67.nq.gz
│   ├── d9f3cc80ab5286a5945c59243d0f6b512e8c05ca.nq.gz
│   ├── da037e09e1c861f30e0114a39d3f60a8757c9f4f.nq.gz
│   ├── dba29102268833c9acae1edd5a93d63c32fa4edf.nq.gz
│   ├── dcce9c78415d92e743828368230879b7c53979e6.nq.gz
│   ├── df21691c37e836d2fedf5cb40a6f9b20b17ad7f5.nq.gz
│   ├── e11b41644b112de340a59962462069267f87412c.nq.gz
│   ├── e2ff963f19f1ad42d80b7d5157517c1e4038058b.nq.gz
│   ├── e4b5e91fe632f02526936ad526713c7d6c0e69b6.nq.gz
│   ├── e5dff78c1a19ce9ebd39908bafc8d7b6af81ef48.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ea13358e40c5355008cb1050c1a79b482f34d01e.nq.gz
│   ├── ea1472ec1f38b2d1410951194a02f8fb9f1c820a.nq.gz
│   ├── ea2c61841f58e5300b796bcdd041a304c5781967.nq.gz
│   ├── ec40e3b1e53ccea48bc0418bec8558b668b9daa0.nq.gz
│   ├── ee6352ad83a79ca97e669429941a9e10a24bfb35.nq.gz
│   ├── ef1b8c68134b9bcf21f69eac2b97f57c7fabf832.nq.gz
│   ├── f288702d2fa16d3cdf0035b15a9fcbc552cd88e7.nq.gz
│   ├── f3032e939143a2ee092869a3d804bf8663437c4b.nq.gz
│   ├── f60ee6782280b043f8014305cffb9b0d2c4d184d.nq.gz
│   ├── f7a4a6744884666baa3b266e19610b1ca4d17401.nq.gz
│   ├── f7c4f00f37692cc723994459d6a5fe351957f1fc.nq.gz
│   ├── f8e28c7e4697b2a064d69a779dd1f5450240e2f9.nq.gz
│   ├── fa6da2b1661b051d14903162bbf785f5fbd805e7.nq.gz
│   ├── fb538271b8494d9233811b19d7b42073f20af647.nq.gz
│   ├── fc0346e58090e00cd3f58041cfc8a4a2c26801ec.nq.gz
│   └── fc57dea6b581e883b5cf76f3b6df8f30a52f086a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── b4f8cb77d8d92b8ebfa5a60acd5be1bd8a9b69f7.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 149 files
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

[ansible-collections/ansible.drill](https://github.com/ansible-collections/ansible.drill)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
