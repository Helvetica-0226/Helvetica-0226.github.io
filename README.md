# Nichijoism (helvetica-0226.github.io)

日常、実存主義、ニヒリズム、そしてシュルレアリスムが交差する私の個人ブログ・思考整理ノートです。

## サイトURL
- https://helvetica-0226.github.io/

## 技術スタック / 仕様
- **SSG:** Jekyll
- **Hosting:** GitHub Pages
- **Theme:** (もしテーマ名があれば記載、なければ default)
- **Features:** giscus (コメント・フィードバック機能), MathJax (LaTeX数式表示)

## 記事の投稿手順（未来の自分へのメモ）
1. パソコンのターミナルで最新状態にする: `git pull origin main`
2. `_posts` フォルダ内に `YYYY-MM-DD-title.md` の形式でファイルを作成
3. 記事の先頭（フロントマター）に以下を記述：
   ```yaml
   ---
   layout: post
   title: "記事のタイトル"
   date: YYYY-MM-DD 12:00:00 +0900
   ---
   
