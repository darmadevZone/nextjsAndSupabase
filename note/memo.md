# Supabaseについて

- BaaS
- RDB
- RLS(row level security)
- SQL

## firebaseとの違い
- NoSQL(データアクセスが`Collection` ->> `Document`の形でデータを保持する)
  - firebase
  - Dynamo DB
  - Mongo DB


## Supabaseの使い方
- Table作成
- RLSの設定
- リレーション
- CASCADE DELETEの設定
- Next.js + Supabaseの連携で **(認証,CRUD)**

## サブコンテンツ
- **Web vitals(TTFB,FCP,LCP)の理解**
  - TTFB,FCPが`html`のときは同じ応答時間になる

|                  TTFB                  |             FCP              |           LCP            |
| :------------------------------------: | :--------------------------: | :----------------------: |
| サーバー初期応答時間(`1bit`を取得する) | 視覚コンテンツの初期表示時間 | 最大コンテンツの表示時間 |


- SSG,SSR,CSF+SSGとWeb vitalsの関係性と測定
- ISRのレンダリング抑制をするためのOn-demand ISRの活用
- 静的配信初回アクセスの理解`Edge CDN`(X-Vercel-Cache:MISS and HIT)
- Middlewareの使い方
- Edge Function, Serverless FunctionのAPI応答時間の比較
