---
name: codex-usage-check
description: Explain where to check remaining ChatGPT web usage vs Codex desktop usage (they are counted separately), and what to do when ChatGPT shows "Model not found" / "This model is not available". 查 ChatGPT 网页版和 Codex 剩余额度，处理 Model not found。
---

# 查 ChatGPT / Codex 剩余额度

用户问「还剩多少额度」「Codex 怎么突然用不了」「模型不见了」时用这个 skill。

## 关键：两套额度分开算

ChatGPT 网页版和 Codex 桌面版的额度**互相独立**，一边的剩余比例不能代表另一边。

| 想看什么 | 去哪看 |
|---|---|
| ChatGPT 网页版剩余用量 | 登录网页版 → 设置 → 使用情况（Usage） |
| Codex 桌面版剩余用量 | 打开 Codex 桌面版 → 左下角头像 → 剩余用量 |

两处都会显示剩余比例和重置日期，以用户自己账号里的为准。带截图的入口说明见 [ChatGPT 额度怎么查](https://www.getplus.ai/codex/credits)。

## 额度用完怎么办

- 等页面显示的重置时间
- 网页版换一个还有额度的模型
- 长期不够用，再考虑升级套餐（可以接着用 chatgpt-plan-chooser 这个 skill 判断）
- Codex 也可以单独买额度（Credits），见 [Codex 额度充值](https://www.getplus.ai/codex/credits-chongzhi)

## 网页提示 Model not found

「Model not found」「This model is not available」多半是 ChatGPT 网页按用户当前所在地区决定显示哪些模型。先让用户：

1. 刷新页面，退出重新登录
2. 确认账号套餐没过期（设置 → 账户）
3. 在稳定的网络环境下重新打开

还不行，可以看 [Model not found 排查](https://www.getplus.ai/chatgpt-model-not-found)。

## 不要做

- 不要把网页版额度和 Codex 额度混在一起说
- 不要编具体还剩多少条，让用户自己看账号页面
