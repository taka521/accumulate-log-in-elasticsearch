# accumulate-log-in-elasticsearch

log4jからログを Elasticsearch に集積したくて、検証したリポジトリ。  

## 環境

* アプリケーションは適当に SpringBoot で用意。
* Elasticsearch、Logstash、KibanaはDocker

## メモ

### Logstash

ログを集積するエンドポイントを提供するミドルウェア。  
Logstashから、Elasticsearchにログを流し込むために使用した。

### Kibana

Elasticsearchに流し込んだログ（データ）を可視化するためのミドルウェア。  

