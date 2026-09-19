# プライバシーポリシー / Privacy Policy

**snsdl**（以下「本ツール」）についてのプライバシーポリシーです。
This is the privacy policy for **snsdl** (the "Tool").

最終更新 / Last updated: 2026-09-19

---

## 日本語

### 本ツールの性質

本ツールは、利用者自身のパソコン上でのみ動作するデスクトップアプリケーションです。
開発者が運営するサーバーは存在せず、利用者のデータが開発者に送信されることはありません。

### 取得・保存する情報

本ツールは、以下の情報を**利用者のパソコン内にのみ**保存します。

| 情報 | 保存場所 | 用途 |
|---|---|---|
| 各サービスの認証情報（APIキー、トークン等） | 設定ファイル `config.yaml` | 各サービスのAPIへの接続 |
| ダウンロードした画像 | 利用者が指定した保存フォルダ | 利用者自身の閲覧・保管 |
| 作品の情報（作者名、投稿URL、投稿日時、評価数、タグ） | 画像と同じフォルダ内の `.json` | 出典の記録 |
| ダウンロード履歴 | ローカルのデータベース `snsdl.sqlite3` | 重複ダウンロードの防止 |

これらはすべて利用者のパソコン内に留まります。

### 情報の送信先

本ツールが通信を行うのは、利用者が設定で有効にした各サービスの**公式API**のみです。
送信されるのは、そのAPIの利用に必要な認証情報とリクエスト内容に限られます。

本ツールは以下を**行いません**。

- 開発者のサーバーへのデータ送信（そのようなサーバーは存在しません）
- 利用状況の収集、統計、トラッキング
- 第三者へのデータ提供・販売
- 広告の配信

### Pinterest から取得する情報

Pinterest 連携を利用する場合、本ツールは利用者自身のアカウントに対して
`boards:read` および `pins:read` の権限のみを要求します。

- 利用者自身のボードおよび保存済みピンの情報の**読み取りのみ**を行います
- ピンやボードの作成・編集・削除は行いません
- 他の利用者のデータにはアクセスしません
- 取得したアクセストークンは利用者のパソコン内にのみ保存されます

### 情報の削除

本ツールが保存した情報は、利用者がいつでも削除できます。

- 画像・履歴・サムネイル: アプリ内の「完全消去」機能、または保存フォルダの削除
- 認証情報: `config.yaml` の該当項目を空にする、またはファイルの削除
- Pinterest 側の連携解除: Pinterest のアカウント設定から行えます

### 連絡先

本ツールは個人が自分のために作成したものです。
問い合わせは、本ツールの配布元に記載の方法でお願いします。

---

## English

### Nature of the Tool

snsdl is a desktop application that runs solely on the user's own computer.
There is no server operated by the developer, and no user data is transmitted
to the developer.

### Information stored

The Tool stores the following **only on the user's own computer**: credentials
for the services the user enables (API keys and tokens, in `config.yaml`),
downloaded images in a folder the user chooses, metadata about each work
(artist name, source URL, publication date, rating, tags) in `.json` files
beside those images, and a local download history (`snsdl.sqlite3`) used to
avoid downloading the same file twice.

### Where information is sent

The Tool communicates only with the official APIs of the services the user has
enabled, sending only the credentials and request parameters those APIs
require.

The Tool does **not** send data to any server operated by the developer (none
exists), collect usage statistics or telemetry, track users, share or sell
data to third parties, or serve advertisements.

### Pinterest data

When Pinterest is used, the Tool requests only the `boards:read` and
`pins:read` scopes on the user's own account. It reads the user's own boards
and saved pins; it does not create, modify or delete pins or boards, and it
does not access other users' data. Access tokens are stored only on the user's
own computer.

### Deleting information

All stored information can be removed by the user at any time: images, history
and thumbnails through the Tool's own "complete erase" function or by deleting
the output folder; credentials by clearing the relevant entries in
`config.yaml` or deleting the file. Access granted to the Tool can be revoked
from the user's Pinterest account settings.

### Contact

This Tool was written by an individual for personal use. Please use the
contact method given wherever the Tool is distributed.
