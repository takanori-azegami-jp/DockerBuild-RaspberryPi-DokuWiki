# DockerBuild-RaspberryPi-DokuWiki
RaspberryPiにDockerでDokuWikiをたてる

## コンテナ起動
docker-compose.ymlを配置したフォルダに移動して実行
~~~powershell
PS C:\>  docker-compose up -d --build
~~~

## 参考
[docker-composeを利用してDokuWikiを構築する](https://mebee.info/2020/07/04/post-13052/)
[bitnami/dokuwiki](https://hub.docker.com/r/bitnami/dokuwiki/)


