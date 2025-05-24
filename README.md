# README.md

# AI Browser Games

---

## 概要 (Overview)

このプロジェクトは、**最新の AI 技術を駆使して作成されたシンプルなブラウザゲーム群**をまとめたギャラリーサイトです。各ゲームは異なる AI ツールを組み合わせることで開発され、その可能性を探求しています。このリポジトリは、AI を用いたゲーム開発の実験と、それらをまとめて紹介するインタラクティブなポートフォリオとして機能します。

This project is a gallery site compiling **simple browser games created using cutting-edge AI technologies**. Each game was developed by leveraging various AI tools in combination, exploring their potential in game creation. This repository serves as an experimental platform for AI-driven game development and an interactive portfolio to showcase these creations.

---

## ゲーム一覧 (Games)

### 1. Floating Letters

- **概要 (Description):** AI が生成する文字の海を泳ぎ、言葉のインスピレーションを探求するシューティング型タイピングゲームです。
- **AI 開発 (AI Development):**
  - **Claude 4:** オシャレな UI の作成
  - **Trae:** ゲームロジックの改良
  - **Gemini:** UI とロジックの統合

### 2. AI Nen Clash (旧称: Leave Koma)

- **概要 (Description):** 大人気漫画『ハンターハンター』のギド対ゴン戦を AI の思考で再現した対戦ゲームです。相手の AI の思考を読み、勝利への一手を導き出してください。
- **AI 開発 (AI Development):**
  - **DeepSeek & ChatGPT:** 既存の`ballgame`をベースに、複雑な対戦ロジックとゲームシステムへの改造に活用。

### 3. Love Phantom

- **概要 (Description):** Claude 4 に「ラブファントム」というタイトルからイメージする創造的なゲームの作成を指示し、一撃で生み出されたゲームです。タイトルからは想像できないかもしれませんが、耽溺性があり、一度プレイすると引き込まれる魅力があります。
- **AI 開発 (AI Development):**
  - **Claude 4:** プロンプトからの直接的なゲーム生成（「一撃シリーズ」）

### 4. Ball Game

- **概要 (Description):** Claude 4 に「みんなが簡単に遊べて面白い滑らかに動くゲーム」というプロンプトで、一撃で作成されたボールゲームです。シンプルながらも洗練されたデザインと、直感的に楽しめる操作性が特徴です。
- **AI 開発 (AI Development):**
  - **Claude 4:** プロンプトからの直接的なゲーム生成（「一撃シリーズ」）

---

## 技術スタック (Tech Stack)

- **HTML5**
- **CSS3 (Flexbox & CSS Grid for responsiveness)**
- **JavaScript (for game logic within each game file)**

---

## 開発 (Development)

このプロジェクトは、様々な AI モデルをゲーム開発の各段階で活用するという実験的なアプローチで進められました。UI デザインの提案、ゲームロジックの改善、既存コードの改造、そしてプロンプトからの直接的なゲーム生成まで、AI が開発プロセスに深く関与しています。

This project adopted an experimental approach, leveraging various AI models at different stages of game development. From UI design suggestions and game logic improvements to modifying existing code and direct game generation from prompts, AI played a significant role throughout the development process.

---

## Vercel でのデプロイ (Deployment on Vercel)

このプロジェクトは静的な HTML ファイルで構成されているため、**Vercel**のようなホスティングサービスと簡単に連携してデプロイすることができます。以下の手順で、あなた自身の Vercel アカウントにデプロイし、オンラインでゲームをプレイできます。

This project, being composed of static HTML files, can be easily deployed by linking it with hosting services like **Vercel**. Follow the steps below to deploy it to your own Vercel account and play the games online.

### デプロイ手順 (Deployment Steps):

1.  **GitHub リポジトリをフォークまたはクローンする (Fork or Clone the GitHub Repository):**
    まず、このリポジトリをあなたの GitHub アカウントにフォークするか、ローカルにクローンします。
    First, fork this repository to your GitHub account or clone it locally.

2.  **Vercel アカウントにログインする (Log in to your Vercel Account):**
    Vercel のウェブサイト ([https://vercel.com/](https://vercel.com/)) にアクセスし、GitHub アカウントでログインします。
    Go to the Vercel website ([https://vercel.com/](https://vercel.com/)) and log in with your GitHub account.

3.  **新しいプロジェクトをインポートする (Import a New Project):**
    ダッシュボードで「Add New...」ボタンをクリックし、「Project」を選択します。
    In the dashboard, click the "Add New..." button and select "Project".

4.  **GitHub リポジトリを連携する (Connect your GitHub Repository):**
    インポートしたい GitHub リポジトリ（このプロジェクトのリポジトリ）を選択し、「Import」をクリックします。
    Select the GitHub repository you want to import (this project's repository) and click "Import".

5.  **デプロイ設定 (Configure Deployment Settings):**
    特別な設定は不要です。デフォルトのままで「Deploy」をクリックします。Vercel が自動的に HTML、CSS、JavaScript ファイルを検出し、デプロイを開始します。
    No special configurations are needed. Simply click "Deploy" with the default settings. Vercel will automatically detect your HTML, CSS, and JavaScript files and start the deployment.

6.  **デプロイされた URL にアクセスする (Access the Deployed URL):**
    デプロイが完了すると、Vercel が生成した URL が提供されます。この URL にアクセスすると、オンラインでゲームギャラリーを楽しむことができます。
    Once the deployment is complete, Vercel will provide a generated URL. You can access this URL to enjoy the game gallery online.

---

## 貢献 (Contributing)

バグ報告や改善提案など、どのような貢献も歓迎します。Issue を立てるか、Pull Request を送ってください。

Contributions are welcome, whether it's bug reports or suggestions for improvement. Please feel free to open an issue or submit a pull request.

---

この`README.md`ファイルが、あなたの GitHub プロジェクトを素晴らしい形で表現する一助となれば幸いです！
