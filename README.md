# PHANTOM — ゲームツールストア

React + Vite で構築した、日本語対応のデジタル製品カタログサイトです。

## 起動

1. ZIPを解凍します。ZIP直下に `package.json` が入っています。
2. VS Codeで `package.json` のあるフォルダを開きます。
3. PowerShellで以下を実行します。

```powershell
npm.cmd install
npm.cmd run dev
```

4. ターミナルに表示されるURL（通常 http://localhost:5173/）を開きます。

## 機能

- 製品検索・カテゴリフィルター
- 製品詳細モーダル
- カートへの追加・数量調整・削除
- `localStorage` によるカート情報保持
- FAQの開閉
- スマートフォン対応

## 運用上の注意

- **オンライン決済および製品配布機能はありません。** チェックアウトは無効化しています。
- 製品名・説明・価格は初期掲載内容です。実際の提供条件・提供可否は別途確認してください。
- 実際に公開する際は運営者情報、利用規約、プライバシーポリシー、サポート窓口などを適切に整備してください。
- ゲームの利用規約・現地法令に従ってください。

## 商品情報の編集

`src/App.jsx` の `PRODUCTS` 配列を編集してください。


## GitHub Pages 公開
1. GitHubでリポジトリ `phantom-store` を作成 (main ブランチ)。
2. このフォルダ内のファイルを、`.github` フォルダを含めてリポジトリ直下にアップロード。
3. Settings → Pages → Build and deployment → Source: GitHub Actions に設定。
4. Actions の Deploy to GitHub Pages が成功すると公開。
5. URLは `https://ユーザー名.github.io/phantom-store/`（リポジトリ名が異なる場合はその名前）。
