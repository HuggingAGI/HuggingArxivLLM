# Ferret-UI 2：精通跨平台的通用用户界面理解

发布时间：2024年10月24日

`LLM应用` `用户界面` `多模态语言模型`

> Ferret-UI 2: Mastering Universal User Interface Understanding Across Platforms

# 摘要

> 构建用于用户界面（UI）理解的通用模型颇具挑战，这源于诸多基础问题，像平台的多样性、分辨率的变化以及数据的限制。在本文中，我们推出了 Ferret-UI 2，这是一款专为涵盖 iPhone、Android、iPad、网页和 AppleTV 等众多平台的通用 UI 理解而设计的多模态大型语言模型（MLLM）。在 Ferret-UI 的基础上，Ferret-UI 2 带来了三项关键创新：对多种平台类型的支持、通过自适应缩放实现高分辨率感知，以及借助 GPT-4o 并带有集合标记视觉提示生成高级任务训练数据。这些改进让 Ferret-UI 2 能够进行复杂且以用户为中心的交互，使其在不断拓展的平台生态系统多样性面前展现出极高的通用性和适应性。在引用、基础、以用户为中心的高级任务（包含 9 个子任务×5 个平台）、GUIDE 下一步行动预测数据集以及 GUI-World 多平台基准上开展的大量实证实验表明，Ferret-UI 2 明显优于 Ferret-UI，同时还展现出强大的跨平台转移能力。

> Building a generalist model for user interface (UI) understanding is challenging due to various foundational issues, such as platform diversity, resolution variation, and data limitation. In this paper, we introduce Ferret-UI 2, a multimodal large language model (MLLM) designed for universal UI understanding across a wide range of platforms, including iPhone, Android, iPad, Webpage, and AppleTV. Building on the foundation of Ferret-UI, Ferret-UI 2 introduces three key innovations: support for multiple platform types, high-resolution perception through adaptive scaling, and advanced task training data generation powered by GPT-4o with set-of-mark visual prompting. These advancements enable Ferret-UI 2 to perform complex, user-centered interactions, making it highly versatile and adaptable for the expanding diversity of platform ecosystems. Extensive empirical experiments on referring, grounding, user-centric advanced tasks (comprising 9 subtasks $\times$ 5 platforms), GUIDE next-action prediction dataset, and GUI-World multi-platform benchmark demonstrate that Ferret-UI 2 significantly outperforms Ferret-UI, and also shows strong cross-platform transfer capabilities.

[Arxiv](https://arxiv.org/abs/2410.18967)