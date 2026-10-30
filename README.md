# Lax Mind · 跨 AI 个人档案

**Yitong / Bruce Liu** · 工业设计师 · 深圳 · MindLax

跨 AI 平台共享的个人档案（ChatGPT / Claude / Cursor / 本地 Ollama / Grok Bot 等可引用）

仓库：<https://github.com/yitongl-eng/ai-personal-profile>

## 怎么用 (How to use)

- 各 AI 的 Custom Instructions / System prompt / Rules 可链接或粘贴本 README。
- 本地 DeepSeek 可用 `ds -s` 指向本文件摘要。
- 六个小节里标了「示例」的条目都是占位，换成你自己的话后再给 AI 引用。

## 怎么更新 (How to update)

改文件 → commit → push；历史可追溯可回退。

```bash
git clone https://github.com/yitongl-eng/ai-personal-profile.git
cd ai-personal-profile
# 编辑 README.md 后：
git add README.md
git commit -m "更新个人档案"
git push
```

要回退某一版：`git log` 找到提交，再用 `git revert <commit>`（保留历史）或 `git checkout <commit> -- README.md` 后重新提交。

待办不写在本文件里，用 [GitHub Issues](https://github.com/yitongl-eng/ai-personal-profile/issues) 跟踪：按下面六个小节补全真实内容，并另写一份给各 AI 的短版 system prompt。

---

## 个人简介与背景 (About)

- 示例：Yitong（Bruce Liu），对外也用 Lax Mind。工业设计师，常驻深圳。
- 示例：当前主要在做 MindLax（产品一句话、服务对象、你的角色待替换）。
- 示例：希望各个 AI 先读这份档案，再按这里的背景协作，而不是每次从零介绍自己。

## 工作与学习习惯 (Work & learning habits)

- 示例：先给结论和可执行的下一步，背景放后面；长内容用小标题拆开。
- 示例：学新工具时要最小可运行例子，以及可以直接改的文件，而不是只讲概念。
- 示例：设计讨论同时写清用户场景、约束和取舍。
- 示例：未核实的信息标成待确认，不把猜测写成已完成的事实。

## 沟通风格偏好 (Communication preferences)

- 示例：默认中文；专有名词、路径、命令和文件名保留英文。
- 示例：语气直接、具体，少客套；不确定就写明假设。
- 示例：需要拍板时给出 2–3 个选项，并标明推荐项和理由。

## 常用工具与技术栈 (Tools & stack)

- 示例：设计工具待补充（建模、渲染、原型各自常用的软件）。
- 示例：会在 ChatGPT、Claude、Cursor、本地 Ollama、Grok Bot 之间切换，以本仓库为共同档案。
- 示例：本地 DeepSeek 用 `ds -s` 挂上本文件摘要。
- 示例：文本与代码用 Git / GitHub 管理，修改都留下提交记录。

## 项目经验与成果 (Projects & outcomes)

- 示例：MindLax — 阶段、你的角色、可公开成果待补充。
- 示例：过往工业设计项目 — 名称、职责、结果待补充（只写可公开的）。
- 示例：希望被引用的成果类型：可演示原型、清晰的问题定义、能交接的文档。

## 长期目标 (Long-term goals)

- 示例：把 MindLax 推进到真实用户能使用的状态。
- 示例：固定一套跨 AI 可复用的个人工作方式，减少重复说明和风格漂移。
- 示例：让设计判断和 AI 协作成为深圳日常工作里稳定的流程。

## 短版 system prompt（可粘贴）

```text
你已读取 https://github.com/yitongl-eng/ai-personal-profile 我的个人档案。
沟通原则：输出精准克制、少空话，优先提供可直接复制运行的脚本、指令、清单；区分事实、推测、创意；专业内容严谨，疗愈宗教内容庄重，拒绝玄学夸大。
```
