# vision_transformer

=== 1. encoder === 

1) positional encoding 

2) Multi - Head attention (self attention) 

3) point wise feed forward network 

=== 2. decoder === 

4) positional encoding 

5) Masked multi - Head attention (self attention) 

6) multi - Head attention => inference

7) point wise feed forward network 

8) linear - softmax - output 


Input Embedding : 차원 축소, 다르게 Embedding하는 이유, value를 구지 하는 이유?  
https://towardsdatascience.com/transformers-explained-visually-part-3-multi-head-attention-deep-dive-1c1ff1024853  
CNN과 비교해서 데이터가 거대화 지면, Transformer가 더 좋은 이유?  Inductive Bias가 없음  

fine tunning할때 pre-trainning할때 높은 해상도가 좋은 이유? 
* https://hipgyung.tistory.com/entry/%EC%89%BD%EA%B2%8C-%EC%9D%B4%ED%95%B4%ED%95%98%EB%8A%94-ViTVision-Transformer-%EB%85%BC%EB%AC%B8-%EB%A6%AC%EB%B7%B0-An-Image-is-Worth-16x16-Words-Transformers-for-Image-Recognition-at-Scale 
=> CNN의 경우에는 일반적으로 fine tunning을 해상도가 낮을것으로 함.  

Position embedding 공간적인 정보를 어떻게 해석해야할지? 
CNN과 Transformer Filter의 차이  


[Deit]
- Deit-B : 파라미터 변경
- Soft distilation 은 확률가 쿨백
- Hard Distilation은 반반
- Bias 때문에 Teacher의 CNN이 더 좋다?
- corrlelation?
- learning rate cosine decay
- repeat augumentation
- https://www.youtube.com/watch?v=0gmd4OVmDU8
https://www.youtube.com/watch?v=DjEvzeiWBTo

[Scale Vit]
- extrapolate
- irreducible entropy
- saturation
- Big models are more sample efficient
