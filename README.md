# About Me  
这是我博士第一年在手部和人体相关的paper 中的survey 主要是基于现在的视觉顶会展开的分别为CVPR，ICCV和ECCV

This is paper list relating with 3d hand and human reconstruction. Note that these papers are collected mainly from CVPR, ICCV, ECCV and NIPS. 

# Hand and Human

## LeadBoard
- [Fri-hand](https://competitions.codalab.org/competitions/21238)

## Arxiv
- [Frankmocap:Fast monocular 3d hand and body motion capture by regres-sion and integration](https://arxiv.org/abs/2008.08324)
- [Reconstructing Hand-Object Interactions in the Wild](https://arxiv.org/pdf/2012.09856.pdf)
- [End-to-End Human Pose and Mesh Reconstruction with Transformers](https://arxiv.org/pdf/2012.09760.pdf)
- [Unsupervised Learning on Monocular Videos for 3D Human Pose Estimation](https://arxiv.org/pdf/2012.01511.pdf)
- [EventHands: Real-Time Neural 3D Hand Reconstruction from an Event Stream](cn.arxiv.org/pdf/2012.06475v2) Note that **MPI**

## NIPS2020 
- Detecting Hands and Recognizing Physical Contact in the Wild\[[Paper](https://proceedings.neurips.cc//paper/2020/file/595373f017b659cb7743291e920a8857-Paper.pdf)  [Code](https://github.com/cvlab-stonybrook/ContactHands)\]

## ECCV2020


- SMPLy Benchmarking 3D Human Pose Estimation in the Wild\[[Paper](https://arxiv.org/pdf/2012.02743.pdf) [Code]()\] 
- Monocular Expressive Body Regression through Body-Driven Attention\[[Paper](https://expose.is.tue.mpg.de/) [Code](https://github.com/vchoutas/expose)\] 

- Pose2Mesh: Graph Convolutional Network for 3D Human Pose and Mesh Recovery from a 2D Human Pose\[[Paper](https://arxiv.org/pdf/2008.09047.pdf) [Code](https://github.com/hongsukchoi/Pose2Mesh_RELEASE)\]


- Coherent Reconstruction of Multiple Humans from a Single Image\[[Paper](https://arxiv.org/pdf/2006.08586.pdf) [Code](https://github.com/JiangWenPL/multiperson)\]   注意这篇工作的main contribution 我认为是，interpenetration loss，用于解插入问题，另外一个是depth loss，来解决估计的mesh的深度错误
- InterHand2.6M: A Dataset and Baseline for 3D Interacting Hand Pose Estimation from a Single RGB Image\[[Paper](https://arxiv.org/abs/2008.09309) [Code](https://github.com/facebookresearch/InterHand2.6M)\]
- I2L-MeshNet: Image-to-Lixel Prediction Network for Accurate 3D Human Pose and Mesh Estimation from a Single RGB Image\[[Paper](https://arxiv.org/abs/2008.03713) [Code](https://github.com/mks0601/I2L-MeshNet_RELEASE)\] 非常有意思的一篇，用lixel 来优化 3d heatmap中的memory 和complexity 爆炸问题
- DeepHandMesh: A Weakly-supervised Deep Encoder-Decoder Framework for High-fidelity Hand Mesh Modeling\[[Paper](https://link.springer.com/chapter/10.1007/978-3-030-58536-5_26) [Code](https://mks0601.github.io/DeepHandMesh/)\]
- JGR-P2O: Joint Graph Reasoning based Pixel-to-Offset Prediction Network for 3D Hand Pose Estimation from a Single Depth Image\[[Paper](https://arxiv.org/abs/2007.04646) [Code](https://github.com/fanglinpu/JGR-P2O)\] **未读**
### without Code
- [Adaptive Computationally Efficient Network forMonocular 3D Hand Pose Estimation](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123490120.pdf)
- [SeqHAND: RGB-Sequence-Based3D Hand Pose and Shape Estimation](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123570120.pdf)
- [Weakly Supervised 3D Hand Pose Estimation via Biomechanical Constraints](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123620205.pdf)
- [Hand-Transformer: Non-Autoregressive Structured Modeling for 3D Hand Pose Estimation](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123700018.pdf)
- [Dual Grid Net: Hand Mesh VertexRegression from Single Depth Maps](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123750443.pdf)


## CVPR2020


- VIBE: Video Inference for Human Body Pose and Shape Estimation  \[[Paper](https://arxiv.org/pdf/1912.05656.pdf)  [Code](https://github.com/mkocabas/VIBE)\]

这篇文章的亮点在于摒弃了VAE 中的合理特征表达，而使用了GAN来对抗生成，输出的视频mesh 是否合理，本质上而言是个非常有趣的代码。另外该paper有很多的技术细节，使用可连续表达的6 个变量来表达旋转变量而不是使用

- Cascaded Deep Monocular 3D Human Pose Estimation with EvolutionaryTraining Data \[[Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Li_Cascaded_Deep_Monocular_3D_Human_Pose_Estimation_With_Evolutionary_Training_CVPR_2020_paper.pdf)  [Code](https://github.com/Nicholasli1995/EvoSkeleton)\]

这篇文章提出了一种数据扩充的方法来扩充我们的数据集，并且用CVPR2015的dictionary来inference 扩充的数据集是否okay。前面其用了更好的2d posenet 自然可以取得比较好的效果。 并且还提供了一个3
00张图片的UDPW 数据集。


- HOPE-Net: A Graph-based Model for Hand-Object Pose Estimation\[[Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Doosti_HOPE-Net_A_Graph-Based_Model_for_Hand-Object_Pose_Estimation_CVPR_2020_paper.pdf)  [Code](https://github.com/bardiadoosti/HOPE)\]

- Weakly-Supervised Mesh-Convolutional Hand Reconstruction in the Wild\[[Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Kulon_Weakly-Supervised_Mesh-Convolutional_Hand_Reconstruction_in_the_Wild_CVPR_2020_paper.pdf
) [Code](https://arielai.com/mesh_hands)\]

- Monocular Real-Time Hand Shape and Motion Capture Using Multi-Modal Data\[[Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Zhou_Monocular_Real-Time_Hand_Shape_and_Motion_Capture_Using_Multi-Modal_Data_CVPR_2020_paper.pdf
) [Code](https://github.com/CalciferZh/minimal-hand)\]


### without code
- HandVoxNet: Deep Voxel-Based Network for 3D Hand Shape and Pose Estimation From a Single Depth Map\[[Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Malik_HandVoxNet_Deep_Voxel-Based_Network_for_3D_Hand_Shape_and_Pose_CVPR_2020_paper.pdf)\]



## CVPR2019
- [Expressive Body Capture](https://arxiv.org/pdf/1904.05866.pdf)



## ICCV2019
- End-to-end Hand Mesh Recovery from a Monocular RGB Image\[[Paper](https://arxiv.org/abs/1902.09305) [Code](https://github.com/MandyMo/HAMR)\]
- Exploiting Spatial-temporal Relationships for 3D Pose Estimation via Graph Convolutional Networks\[[Paper](https://openaccess.thecvf.com/content_ICCV_2019/papers/Cai_Exploiting_Spatial-Temporal_Relationships_for_3D_Pose_Estimation_via_Graph_Convolutional_ICCV_2019_paper.pdf) [Code](https://github.com/vanoracai/Exploiting-Spatial-temporal-Relationships-for-3D-Pose-Estimation-via-Graph-Convolutional-Networks)\] 这篇工作其实就是借鉴了st-gcn的思路将时序估计问题转化到了3d pose 估计上


## CVPR 2015
Although this work was released serveral years ago, the contribution related with prior angle limts still is useful. Therefore this paper is worthy of reading.   
- [Pose-Conditioned Joint Angle Limits for 3D Human Pose Reconstruction](https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Akhter_Pose-Conditioned_Joint_Angle_2015_CVPR_paper.pdf)

## ICML 2014
The most of works leaded by MPI followed the paper variational auto-decode to provide a prior about poses. Therefore I think this paper is useful to us.

- [Auto-Encoding Variational Bayes](https://arxiv.org/pdf/1312.6114.pdf）
- [Tutorial for VAE](https://zhuanlan.zhihu.com/p/34998569). If you still find that VAE is too hard to understand, pls, seeing the tutorial of VAE written by [CMU](https://arxiv.org/pdf/1606.05908.pdf)  



# Rendering

## Arixv
- [pixelNeRF: Neural Radiance Fields from One or Few Images](https://arxiv.org/pdf/2012.02190.pdf)



# Representation

## ECCV2020
- Curriculum DeepSDF\[[Paper](https://arxiv.org/abs/2003.08593) [Code](https://github.com/Janus-Shiau/6d_rot_tensorflow)]

- On the continuity of rotation representations in neural networks\[[Paper](https://openaccess.thecvf.com/content_CVPR_2019/papers/Zhou_On_the_Continuity_of_Rotation_Representations_in_Neural_Networks_CVPR_2019_paper.pdf)\]

## CVPR2019
- [deepSDF](https://openaccess.thecvf.com/content_CVPR_2019/papers/Park_DeepSDF_Learning_Continuous_Signed_Distance_Functions_for_Shape_Representation_CVPR_2019_paper.pdf)



