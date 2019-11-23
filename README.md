# Reading-list-in-2019

## Knowledge Distillation:
- **Basic work**: "Distilling the Knowledge in a Neural Network", in NIPS, 2014.
- **Mimic Feature Maps**: "Fitnets: Hints for thin deep nets", in ICLR, 2014.
- **Mimic Attention Maps**: "Paying more attention to attention: Improving the performance of CNN via attention transfer", in ICLR, 2017.
- **Mimic Weight Matrix**: "A gift from knowledge distillation: Fast Optimization, Network Minimization and Transfer Learning", in CVPR, 2017.
- **Mimic Feature Dist.**: "Like What You Like: Knowledge Distill via Neuron Selectivity Transfer", in CVPR, 2017.
- **Mimic by Adversary**: "Training Shallow and Thin Networks for Acceleration via Knowledge Distillation with Conditional Adversarial Networks", 2017.
- **Multi teachers**: "Amalgamating Knowledge towards Comprehensive Classification", in AAAI, 2019.
- **DML**: "Deep Mutual Learning", in CVPR, 2018.
- **Dual Student**: "Dual Student: Breaking the Limits of the Teacher in Semisupervised Learning", in ICCV, 2019. (根据两网络的stability设置相互学习的条件)⭐️⭐️⭐️


## Learning with Noisy Labels:
- **Co-teach**: "Co-teaching: Robust Training of Deep Neural Networks with Extremely Noisy Labels", in NIPS, 2018.
- **Mutual Attention**: "A Two-Stream Mutual Attention Network for Semi-supervised Biomedical Segmentation with Noisy Labels", in AAAI, 2019.


## Domain Adaptation:
- **Basic work**: "Domain-Adversarial Training of Neural Networks", in Journal of Machine Learning Research, 2016.
- **Attention based**: "Transferable Attention for Domain Adaptation", in AAAI, 2019.
- **Structured KD**: "Structured Knowledge Distillation for Semantic Segmentation", in CVPR, 2019.


## Weakly Supervised:
- **Cls. & Seg.**: "Weakly-Supervised Simultaneous Evidence Identification and Segmentation for Automated Glaucoma Diagnosis", in AAAI, 2019. (写的一般，没太看懂)．


## Saliency Detection:
- **Select & Remove salient region**: "Real Time Image Saliency for Black Box Classifiers", in NIPS, 2017.⭐️⭐️⭐️⭐️
- **Multi-scale with SE block**: "Pyramid Feature Selective Network for Saliency detection", in CVPR, 2019.⭐️⭐️⭐️
- **Attentive feedback & boundary aware**: "AFNet: Attentive Feedback Network for Boundary-Aware Salient Object Detection", in CVPR, 2019. （Ternary saliency有点意思）⭐️⭐️⭐️
- **Feature Selection**: "Efficient saliency detection using convolutional neural networks with feature selection", in Information Science, 2018.⭐️⭐️
- **Deep Supervision**: "DNA: Deeply-supervised Nonlinear Aggregation for Salient Object Detection", in CVPR, 2019.⭐️⭐️⭐️
- **Mutual Supervision**: "Multi-source weak supervision for saliency detection" in ICCV, 2019. (classification网络和caption得到的saliency互相提供psuedo lable监督)⭐️⭐️⭐️


## Attention:
- **Attention prior**: "Attention Based Glaucoma Detection: A Large-scale Database and CNN Model", in CVPR, 2019. (和ISBI的思路类似)．⭐️⭐️
- **Self attention**: "SSA-CNN: Semantic Self-Attention CNN for Pedestrian Detection", in Arxiv, 2019. (segmentation results concat feature maps).⭐️⭐️⭐️
- **Spatial attention**: "LEARN TO PAY ATTENTION", in ICLR, 2018.⭐️⭐️⭐️
- **Attention Mask**: "Attention Branch Network : Learning of Attention Mechanism for Visual Explanation", in CVPR, 2019.⭐️⭐️
- **Attention Consistency**: "Visual Attention Consistency under Image Transforms for Multi-label Image Classification", in CVPR, 2019. (先变换后求attention和先求attention后变换之间保持一致)．⭐️⭐️⭐️
- **Attention Constraint**: "DELTA: DEep Learning Transfer using Feature Map with Attention for Convolutional Networks", in ICLR, 2019. (限制pre-trained和fine-tuned network产生的attention map接近，避免fine-tune之后跑太偏产生over-fitting)．⭐️⭐️
- **Spatial & Task Attention**: "A Dual Attention Network with Semantic Embedding for Few-shot Learning", in AAAI, 2019. ⭐️⭐️⭐️⭐️
- **Spatial Attention**: "PSANet: Point-wise spatial attention network for scene parsing", in ECCV, 2018. (bi-direction spatial attention和over-completed conv有点意思)．⭐️⭐️⭐️⭐️
- **Depth Attention**: "Depth-attentional Features for Single-image Rain Removal", in CVPR, 2019. (之后做polyp detection可以考虑用depth信息)．⭐️⭐️⭐️
- **Pyramid Attention**: "Salient Object Detection with Pyramid Attention and Salient Edges", in CVPR, 2019. ⭐️⭐️
- **Co-Attention**: "See More, Know More: Unsupervised Video Object Segmentation with Co-Attention Siamese Networks", in CVPR, 2019. （之后可以仔细研究一下Co-attention）. ⭐️⭐️⭐️⭐️
- **Contextual Attention**: "PiCANet: Learning Pixel-wise Contextual Attention for Saliency Detection", in CVPR, 2018. ⭐️⭐️⭐️⭐️⭐️
- **Attention Dropout**: "Attention-based Dropout Layer for Weakly Supervised Object Localization", in CVPR, 2019. ⭐️⭐️⭐️
- **Spatial Enhance**: "Spatial Group-wise Enhance (SGE): Improving Semantic Feature Learning in Convolutional Networks", in Arxiv. (根据global和local feature的similarity分配weight).⭐️
- **Gather-Excite**: "Gather-Excite(GE): Exploiting Feature Context in Convolutional Neural Networks", in NIPS, 2018. (对SE module的改进)⭐️⭐️⭐️
- **GC-Net**: "GCNet: Non-local Networks Meet Squeeze-Excitation Networks and Beyond", in CVPR, 2019. (SE和nonlocal的结合)⭐️⭐️⭐️⭐️
- **Attention Mining**: "Tell Me Where to Look: Guided Attention Inference Network", in CVPR, 2018. (根据attention对原图mask之后也作为网络输入)⭐️⭐️
- **Spatial Attention**: "An Empirical Study of Spatial Attention Mechanisms in Deep Networks", in ICCV, 2019. (深入分析各种attention mechanism，值得研究)⭐️⭐️⭐️⭐️
- **Attention Mask**: "Learning to Detect Salient Objects with Image-level Supervision", in CVPR, 2017. ⭐️⭐️⭐️
- **Self-Critic**: "Self-Critical Attention Learning for Person ReIdentification", in ICCV, 2019. ⭐️⭐️⭐️⭐️
- **Self Attention Distillation**: "Learning Lightweight Lane Detection CNNs by Self Attention Distillation", in AAAI, 2019. (浅层学习深层attention maps)⭐️⭐️⭐️
- **Attention Guide**: "Guided Soft Attention Network for Classification of Breast Cancer Histopathology Images", in TMI, 2019. ⭐️


## Non-local:
- **Basic work**: "Non-local Neural Networks", in CVPR, 2018.⭐️⭐️⭐️⭐️⭐️
- **Spatial & Channel-wise Non-local**: "Dual Attention Network for Scene Segmentation", in CVPR, 2019.⭐️⭐️⭐️⭐️
- **Residual Non-local Attention**: "RESIDUAL NON-LOCAL ATTENTION NETWORKS FOR IMAGE RESTORATION", in ICLR, 2019.⭐️⭐️⭐️
- **Non-local & SENet**: "GCNet: Non-local Networks Meet Squeeze-Excitation Networks and Beyond", in Arxiv, 2019.⭐️⭐️⭐️⭐️
- **Non-local & Context Encoding**: "Non-Local Context Encoder: Robust Biomedical Image Segmentation against Adversarial Attacks", in AAAI oral, 2019.⭐️⭐️⭐️


## Attention Guided Resampling:
- **Trilinear Attention Sampling**: "Looking for the Devil in the Details : Learning Trilinear Attention Sampling Network for Fine-grained Image Recognition", in CVPR, 2019.⭐️⭐️⭐️⭐️
- **Saliency-based Sampling**: "Learning to Zoom : a Saliency-Based Sampling", in ECCV, 2018.⭐️⭐️⭐️
- **Retargeting**: "Weakly- and Self-Supervised Learning for Content-Aware Deep Image", in ICCV, 2017. ⭐️⭐️⭐️

## Semantic Segmentation:
- **Sub-net & Sub-stage aggregation**: "DFANet: Deep Feature Aggregation for Real-Time Semantic Segmentation", in CVPR, 2019.⭐️⭐️
- **Saliency transformation**: "Saliency Transformation Network: Incorporating Multi-stage Visual Cues for Pancreas Segmentation", in CVPR, 2018. (利用saliency对原图crop得到fine-scaled input)．⭐️⭐️⭐️⭐️

## Network Ensemble:
- **High/low scale networks**: "High Frequency Residual Learning for Multi-Scale Image Classification", in Arxiv, submitted to BMCV.⭐️⭐️

## Second-order Information:
- **Basic Work**: "Is Second-order Information Helpful for Large-scale Visual Recognition?", in ICCV, 2017.⭐️⭐️⭐️⭐️
- **Second-order & SENet**: "Second-order Attention Network for Single Image Super-Resolution", in CVPR oral, 2019.⭐️⭐️⭐️⭐️
- **Second-order channel attention**: "Global Second-order Pooling Convolutional Networks", in CVPR, 2019. ⭐️⭐️⭐️⭐️⭐️
- **First & Second-order Feature**: "FASON: First and second order information fusion network for texture recognition", in CVPR, 2017. ⭐️⭐️⭐️
- **Second-order feature fusion**: "SORT: Second-Order Response Transform for Visual Recognition", in ICCV, 2017.⭐️⭐️ 
- **Covariance Pooling**: "Remote sensing scene classification using multilayer stacked covariance pooling", 2018 Q1. ⭐️
- **SONA**: "Second-order Non-local Attention Networks for Person Re-identification", in ICCV, 2019. ⭐️⭐️ 

## Loss Function:
- **AdaCos Loss**: "AdaCos: Adaptively Scaling Cosine Logits for Effectively Learning Deep Face Representations", in CVPR, 2019. (对cosface loss的改进)⭐️⭐️⭐️⭐️
- **Margin ranking Loss**: "Multi-Task Deep Model with Margin Ranking Loss for Lung Nodule Analysis", in TMI, 2019. ⭐️⭐️


## Deformable Convolution:
- **Basic Work**: "Deformable Convolutional Networks", in CVPR, 2017. ⭐️⭐️⭐️⭐️⭐️
- **Basic Work**: "Deformable ConvNets v2: More Deformable, Better Results", in Arxiv. ⭐️⭐️⭐️⭐️
- **Location aware deformable conv**: "Object detection with location-aware deformable convolution and backward attention filtering", in CVPR, 2019. (和deformable conv不同，本文的每个采样点都是作为生成offsets的中心)⭐️⭐️⭐️

## 待读：

