---
title: Home
layout: home
permalink: /
---

<script type="text/x-mathjax-config">MathJax.Hub.Config({tex2jax:{inlineMath:[['\$','\$'],['\\(','\\)']],processEscapes:true},CommonHTML: {matchFontHeight:false}});</script>
<script type="text/javascript" async src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.1/MathJax.js?config=TeX-MML-AM_CHTML"></script>

小林研究室のウェブページへようこそ. 小林研は東京科学大学 工学院 経営工学系に所属し, オペレーションズ・リサーチや数理最適化, 機械学習などの研究を行っています.   

このページでは小林研の研究内容や最新のお知らせを掲載しています. 

Last Updated: {{ site.time | date: "%Y 年 %m 月 %d 日" }}
<br>
## 研究室基本情報
- 研究分野: オペレーションズ・リサーチ, 数理最適化, 機械学習
- 構成員
  - 教員: 小林 健 ([個人のページ](https://kenkoba2119.github.io/))
  - 学部生: 3 名
- 所在地
  - 〒152-8552  東京都目黒区大岡山2-12-1 東京科学大学 大岡山キャンパス 西 9 号館 ([Google Map](https://maps.app.goo.gl/YozBDce4D6CBm4dk8))
    - 教員室: 4 階 416 号室
    - 学生室: 5 階 526 号室

## お知らせ

{% for item in site.posts limit:site.posts_on_home %}
{% include card.html %}
{% endfor %}
<br>
過去のお知らせは[こちら](/archive/)
