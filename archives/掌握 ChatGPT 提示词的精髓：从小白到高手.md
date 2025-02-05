# 掌握 ChatGPT 提示词的精髓：从小白到高手

![掌握 ChatGPT 提示词的精髓](https://bbtdd.com/img/204195568642548.webp)

## 前言

ChatGPT 的输出质量完全取决于你如何提问和引导。问得好，引导得当，它会生成让你惊喜的答案；反之，则可能无价值甚至假大空。因此，想要获得高质量的回答，必须学会撰写高质量的提示词。

那么，如何写出高质量的提示词呢？

## 1. 基础认识

![基础认识](https://bbtdd.com/img/4665736442689.webp)

由于目前自然语言处理技术尚不完美，AI 生成内容的质量非常依赖于提示词（prompt）。要获得高质量的提示词，首先要让 ChatGPT 明白你的需求，避免模糊指令。

高质量提示词的核心要点是具体、丰富、少歧义，要把 AI 当人看。清晰地表达你的需求，不要让 AI 猜测。AI 猜测得越少，你越可能获得满意的答案。

此外，对提示词进行格式调整也能大大帮助 ChatGPT 理解你输入的意图。例如：

![格式调整](https://bbtdd.com/img/96369187058072.webp)

在提示词中使用分隔符（如`""`）可以清晰地区分不同段落或类型的内容，这对 ChatGPT 解析输入非常有帮助。

## 2. 进阶技巧

![进阶技巧](https://bbtdd.com/img/3129017396862681.webp)

通过阅读 OpenAI 官方的[提示工程指南](https://platform.openai.com/docs/guides/prompt-engineering)，我们可以总结出六大提高 ChatGPT 性能的策略：

1. **编写清晰的说明**
2. **提供参考文本**
3. **将复杂的任务拆分成简单的任务**
4. **给模型“思考”的时间**
5. **使用外部工具以及系统地测试**
6. **系统地测试更改**

以下是一个翻译类提示词的例子：

![翻译类提示词](https://bbtdd.com/img/0507315854.webp)

从上述例子中，我们可以得出以下撰写高质量提示词的方法：

1. **让 ChatGPT 扮演专家角色**，引导 AI 进入具体场景，赋予行家身份可以帮助 AI 确定问题范围。
2. **明确列出每个步骤**，并用序号标注，逐步引导 ChatGPT 完成任务。
3. **直接粘贴与任务相关的优质素材**，例如在修改论文时，可以直接发送论文原文。
4. **适时让 ChatGPT“冷静思考”**，以提高回复质量。

当然，以上总结并不全面。为了进一步提升提示词的书写技巧，我们还可以学习并运用其他人的优质提示词。推荐去看看 GitHub 上的一个关于 [ChatGPT 提示词整理](https://github.com/f/awesome-chatgpt-prompts) 的明星项目。

![GitHub 项目](https://bbtdd.com/img/31308983.webp)

![GitHub 项目](https://bbtdd.com/img/53283768.webp)

这里再补充一些细节：

- ChatGPT 的单次最大输出字符数为 2048，超过部分会被截断，回复“继续”即可。
- ChatGPT 可能会产生“幻觉”（一本正经地胡说八道），因此要仔细甄别其回答的真伪，不要过于信任。

## 3. 好用的小技巧

![小技巧](https://bbtdd.com/img/220709046227.webp)

通过阅读 Google、Meta、Microsoft 等大厂发表的 Prompt Engineering 论文，我们发现，在提示词中加入一些“咒语”可以显著提高 AI 的回答质量。

### 咒语一：Let's think step by step（让我们一步一步地思考）

![论文](https://bbtdd.com/img/983344487084180.webp)

提示词中加入 "Let's think step by step"，就能大幅提升模型的推理能力。

### 咒语二：take a deep breath and work on this problem step-by-step（深呼吸，然后分步骤思考这个问题）

![论文](https://bbtdd.com/img/8886402558058422.webp)

### 其他咒语合集

- "你确定么？有没有漏掉了什么?你要不再检查一下？你要对你的答案负责。"
- "这个任务对我的职业生涯至关重要，我非常重视你的彻底分析。"
- "我将支付100美金小费，以获得更好的解决方案。"
- "请用8岁小孩都能听懂的话解释。"

当然，授人以鱼不如授人以渔。在众多用途的 prompt 中，有一类被称为 **Prompt Creator（指令生成器）**，即让 ChatGPT 帮助你生成或改善 prompt。

这里介绍一个这样的 prompt：

![Prompt Creator](https://bbtdd.com/img/65348898972396.webp)

此外，一些网站也提供指令生成服务：

![NeuralWriter](https://bbtdd.com/img/25354250004.webp)

![Coefficient](https://bbtdd.com/img/342100731.webp)

![Feedough](https://bbtdd.com/img/18927440030.webp)

## 写在最后

虽然 AI 已经取得了很大的进步，但它仍然受到人类知识、经验、数据和算法的限制。因此，在使用 AI 时，我们应该保持谨慎和理性，将其视为一种工具，而不是万能的方法。

👉 [WildCard | 一分钟注册，轻松订阅海外线上服务](https://bbtdd.com/WildCard)