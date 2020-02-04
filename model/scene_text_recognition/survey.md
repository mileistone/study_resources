
### 2020
- [AAAI2020] [Decoupled Attention Network for Text Recognition](https://arxiv.org/abs/1912.10205)
  - **narrow advantage**
  - annotation
    - word level
  - feature map
    - 2d
  - decoder
    - RNN
  - motivation
    - there is misalignment between the ground truth strings and the attention’s output sequences of probability distribution, which is caused by missing or superfluous characters
  - solution & novelty
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
  - motivation
    - CTC and RNN based mechanism is not easy enough
  - solution & novelty
    - proposes the ACE loss function
      - much quicker implementation, faster inference/back-propagation, approximately O(1) in parallel
      - less storage requirement (no parameter and negligible runtime memory)
      - convenient employment (by replacing CTC with ACE)
      - competitive performance to CTC and the attention mechanism
  - the devil in the details
    - None
    
### 2018
[CVPR2018] [Edit Probability for Scene Text Recognition](https://arxiv.org/abs/1805.03384)
  - ****
  - annotation
    - word level
  - feature map
    - 1d
  - decoder
    - RNN and attention
  - motivation
    - there is misalignment between the ground truth strings and the attention’s output sequences of probability distribution, which is caused by missing or superfluous characters
  - solution & novelty
    - propose a novel method called edit probability (EP) for scene text recognition
    - EP tries to effectively estimate the probability of generating a string from the output sequence of probability distribution conditioned on the input image, while considering the possible occurrences of missing/superfluous characters
    - the advantage lies in that the training process can focus on the missing, superfluous and unrecognized characters, and thus the impact of the mis- alignment problem can be alleviated or even overcome
  - the devil in the details
    - None
    
- [CVPR2018] [AON: Towards Arbitrarily-Oriented Text Recognition](https://arxiv.org/abs/1711.04226)
   - ****
  - annotation
    - word level
  - feature map
    - 1d
  - decoder
    - RNN and attention
  - motivation
    - most existing methods directly encode a text image as a 1D sequence of features and then decode them to the predicted text, which implies that any text in an image is treated in the same direction such as from left to right by default. However, this is not true in the wild
  - solution & novelty
    -
  - the devil in the details
    - None

