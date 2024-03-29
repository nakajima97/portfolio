---
layout: post
title: 'Weather App'
author: [Yudai Nakajima]
tags: ['Portfolio']
image: img/wether-app-image.png
date: '2021-06-06T23:46:37.121Z'
draft: false
excerpt: Profile
---

# 概要

現在地を取得し、その地点の天気を表示するだけのシンプルな天気アプリです。

[アプリ](https://yudai-nakajima.github.io/weather-app/)  
[ソースコード](https://github.com/yudai-nakajima/weather-app)  
[Storybook](https://www.chromatic.com/builds?appId=60ac4c700647b700446c2f77)

# 作成経緯

以下 2 つの技術を用いてアプリを作成したいと思いました。

- Atomic Design
- Storybook

これらの技術は今まで触れたことがないため、作成難易度が低いアプリのほうが挫折しにくいと考えました。  
また、コンポーネント数を簡単に増やすことができれば Atomic Design によるコンポーネントの分割の恩恵を実感しやすいと考えました。

「現在地を取得し、その地点の天気を表示する」だけのシンプルなアプリであれば難易度は低く、  
表示する情報を増やせば、自然とコンポーネントも増えるため、今回作成するのにぴったりなアプリだと考え、天気アプリを作成しました。

# 使用技術

- React 17.0.2
- TypeScript 4.1.5
- ESLint
- Prettier
- Storybook
- chromatic + github actions を用いたテスト
- React Query
- Formik
- Recharts

## 使用 API

- Open Weather Map
- Geolocation API
- HeartRails Geo API

# 機能一覧

- 現在地の取得
- 取得した現在地をもとに天気を表示する
- 都市名を検索し、その都市の天気を表示する

# テスト

- Chromatic を用いたスナップショットテスト

# 反省点

Atomic Design・Storybook の学習に注力するため本アプリは意図的に機能を最低限に絞った。  
これらの技術に対して理解を深めることはできたが、  
メリットを実際に実感するにはもう少し大きな規模のほうが実感しやすい。  
次はこれらの技術を採用しつつもう少し大きい規模のアプリを作成したい。

# 使用イラストについて

## 天気予報のイラスト

本アプリで使用している天気に関するイラストはすべてイラストや様のものを使用しております。  
https://www.irasutoya.com

使用点数：11 点

イラストや様の利用規約  
https://www.irasutoya.com/p/terms.html

## アイコン

### 削除ボタン

Icon rainbow より  
https://icon-rainbow.com/%E7%A6%81%E6%AD%A2%E3%80%81%E9%96%89%E3%81%98%E3%82%8B%E3%81%AE%E3%82%A2%E3%82%A4%E3%82%B3%E3%83%B3%E7%B4%A0%E6%9D%90-2/
