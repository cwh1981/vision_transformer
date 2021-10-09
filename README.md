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
