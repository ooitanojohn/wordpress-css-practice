## Docker
以下はdocker-compose.ymlが存在する階層で行う
- コンテナ起動
```
docker-compose up
```

- コンテナ停止

Ctr+C

または
```
docker-compose stop
```

## Sass

パッケージのインストール

実行はgit cloneした後の初回のみで良い。

```
npm install
```

scssコンパイル開始

作業開始時に毎回実行する。作業終了時に Ctr+C で停止する

```
npm run dev
```