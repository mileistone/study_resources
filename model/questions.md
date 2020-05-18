- 怎么选
  - 数据增强方法有哪些，怎么选择具体使用哪些数据增强方法
  - 数据预处理有哪些，怎么选择具体使用哪些预处理方法
    - mean是在训练集上计算还是全部数据集上计算
  - 分类器有哪些，怎么选择使用哪个分类器
  - normalization方法有哪些，怎么选择使用哪个normalization方法
    - 白化的直观理解
  - loss function这么多，怎么选择使用哪个loss function
  - loss归一化有哪些，怎么选择使用哪个loss归一化方法
  - 评价指标有哪些，怎么选择使用哪个评价指标，ROC、PR曲线选择标准
  - distance metric有哪些，怎么选择使用哪个distance metric方法
    - 用L2距离计算两张图像的相似性有什么问题
    
- 改进
  - resnetv1 -> resnetv2的改进是什么
  - resnet downsample模块是怎样的，怎么改进
  
- 优化
  - 为什么不要全零初始化
  - 正则项对bias正则吗
  - 正则化项的神经元解释
  - 为什么使用mini-batch gradient descent
  - 为什么mini-batch gradient descent奏效
  - 为什么不用single example gradient descent
  - step size的影响
  - sgd的优缺点
  - what about second order optimization method?
  
- 模型理解
  - 线性分类器的几何理解
  - 使用模板匹配来理解线性分类器
  - is dnn universal function approximator?
  - 分类和检索的区别与联系
  - translation invariance与translation equivariance
  - pooling能提高模型的translation invariance吗？为什么？
  - stride的pooling和stride的conv有什么区别？
  - stride的pooling能由多层conv来表达吗？
  
- 采样
  - 有哪些升采样的方法
  - 有哪些降采样的方法
  - 为什么要降采样
  - 降采样会带来什么问题
  
- debug
  - 如何做可视化
  - 优化之前需要做的check
  
- 实现
  - softmax实现的时候需要注意什么（softmax的数值稳定性如何保证）
  - dilated conv在tf中如何实现
  - reorg怎么通过基础模块实现
  - anchor致密化怎么通过基础模型实现
  
- 超参
  - 我们说的超参到底指哪些
  - 验证集怎么来的
  - 如果训练集数量很少，验证集怎么来
  - 交叉验证是什么意思，优缺点是什么
  - 当超参调完之后，是否要将验证集加入到训练集中重新训练
  - 验证集的大小和什么有关
  
- 目标检测
  - multi-scale问题怎么解决
  - 如何理解SNIP
  - roi align应该从哪层特征层抽取特征，有什么更好的方式
  
- 思维
  - cls2seg
    - 如何将fc转为conv
  - cls2det
  - detection
    - dense scene
    - crowded scene
    - small object
  - kfc实时检测、识别不稳定问题（相机噪声、检测框抖动）
  - 人脸检测与行人检测网络先验
  - 感受野不变，怎么让分辨率变大
  - anchor stride会影响什么
  - 分类为什么用average pooling而不用max pooling
  - 像素点的定义
  - translation equivariance
    - 检测的时候，输入图片平移一个像素点，检测结果就变掉，这是为什么
  - BN里的scale关掉会有什么问题
  - feature alignment
  - 模型收敛不好怎么定位问题
  - anomaly detection
  - 如果类别很多，使用softmax with cross entropy loss会有什么问题
  - ReLU会丢失一半信息，有什么改进方法
  - padding的方式有哪些，各有什么优缺点
