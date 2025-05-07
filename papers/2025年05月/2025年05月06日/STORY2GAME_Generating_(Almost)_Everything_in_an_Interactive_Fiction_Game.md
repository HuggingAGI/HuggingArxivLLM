# STORY2GAME：打造几乎一切的互动小说游戏体验。

发布时间：2025年05月06日

`LLM应用` `游戏引擎`

> STORY2GAME: Generating (Almost) Everything in an Interactive Fiction Game

# 摘要

> 我们介绍STORY2GAME，这是一种全新的方法，利用大型语言模型生成基于文本的交互式小说游戏。该方法从生成故事开始，构建游戏世界，并为游戏引擎生成动作代码，使故事能够以交互方式呈现。虽然硬编码动作可能会限制故事生成，但生成动作的能力使故事生成过程更加开放，同时仍能提供基于游戏状态的沉浸式体验。成功生成动作的关键在于利用大型语言模型生成的故事中的动作前提条件和效果，作为指导游戏引擎必须跟踪和更改哪些游戏状态的依据。我们还引入了一种动态生成新动作的技术，以满足玩家执行不在故事中的动作的需求。动态生成动作可能需要实时更新游戏引擎的状态表示并修改先前生成的动作。我们评估了动作代码生成的成功率，以确定玩家是否能够交互式地完整体验生成的故事。

> We introduce STORY2GAME, a novel approach to using Large Language Models to generate text-based interactive fiction games that starts by generating a story, populates the world, and builds the code for actions in a game engine that enables the story to play out interactively. Whereas a given set of hard-coded actions can artificially constrain story generation, the ability to generate actions means the story generation process can be more open-ended but still allow for experiences that are grounded in a game state. The key to successful action generation is to use LLM-generated preconditions and effects of actions in the stories as guides for what aspects of the game state must be tracked and changed by the game engine when a player performs an action. We also introduce a technique for dynamically generating new actions to accommodate the player's desire to perform actions that they think of that are not part of the story. Dynamic action generation may require on-the-fly updates to the game engine's state representation and revision of previously generated actions. We evaluate the success rate of action code generation with respect to whether a player can interactively play through the entire generated story.

[Arxiv](https://arxiv.org/abs/2505.03547)