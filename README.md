# XECTOR1 KPI Dashboard

黒ベース・ネオングリーンのKPI管理ダッシュボード。

## Vercelへのデプロイ手順

### 1. GitHubにプッシュ

```bash
cd xector1-dashboard
git init
git add .
git commit -m "init: XECTOR1 KPI dashboard"
gh repo create xector1-kpi --public --source=. --push
```

### 2. Vercelでデプロイ

1. https://vercel.com にログイン
2. "Add New Project" → GitHubのリポジトリを選択
3. Framework Preset: **Other**
4. そのまま "Deploy" をクリック

デプロイ完了で固定URLが発行される。

## データについて

- ブラウザのlocalStorageに保存
- PC・スマホそれぞれのブラウザで独立して保存される
- スマホのホーム画面に追加（PWA対応済み）すると毎日開きやすい
