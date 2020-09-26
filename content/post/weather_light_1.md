---
title: "Esp32 Weather Light"
date: 2019-05-03T08:04:44+09:00
description: "ワンボードマイコンを使った作成物"
categories: [Product]
tags: [esp32, Arduino]
featuredImage: "/img/IMG_0841.JPG"
featuredImageDescription: ""
dropCap: true
displayInMenu: false
displayInList: true
draft: false
---

![](/img/IMG_0841.JPG)

## 作成期間

- 5ヶ月くらい

## 概要

- WebAPIを使って数時間後の天気予報を通知する
- WebAPIは[openweathermap.org](https://openweathermap.org/)を使用
- マイコンボードは[ESPr® Developer 32](https://www.switch-science.com/catalog/3210/)を使用
- 以下の項目をブラウザから設定できる
  - どこの地域の天気情報を通知するか(東京、名古屋、大阪を選べる)
  - 何時間後の天気情報を通知するか(0-15時間まで3時間刻みで設定できる)
  - 接続するWiFiルータのSSID、パスワード
- 一度接続に成功したWiFiルータの情報は不揮発領域に記憶する
  - 次回起動時は自動的に過去に接続したルータに接続を試みる
- 単3電池2本で駆動する
- ソースコードは[こちら](https://github.com/kouya17/esp32_weather_light)

## 雑記

- エネループだと連続で8時間しか駆動しない
- 外装とかが色々とお粗末