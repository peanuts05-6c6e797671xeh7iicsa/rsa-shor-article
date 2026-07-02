# なぜ今RSA暗号は安全か？ 量子コンピュータでどうやって破るのか

**RSA × Shor — 理論とハンズオンで理解する教材**

「量子コンピュータがRSA暗号を破る」とは、具体的にどういう意味か。
本教材では、Shorのアルゴリズムによる素因数分解を理論とハンズオンの両面から解説し、現状の技術的制約までを含めて体系的に理解できるようにまとめています。

> 本教材は個人が無償・非営利で公開している技術解説です。営利目的の販売や広告を含みません。

## この教材で分かること

- RSA暗号はどのような仕組みで動いているのか
- なぜ古典コンピュータでは破れないのか
- 量子コンピュータはどのような手順でRSAを破るのか（Shorのアルゴリズム）
- 古典と比べてどれくらい速いのか
- なぜ今の量子コンピュータではまだ破れないのか

## 教材の構成

| 対象 | 内容 | 前提知識 |
|------|------|----------|
| 第2章（PDF） | RSAの安全性とRSA暗号の原理 | 高校数学（合同式・指数）。必要な整数論は本文で導入 |
| 第3章（PDF） | Shorのアルゴリズム | 線形代数（固有値問題を含む）、複素指数関数 |
| 付属ハンズオン | Qiskitで回路を組んで素因数分解を体験 | Python基礎、Qiskit初歩（量子レジスタ・測定・ビット順・シミュレータの感覚） |

## 入手方法

- **PDF（理論編）**: [最新版をダウンロード](../../releases/latest)
- **ハンズオン（実行編）**: [`notebooks/`](notebooks/) または [Google Colabで開く](https://colab.research.google.com/github/peanuts05-6c6e797671xeh7iicsa/rsa-shor-article/blob/main/notebooks/rsa-shor-handson-ja-latest.ipynb)
- **正本・更新履歴・正誤表**: [peanuts-chicken-little.com/research/rsa-shor](https://peanuts-chicken-little.com/research/rsa-shor/?utm_source=github&utm_medium=repo&utm_campaign=rsa-shor-v1)

## 対象読者

- 量子コンピュータの応用に興味がある方
- セキュリティエンジニアとしてPQC移行を検討している方
- 物理・情報系の学生でQPEやQFTに取り組みたい方
- 暗号の数学的基盤を理解したいエンジニア

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

---

*本教材の数値・見積り・ロードマップは執筆時点の公開文献に基づいています。量子コンピューティングは急速に発展する分野であり、最新の状況については各参考文献の原典を確認してください。*
