# arx-isv-guide — ARX OS アプリ移植リファレンスキット

[English](README.md) | [繁體中文](README.zh-TW.md) | **日本語**

ISV（独立系ソフトウェアベンダー）が ARX OS アプリを開発・移植するためのリファレンスキットです。実行できるサンプルアプリ、移植ドキュメント、AI エージェント向けの skills が含まれています。

> このリポジトリにはドキュメントのみを置いています。キットは [Releases](https://github.com/ardge-cookbook/arx-isv-guide/releases) からダウンロードしてください。

## ダウンロード

| バージョン | ファイル |
|---|---|
| 最新版 | [Releases › Latest](https://github.com/ardge-cookbook/arx-isv-guide/releases/latest) |
| v0.6.7 | [arx-isv-guide-v0.6.7.zip](https://github.com/ardge-cookbook/arx-isv-guide/releases/download/v0.6.7/arx-isv-guide-v0.6.7.zip) |

同じリリースに添付された `SHA256SUMS.txt` で、ファイルが完全かどうかを確認できます。

```bash
sha256sum -c SHA256SUMS.txt
```

## キットの内容

| パス | 用途 |
|---|---|
| `apps/` | 実行できる最小サンプル、リファレンスアプリ、サードパーティアプリの移植例 |
| `docs/` | プラットフォームの機能、移植方法、template のフィールドリファレンス |
| `.claude/skills/` | ARX OS アプリのビルド・検証・操作に使う AI エージェント向け skills |

解凍したら、まずキット直下の `README.md` を読み、アプリの状況に合った進め方（ゼロから作る、docker-compose から移植する、サードパーティアプリを移植する）を選んでください。キットのドキュメントは繁体字中国語で書かれています。

## ドキュメント

- [ARX OS 開発ガイド](https://developer.ardge.com/en/guide/overview)：バージョン管理された公式ガイドです。内容はこちらを優先してください（日本語版はないため英語版にリンクしています）
- [ARX ISV Cookbook](https://arx-isv-cookbook.pages.dev/ja/)：実践的なサンプルと経験

## バージョン

各バージョンの違いは [CHANGELOG](CHANGELOG.md) を参照してください。開発ガイドで提供されている v0.6.4（`arx-isv-skills-v0.6.4.zip`）は skills のみです。このリポジトリでは v0.6.7 からキット全体を提供します。

## 質問とフィードバック

このリポジトリでは Issues を受け付けていません。ARDGE の窓口にお問い合わせください。

## ライセンス

Copyright © 2026 ARDGE. All rights reserved. 利用範囲は [LICENSE](LICENSE) を参照してください。
