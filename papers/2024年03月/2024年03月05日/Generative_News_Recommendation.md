# 创新性生成新闻推荐技术步骤 1 翻译：Generative News Recommendation 直译为“生成式新闻推荐”。步骤 2 翻译：为了更生动活泼、简洁优雅地表达，可以将“生成式新闻推荐”进一步诠释为“创新性生成新闻推荐技术”，既体现了该技术的前沿性和智能性，也突出了其在新闻推荐领域的独特应用。

发布时间：2024年03月05日

`LLM应用`

> Generative News Recommendation

# 摘要

> 当前多数新闻推荐技术仅基于历史点击新闻产生的用户表示与候选新闻间的语义匹配，却忽视了新闻间的高层联系及新闻与用户的深层关联。这类方法受限于其定义，只能按部就班地推送新闻。相比之下，将多篇相关新闻编织成一则连贯的故事叙述，可帮助用户快速全面地掌握事件全貌。本文创新性地提出了一种生成式新闻推荐新框架，它包含两大步骤：一是借助大型语言模型(LLM)的内在知识与推理能力进行高级别的新闻与用户表示匹配；二是基于相关新闻与用户兴趣的关联性，生成逻辑紧密且叙事连贯的新闻故事，引导用户深入阅读。为实现此框架，我们设计出GNR模型，首先运用LLM生成新闻的主题层级表示，并结合其语义层级表示，形成新闻与用户的双重表示。之后，我们发掘新闻之间的关联，并依据用户喜好筛选相关新闻以构建连贯的叙述。最后，我们独创了一种称为UIFT的训练方法，以训练LLM如何巧妙地融合多篇新闻，生成一脉相承的新闻故事。大量实验证明，GNR能有效提升推荐准确性，并成功生成更加个性化且具有事实一致性的新闻情节。

> Most existing news recommendation methods tackle this task by conducting semantic matching between candidate news and user representation produced by historical clicked news. However, they overlook the high-level connections among different news articles and also ignore the profound relationship between these news articles and users. And the definition of these methods dictates that they can only deliver news articles as-is. On the contrary, integrating several relevant news articles into a coherent narrative would assist users in gaining a quicker and more comprehensive understanding of events. In this paper, we propose a novel generative news recommendation paradigm that includes two steps: (1) Leveraging the internal knowledge and reasoning capabilities of the Large Language Model (LLM) to perform high-level matching between candidate news and user representation; (2) Generating a coherent and logically structured narrative based on the associations between related news and user interests, thus engaging users in further reading of the news. Specifically, we propose GNR to implement the generative news recommendation paradigm. First, we compose the dual-level representation of news and users by leveraging LLM to generate theme-level representations and combine them with semantic-level representations. Next, in order to generate a coherent narrative, we explore the news relation and filter the related news according to the user preference. Finally, we propose a novel training method named UIFT to train the LLM to fuse multiple news articles in a coherent narrative. Extensive experiments show that GNR can improve recommendation accuracy and eventually generate more personalized and factually consistent narratives.

[Arxiv](https://arxiv.org/abs/2403.03424)