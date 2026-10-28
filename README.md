# ダイエットサポート（静的Webサイト）

## 含まれる機能
- 日別の体重・歩数・摂取カロリー記録
- 厚生労働省 e-ヘルスネット掲載の日本人基礎代謝基準値を使った推定（18歳以上）
- 歩数からの歩行消費カロリー概算、簡易カロリー収支
- 直近7日間の表・グラフ・条件分岐式レポート
- シンプル/kawaiiテーマ、アクセントカラー選択
- 記録はブラウザの localStorage に保存（アカウント間・端末間では同期しません）

## GitHub Pages で公開する手順
1. GitHub アカウントにサインイン（アカウントがなければ作成）。
2. 右上の `+` → `New repository` を選ぶ。
3. Repository name に `diet-support` と入力し、`Public` を選択して作成。
4. リポジトリ画面の `Add file` → `Upload files` を選択。
5. このZIPを展開し、中の `index.html` と `README.md` をアップロードして `Commit changes`。
6. リポジトリの `Settings` → `Pages` を開く。
7. `Build and deployment` の `Source` を `Deploy from a branch` にし、Branch を `main`、フォルダを `/(root)` にして `Save`。
8. 1〜10分ほど待ち、同じ `Settings` → `Pages` に表示される公開URLを開く。通常は `https://GitHubユーザー名.github.io/diet-support/` の形式です。

公開URLはリポジトリの `Settings → Pages` に表示される実際のURLを使ってください。ユーザー名からURLを推測して共有しないでください。

## 注意
- GitHub Pages は公開サイトです。個人情報をコードや公開ファイルに入れないでください。
- 収支式は「摂取 −（基礎代謝推定値＋歩行消費推定値）」という簡易指標で、総消費エネルギーや体重変化を正確に示すものではありません。
- 年齢・性別・体重に基づく基礎代謝推定値は目安です。公的資料の基準値は個人の測定値ではありません。
- 記録はブラウザ内に保存されます。別端末や別ブラウザには同期されません。
- 公的参考資料：
  - https://kennet.mhlw.go.jp/information/information/food/e-07-002
  - https://kennet.mhlw.go.jp/information/information/exercise/s-02-003
  - https://kennet.mhlw.go.jp/information/information/food/e-02-001
