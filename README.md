# .github

Yukio0315 のリポジトリに既定として継承させる community health files を置く。

GitHub がこの仕組みで配れるのは決まった種類のファイルだけで、同じ種類のファイルを持たないリポジトリにだけ効く。このリポジトリが公開でないと継承されない（[GitHub のドキュメント](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file)）。

| ファイル | 効く場所 |
| --- | --- |
| [`PULL_REQUEST_TEMPLATE.md`](PULL_REQUEST_TEMPLATE.md) | PR 作成画面の本文 |

Actions のワークフローと CODEOWNERS は継承されない。規約・検査・CI は <https://github.com/Yukio0315/common-template> が copier のテンプレートとして配る。

## 足す前に確認する

継承される種類のファイルだけを置く。それ以外を置くと、このリポジトリの名前が意味を失う。実際に使う場面が出てから足す。
