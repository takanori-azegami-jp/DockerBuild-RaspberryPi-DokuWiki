# DockerBuild-RaspberryPi-DokuWiki
RaspberryPiにDockerでDokuWikiをたてる

## コンテナ起動
docker-compose.ymlを配置したフォルダに移動して実行
~~~powershell
PS C:\>  docker-compose up -d --build
~~~
## ブラウザからURLでDokuWikiに接続
~~~
http:// [DockerホストのIPアドレス] :8080
~~~
![image](https://user-images.githubusercontent.com/81016034/147951654-0d22babd-5fe9-483e-8cbb-b736dabe0b7f.png)

## 参考
[docker-composeを利用してDokuWikiを構築する](https://mebee.info/2020/07/04/post-13052/)

RaspberryPi(arm32bit)環境でビルドされた下記のDockerイメージを使用

[Docker Hub：xtremxpert/rpi-dokuwiki](https://hub.docker.com/r/xtremxpert/rpi-dokuwiki)

