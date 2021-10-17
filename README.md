# Upload to GitHub
GitHubにソースコード含めファイルをアップロードする方法について

==必須==  
・GitHubでは英語で文字を入力してください  
・サイトも同様に英語表記で使用することを推奨しています  
・本記事は英語表記・英語入力を前提に説明していきます  

## --Gitを使用したアップロード方法--
前提：アップロード作業を行うパソコン内にgitがインストールされている
### リポジトリを作成する
まず[New]をクリックしてレポジトリを新規作成しましょう。  
[Repository name]にはプロジェクトの名前を書いてください(必須)  
[Description(optional)]はリポジトリ(プロジェクト)の説明を書きます。(任意)  
[Public / Private]は基本Privateで大丈夫です。(必須)  
[Initialize this repository with:]は基本すべてチェックしなくて大丈夫です。(任意)  

最後に[Create repository]をクリックしてリポジトリの作成は完了です。  

### ファイルをアップロードする
１.リポジトリを作成した直後の画面に[Quick setup ーif you've done this kind of thing before]という項目があり、
[HTTP]を選択して右のURLをコピーしておいてください。  

２.windowsのコマンドプロンプト(cmd)を起動してアップロードするリポジトリに移動してください。  

３.続いて下記のコマンドを順に実行してください。  
　・git init  
　・git remote add origin コピーしておいたURL  
　・git add .  
　・git commit -m"コミット名"  
　・git push origin master  
 
コミット名はリポジトリ内のファイルをまとめた名前のことです。一般的には「first」などが使用されます。

４.作成したリポジトリの画面(URLをコピーした画面)で[F5]を押しページを再読み込みするとアップロードしたファイルを確認することができます。

## --GUIで簡単なアップロード方法--

こちらのYouTube動画をご覧ください>> 
https://www.youtube.com/watch?v=WM08G17idt0

## リポジトリを削除する方法

１.リポジトリ内[Setting]より最下にある[Delete this repository]をクリック  
２.[Please type 〇〇/〇〇◯◯ to confirm.]と書かれている「〇〇/〇〇〇〇」の部分を下に入力し  
　 [I understand the consequences, delete this repository]をクリックして削除完了
