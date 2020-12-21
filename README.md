# GradleMultiProjectSample
## 概要
一つのリポジトリで複数の異なるバージョンのSpring Bootのアプリを複数動かしたい（ex:Spring Bootのアップグレードを順次行うため）。現在対応しているリポジトリの構成を簡略化して(なんちゃってマルチプロジェクトなので、片方をアップグレードすると動かなくなる)、gradle関連のファイルをどう記述すべきか調査するためのリポジトリである。

## 想定
* SampleApp01
    * Spring Boot 2系のアプリ
* SampleApp01Unit01
    * Spring Boot 2系のアプリから使用されるもの
* SampleApp02
    * Spring Boot 1系のアプリ