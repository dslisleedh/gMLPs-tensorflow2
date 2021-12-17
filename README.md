<h1>
Pay Attention to MLPs

[arXiv](https://arxiv.org/abs/2105.08050)
</h1>

![Model](https://github.com/dslisleedh/gMLPs-tensorflow2/blob/master/Model.PNG)

<h3>
요약 :  
Spatial Gating Unit(SGU)을 제안함. SGU 전의 Channel FC로 Channel을 늘린 후 뒤 절반만 split(Gating)하여 Spatial FC에 넣은 다음 Spatial FC를 거치지 않은 나머지 절반과 element wise product로 합침.  
Gated split이 channel 정보를 갖지 않는다는 점에서 SE Block과 차이를 보임.
</h3>

<h5>
주의 :  
Spatial FC의 Bias는 1로 initialization함. 학습 초반에 더 안정화 하는 것이 목적임. 
  
[ResMLP](https://github.com/dslisleedh/ResMLP-tensorflow2)의 Affine layer와 유사
</h5>
