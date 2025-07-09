# SenseShift6D: 多模态 RGB-D 基准测试，用于跨环境与传感器变化的鲁棒 6D 姿态估计

发布时间：2025年07月08日

`其他` `计算机视觉` `机器人学`

> SenseShift6D: Multimodal RGB-D Benchmarking for Robust 6D Pose Estimation across Environment and Sensor Variations

# 摘要

> # 摘要  
    最近，6D物体姿态估计技术在LM-O、YCB-V和T-Less等代表性基准测试中表现出色。然而，现有数据集大多在固定光照和相机设置下采集，对现实世界中光照、曝光、增益或深度传感器模式变化的实际影响，以及测试时通过传感器控制缓解这些变化的潜力，尚未得到充分研究。  
    为解决这一问题，我们推出了SenseShift6D——首个专注于传感器与光照组合的RGB-D数据集。该数据集涵盖了13种RGB曝光、9种RGB增益、自动曝光、4种深度捕获模式以及5种光照水平的物理扫描。针对喷雾瓶、脆片罐和铝箔盒这三种常见家用物体，我们采集了10.19万RGB图像和1万深度图像，为每种物体姿态提供了1,380种独特的传感器-光照组合。  
    在SenseShift6D数据集上进行的实验表明，与数字数据增强相比，测试时应用传感器控制能带来更大的性能提升，其效果可与增加真实世界训练数据量和多样性相媲美，甚至更优。单独调整RGB或深度传感器均能取得良好效果，而联合优化多模态RGB-D配置则能进一步提升性能。  
    SenseShift6D将6D姿态评估范式从数据驱动扩展至传感器感知稳健性，为适应性强、自我调节的感知系统奠定了基础，使系统能在复杂多变的现实环境中稳健运行。  
    我们的SenseShift6D数据集已在Hugging Face平台上线，相关代码和脚本也可在GitHub上获取。  
    

> Recent advances on 6D object-pose estimation has achieved high performance on representative benchmarks such as LM-O, YCB-V, and T-Less. However, these datasets were captured under fixed illumination and camera settings, leaving the impact of real-world variations in illumination, exposure, gain or depth-sensor mode - and the potential of test-time sensor control to mitigate such variations - largely unexplored. To bridge this gap, we introduce SenseShift6D, the first RGB-D dataset that physically sweeps 13 RGB exposures, 9 RGB gains, auto-exposure, 4 depth-capture modes, and 5 illumination levels. For three common household objects (spray, pringles, and tincase), we acquire 101.9k RGB and 10k depth images, which can provide 1,380 unique sensor-lighting permutations per object pose. Experiments with state-of-the-art models on our dataset show that applying sensor control during test-time induces greater performance improvement over digital data augmentation, achieving performance comparable to or better than costly increases in real-world training data quantity and diversity. Adapting either RGB or depth sensors individually is effective, while jointly adapting multimodal RGB-D configurations yields even greater improvements. SenseShift6D extends the 6D-pose evaluation paradigm from data-centered to sensor-aware robustness, laying a foundation for adaptive, self-tuning perception systems capable of operating robustly in uncertain real-world environments. Our dataset is available at: huggingface.co/datasets/Yegyu/SenseShift6D Associated scripts can be found at: github.com/yegyu-han/SenseShift6D

[Arxiv](https://arxiv.org/abs/2507.05751)