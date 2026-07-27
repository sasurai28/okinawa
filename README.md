# 沖縄家族旅行しおり 2026夏 PWA

辻家の宮古島＋沖縄本島旅行（2026/8/4〜8/17・13泊14日）のインタラクティブしおり。
四国旅行しおり（sasurai28/shikoku）と同じ構成。

## 使い方
- URL: https://sasurai28.github.io/okinawa/
- iPhone: Safari → 共有 → 「ホーム画面に追加」
- 初回アクセスでオフラインキャッシュされる

## タブ
予定（タイムライン＋地図リンク）／ごはん／持ち物（チェックリスト）／メモ／緊急連絡先

## 更新方法
index.html を編集して git push。sw.js の CACHE_NAME を v1→v2 に上げるとユーザー側キャッシュも更新。

## メモ・写真の家族同期について
四国版の Firebase は期限切れのため FB_DB_URL="" で同期オフにしてある（端末内保存では動く）。
復活させる場合は Firebase Realtime Database を新規作成して index.html 内の FB_DB_URL に入れる。
