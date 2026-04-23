# うわさのゲームセンター

U.wasano Shisha Bar presents

## フォルダ構成
```
uwasa-game-center/
├── index.html                   ← ランチャー（これをブラウザで開く）
└── games/
    └── uwasa-brothers/
        └── index.html           ← UWASA BROTHERS ゲーム本体
```

## GitHub Pages での公開方法
1. このフォルダの中身をGitHubリポジトリにアップロード
2. Settings → Pages → Deploy from branch (main / root)
3. 公開URL: `https://ユーザー名.github.io/uwasa-game-center/`

## Supabase 設定
`index.html` と `games/uwasa-brothers/index.html` の両方に：
```javascript
const SUPABASE_URL = 'https://xxxxx.supabase.co';
const SUPABASE_KEY = 'eyJxxxxxx...';
```
を入力してください。

## Supabase SQL
```sql
create table scores (
  id uuid default gen_random_uuid() primary key,
  player_name text not null,
  game text default 'uwasa_brothers',
  coins integer default 0,
  score integer default 0,
  distance real default 0,
  stage integer default 0,
  powers_collected integer default 0,
  created_at timestamptz default now()
);
alter table scores enable row level security;
create policy "read" on scores for select to anon using (true);
create policy "insert" on scores for insert to anon with check (true);
```
