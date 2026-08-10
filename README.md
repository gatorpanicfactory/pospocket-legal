# PosPocket — support & privacy

iPhoneアプリ「PosPocket（ポスポケット）」のサポートページとプライバシーポリシーを公開するためのリポジトリです。

- サポート: https://gatorpanicfactory.github.io/pospocket-legal/
- プライバシーポリシー: https://gatorpanicfactory.github.io/pospocket-legal/privacy.html

## 更新方法

各HTMLは手書きせず、原本のMarkdownから生成しています。

- 原本: `ProductWork/docs/pospocket/` の `support.md`、`privacy_policy.md`
- 生成: `ProductWork/tools/build_pospocket_pages.py` を実行すると、このディレクトリのHTMLが上書きされる

原本を編集 → スクリプト実行 → ここでコミットしてpush、の順で更新してください。
`.nojekyll` は Jekyll のビルドを介さず、置いたHTMLをそのまま配信させるために必要です。
