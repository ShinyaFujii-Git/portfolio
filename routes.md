# ルーティング一覧

## 1. 認証関連ルーティング

* **ログイン**
    * `GET /login`: ログインページを表示
    * `POST /login`: ログイン処理を実行
* **ユーザー登録**
    * `GET /register`: ユーザー登録ページを表示
    * `POST /register`: ユーザー登録処理を実行
* **パスワードリセット**
    * `GET /reset-password`: パスワードリセットページを表示
    * `POST /reset-password`: パスワードリセット処理を実行

## 2. ダッシュボード関連ルーティング

* **ダッシュボード**
    * `GET /dashboard`: ダッシュボードページを表示

## 3. 工数関連ルーティング

* **工数入力**
    * `GET /timesheets/new`: 新しい工数入力ページを表示
    * `POST /timesheets`: 新しい工数を保存
* **工数一覧**
    * `GET /timesheets`: 工数一覧ページを表示
* **工数編集**
    * `GET /timesheets/:id/edit`: 特定の工数編集ページを表示
    * `PUT /timesheets/:id`: 特定の工数を更新
* **工数削除**
    * `DELETE /timesheets/:id`: 特定の工数を削除

## 4. 管理者関連ルーティング

* **ユーザー管理**
    * `GET /admin/users`: 全ユーザーの一覧ページを表示
    * `POST /admin/users/bulk`: ユーザーの一括登録処理を実行
* **データ出力**
    * `GET /admin/export`: データ出力ページを表示
    * `POST /admin/export`: データ出力処理を実行

## 5. 設定関連ルーティング

* **プロフィール設定**
    * `GET /settings/profile`: プロフィール設定ページを表示
    * `PUT /settings/profile`: プロフィール情報を更新

## 6. その他のルーティング

* **ホーム**
    * `GET /`: ホームページを表示
* **ログアウト**
    * `POST /logout`: ログアウト処理を実行