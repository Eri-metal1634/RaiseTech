# 第3回講義の学び

1.サンプルアプリケーションのデプロイ  
![sample](/picture03/sample.png)  

2.APサーバーについて　　
  - サーバー名とバージョン　puma version 5.6.5  
![puma runnng](/picture03/puma-runnng.png)  　
  - サーバーを終了させた場合引き続きアクセスできるか→できない  
![puma st](/picture03/puma-stop.png)　　 
  - 確認後、サーバー再起動する  
![puna re](/RaiseTech/picture03/puma-restart.png)  

3.DBサーバーについて  
  - サーバー名とバージョン　mysql ver.8.0.33  
  ![db ver](/picture03/mysql-v.png)  
  - サーバーを終了させた場合、引き続きアクセスできるか→できない  
  ![db st](/picture03/mysql-stop.png)  

4.Railsの構成管理ツール名→Bundler  
5.今回の課題から学んだこと  
  - アプリケーションの起動にはAPサーバーとDBサーバーの起動が必要なこと。
  - マークダウン形式での画像挿入の方法
  - タイプミスやコマンド忘れなど小さなミスでもアプリケーションが作動しないこと。
  - 作業中にできていること、できていないことを確認しながらすすめることの重要性。
  - 第2回講義で学んだGit,Githubの操作がひつようになるので、躓いたら前回の講義を
  - 振り返って、何度も復習する必要がある。