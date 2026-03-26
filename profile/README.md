# 🏢 株式会社IDEA システム課 GitHub 運用ルール

ここは株式会社IDEAのシステム・インフラ管理、および各クリニック向けアプリケーション開発を行うための公式GitHub Organizationです。
新たにプロジェクトへ参加した社内エンジニア、および外部パートナー様は、作業を開始する前に必ず以下の運用ルールをご一読ください。

---

## 📌 1. 権限・リポジトリ作成ルール

ガバナンスとセキュリティ維持のため、以下のルールを設けています。

- **リポジトリの新規作成**
  一般メンバー権限でのリポジトリ作成は制限されています。新規作成が必要な場合は、システム課管理者（村木、平山）まで作成依頼を行ってください。
- **公開範囲の設定**
  原則として、作成する全てのリポジトリは **Private（非公開）** とします。

## 🔒 2. セキュリティ・機密情報の取り扱い（重要）

**パスワードやAPIキーなどの機密情報を、絶対にGitHub上にPushしないでください。**

- **`.env` ファイルでの管理**
  システム接続用のID、パスワード、アクセスキー等の管理情報は、ソースコードに直接書き込まず、必ず環境変数（`.env` ファイル等）として分離して管理してください。
- **`.gitignore` の徹底**
  `.env` ファイルや、ローカルの開発環境固有のパスワードが記載されたファイルは、必ずリポジトリ作成時に `.gitignore` に登録し、GitHubへのアップロード対象から除外してください。

---


<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
