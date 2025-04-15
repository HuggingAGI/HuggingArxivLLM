# SceneScout：为盲人用户实现AI驱动的街景访问方案

发布时间：2025年04月12日

`LLM应用` `残障辅助` `无障碍导航`

> SceneScout: Towards AI Agent-driven Access to Street View Imagery for Blind Users

# 摘要

> 视障人士在陌生环境中独立出行时常常面临诸多困难，这主要是由于他们难以掌握周边环境的视觉信息。现有辅助工具多专注于实时导航，但那些提供出行前规划的工具往往仅限于地标和分步指引，缺乏细致的视觉背景。街景图像中蕴含着丰富的视觉信息，能够揭示大量环境细节，但对视障人士而言仍是一片未被充分利用的资源。为此，我们开发了SceneScout——一个由多模态大语言模型驱动的AI代理，旨在让视障人士无障碍地探索街景图像。SceneScout提供了两种交互模式：路线预览让用户提前熟悉沿路的视觉细节，而虚拟探索则让用户在街景图像中自由漫游。通过用户研究（N=10），我们发现SceneScout能够为视障用户提供传统工具无法获取的视觉信息。技术评估表明，SceneScout的描述准确率高达72%，且95%的描述聚焦于稳定的视觉元素，即使是在较旧的街景图像中也表现良好。不过，偶尔出现的微妙误差使得在没有视觉辅助的情况下难以完全验证描述的准确性。最后，我们探讨了利用街景图像提升视障人士导航体验的未来机遇与挑战。

> People who are blind or have low vision (BLV) may hesitate to travel independently in unfamiliar environments due to uncertainty about the physical landscape. While most tools focus on in-situ navigation, those exploring pre-travel assistance typically provide only landmarks and turn-by-turn instructions, lacking detailed visual context. Street view imagery, which contains rich visual information and has the potential to reveal numerous environmental details, remains inaccessible to BLV people. In this work, we introduce SceneScout, a multimodal large language model (MLLM)-driven AI agent that enables accessible interactions with street view imagery. SceneScout supports two modes: (1) Route Preview, enabling users to familiarize themselves with visual details along a route, and (2) Virtual Exploration, enabling free movement within street view imagery. Our user study (N=10) demonstrates that SceneScout helps BLV users uncover visual information otherwise unavailable through existing means. A technical evaluation shows that most descriptions are accurate (72%) and describe stable visual elements (95%) even in older imagery, though occasional subtle and plausible errors make them difficult to verify without sight. We discuss future opportunities and challenges of using street view imagery to enhance navigation experiences.

[Arxiv](https://arxiv.org/abs/2504.09227)