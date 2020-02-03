
### 2020
- [AAAI2020] [Decoupled Attention Network for Text Recognition](https://arxiv.org/abs/1912.10205)
  - **narrow advantage**
  - annotation
    - word level
  - feature map
    - 2d
  - decoder
    - GRU
  - novelty
    - decouples the alignment operation from using historical decoding results
    - alignment is achived by a spatial attention module
  - the devil in the details
    - None

### 2019
- [CVPR2019] [Aggregation Cross-Entropy for Sequence Recognition](https://arxiv.org/abs/1904.08364)
  - **unfair comparison**
  - annotation
    - characters and their count in the sequence annotation
  - feature map
    - 2d
  - decoder
    - ACE
  - novelty
    - proposes the ACE loss function
      - much quicker implementation, faster inference/back-propagation, approximately O(1) in parallel
      - less storage requirement (no parameter and negligible runtime memory)
      - convenient employment (by replacing CTC with ACE)
      - competitive performance to CTC and the attention mechanism
  - the devil in the details
    - None
    
### 2018
[CVPR2018] [Edit Probability for Scene Text Recognition](https://arxiv.org/abs/1805.03384)

