## RL组

强化学习（RL）是机器学习（ML）三个组成部分之一，主要研究交互过程中的时序决策问题，目前部分AI顶会有超过五分之一的工作是与RL有关的

在本次任务中，以下两个题目可以被选择，你只需要尽可能达到任务要求

### Gym-Taxi项目

Taxi来自OpenAI提供的开源环境Gym，它在[Gym说明文档](https://www.gymlibrary.ml/environments/toy_text/taxi/)中被详细介绍了

你被要求：

- 选择至少一个RL算法建立智能体（Agent），在Taxi环境中训练和测试，记录测试结果并可视化
- 试图使Agent收敛（在每一个episode中，可以稳定地将乘客送到目的地），如果不能得到收敛的结果，分析原因并继续尝试，记录算法的改进过程
- 关注你使用的算法中的细节（例如动作的探索（Exploration）和利用（Exploitation）、经验回放（Experience Replay）），分析它们在该算法中被使用的原因
- 了解Reward Shaping技巧，尝试在训练过程中使用它，并记录它带来的影响

另外，Taxi环境的动作和状态都是尺度相当小的离散值（向量），如果你在此环境取得了成功，选择更复杂的环境（例如[Atari](https://www.gymlibrary.ml/environments/atari/)系列，它们的Observation往往是RGB图像），你可以使用任何技巧和算法，试图在新的环境中得到收敛结果

### 自定义

你可以在以下任务中选择一项：

- 在以RL为主题的文献、网课或其它资源中学习，详细记录你的学习成果，注意完成代码编写是相当重要的
- 建立一个仿真环境（或使用一个感兴趣的），在该环境中使用至少一种RL算法得到结果并展示
- 选择一个RL前沿方向深入研究，你只需要详尽地展示研究成果
- 参加一个RL主题的竞赛，汇报比赛内容和比赛结果，总结参赛经历

### 附录-RL打怪升级之路

### 入门

在这个部分，一些RL的学习资源被推荐。它们具有不同的难度和风格，你需要选择适合自己的学习路线

#### 课程/课件

- [David Silver(UCL)](https://www.bilibili.com/video/BV1kb411i7KG?from=search&seid=12335836101694062300)
  以上是网课，这里是[课件](https://www.davidsilver.uk/teaching/)
  大神David Silver亲自授课，它仅包含RL最基础的理论部分，注重数学解析

- [李宏毅(NTU台大)](https://www.bilibili.com/video/BV1UE411G78S?from=search&seid=9725909430531578664)
  以上是网课，这里是[(部分)课件](http://speech.ee.ntu.edu.tw/~tlkagk/courses_MLDS18.html)
  它覆盖知识较多和琐碎

- [周博磊(UCLA)](https://github.com/zhoubolei/introRL)
  这是Github中的课件资源，在README附中有网课资源
  它注重数学解析，提供高质量代码

- [百度(Baidu)](https://www.bilibili.com/video/BV1yv411i7xd?p=1)
  这是百度提供的网课
  它手把手教学，有详细的算法和代码汉语讲解，相当基础，但覆盖知识少

- [Spinning Up](https://github.com/openai/spinningup)
  这是OpenAI提供的课程
  它内容多而结构清晰，每个部分都有完整的概念、代码和文献清单

#### 博客

- [Hands-on-RL(SJTU)](https://hrl.boyuai.com/)
  上交大强化学习课程材料，包含足够多的RL模型详解，提供完整[代码](https://github.com/boyu-ai/Hands-on-RL)

- [深度强化学习实验室](https://github.com/NeuronDance/DeepRL)
  由深度强化学习实验室发起的项目，是各种课程、机构、竞赛等资源的汇总
  或许这一个项目用来学习就足够了

#### 书籍

- [Reinforcement Learning: An Introduction (By Richard S. Sutton and Andrew G. Barto)](https://web.stanford.edu/class/psych209/Readings/SuttonBartoIPRLBook2ndEd.pdf)
  经典教材，包含RL基础部分，内容古老

### 进阶

在这个部分，一些有关RL的机构/网站被给出。如果你希望进行RL的科研/竞赛，就会更经常在社区和论文中学习，而且你需要的资料很可能并不在下文中

#### 竞赛

- [及第](http://www.jidiai.cn/compete_list)
  这是一个汇总RL竞赛的平台

- [Google Research Football with Manchester City F.C.](https://www.kaggle.com/competitions/google-football)
  这是一个谷歌和曼城合作的竞赛，它提供了一个开源环境以训练足球机器人
  Kaggle平台偶尔会出现RL比赛

- [MineRL](https://minerl.io/)
  这是专门训练智能体玩Minecraft的竞赛，来自MineRL Labs
  它发起的[BASALT Competition 2022](https://minerl.io/basalt/)正在进行中！

- [AIcrowd](https://www.aicrowd.com/challenges)
  AIcrowd，包括许多企业和高校发布的竞赛，一部分是RL竞赛，如前段时间刚结束的2nd Neural MMO challenge

#### 社区

- [RLChina](http://rlchina.org/)
- [深度强化学习实验室](http://www.deeprlhub.com/)
  两个国内强化学习社区，包含竞赛发布、企业招聘等信息

#### 科研

RL相关的方向相当多，想必你已经有心仪的目标了

- [Bandit](https://banditalgs.com/)
  Bandit算法社区，MAB问题是团队目前做的工作

#### 其它

- [stable-baselines3](https://github.com/DLR-RM/stable-baselines3)

- [Tianshou](https://github.com/thu-ml/tianshou/)

- [garage](https://github.com/rlworkgroup/garage)
  这些是用PyTorch实现的RL算法包，可以辅助研究人员快速验证想法

- [Gym](https://www.gymlibrary.ml/)
  这是OpenAI提供的RL开源环境Gym，被广泛用于RL研究
  你可以使用它训练自己的智能体，验证自己的RL算法

- [DeepMind](https://www.deepmind.com/)

- [OpenAI](https://openai.com/)
  两个著名研究机构，经常发布有趣的工作