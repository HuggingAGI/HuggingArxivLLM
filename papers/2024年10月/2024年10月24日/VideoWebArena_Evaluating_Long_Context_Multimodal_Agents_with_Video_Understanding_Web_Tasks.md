# VideoWebArena：借助视频理解网络任务对长上下文多模态代理进行评估

发布时间：2024年10月24日

`Agent` `多模态代理`

> VideoWebArena: Evaluating Long Context Multimodal Agents with Video Understanding Web Tasks

# 摘要

> 视频常被用于以有别于文本和静态图像单独所能给予的方式来学习或提取完成任务所需的信息。然而，众多现有的代理基准测试都忽视了长上下文视频理解，反倒聚焦于文本或静态图像输入。为填补这一空缺，我们推出了 VideoWebArena（VideoWA），这是一个用于评测长上下文多模态代理对视频的理解能力的基准。VideoWA 包含基于手工制作的视频教程的 2021 个网络代理任务，其内容时长总计近四小时。针对我们的基准，我们定义了基于长上下文视频的代理任务分类法，主要有两个关注领域：技能留存和事实留存。技能留存任务用于评估代理能否借助给定的人类演示高效完成任务，而事实留存任务则评估代理能否从视频中检索与指令相关的信息以完成任务。我们发现，最佳模型在事实留存任务上的成功率为 13.3%，在事实留存问答对上的成功率为 45.8%，远低于人类分别 73.9%和 79.3%的表现。在技能留存任务上，长上下文模型在有教程时的表现比无教程时更差，在 WebArena 任务中的性能下降 5%，在 VisualWebArena 任务中的性能下降 10.3%。我们的工作凸显了提升长上下文多模态模型代理能力的必要性，并为长上下文视频代理的未来发展提供了一个测试平台。

> Videos are often used to learn or extract the necessary information to complete tasks in ways different than what text and static imagery alone can provide. However, many existing agent benchmarks neglect long-context video understanding, instead focusing on text or static image inputs. To bridge this gap, we introduce VideoWebArena (VideoWA), a benchmark for evaluating the capabilities of long-context multimodal agents for video understanding. VideoWA consists of 2,021 web agent tasks based on manually crafted video tutorials, which total almost four hours of content. For our benchmark, we define a taxonomy of long-context video-based agent tasks with two main areas of focus: skill retention and factual retention. While skill retention tasks evaluate whether an agent can use a given human demonstration to complete a task efficiently, the factual retention task evaluates whether an agent can retrieve instruction-relevant information from a video to complete a task. We find that the best model achieves 13.3% success on factual retention tasks and 45.8% on factual retention QA pairs, far below human performance at 73.9% and 79.3%, respectively. On skill retention tasks, long-context models perform worse with tutorials than without, exhibiting a 5% performance decrease in WebArena tasks and a 10.3% decrease in VisualWebArena tasks. Our work highlights the need to improve the agentic abilities of long-context multimodal models and provides a testbed for future development with long-context video agents.

[Arxiv](https://arxiv.org/abs/2410.19100)