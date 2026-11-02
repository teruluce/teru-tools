# teru-tools — 公開用ツールサイト

ツール専用の正式な保管先です。ディズニー系サイトとは別に管理します。

- 公開トップ: https://teruluce.github.io/teru-tools/
- トップのファイル: index.html
- 各機能: duckmail/、roulette/、split/、timer/、qr/、url-cleaner/、constellation/、rally/
- 共通デザイン: site.css
- 公開用SEO: 各HTML、sitemap.xml、robots.txt

旧duck-address-generatorとteruluce.github.io/toolsから、ツール本体をこのリポジトリへ集約します。旧duck-address-generatorは公開終了・リポジトリ削除対象です。teruluce.github.io/toolsの旧URLは互換転送のみを残します。

## リポジトリの役割

てる側は以下の4つに整理します。

| リポジトリ | 用途 |
| --- | --- |
| teruluce/teru-tools | このツールサイト |
| teruluce/teruluce.github.io | ディズニー系入口・About Me |
| teruluce/disney-bgs | BGS Chronicles |
| teruluce/disney-discovery | Disney Discovery |

個人用のyuuki0928git/yuuki0928git.github.ioは別枠です。

個人側をモデルにしていますが、自動同期はありません。公開URLと説明・SEOを確認して更新してください。

URLクリーナーの検証: `node url-cleaner/cleaner.test.mjs`。全体の移転記録はdocs/SITE_STRUCTURE.mdを参照してください。
