# FXトレード日記（fx.iwonderful.okinawa）

WordPress（ThemeinProgress のテーマ）から EmDash（Cloudflare Workers ＋ D1 ＋ R2）へ移したブログ。blog.delta-a.net・117fx の仕組みを流用。

- トップは新着一覧（site.ts の stickyPostId で先頭に固定する記事を指定できる）。
- 上部メニューは管理画面の「メニュー」→「top」（WordPress から取り込み）。
- 非公開（private）の記事・固定ページは EmDash では下書きになる。
- 広告・アナリティクスなし。メールでログイン（送信元 noreply@mail.delta-a.net）。
- `npm run deploy` … 公開
