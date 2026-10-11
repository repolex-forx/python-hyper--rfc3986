# Repolex Knowledge Graph of python-hyper/rfc3986

RDF knowledge graph data for [python-hyper/rfc3986](https://github.com/python-hyper/rfc3986), parsed by [repolex](https://repolex.ai).

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
rlex download python-hyper/rfc3986
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3bd3832b72eb981d080514a8192046e3177263be
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 3bd3832b72eb981d080514a8192046e3177263be
│           └── chunk-001.nq.gz
├── blob
│   ├── 06ed84b882942fce28f145fa1dc12f729f9e3c90.nq.gz
│   ├── 09b03b42f8536bfe114d209dc2a59fc1aa6ac66d.nq.gz
│   ├── 09d8e2d5268b7cc0a4b374400a3f5c8583970d96.nq.gz
│   ├── 135af29b11e49082e140963eab7b6f289f6833f3.nq.gz
│   ├── 163800db7dacc74734615c5f7af4d021e13a87c5.nq.gz
│   ├── 18e31d8e0686eec53a7680bbc3e42a9bb022bb37.nq.gz
│   ├── 205221e981a14819bcc45693f2a2620debf179c9.nq.gz
│   ├── 21b626343b5d78058b65792961a3231c0efd3d98.nq.gz
│   ├── 237bf72d5fe4293365ced904b48fd363e0813772.nq.gz
│   ├── 271c32142211db530b190fa867dd0cb300702431.nq.gz
│   ├── 28de355e4ca79f7dc4bb0c6744cd172be63f0e3a.nq.gz
│   ├── 2bab3a1ffa834811cbe292ac4147d7225a828fe8.nq.gz
│   ├── 330c5c52854a12fe215297409209d310ac66eb4b.nq.gz
│   ├── 340511c638cafc30e4ecaa56dd516f89c2f06083.nq.gz
│   ├── 36d9f2d326170bc647691de428f4160936a408b8.nq.gz
│   ├── 385ca67d8a00023515b6d1c54ed2a5e835528153.nq.gz
│   ├── 4706e44149cef3e16047147251fbc89fc1b9f376.nq.gz
│   ├── 4ae383c587de1c26a12c2f26267175b895cd0044.nq.gz
│   ├── 4b5f564a99fb89e5dbee8eef7193dd88884d30b1.nq.gz
│   ├── 4cf3d01080121d9316a72d83e1a201432e469cbd.nq.gz
│   ├── 4d28380efe1834400530cf8cc5ad27c7d2309011.nq.gz
│   ├── 54cb3c9e11e829d8cfa796cba4487a4991cc9380.nq.gz
│   ├── 551d1c6739fecbbe1b2a4c96ebcf86e7cd568198.nq.gz
│   ├── 57884483bde116cc52c5ef22d5f83bac7eb3b015.nq.gz
│   ├── 579368e8be560da1980ec36531ea9fe89e807cf5.nq.gz
│   ├── 599ac8c12950ce70c99276406853f188a3167774.nq.gz
│   ├── 5df92fd06c355a68b84e01f8b85178d0b341b146.nq.gz
│   ├── 5e4e36c88e28430ea1b9138452e6430cb290ca76.nq.gz
│   ├── 5ec39cf6fd26699899a24baa0a5b50fc108da720.nq.gz
│   ├── 646dc24c7efafbee285d0f6cc6812135f46301c4.nq.gz
│   ├── 66c12f7a9c25b81cc7be2c7353b7c5cc1dc1408c.nq.gz
│   ├── 6d635a91de811efcb74d8e4157ce847dfc632e8e.nq.gz
│   ├── 6dac5bd3ad9b2511682f26c588d386f71c2025ea.nq.gz
│   ├── 72ce24cf02822ef81cd50905c094b5c7ac958df8.nq.gz
│   ├── 73b42994021666e97cdaa6c4bafc22d7b4fa294c.nq.gz
│   ├── 77904444b1c07b4214681f8199ea467a68e5be42.nq.gz
│   ├── 79b3585237a07021908a0c239371d866b6b621a3.nq.gz
│   ├── 7ebf027e08cf31c5458f98ea0f1dcbe3a8d95d8e.nq.gz
│   ├── 8107d70aab6ff3fea01ba6075834c56eeab02603.nq.gz
│   ├── 87562ac0260a8a8d3553647a912c36fe643b0e10.nq.gz
│   ├── 889f91cb09ed28bb5dc9c49a1503cfbfcbf3c8bf.nq.gz
│   ├── 8c388fb514e00464b71dcf072100ba4a8958d581.nq.gz
│   ├── 8d28c53eaa6255114d5f8deb1c9d2e1ba6a5717a.nq.gz
│   ├── 9284f3765ec8894e9916a619a13a36827f4f9d20.nq.gz
│   ├── 96d88b3198be3885fb3207d21bf088ffb77e47b5.nq.gz
│   ├── 9a1954fc797dc2a8a59e232c15e3c7ef873dc5ca.nq.gz
│   ├── 9bda6b4fb9ad5b1f74864f9b31010899605ceebe.nq.gz
│   ├── a12ed69efba791589aa0e0fd00da4a277f10e33f.nq.gz
│   ├── a8e414ed3c7ee7edc9ccd63dc2163442d53f2dba.nq.gz
│   ├── aecbdef38c4ac5aa55ff9b97d482dcf9db8055c2.nq.gz
│   ├── afc4c0de41809220d2edc9ea5e1ad6f8a496c1e6.nq.gz
│   ├── b03b772b6ce880539c82af846ebd2eb72b10a28f.nq.gz
│   ├── b0b23509a89c116cda172563bdcfa6e49044a141.nq.gz
│   ├── b18d15816d0febe23775f85000660afcd1c8783a.nq.gz
│   ├── b5755c66ea8b6ae22a5c6ce5ab7cb21df6c0c6bb.nq.gz
│   ├── b7c6372f961bf927266313ddf5fde474d0994b9f.nq.gz
│   ├── b908cbe55cb344569d32de1dfc10ca7323828dc5.nq.gz
│   ├── b99df9ad323d702b2f34e8612a6186395686bf7b.nq.gz
│   ├── c0291c8b288143219440937052c7994f666d04f2.nq.gz
│   ├── cf0d1f53494fb67be654dbf992c94bec0cef0518.nq.gz
│   ├── d0e853b3b31a7fd54a5c3cf669b81f6781762949.nq.gz
│   ├── d1db1917f253285e31d625ab63cd7cb4bbd85d3c.nq.gz
│   ├── d68f16b26846b01e046fa1e658c0d54e0fb46544.nq.gz
│   ├── d93b69f9aa0e6b2422b374899652bce84c1e9084.nq.gz
│   ├── dab34a7349b0c6809a03a01c1dff3f8dc79e2386.nq.gz
│   ├── dacae72f61831e74395fb94e869e683f930b7013.nq.gz
│   ├── dd0e9dce4ad20b4fc366d5875529dbb01779b30a.nq.gz
│   ├── e1e6665c9fffffa956743423735fb69cdf00f50c.nq.gz
│   ├── e288754e551f3426dafc6139dc4287ae19d93cf7.nq.gz
│   ├── e3824984e4794b0469f712741212c07f503a7d9a.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e69f482a2ad4f62023bba670c275ece331f71ca6.nq.gz
│   ├── e95ecae2eb1e26fb73361f5915d2f1a878632bcf.nq.gz
│   ├── eae3ec3cbc1ad6c41847418d6d6d45463f7c58f0.nq.gz
│   ├── f2ffbaba9e1e6b5559b540237f168761f8d10e41.nq.gz
│   ├── f74bf583a95e7a5b1ee357aacd1ae00d014bb576.nq.gz
│   ├── f8f19aac5a4247e93e23725960136c751cac744b.nq.gz
│   └── fbcf9cc2c072b7ac6e9fff195ce0ce260d23f173.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 3bd3832b72eb981d080514a8192046e3177263be.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 86 files
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

[python-hyper/rfc3986](https://github.com/python-hyper/rfc3986)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
