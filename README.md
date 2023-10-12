# kibana-kube
kibana-kube は Elasticsearch が集めたログデータからユーザーが検索したいキーワードの件数を
可視化することができます。
本リポジトリには、必要なマニフェストファイル等が入っています。

## 動作環境
- Elasticsearch: >=8

## 設定
```
k apply -f kibana.yaml
```
