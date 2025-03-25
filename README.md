# Cursor で Git の利用

## 背景

「Cursor 完全入門」という本を購入し、Cursor 上で簡単なモックの作成などしかしていなかったが Git の利用という章があったので実践する

## 準備で実施した内容

- Git のアップグレード
- Github ログイン
- ローカルリポジトリ準備
  - ローカルリポジトリ用のフォルダ作成
  - Cursor でワークスペースのフォルダとして開く
  - フォルダの Git 初期化 ※フォルダ初期化の際にワークスペースのフォルダ全てを Git 初期化してしまう？

## ローカルリポジトリフォルダのファイル操作

- ファイル作成
- 「+」アイコンでステージ
- コミットメッセージ入力してコミット

## コミットメッセージを生成してもらう ①

- 「+」アイコンでステージ
- コミットメッセージの右側のアイコン選択
- コミットメッセージ修正してコミット

## コミットメッセージを生成してもらう ②

- chat で@Symbol 機能で「Git」>「Commit(Diff of Working State)を選択」※コード生成されて Github との連携を求められたので対応
- 「@Commit(Diff of Working State) 現在の変更に対するコミットメッセージを生成して」と入力

## コミット破棄用

変更をなかったことにしたい

- 「ソース管理」パネルの三点リーダーを選択
- 「コミット」>「前回のコミットを元に戻す」を選択
- コミットが破棄されステージに戻る

## リモートリポジトリのクローン

- 「エクスプローラー」パネルを選択
- 「リポジトリの複製」を選択
- 「Githubから複製」を選択
- 対象のリポジトリを選択
- PC内のリポジトリを作成するフォルダを選択
- 「開く」か「新しいウィンドウで開く」か「ワークスペエースに追加」を選択　※クローンは何度も行う必要はなく、今後はローカルリポジトリで作業

## コンフリク

## リモートリポジトリからプル

- Cursorのステータスバーで更新アイコンの表示確認
- 更新アイコンをクリック
- コミットが増えていることを確認
