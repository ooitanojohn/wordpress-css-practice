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

## 練習の仕方

編集する対象のファイルは

html/wp-content/themes/theme-bones-master/

の中のファイルです。

home.php

がトップページのテンプレート。自由に書き換えて練習してください。

余裕があれば以下のファイルも書き換えてみてください。

- header.php

```
<?php get_header(); ?>
```

で呼び出される。ワードプレスのヘッダー部分。

- footer.php

```
<?php get_footer(); ?>
```

で呼び出される。ワードプレスのフッター部分。

## おかしくなったら

```
docker-compose rm
```

で全て消去できます。その後

```
docker-compose up
```

で初めの状態になります。エラーが直せなくなったら、あまり頭を悩ませずにリセットしちゃいましょう。