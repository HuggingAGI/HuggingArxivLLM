# 利用蒙特卡洛树搜索评估多模态大语言模型的视频字幕生成能力

发布时间：2025年06月11日

`LLM应用` `计算机视觉`

> Evaluating Multimodal Large Language Models on Video Captioning via Monte Carlo Tree Search

# 摘要

> 视频描述任务是评估多模态大语言模型（MLLMs）理解视频能力的重要手段。然而，现有的基准测试和评估协议却面临关键问题，例如关键点的创建不足或过于单一、数据创建成本过高，以及评估范围有限。为了解决这些问题，我们提出了一种名为AutoCaption的自动框架。该框架利用蒙特卡洛树搜索（MCTS）来构建大量且多样化的描述性句子（即关键点），从而全面、迭代地表示视频内容。这种迭代式的描述策略能够持续提升视频细节的捕捉，如动作、物体属性、环境细节等。我们通过AutoCaption构建了MCTS-VCB，这是一个涵盖视频细节的细粒度视频描述基准测试，从而能够全面评估MLLMs在视频描述任务上的表现。我们在MCTS-VCB上评估了20多种不同规模的开源和闭源MLLMs。结果显示，MCTS-VCB能够有效且全面地评估视频描述能力，其中Gemini-1.5-Pro达到了最高的F1分数71.2。有趣的是，我们使用AutoCaption生成的数据对InternVL2.5-8B进行了微调，这帮助模型在MCTS-VCB上整体提升了25.0%，在DREAM-1K上提升了16.3%，进一步证明了AutoCaption的有效性。代码和数据可在https://github.com/tjunlp-lab/MCTS-VCB获取。

> Video captioning can be used to assess the video understanding capabilities of Multimodal Large Language Models (MLLMs). However, existing benchmarks and evaluation protocols suffer from crucial issues, such as inadequate or homogeneous creation of key points, exorbitant cost of data creation, and limited evaluation scopes. To address these issues, we propose an automatic framework, named AutoCaption, which leverages Monte Carlo Tree Search (MCTS) to construct numerous and diverse descriptive sentences (\textit{i.e.}, key points) that thoroughly represent video content in an iterative way. This iterative captioning strategy enables the continuous enhancement of video details such as actions, objects' attributes, environment details, etc. We apply AutoCaption to curate MCTS-VCB, a fine-grained video caption benchmark covering video details, thereby enabling a comprehensive evaluation of MLLMs on the video captioning task. We evaluate more than 20 open- and closed-source MLLMs of varying sizes on MCTS-VCB. Results show that MCTS-VCB can effectively and comprehensively evaluate the video captioning capability, with Gemini-1.5-Pro achieving the highest F1 score of 71.2. Interestingly, we fine-tune InternVL2.5-8B with the AutoCaption-generated data, which helps the model achieve an overall improvement of 25.0% on MCTS-VCB and 16.3% on DREAM-1K, further demonstrating the effectiveness of AutoCaption. The code and data are available at https://github.com/tjunlp-lab/MCTS-VCB.

[Arxiv](https://arxiv.org/abs/2506.11155)