# docker-elasticsearch-kibana
ローカルで Elasticsearch, Kibanaを動かす docker-compose設定

# 起動方法
```bash
docker-compose up -d
```

# Services
## Elasticsearch
* 待ち受け host:port
	* `127.0.0.1:9200`
* Volume共有
	* `.data`: data
	* `.logs`: logファイル
* 認証
	* 無し

## Kibana
* 待ち受け host:port
	* `127.0.0.1:5601`
* 認証
	* 無し
