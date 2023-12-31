# ChatGPTを用いてシステムのユースケース図を生成する

## はじめに
本ドキュメントでは、ChatGPTを用いてシステムの概要からユースケースを簡単に生成する方法について解説します。対象読者は、システム開発者、プロダクトマネージャーなど、システムの要件定義や設計に携わる方々です。

## ChatGPTの基本的な使用方法

### インストールとセットアップ
ChatGPTの利用を開始するには、適切なインストールとセットアップが必要です。公式ドキュメントを参照し、必要なソフトウェアのインストールと、APIキーの取得・設定を行ってください。
また、Web版のChatGPTを利用することで、インストールやセットアップなしで直接利用することができます。

### 基本的なコマンドと操作方法
ChatGPTは、テキストベースのインターフェースを通じて操作します。
基本的なコマンドをマスターすることで、効率的にユースケースの洗い出しを行うことができます。
- `start`: セッションの開始
- `ask`: 質問の投稿
- `stop`: セッションの終了

#### 使用例
```
> start
ChatGPT: セッションを開始しました。何かお手伝いできることがありますか？
> ask システムのユースケースを生成したい
ChatGPT: ユースケースの生成には、以下のステップがあります。...
```

## ユースケースの生成の仕方
ChatGPTのプロンプトを用いてユースケースの洗い出しを行います。以下はそのステップです。
```
作りたいシステムの概要を伝えるので、要件のヒアリングを行ってユースケース図を作成してください。
1.  まず最初に、概要から想定されるユースケース一覧を提示してください。
　ユースケースは誰が、何をできるか明記するようにしてください。
2. 次に私が1.で提示された一覧に対して、必要なユースケース一覧に追加・削除する、ユースケースを伝えるので、私が「ユースケースは以上です」と伝えるまでヒアリングを続けてください。
3. 2.で作成したユースケース一覧を元にユースケース図を表示してください。
```

## ユースケースの生成例
本章では、ChatGPTを用いてオンラインショッピングシステムのユースケースを生成する一例を示します。
1. **システムの概要伝達(あなた → ChatGPT)**
   - システムの概要：オンラインショッピングシステム
   - 主な機能：商品検索、カート追加、購入
2. **ユースケース一覧の提示(ChatGPT → あなた)**
   - 顧客は商品を検索できる
   - 顧客は商品をカートに追加できる
   - 顧客は商品を購入できる
3. **ユースケース一覧の確認と修正(あなた → あなた)**
   - 追加ユースケース：顧客はアカウントを作成できる
   - 最終ユースケース一覧の確認
4. **ユースケース図の生成(ChatGPT→あなた)**
   - ChatGPTによるユースケース図の生成と表示

Web版のChatGPTを利用した生成例を以下に示します。
![gen_image](https://github.com/chiba244qq/tools/assets/19734492/7bc4a337-3686-49ab-8c60-eb65f7496c5f)


## ベストプラクティスと注意点

### ベストプラクティス
- **明確な要件定義**: システムの要件を明確に定義することで、ChatGPTが正確なユースケースを生成しやすくなります。
- **具体的な質問**: ChatGPTに対する質問は、具体的かつ詳細にすることで、より適切な回答が得られます。
- **反復的な確認**: ユースケース一覧が完成したら、ステークホルダーとの確認を反復的に行い、漏れや誤解を防ぎます。

### 注意点
- **回答の評価**: ChatGPTの回答はあくまで提案であり、全てが正しいわけではないため、適切に評価する必要があります。
- **制約の理解**: ChatGPTには一定の制約が存在するため、その制約を理解し、適切な使用方法を考えることが重要です。

## まとめ
本ドキュメントでは、ChatGPTを用いてシステムのユースケースを効果的に作成する方法について解説しました。ChatGPTの基本的な使用方法から、ユースケースの洗い出し方、具体的な生成例、ベストプラクティスと注意点に至るまで、幅広くカバーしました。ChatGPTは、テキストベースの対話を通じてユースケースの洗い出しをサポートする強力なツールですが、その使用には適切な評価と制約の理解が必要です。本ドキュメントが、ChatGPTを用いたユースケース洗い出しの一助となることを願っています。

