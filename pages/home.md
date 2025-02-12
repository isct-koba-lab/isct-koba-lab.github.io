---
title: Home
layout: home
permalink: /
---

<script type="text/x-mathjax-config">MathJax.Hub.Config({tex2jax:{inlineMath:[['\$','\$'],['\\(','\\)']],processEscapes:true},CommonHTML: {matchFontHeight:false}});</script>
<script type="text/javascript" async src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.1/MathJax.js?config=TeX-MML-AM_CHTML"></script>

小林研究室のウェブページへようこそ. 小林研は東京科学大学 工学院 経営工学系に所属し, オペレーションズ・リサーチや数理最適化, 機械学習などの研究を行っています. 

このページでは小林研の研究内容や最新のお知らせを掲載しています. まだ準備中の部分も多いですが, 順次更新していく予定です.

最終更新日: {{ site.time | date: "%Y 年 %m 月 %d 日" }}
<br>
## 研究室基本情報
- 研究分野: オペレーションズ・リサーチ, 数理最適化, 機械学習
- 構成員
  - 教員: 小林 健 ([個人のページ](https://kenkoba2119.github.io/))
- 所在地
  - 〒152-8552  東京都目黒区大岡山2-12-1 東京科学大学 大岡山キャンパス 西 9 号館 ([Google Map](https://maps.app.goo.gl/YozBDce4D6CBm4dk8))
    - 教員室: 4 階 416 号室
- 関連する記事
    - [基数制約つき平均・分散モデルに対する切除平面法](https://orsj.org/wp-content/corsj/or67-7/or67_7_360.pdf)
    - [半正定値最適化問題に対する切除平面法と混合整数半正定値最適化問題への拡張](https://orsj.org/wp-content/corsj/or65-12/or65_12_656.pdf)  

## 研究室に興味のある学生へ

- **経営工学系に所属する学生へ**
  - 2025 年度より学士特定課題研究に関する学生の受け入れを開始します.
  - 研究室所属に関する質問や相談は随時受け付けています. 小林にメールあるいは Slack で連絡してください. 
- **他大学, 他系から大学院での進学を考えている学生へ**
  - 2025 年 2 月, 3 月に経営工学系の大学院説明会 (スケジュールは[こちら](https://educ.titech.ac.jp/iee/event_information/)) が開催されます. こちらの説明会では研究室紹介を行いますので, 進学を検討している学生はぜひ参加してください. なお研究室紹介は対面での実施で, オンラインでの参加はできません. 
  - 進学に関する質問や相談は, 随時受け付けています. 小林にメールで連絡してください. なお, 小林研究室を第 1 志望として出願することを検討している学生は, 出願前に必ず小林までコンタクトを取ってください.

## お知らせ

{% for item in site.posts limit:site.posts_on_home %}
{% include card.html %}
{% endfor %}
<br>
過去のお知らせは[こちら](/archive/)
