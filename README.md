<div align="center">

<h1>Lulu Cheng.skill</h1>

<p><em>传播是让正确的受众相信正确的事，并因此行动。</em></p>

<p>
  <a href="./LICENSE"><img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License: MIT"></a>
  <a href="https://agentskills.io"><img src="https://img.shields.io/badge/Agent%20Skills-Standard-4C9F38.svg" alt="Agent Skills Standard"></a>
  <a href="https://github.com/alchaincyf/nuwa-skill"><img src="https://img.shields.io/badge/Made%20with-%E5%A5%B3%E5%A8%B2.skill-E86E38.svg" alt="Made with 女娲.skill"></a>
</p>

<p>大多数营销从渠道、爆款、标题方面给出建议，但这往往是在更大声地传播一个不够重要的信息。</p>

<p><code>lulu-cheng-marketing</code> 基于硅谷<strong>传播与公关</strong>的顶级大神 <a href="https://www.linkedin.com/in/lulu-cheng-meservey/">Lulu Cheng Meservey</a> 的公开访谈与文章，提炼出一套可执行的 Skill，帮助创始人、PM、营销人和内容创作者看清要传播的信息，如何吸引注意力，如何讲好产品故事。</p>

<p><a href="#你会得到什么">你会得到什么</a> · <a href="#安装方式">安装</a> · <a href="#效果示例">效果示例</a> · <a href="#一手信息来源">研究来源</a></p>

</div>

---

## 你会得到什么

- **传播策略：** 从业务目标倒推关键受众、行动与所需信念，制定发布策略
- **注意力设计：** 找到受众已在意的入口，不强行蹭热点
- **故事工作流：** 把复杂产品讲成真实、可复述、能促成行动的故事
- **发布判断：** 选择正确的发言人、渠道与由内向外的发布顺序
- **争议分诊：** 判断何时该回应、何时应先核实、何时不该放大噪声

<br>

## 适合的场景

如果你正在问以下任一问题，这个 Skill 值得安装：

💡 产品明明不错，为什么没人真正理解？
💡 怎么吸引注意力，但不沦为标题党？
💡 复杂产品、创始人故事或发布信息，到底该怎么讲？

*当请求涉及文案优化、重写、翻译改写、标题或钩子时，Skill 会先问一个会实质影响结果的问题；只有用户明确要求“直接改”时才跳过。
*适用于内容营销与传播，不适用于SEO技术优化相关。

<br>

## 核心框架


### 1. 从业务结果倒推传播

```text
业务目标 → 关键行动 → 目标受众 → 所需信念 → 传播任务
```

不从“上什么节目”“发什么平台”“如何爆款”开始。先明确：谁要做什么、为什么会做。

### 2. Message → Medium → Messenger

先打磨值得传播的信息，再选择受众实际出现的媒介，最后找最有资格讲这句话的人。

### 3. 吸引注意力的 X → Y 受众桥

从受众已经在意、焦虑或讨论的 `X` 出发，诚实地连接到你希望他们理解的 `Y`。没有真实的桥，就不要硬蹭热点。

### 4. 把故事变成行动

用具体人物的欲望、阻碍、选择、结果与意义替代抽象形容词；再通过复述测试确认受众记住的是正确的核心真相。

<br>

## 安装方式

### Claude Code

```bash
mkdir -p ~/.claude/skills && git clone https://github.com/jmtom-io/lulu-cheng-marketing.git ~/.claude/skills/lulu-cheng-marketing
```
### Codex

```bash
mkdir -p ~/.agents/skills && git clone https://github.com/jmtom-io/lulu-cheng-marketing.git ~/.agents/skills/lulu-cheng-marketing
```

<br>

## 效果示例

下面是一次真实对话记录，以一个日记类app为例，展示 Skill 的能力。

> **👤 用户**
>
> 我们团队刚刚做出一个产品，目前要进行marketing，我们应该怎么做？

**🤖 Agent**

```text
这是一个策略型问题，我会先从业务结果倒推，而不是先给渠道清单。

你们这次营销最希望促成的一个具体结果是什么——例如首批付费客户、试用注册、预约演示、融资关注，还是招聘？
```

> **👤 用户**
>
> 我们希望先带来更多的新用户

**🤖 Agent**

```text
新用户是结果；下一步要确定最值得先赢下的那一类人。

你们的产品解决什么问题，最希望哪类人注册并完成什么关键动作（例如创建项目、邀请同事、完成首次任务或付费）？
```

> **👤 用户**
>
> 我们的产品是一个日记类app，希望吸引那些有记录生活习惯的白领，他们工作很忙碌，有一定的生活品质，有比较多的思考、感受和表达欲

**🤖 Agent**

```text
受众已经很清楚：忙碌但重视生活质感、记录与表达的白领。

他们注册后，最希望完成的关键动作是什么——立刻写下第一篇日记、连续记录 7 天、导入旧日记，还是邀请朋友？
```

> **👤 用户**
>
> 立刻开始写第一条记录

**🤖 Agent**

```text
营销的首要任务不是让白领“下载一个日记 App”，而是让他们相信：**忙碌不该吞掉生活；写下第一条，才能把今天还给自己。**

基于目前信息，我会这样启动。

**因果链**

- 业务目标：获得更多新用户
- 关键行动：注册后立即写下第一条记录
- 核心受众：忙碌、有生活品质、已有记录习惯与表达欲的白领
- 必要信念：这不是又一个待完成的自律任务，而是一个能在忙碌中留下“我真实感受”的低门槛空间

**先只打一个主张**

> 不是记录更完美的生活，而是别让忙碌替你忘记生活。

它接住了受众已有的焦虑：日程很满、生活过得很快、很多感受来不及拥有就消失了；再自然引到产品价值：用很小的动作开始保存自己。

**注意力入口：不要从“日记功能”讲起**

优先做能让他们立刻代入的内容，每条内容只服务一个 CTA：**现在写下你的第一条。**

- “有些日子忙到最后，只记得开过哪些会，不记得自己怎么过。”
- “成年人最容易丢的，不是时间，是对自己生活的记忆。”
...

**故事怎么讲**

不要说“我们提供极简、沉浸式的记录体验”。讲一个具体时刻：

> 写下第一句，不是为了把生活管理得更好，而是为了不让这一天完全过去。

创始人讲“为什么不能让生活只剩待办事项”；
真实用户讲“我写下第一条后留下了什么”。
前者负责叙事，后者负责证明。

**发布顺序：先形成小范围的真实复述，再扩散**

1. 找 20–50 位高度匹配的白领种子用户，邀请他们完成第一条记录。
2. 收集他们真实写下的瞬间、开始记录的原因与原话；获得授权后做匿名/署名故事。
3. 在一个主阵地集中发布：例如小红书或公众号，而不是同时铺满所有平台。
4. 与“效率焦虑、都市生活、工作与自我、生活方式”领域的小创作者合作；他们展示自己的第一条，而非替你念卖点。
5. 等用户能复述“这是帮我留住生活，而不是逼我自律的日记 App”后，再扩大渠道。

先验证三件事：用户是否愿意立刻写第一条、他们如何用自己的话描述价值、哪一种“忙碌中失去生活感”的瞬间最能促成注册。若这三项没有成立，不要急着加投放；先修正信息与首次记录体验。
```

<br>

## 一手信息来源


以下是本 Skill 使用的一手信息来源，详细内容与方法边界见 `[references/research/](./references/research/)`。

### Lulu Cheng写的文章

- [Go Direct: The Manifesto](https://www.getflack.com/p/go-direct-the-manifesto)
- [Comms Foundation #2: Tactics](https://www.getflack.com/p/tactics)
- [Build your fanbase using the K-pop method](https://www.getflack.com/p/fandom)

### 视频访谈

- [Learn Marketing in 80 Minutes — David Perell](https://www.youtube.com/watch?v=0EheiIUFjUI)
- [Navigating comms and PR — Lenny's Podcast](https://www.youtube.com/watch?v=LTSEOeKV_Hs)
- [How to Build a Powerful Cult](https://www.youtube.com/watch?v=I9Njb8Lw5Xc&t=792s)
- [The Comms Strategist Behind Anduril, Shopify & Cognition — David Senra](https://www.youtube.com/watch?v=DFImJfJGXl0)
- [Helping Founders Go Direct in a New Era of PR & Comms — Uncapped / Jack Altman](https://www.youtube.com/watch?v=GRoU1T4E9rQ&t=22s)

<br>

## 本Skill的制作方法

用 [女娲 · Skill造人术](https://github.com/alchaincyf/nuwa-skill) 生成，并进行了一些调整。

---
<br>
⭐️ 如果觉得这个项目有用，请点点 Star 表示支持 ⭐️
