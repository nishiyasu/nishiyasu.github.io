---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## International Journal (refereed)

1.(in submission)
2. Kristen Grauman, Andrew Westbury, Eugene Byrne, Zachary Chavis, Antonino Furnari, Rohit Girdhar, ..., **Takumi Nishiyasu**, ... Jitendra Malik. "Ego4D: Around the World in 3,000 Hours of Egocentric Video," IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI), 2024.
3. Takuma Yagi, **Takumi Nishiyasu**, Kunimasa Kawasaki, Moe Matsuki, and Yoichi Sato.  GO-Finder: Registration-Free Wearable System for Assisting Users in Finding Hand-Held Lost Objects. ACM Transactions on Interactive Intelligent System (TiiS), December 2022
  
## International Conference(refereed)
1. **Takumi Nishiyasu**, Tobias Kostorz, Yao Wang, Yoichi Sato, and Andreas Bulling. “ChartQC: Question Classification from Human Attention Data on Charts”, In the 9th Workshop on Eye Tracking and Visualization (ETVIS) (in conjunction with ETRA2025). 2025
2. **Takumi Nishiyasu** and Yoichi Sato. "Gaze Scanpath Transformer: Predicting Visual Search Target by Spatiotemporal Semantic Modeling of Gaze Scanpath", In the 6th International Workshop on Gaze Estimation and Prediction in the Wild (GAZE 2024) (in conjunction with CVPR'24). 2024
3. **Takumi Nishiyasu**, Wataru Shimoda, and Yoichi Sato. Image Cropping under Design Constraints. In Proceedings of the 5th ACM International Conference on Multimedia in Asia (MMAsia’23). 2023
4. Kristen Grauman, Andrew Westbury, Eugene Byrne, Zachary Chavis, Antonino Furnari, Rohit Girdhar, ..., **Takumi Nishiyasu**, ... Jitendra Malik. Ego4D: Around the World in 3,000 Hours of Egocentric Video.In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR'22). 2022
5. Takuma Yagi, **Takumi Nishiyasu**, Kunimasa Kawasaki, Moe Matsuki, and Yoichi Sato. GO-Finder: Registration-Free Wearable System for Assisting Users in Finding Lost Objects via Hand-Held Object Discovery. In Proceedings of the 26th International Conference on Intelligent User Interfaces (IUI'21). 2021.

## Domestic Conference / Symposium (refereed)

1. **西保匠**，繁田亮，川原圭博，ビッグロール工法下で設置可能な土壌センサのための薄膜アンテナ設計，マルチメディア，分散協調とモバイルシンポジウム2018(DICOMO2018)，pp.349-355，福井，2018年7月
  
## Domestic Conference / Symposium (non-refereed)
    
1. **Takumi Nishiyasu**, Wataru Shimoda, Yoichi Sato,Multiple Conditioned Image Cropping,第26回画像の認識・理解シンポジウム（一般論文）,2023年7月
2. **西保匠**，佐藤洋一，視線と画像の意味的情報の統合モデルによる内部状態推定に向けた検討，第25回画像の認識・理解シンポジウム（一般論文）, 2022年7月
3. **西保匠**，松井勇佑，佐藤洋一，審美性を考慮した画像の凸四角形領域切り出し，第23回画像の認識・理解シンポジウム （一般論文），2020年8月
4. **西保匠**，繁田亮，川原圭博，芝管理用埋没設置型センサにおける920MHz帯IEEE802.15.4gの通信安定性評価，知的環境とセンサネットワーク研究会 (ASN)，pp.29-33，山形，2017年11月
5. 塚本想也，**西保匠**，菅野裕介，個人学習を伴わない視線変更モデル適応のための目領域画像合成,情報処理学会全国大会 2022年3月
6. 塚本想也，**西保匠**，菅野裕介，視線変更視線変更モデルの個人適用のための目領域画像合成手法, The 18th IEEE TOWERS, 2021年11月
7. 八木拓真，**西保匠**，川崎邦将，松木萌，佐藤洋一，GO-Finder: 手操作物体の発見に基づく事前登録不要のウェアラブル物探し支援システム，インタラクション，2021年3月
8. 八木拓真，川崎邦将，松木萌，**西保匠**，佐藤洋一，手操作物体の識別による手-物体インタラクション可視化システム，第23回画像の認識・理解シンポジウム（一般論文）, 2020年8月



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
