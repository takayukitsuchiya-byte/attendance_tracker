# GitHub Pages公開手順

1. Supabase SQL Editorで `supabase-schema.sql` を実行します。
2. Supabase Authentication → URL Configurationで、GitHub PagesのURLをRedirect URLに追加します。
3. このフォルダの `index.html`、`app.js`、`styles.css`、`supabase-schema.sql`、`README.md`をGitHubリポジトリへアップロードします。
4. GitHubの Settings → Pages → Deploy from a branch → `main` / `/ (root)` を選択します。
5. Supabase Authenticationのメールテンプレートや迷惑メール設定を確認します。

管理者メールは `app.js` と `supabase-schema.sql` の `takayuki.tsuchiya@gmail.com` です。変更する場合は両方を同じメールアドレスに変更してください。ブラウザで使うpublishable keyのみを含めています。サービスロールキーは配置しないでください。
