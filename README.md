<h1>
Pay Attention to MLPs

[arXiv](https://arxiv.org/abs/2105.08050)
</h1>

![Model](https://github.com/dslisleedh/gMLPs-tensorflow2/blob/master/Model.PNG)

<h3>
요약 :  
Spatial Gating Unit(SGU)을 제안함. SGU 전의 Channel FC로 Channel을 늘린 후, SGU 안에서 절반만 split(Gating)한 후 절반을 Spatial FC에 넣은 후 element wise product로 합침.  
</h3>

<h5>
주의 :  
Spatial FC의 Bias는 1로 initialization함.
</h5>
