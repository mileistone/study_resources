### 2022-05-10
#### Dropout, drop channel, drop path, drop layer
- [1904.03392][Efficient and Effective Dropout for Deep Convolutional Neural Networks](https://arxiv.org/abs/1904.03392)
  - knowledge distillation

### 2022-05-07
#### Efficient video classification
- [ICLR2021][VA-RED2: Video Adaptive Redundancy Reduction](https://arxiv.org/abs/2102.07887)
  - not suitable for GPU
  - recognize redudandent feature map in temporal or channels
  - L1 norm for redudandent factor
- [ICCV2021][MGSampler: An Explainable Sampling Strategy for Video Action Recognition](https://arxiv.org/abs/2104.09952)
- [ICCV2021][Adaptive Focus for Efficient Video Recognition](https://openaccess.thecvf.com/content/ICCV2021/papers/Wang_Adaptive_Focus_for_Efficient_Video_Recognition_ICCV_2021_paper.pdf)
  - reinforcement learning
  - spatial and temporal
- [CVPR2021][Less is More: CLIPBERT for Video-and-Language Learning via Sparse Sampling](https://arxiv.org/abs/2102.06183)
- [BMVC2021][Conditional Model Selection for Efficient Video Understanding](https://www.bmvc2021-virtualconference.com/assets/papers/1376.pdf)
- [NIPS2020][Glance and Focus: a Dynamic Approach to Reducing Spatial Redundancy in Image Classification](https://proceedings.neurips.cc/paper/2020/file/1963bd5135521d623f6c29e6b1174975-Paper.pdf)
  - reinforcement learning
- [CVPR2019][Efficient Video Classification Using Fewer Frames](https://openaccess.thecvf.com/content_CVPR_2019/html/Bhardwaj_Efficient_Video_Classification_Using_Fewer_Frames_CVPR_2019_paper.html)
- [CVPR2019][AdaFrame: Adaptive Frame Selection for Fast Video Recognition](https://arxiv.org/abs/1811.12432)
  - reinforcement learning
- [IJCAI2018][Watching a Small Portion could be as Good as Watching All: Towards Efficient Video Classification](https://www.ijcai.org/Proceedings/2018/0098.pdf)
  - reinforcement learning

#### Conditional cumputation
- [CVPR2018][Learning Strict Identity Mappings in Deep Residual Networks](https://arxiv.org/abs/1804.01661)
- [ECCV2018][Convolutional Networks with Adaptive Inference Graphs](https://arxiv.org/abs/1711.11503)
  - Gumbel sampling
- [CVPR2017][Spatially Adaptive Computation Time for Residual Networks](https://arxiv.org/abs/1612.02297)
  - mask is determined by a probability predicted by an extra head
- [NIPS2016][PerforatedCNNs: Acceleration through elimination of redundant convolutions](https://proceedings.neurips.cc/paper/2016/file/f0e52b27a7a5d6a1a87373dffa53dbe5-Paper.pdf)
  - mask is determined by gradient  

### 2022-05-02
#### Model design
- [2204.07143][Neighborhood Attention Transformer](https://arxiv.org/abs/2204.07143)
- [ICLR2022][MobileViT: Light-weight, General-purpose, and Mobile-friendly Vision Transformer](https://arxiv.org/abs/2110.02178)
  - Combine the strengths of CNNs and ViTs to build a light-weight and low latency network for mobile vision tasks
- [NIPS2021][Revisiting ResNets: Improved Training and Scaling Strategies](https://arxiv.org/abs/2103.07579)
  -  Training and scaling strategies may matter more than architectural changes, and further, that the resulting ResNets match recent state-of-the-art models
  -  We show that the best performing scaling strategy depends on the training regime and offer two new scaling strategies: (1) scale model depth
in regimes where overfitting can occur (width scaling is preferable otherwise); (2) increase image resolution more slowly than previously recommended 
- [CVPR2021][Rethinking Channel Dimensions for Efficient Model Design](https://openaccess.thecvf.com/content/CVPR2021/html/Han_Rethinking_Channel_Dimensions_for_Efficient_Model_Design_CVPR_2021_paper.html)
- [CVPR2020][Designing Network Design Spaces](https://arxiv.org/abs/2003.13678)

### 2022-04-19
#### Stem design
- [2201.09792][Patches Are All You Need?](https://arxiv.org/abs/2201.09792)
- [NIPS2021][Early Convolutions Help Transformers See Better](https://proceedings.neurips.cc/paper/2021/hash/ff1418e8cc993fe8abcfe3ce2003e5c5-Abstract.html)
- [CVPR2021][Fast and Accurate Model Scaling](https://openaccess.thecvf.com/content/CVPR2021/html/Dollar_Fast_and_Accurate_Model_Scaling_CVPR_2021_paper.html)
- [ICCV2021][Incorporating Convolution Designs into Visual Transformers](http://openaccess.thecvf.com/content/ICCV2021/html/Yuan_Incorporating_Convolution_Designs_Into_Visual_Transformers_ICCV_2021_paper.html)
- [ICCV2021][Tokens-to-Token ViT: Training Vision Transformers from Scratch on ImageNet](https://openaccess.thecvf.com/content/ICCV2021/html/Yuan_Tokens-to-Token_ViT_Training_Vision_Transformers_From_Scratch_on_ImageNet_ICCV_2021_paper.html)
- [2105.02723][Do You Even Need Attention? A Stack of Feed-Forward Layers Does Surprisingly Well on ImageNet](https://arxiv.org/abs/2105.02723)
- [ICCV2019 Workshop][Non-Discriminative Data or Weak Model? On the Relative Importance of Data and Model Resolution](https://openaccess.thecvf.com/content_ICCVW_2019/html/RLQ/Sandler_Non-Discriminative_Data_or_Weak_Model_On_the_Relative_Importance_of_ICCVW_2019_paper.html)
- [2105.03404][ResMLP: Feedforward networks for image classification with data-efficient training](https://arxiv.org/abs/2105.03404)
- [awesome-vit](https://github.com/open-mmlab/awesome-vit)

### 2022-04-08
#### Pinned Memory / Page-Locked Memory
- [PyTorch: How does pin_memory work in Dataloader](https://stackoverflow.com/questions/55563376/pytorch-how-does-pin-memory-work-in-dataloader)
- [How to Optimize Data Transfers in CUDA C/C++](https://developer.nvidia.com/blog/how-optimize-data-transfers-cuda-cc/)
- [Page-Locked Host Memory for Data Transfer](https://leimao.github.io/blog/Page-Locked-Host-Memory-Data-Transfer/)

### 2022-04-07
#### JPEG
- [Image-Compression-using-MATLAB-Project-Report](https://www.slideshare.net/kgaurav113/image-compression-using-matlab-project-report?next_slideshow=66007871)
- [JEPG encoding](https://cseweb.ucsd.edu/classes/sp03/cse126/lecture/lecture5.pdf)
- [JPEG Image Compression Systems](https://www.ece.ucdavis.edu/cerl/reliablejpeg/compression/)
- [JPEG: Image compression algorithm](http://pi.math.cornell.edu/~web6140/TopTenAlgorithms/JPEG.html)
- [PIL convert('ycbcr') gives different result from formula](https://github.com/python-pillow/Pillow/issues/4668)

### 2019-11-01
- [Detectron1-Comparisons](https://github.com/facebookresearch/detectron2/tree/master/configs/Detectron1-Comparisons)

### 2019-08-19
- [Adversarial Examples Are Not Bugs, They Are Features](https://arxiv.org/abs/1905.02175)

### 2019-08-06
- [A Survival Guide to a PhD](https://karpathy.github.io/2016/09/07/phd/)

### 2019-08-01
- [An embarrassingly simple approach to neural multiple instance classification](https://arxiv.org/abs/1905.01947)

- [A 2019 Guide to Semantic Segmentation](https://heartbeat.fritz.ai/a-2019-guide-to-semantic-segmentation-ca8242f5a7fc)

### 2019-02-13
- [Approximating CNNs with Bag-of-local-Features models works surprisingly well on ImageNet](https://openreview.net/forum?id=SkfMWhAqYQ)

- [ImageNet-trained CNNs are biased towards texture; increasing shape bias improves accuracy and robustness](https://arxiv.org/abs/1811.12231)

- [Thoughts on the BagNet Paper](https://blog.evjang.com/2019/02/bagnet.html)
- [What are the main differences between the word embeddings of ELMo, BERT, Word2vec, and GloVe](https://www.reddit.com/r/MachineLearning/comments/aptwxm/d_what_are_the_main_differences_between_the_word/)

### 2019-01-16
- [Self-Driving Cars: A Survey](https://arxiv.org/abs/1901.04407)

### 2019-01-15
- [Hungarian algorithm](https://www.cc.gatech.edu/~rpeng/18434_S15/hungarianAlgorithm.pdf)
- [Bipartite Matching](https://www.cse.ust.hk/~golin/COMP572/Notes/Matching.pdf)

### 2019-01-09
- [Transformer Implementation Details Not Described in The Paper](https://tunz.kr/post/4)

### 2019-01-08
- [Gaussian processes](https://planspace.org/20181226-gaussian_processes_are_not_so_fancy/)
- [TVM](https://sampl.cs.washington.edu/tvmconf/#about-tvmconf)
