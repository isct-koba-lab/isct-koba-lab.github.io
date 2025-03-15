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
- 関連する解説記事
    - [機械学習の反実仮想説明と混合整数最適化](https://orsj.org/wp-content/corsj/or69-3/or69_3_143.pdf)
    - [基数制約つき平均・分散モデルに対する切除平面法](https://orsj.org/wp-content/corsj/or67-7/or67_7_360.pdf)
    - [半正定値最適化問題に対する切除平面法と混合整数半正定値最適化問題への拡張](https://orsj.org/wp-content/corsj/or65-12/or65_12_656.pdf)  

## 研究室に興味のある学生へ

研究室配属に関する質問や研究室見学に関する相談は随時受け付けていますので, 興味がある学生は[小林](https://kenkoba2119.github.io/)まで気軽にメール (あるいは大学の Slack) で連絡をしてください. 他大学や経営工学系以外の系に所属し, 小林研を第一志望として大学院入試を検討している学生は, 出願前に必ず一度小林まで連絡してください.

## お知らせ

{% for item in site.posts limit:site.posts_on_home %}
{% include card.html %}
{% endfor %}
<br>
過去のお知らせは[こちら](/archive/)
