# VSCode AI 連携　拡張機能
> GminiAPIキー利用

Continue - open-source AI code agent
https://marketplace.visualstudio.com/items?itemName=Continue.continue

### 概要
Continueは、VS CodeおよびJetBrains向けのオープンソースAIコードアシスタントです。開発者は独自のAIモデル（LLM）を接続して、IDE内でチャット、コード生成、リファクタリング、ドキュメント作成などを行うことができます。

### 主な特徴 
- **チャット (Chat):** コードに関する質問をしたり、新しいコードの作成を依頼したりできます。
- **オートコンプリート (Autocomplete):** 入力中にリアルタイムでコードの補完を提案します。
- **エディット (Edit/Refactor):** 選択したコード範囲に対して、具体的な指示（「この関数をリファクタリングして」「コメントを追加して」など）を出して直接修正できます。
- **カスタムモデルの利用:** Gemini, OpenAI, Claude, またはローカルLLM (Ollama等) を自由に設定して利用可能です。
- **コンテキストの追加:** `@file` や `@codebase` などのシンボルを使って、特定のファイルやプロジェクト全体をAIに参照させることができます。

### 利用方法
1. **インストール:** VS Code Marketplaceから「Continue」をインストールします。
2. **モデルの設定:**
3. - AI連携未設定の場合は、デフォルト表示画面より利用するフロンテキアモデル（OpenAI,Geminiなど）からAPIキーを設定
4. - 既に１件以上のフロンティアモデル設定がある場合 
       1. サイドバーにあるContinueアイコンをクリックします。
       2. 上部の設定Continueアイコン（歯車）をクリックして Continueメニュー表示して、「Models」クリックします。
       3. 表示の「Models」画面から「＋」アイコンをクリックして利用したいモデルの情報を追記します。
5. **チャットの開始:** `Ctrl + L` (Windows/Linux) または `Cmd + L` (Mac) でチャットウィンドウを開きます。
6. **コードの編集:** コードを選択して `Ctrl + I` (Windows/Linux) または `Cmd + I` (Mac) を押し、指示を入力します。

### 基本ショートカット
| 機能 | Windows/Linux | macOS |
| :--- | :--- | :--- |
| チャットを開く/フォーカス | `Ctrl + L` | `Cmd + L` |
| 選択範囲を編集 (Inline Edit) | `Ctrl + I` | `Cmd + I` |
| 新しいセッションを開始 | `Ctrl + Shift + L` | `Cmd + Shift + L` |
| コンテキストの追加 | `@` を入力 | `@` を入力 |


---
`END`
