# 郵便番号更新プログラム

[住所.jp](http://jusyo.jp/ "住所.jpトップページ") にある郵便番号データベース（SQLite）を取ってくるだけのプログラムです。

## はじめて使う場合

1. プロジェクトをクローンして、IDE上で必要に応じてビルドします。（わからない場合は「ビルドを行わない場合」へ）
2. target/GetJushoJP-1.0-SNAPSHOT-jar-with-dependencies.jarが成果物です。
3. 成果物を、データベースを使いたい他のプログラムのprogramフォルダへコピーします。
4. プロジェクトに含まれる郵便番号更新.batを、データベースを使いたい他のプログラムのトップ階層へコピーします。
5. 郵便番号更新.batをダブルクリックで起動します。
6. programフォルダ内にzenkoku.sqlite3ができたら完了です。

## 使い方（2回目以降）

1. 郵便番号更新.batをダブルクリックで起動します。
2. programフォルダ内のzenkoku.sqlite3が上書きされたら完了です。

## ビルドを行わない場合

1. このプロジェクト内にあるprogramフォルダとその中身のtarget/GetJushoJP-1.0-SNAPSHOT-jar-with-dependencies.jarをダウンロードします。
2. 郵便番号更新.batをダウンロードして、programフォルダと同じ階層に配置します。
3. 郵便番号更新.batをダブルクリックで起動します。
4. programフォルダ内にzenkoku.sqlite3ができたら完了です。

## 動作環境

* Java 1.7以降
