# html_study

HTML + JavaScript + CSSを使うことでどういったことができるのかを覚えていきましょう。

このリポジトリではjQueryやBootStrapといったようなフレームワークは使用していません。

## デモページ

まずはデモページを確認していきましょう。

https://html-study.netlify.com/


## 環境構築方法

ローカルで開発・実行する場合は以下の手順を実施します。  
※環境構築には様々は手順が存在します。紹介する手順はあくまで1つの例です。

1. Git for Windowsをインストール
1. GitHubアカウントを作成
1. GitHubの<a href="https://github.com/yfujii01/html_study">yfujii01/html_study</a>をforkする
1. ターミナルを開きGitHubからプロジェクトをcloneする
    ```
    $ git clone https://github.com/【自分のアカウント名】/html_study.git
    ```
1. VSCodeをインストール
1. VSCode拡張のLive Serverをインストール
1. index.htmlを右クリックしてOpen with Live Serverを選択

## ページ説明(概要)

サンプルページは以下の種類を用意しています。  
一つずつソースを見てみましょう。

* index.html  
各種ページへのリンク

* sample_js.html  
JavaScriptの実装サンプル

* sample_css.html  
CSSの実装サンプル

* sample_sendparam.html  
formをgetで送信するサンプル

* sample_getparam.html  
get送信されたパラメータを受け取るサンプル

* sample_ajax.html  
ajaxを使用したjson受信サンプル

* sample_layout.html  
よくあるサイト構成のサンプル(html + cssのみ)

## 課題

1. 以下のサイトを真似して作ってみよう(※似たようなものができればOKです)  
https://kyokou.netlify.com/
1. 作成したサイトに対するリンクをindex.htmlに作成すること
1. GitHubにpushしてNetlifyに連携して公開してみよう

## Netlify公開手順

https://www.netlify.com/

1. GitHubに変更をpushする  
```
$ git add -A
$ git commit -m '変更のコミット'
$ git push origin master
```
1. アカウントを持っていない場合はSingUpする(GitHubアカウント連携でOK)  
1. New site from Gitボタン押下  
1. Continuous DeploymentでGitHubを選択  
1. リポジトリを選択  
1. Deploy siteボタン押下  
※ settingのChange site nameからドメイン名を変更可能
