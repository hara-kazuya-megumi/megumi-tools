# megumi-tools

めぐみ事務所の社内向けツールをGitHub Pagesで公開するためのリポジトリ。

## 構成

- `index.html` … トップページ（ツール一覧）
- `<ツール名>/index.html` … 各ツール本体（単一HTML・オフライン動作）

## 新しいツールを追加する手順

1. このリポジトリ直下に新しいフォルダを作り、その中に `index.html` としてツールを置く。
2. ルートの `index.html` の一覧に、そのツールへのリンクカードを1件追加する。
3. `git add` → `git commit` → `git push` すると、数分でPagesに反映される。

## 公開URL

- トップ: https://hara-kazuya-megumi.github.io/megumi-tools/
- 労働条件通知書・雇用契約書 作成ツール: https://hara-kazuya-megumi.github.io/megumi-tools/roudou-tsuchisho/

## 注意

公開リポジトリのため、ここに置いたファイルのソースコードは誰でも閲覧できます。顧客の個人情報や機密情報は含めないこと（各ツールは入力データをブラウザ内で処理し、外部送信しない設計を前提とする）。
