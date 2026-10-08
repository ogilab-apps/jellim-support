# jellim-support

Jellim の公開ページ（プライバシーポリシー・利用規約・サポート）。

**このフォルダの中身が、そのまま `ogilab-apps/jellim-support` リポジトリのルートになる。**
`tokiip-support` と同じ構成・同じレイアウトに揃えてある。

| ファイル | 公開URL | 用途 |
|---|---|---|
| `index.html` | `https://ogilab-apps.github.io/jellim-support/` | Support URL（ASC必須） |
| `privacy.html` | `.../privacy.html` | Privacy Policy URL（ASC必須・日本語） |
| `terms.html` | `.../terms.html` | 利用規約（日本語） |
| `privacy-en.html` | `.../privacy-en.html` | Privacy Policy（英語） |
| `terms-en.html` | `.../terms-en.html` | Terms of Use（英語） |

アプリからのリンクは `src/features/plus/config.ts` の `LEGAL_URLS` に定義している（端末の言語で日本語版と英語版を出し分ける）。
**URLを変えるときは両方を直す。**

## 公開の手順

1. `ogilab-apps` に `jellim-support` リポジトリを作る（Public）
2. このフォルダの中身をリポジトリのルートへ置いて push
3. Settings → Pages → Source を `main` ブランチのルートにする
4. 上表のURLが表示されることを確認する

## 問い合わせ先

`ogilab.apps@gmail.com`。ogilab 共通アドレスを使う。アプリ専用のアドレスは作らない。

## 更新のたびに確認すること

- 価格（年額 ¥600 / 買い切り ¥1,500。2026-10-06 制定）が App Store Connect の設定と一致しているか
- 無料の範囲（きろくは今週とはじめの月・コップはタンブラーとトール・見た目はライト・効果音はあわ・とぷん・ぷるん）が実装と一致しているか
- 医療的な表現を使わない（診断・治療・予防をうたわない。「ストレスを目に見える形で記録する」にとどめる）
- 共有の画像に入るもの（コップ・%・色の内訳・選んだ場合は種類の名前）が実装と一致しているか
