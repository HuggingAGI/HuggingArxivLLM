# MAGIC：借助协作的 LLM 代理掌控上下文中的物理对抗生成

发布时间：2024年12月10日

`Agent` `对象检测`

> MAGIC: Mastering Physical Adversarial Generation in Context through Collaborative LLM Agents

# 摘要

> 在驾驶场景中的物理对抗攻击能够暴露出视觉感知模型的关键漏洞。然而，鉴于现实世界背景的多样化以及保持视觉自然性的需求，开展此类攻击颇具挑战。基于此，我们将物理对抗攻击重新定义为一次性补丁生成问题。我们的方法借助深度生成模型生成对抗补丁，该模型会考虑特定场景的上下文，能够在匹配环境中直接进行物理部署。主要难题在于同时达成两个目标：生成能有效误导对象检测系统的对抗补丁，并确定在场景中符合上下文的恰当位置。我们提出了 MAGIC（掌握上下文物理对抗生成）这一新颖框架，它由多模态 LLM 代理驱动，以应对这些挑战。MAGIC 通过语言和视觉能力的协同交互，自动理解场景上下文并协调对抗补丁的生成。MAGIC 协调了三个专门的 LLM 代理：对抗补丁生成代理（GAgent）通过对文本到图像模型进行策略性提示工程，掌握欺骗性补丁的创建。对抗补丁部署代理（DAgent）基于场景理解确定最优放置策略，确保上下文的连贯性。自我检查代理（EAgent）通过对这两个过程进行关键监督和迭代改进，完成这三部曲。我们在数字和物理层面进行了方法验证，即 nuImage 和手动捕获的真实场景，统计和视觉结果均表明我们的 MAGIC 强大且能有效攻击广泛使用的对象检测系统。

> Physical adversarial attacks in driving scenarios can expose critical vulnerabilities in visual perception models. However, developing such attacks remains challenging due to diverse real-world backgrounds and the requirement for maintaining visual naturality. Building upon this challenge, we reformulate physical adversarial attacks as a one-shot patch-generation problem. Our approach generates adversarial patches through a deep generative model that considers the specific scene context, enabling direct physical deployment in matching environments. The primary challenge lies in simultaneously achieving two objectives: generating adversarial patches that effectively mislead object detection systems while determining contextually appropriate placement within the scene. We propose MAGIC (Mastering Physical Adversarial Generation In Context), a novel framework powered by multi-modal LLM agents to address these challenges. MAGIC automatically understands scene context and orchestrates adversarial patch generation through the synergistic interaction of language and vision capabilities. MAGIC orchestrates three specialized LLM agents: The adv-patch generation agent (GAgent) masters the creation of deceptive patches through strategic prompt engineering for text-to-image models. The adv-patch deployment agent (DAgent) ensures contextual coherence by determining optimal placement strategies based on scene understanding. The self-examination agent (EAgent) completes this trilogy by providing critical oversight and iterative refinement of both processes. We validate our method on both digital and physical level, \ie, nuImage and manually captured real scenes, where both statistical and visual results prove that our MAGIC is powerful and effectively for attacking wide-used object detection systems.

[Arxiv](https://arxiv.org/abs/2412.08014)