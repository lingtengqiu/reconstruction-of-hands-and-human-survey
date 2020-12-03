# About Me
这是我博士第一年在手部和人体相关的paper 中的survey 主要是基于现在的视觉顶会展开的分别为CVPR，ICCV和ECCV

# Hand and Human

## NIPS2020 
- Detecting Hands and Recognizing Physical Contact in the Wild\[[Paper](https://proceedings.neurips.cc//paper/2020/file/595373f017b659cb7743291e920a8857-Paper.pdf)  [Code](https://github.com/cvlab-stonybrook/ContactHands)\]

## ECCV2020
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
- HOPE-Net: A Graph-based Model for Hand-Object Pose Estimation\[[Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Doosti_HOPE-Net_A_Graph-Based_Model_for_Hand-Object_Pose_Estimation_CVPR_2020_paper.pdf)  [Code](https://github.com/bardiadoosti/HOPE)\]

### without code
- HandVoxNet: Deep Voxel-Based Network for 3D Hand Shape and Pose Estimation From a Single Depth Map\[[Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Malik_HandVoxNet_Deep_Voxel-Based_Network_for_3D_Hand_Shape_and_Pose_CVPR_2020_paper.pdf)\]



## ICCV2019
- End-to-end Hand Mesh Recovery from a Monocular RGB Image\[[Paper](https://arxiv.org/abs/1902.09305) [Code](https://github.com/MandyMo/HAMR)\]
- Exploiting Spatial-temporal Relationships for 3D Pose Estimation via Graph Convolutional Networks\[[Paper](https://openaccess.thecvf.com/content_ICCV_2019/papers/Cai_Exploiting_Spatial-Temporal_Relationships_for_3D_Pose_Estimation_via_Graph_Convolutional_ICCV_2019_paper.pdf) [Code](https://github.com/vanoracai/Exploiting-Spatial-temporal-Relationships-for-3D-Pose-Estimation-via-Graph-Convolutional-Networks)\] 这篇工作其实就是借鉴了st-gcn的思路将时序估计问题转化到了3d pose 估计上


