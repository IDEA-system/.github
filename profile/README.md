# 🏢 株式会社IDEA システム課 GitHub Organization

ここは株式会社IDEAのシステム・インフラ管理、および各クリニック向けアプリケーション開発を行うための公式GitHub Organizationです。
新たにプロジェクトへ参加した社内エンジニア、および外部パートナー様は、作業を開始する前に必ず以下の運用ルールをご一読ください。

---

## 📌 1. 権限・リポジトリ作成ルール

ガバナンスとセキュリティ維持のため、以下のルールを設けています。

- **リポジトリの新規作成**
  一般メンバー権限でのリポジトリ作成は制限されています。新規作成が必要な場合は、システム課管理者（平山）まで作成依頼を行ってください。
- **公開範囲の設定**
  原則として、作成する全てのリポジトリは **Private（非公開）** とします。Public（公開）設定が必要な場合は事前の申請・承認が必要です。

## 🏷 2. リポジトリの命名規則

用途がひと目で分かるよう、以下の命名規則に従ってください。
すべて「半角小文字の英数字」と「ハイフン（`-`）」を使用します。

- 形式: `[プロジェクト名]-[役割]`
- 命名例:
  - `agasite-frontend` （AGAサイトのフロント側）
  - `agasite-api` （AGAサイトのバックエンド側）
  - `network-redundancy-config` （ネットワーク系の設定ファイル等）

## 🌿 3. ブランチと開発の基本ルール

弊社では、基本的に「GitHub Flow」を採用しています。

1. **`main` ブランチの保護**
   `main` ブランチは常に本番環境と同じ（安定して動く）状態を保ちます。`main` への **直接のPushは禁止** されています。
2. **作業ブランチの作成**
   機能追加や修正を行う際は、必ず最新の `main` から作業用のブランチを切ってください。
   （例: `feature/login-page`, `fix/form-bug` など）
3. **Pull Request（PR）の必須化**
   開発が終わったら `main` に対して Pull Request を作成し、必ず1名以上のレビュー（Approve）をもらってからマージしてください。

## 🚀 4. デプロイ（本番反映）について

プロジェクトによりますが、基本的に **GitHub Actions** などを利用した自動デプロイ（CI/CD）環境を構築しています。
本番環境への反映タイミング（mainマージ時など）は、各リポジトリ個別の `README.md` を確認してください。

## 💬 5. お問い合わせ・連絡先

GitHubのアカウント追加・権限変更依頼、またはインフラ設定に関するご相談は以下までご連絡ください。

- **担当窓口**: 経営企画部 システム課 平山
- **社内連絡先**: 社内チャットの `#システム課_依頼` チャンネル、またはメンションにて

---


<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
