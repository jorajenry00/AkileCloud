# Cursor 收费太高？3 分钟接入超低价 DeepSeek-V3，代码质量媲美 Claude 3.5

![DeepSeek-V3](https://segmentfault.com/img/bVdgRfq)

DeepSeek-V3 的价格实在是令人惊喜：**每百万输入 tokens 仅需 0.1 元（缓存命中）或 1 元（缓存未命中），每百万输出 tokens 只需 2 元**。与其他模型相比，DeepSeek-V3 的性价比极高，用“真香”来形容毫不为过。

![DeepSeek-V3 性价比对比](https://segmentfault.com/img/bVdgRfr)

Sealos 提供的 AI 聚合代理服务 **Sealos AI Proxy**，为用户提供了便捷的 AI 模型访问通道，其中包括 DeepSeek-V3 模型。通过 Sealos AI Proxy 使用这些模型时，**价格与官方定价完全一致**，真正做到零溢价，让用户以最实惠的价格享受优质的 AI 服务。

## 如何让 Cursor 使用 DeepSeek-V3 模型？

虽然 Cursor 价格较高且试用时间有限，但它支持用户接入自定义 API。因此，我们可以通过接入 Sealos AI Proxy 的 API，让 Cursor 使用 DeepSeek-V3 模型以及其他多种模型。

> 注意：Cursor 接入自定义 API 只能使用 Chat 模型，不能使用 Composer 模式，但已经非常实用。

如果你只想接入 DeepSeek-V3 模型，也可以选择使用 DeepSeek 官方的 API。而 **Sealos AI Proxy 的优势在于它可以同时接入多个模型，而不仅仅局限于 DeepSeek**。

👉 [WildCard | 一分钟注册，轻松订阅海外线上服务](https://bbtdd.com/WildCard)

## 操作步骤

### 1. 登录 Sealos Cloud
1. 首先登录 [Sealos Cloud](https://bbtdd.com/WildCard)，打开桌面上的【AI Proxy】。
2. 新建一个 Key，创建完成后，你将获得一个 API Key。

### 2. 配置 Cursor
1. 回到 Cursor，点击顶部菜单栏的 `Cursor` -> `Settings` -> `Cursor Settings`。
2. 取消勾选其他所有模型。
3. 点击 “Add Model” 添加一个自定义模型。
4. 输入模型名称为 `deepseek-chat`，然后回车。
5. 在 “Override OpenAI Base URL” 下方输入 Sealos AI Proxy 的 API 地址：`https://aiproxy.hzh.sealos.run/v1`，然后点击 “Save” 按钮。
6. 输入之前在 Sealos AI Proxy 中创建的 API Key，然后点击 “Verify” 按钮。
7. 在弹出来的对话框中点击 “Enable OpenAI API Key” 按钮。

### 3. 使用 DeepSeek-V3 模型
验证完成后，你就可以在 Cursor 中使用 DeepSeek-V3 模型了。直接按下快捷键 `CMD + L` 打开 Cursor 的 Chat 界面，开始对话。

![Cursor 使用 DeepSeek-V3](https://segmentfault.com/img/bVdgRfE)

### 4. 生成代码示例
DeepSeek-V3 可以帮助你生成高质量的代码。例如，输入以下提示词，DeepSeek 就能为你生成完整的二份查找算法代码：

python
# 示例：让 DeepSeek 生成一个二份查找算法
# 输入注释
"""
实现一个二份查找算法，要求：
1. 使用迭代方式实现
2. 处理目标值不存在的情况
3. 添加详细注释
4. 考虑数组可能为空的情况
5. 返回目标值的索引，如果不存在则返回-1
"""


![生成代码示例](https://segmentfault.com/img/bVdgRfF)