---
title: "斜方投射軌道計算アプリ"
date: 2019-05-01T21:15:59+09:00
description: "Androidアプリの作成実績"
categories: [Product]
tags: [Android, Java]
featuredImage: "/img/20160613055616e9e.png"
featuredImageDescription: ""
dropCap: true
displayInMenu: false
displayInList: true
draft: false
---

## 作成期間

- ちまちま作成して半年くらい

## 概要

- x方向の速度、y方向の速度を入力することでボールの軌道をシミュレーションできる
- 青い四角が的になっており、的に当てるとクリア
- 描画領域右上に速度等の数値を表示する
- 描画領域下部に距離目盛りがあり、現在の距離に応じて自動でパースされる

## 雑記

- 学生時代に就職活動のネタ用に作成
- 数値計算部分には時間積分法として4段4次ルンゲクッタ法を採用
  - 元数値計算屋として計算精度にはこだわりがある
- GooglePlayにもテスト版を公開した
  - 開発用に公開していたアドレスに1通だけメールが来た