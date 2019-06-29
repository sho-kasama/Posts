

## Docker-composeを使って、rails+MySQL on Dockerの環境構築


① git clone https://github.com/sho-kasama/Posts.git

Dockerを起動

2. docker-compose build     ( Dockerfile から独自のイメージをビルドするためのコマンド。 ) 

3. docker-compose up        ( コンテナを作成して、起動します。 ) 

4. docker-compose run web rails db:create ( DB構築 ) 

5. docker-compose down ( サーバーを止める ) 
