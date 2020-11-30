---
title: butterCMS 始めました
date: "2019-12-16T08:40:32.169Z"
description: 慣れないながら、vue.jsを使ってbutterCMSを使ってみました。何か少しでも参考になれば嬉しいです
---

## ButterCMSをオススメする理由

WordPressじゃなくてButterCMSの方が良いのかと言われると、現時点ではWordPressよりも良いかは分からない、というのが本音です。

元々、ロリポップでレンタルサーバ＋WordPressでサイト構築にチャレンジしましたが、半年で5,000円くらいかかっていました。

ちょっと出費が痛いですよね。

無料でやろうとすると、プログラミングのスキルは少し必要だけど、Google Firebase+ButterCMSで無料になります。

無料になるなら、ちょっとやってみようかな、というのがそもそものきっかけです。

ButterCMSはPersonalプランで無料で利用可能です。

ドメイン取得に少額かかりましたが、トータルではレンタルサーバよりも遥かに安く運用できています。

## 実際のサイト
[作成したサイトはこちら](https://reachan-p.firebaseapp.com)

## 感じたメリット

- レンタルサーバよりも費用が安い（Firebaseを使う）
- 検索すれば色んなテンプレートが公開されており、プログラミング初学者でも取りかかりやすい
- それでもWordPressの方がテンプレートは充実しており、コンテンツに注力できる

## 構築時にハマったこと

ButterCMSのPreviewを押しても404エラーが出て表示されない

これはvue.jsの公式に記載がありました。

[サーバの設定例](https://router.vuejs.org/ja/guide/essentials/history-mode.html#%E3%82%B5%E3%83%BC%E3%83%90%E3%83%BC%E3%81%AE%E8%A8%AD%E5%AE%9A%E4%BE%8B)

私の環境はFirebaseを利用しているので、firebase.jsonに数行追記するだけで解決できました。

少しでもbuttercmsを利用するのに役立てたなら幸いです！