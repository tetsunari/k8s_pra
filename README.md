# k8s_pra


### コマンド
`kubectl apply -f apache_dev.yml　`　　//デプロイメントのファイルを読み込ませて反映（-f でファイルを指定しないとエラーになる）
 
`kubectl get pods` 　//podが作られているかの確認
 
`kubectl apply -f apache_ser.yml`　　//サービスの定義ファイルを読み込ませる
 
`kubectl get services`　　//サービスが作られているかの確認
