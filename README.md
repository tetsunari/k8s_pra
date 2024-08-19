# k8s_pra


### コマンド
`kubectl apply -f apache_dev.yml　`　　//デプロイメントのファイルを読み込ませて反映（-f でファイルを指定しないとエラーになる）
 
`kubectl get pods` 　//podが作られているかの確認
 
`kubectl apply -f apache_ser.yml`　　//サービスの定義ファイルを読み込ませる
 
`kubectl get services`　　//サービスが作られているかの確認

`kubectl delete -f apache_dev.yml`  //デプロイメントの削除

`kubectl get deployment`  //デプロイメントの削除の確認
``` 
No resources found in default namespace. 
```

`kubectl delete -f apache_ser.yml`  //サービスの削除

`kubectl get service` //サービス削除の確認
```
NAME         TYPE        CLUSTER-IP   EXTERNAL-IP   PORT(S)   AGE
kubernetes   ClusterIP   10.96.0.1    <none>        443/TCP   56m
```

# 2024/08/19
[つくって、壊して、直して学ぶ Kubernetes入門](https://www.shoeisha.co.jp/book/detail/9784798183961)
でkubernetesをさわってみる
