# なぜ今RSA暗号は安全か？ 量子コンピュータでどうやって破るのか

**RSA × Shor — 理論とハンズオンで理解する教材**

「量子コンピュータがRSA暗号を破る」とは、具体的にどういう意味か。
本教材では、Shorのアルゴリズムによる素因数分解を理論とハンズオンの両面から解説し、現状の技術的制約までを含めて体系的に理解できるようにまとめています。

## この教材で分かること

- RSA暗号はどのような仕組みで動いているのか
- なぜ古典コンピュータでは破れないのか
- 量子コンピュータはどのような手順でRSAを破るのか（Shorのアルゴリズム）
- 古典と比べてどれくらい速いのか
- なぜ今の量子コンピュータではまだ破れないのか

## 教材の構成

| 部 | 内容 |
|----|------|
| 第1部（PDF） | RSAの安全性とRSA暗号の原理 |
| 第2部（PDF） | Shorのアルゴリズム |
| 第3部（ハンズオン） | Qiskitで回路を組んで素因数分解を体験 |

## 入手方法

- **PDF（理論編）**: [最新版をダウンロード](../../releases/latest)
- **ハンズオン（実行編）**: [`notebooks/`](notebooks/)
- **正本・更新履歴・正誤表**: [peanuts-chicken-little.com/research/rsa-shor](https://peanuts-chicken-little.com/research/rsa-shor)

## 引用方法

このリポジトリの root に [`CITATION.cff`](CITATION.cff) を置いています。
GitHub上で「Cite this repository」からBibTeX等の形式で取得できます。

## フィードバック

本教材へのフィードバックは [Issues](../../issues) または [Discussions](../../discussions) でお寄せください。

> **注意**: Pull Requestは受け付けていません。誤植・技術的誤り・出典ミス・実行環境の問題は、Issueテンプレートから報告をお願いします。

## ライセンス

本教材の文章・図表は [CC BY-NC-ND 4.0](LICENSE) の下で提供しています。
コードセル部分は [MIT License](NOTICE.md) です。
詳細は各ファイルを参照してください。

## 著者

甘利 丈慈 (Jorge Amari)
