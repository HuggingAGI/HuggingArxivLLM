# ScreenSpot-Pro：专业级高分辨率计算机应用的图形界面定位

发布时间：2025年04月04日

`Agent` `专业领域` `GUI`

> ScreenSpot-Pro: GUI Grounding for Professional High-Resolution Computer Use

# 摘要

> # 摘要
近期，多模态大语言模型（MLLMs）在通用任务（如网页浏览和手机操作）中的GUI代理开发取得了显著进展。然而，这些模型在专业领域的应用仍处于探索阶段。专业领域特有的高分辨率显示屏、较小的目标尺寸以及复杂的环境，为GUI感知模型带来了独特挑战。本文推出ScreenSpot-Pro，这是一个全新基准测试，旨在严格评估MLLMs在高分辨率专业环境中的基础能力。该基准测试包含来自多个专业领域的高质量高分辨率图像，并附有专家标注，涵盖五个行业和三个操作系统的23种应用程序。现有GUI基础模型在该数据集上的表现欠佳，最佳模型的准确率仅为18.9%。我们的实验表明，缩小搜索范围能显著提升准确性。基于这一发现，我们提出了ScreenSeekeR，这是一种视觉搜索方法，通过利用强大规划器的GUI知识来引导级联搜索，在无需额外训练的情况下实现了48.1%的最先进性能。我们希望这一基准测试和研究发现将推动专业领域GUI代理的发展。代码、数据和排行榜可在https://gui-agent.github.io/grounding-leaderboard获取。

> Recent advancements in Multi-modal Large Language Models (MLLMs) have led to significant progress in developing GUI agents for general tasks such as web browsing and mobile phone use. However, their application in professional domains remains under-explored. These specialized workflows introduce unique challenges for GUI perception models, including high-resolution displays, smaller target sizes, and complex environments. In this paper, we introduce ScreenSpot-Pro, a new benchmark designed to rigorously evaluate the grounding capabilities of MLLMs in high-resolution professional settings. The benchmark comprises authentic high-resolution images from a variety of professional domains with expert annotations. It spans 23 applications across five industries and three operating systems. Existing GUI grounding models perform poorly on this dataset, with the best model achieving only 18.9%. Our experiments reveal that strategically reducing the search area enhances accuracy. Based on this insight, we propose ScreenSeekeR, a visual search method that utilizes the GUI knowledge of a strong planner to guide a cascaded search, achieving state-of-the-art performance with 48.1% without any additional training. We hope that our benchmark and findings will advance the development of GUI agents for professional applications. Code, data and leaderboard can be found at https://gui-agent.github.io/grounding-leaderboard.

[Arxiv](https://arxiv.org/abs/2504.07981)