<img src="https://user-images.githubusercontent.com/81548811/229280709-88d64595-59c4-42b4-80f1-a72c6e7d1531.PNG" alt="connect metamask" width="20%"> <img src="https://user-images.githubusercontent.com/81548811/229280713-f5e8a52b-746d-488e-8e96-02c6dd0d0fbb.PNG" alt="verify" width="20%"> <img src="https://user-images.githubusercontent.com/81548811/229280716-ff340730-9368-4bfa-b3a1-d0e6688a19dc.PNG" alt="info" width="20%">

## このプロジェクトについて
FaucetTokenは「FlutterとSolidityを使ってERC20トークンをメタマスクに送るアプリ」です。  
Solidityは最新技術で、情報が英語でも存在しなかったので公式リファレンスを見ながら作りました。  
後から作る人のために、作り方の記事を書きました。  

記事URL: https://qiita.com/KeiIT11/items/b73116e592fa41907d37

- 使用技術：Solidity, Dart, Flutter  
- 開発期間：2週間  
- 担当　　：全部  

## 使い方
### ローカルで実行
```
git clone ~.git
flutter clean
flutter packages get
flutter run
```

## 機能と使用技術（特徴を箇条書きなど）
### 1. ウォレットを接続する機能

<img src="https://user-images.githubusercontent.com/81548811/229280709-88d64595-59c4-42b4-80f1-a72c6e7d1531.PNG" alt="connect metamask" width="20%">

connect walletボタンを押すと、メタマスクのアプリが起動し、承認するとメタマスクを接続することができます。

### 2. ウォレットの情報を表示する機能
<img src="https://user-images.githubusercontent.com/81548811/229280713-f5e8a52b-746d-488e-8e96-02c6dd0d0fbb.PNG" alt="verify" width="20%">
接続されたウォレットの詳細が見れます。
- 公開鍵のアドレス
- 接続しているネットワーク番号（Goerliネットワークは5）
- 持っているERC20トークンの数

### 3. ウォレットにERC20を送る機能
<img src="https://user-images.githubusercontent.com/81548811/229280716-ff340730-9368-4bfa-b3a1-d0e6688a19dc.PNG" alt="info" width="20%">

Get a Token!ボタンを押すと、metamaskに遷移し、承認するとトークンが送付されます。
