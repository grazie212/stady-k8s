# 01_helloWorldを実行する手順

1. dockerコンテナをビルド
   > docker build -t python_bottle .
2. コンテナを起動
   > docker run -d -p 8080:8080 python_bottle  
   > docker ps -a
3. ブラウザでアクセスして動作確認
   > http://localhost:8080/

[参考] https://qiita.com/RyosukeKamei/items/02ee6e266ffa2a265d9b