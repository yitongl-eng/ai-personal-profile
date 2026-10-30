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

道号灵丹子，www.Mindlax.com，上海鑫境声愈健康科技有限公司创始人CEO、CTO。深耕身心声学疗愈、具身智能、自主神经干预方向，研发MindLax元籁声场系统、化蝶共生空间。有脑梗康复慢病管理经验，长期研究神经可塑性、节律声学刺激、生理监测与NVH声学谐振。同时做短视频内容策划、多Agent自治工作流搭建，爱好军武考据、模型、音响与赛车文化。

## 工作与学习习惯 (Work & learning habits)

偏向目标驱动、模块化推进，习惯用“方面线推进+麦田表达心法”梳理方案；喜欢搭建自治多Agent工作流，拆分任务并行调度。
重视底层原理考据，拒绝浅层跟风；同步兼顾项目研发、内容创作、自我慢病康复管理。
追求高效、精简输出，讨厌冗余话术；遇到复杂问题优先建立可验证的模型，而不是单纯堆砌资料。

## 沟通风格偏好 (Communication preferences)

沟通追求直击重点、克制精炼，拒绝鸡汤、空洞抒情和冗余铺垫。
优先要可落地、可复制的方案、脚本、参数清单；回答里要清晰区分客观事实、合理推演、创意构想。
严谨类课题（医学、声学、文献）拒绝夸大伪科学；宗教、疗愈相关内容保持庄重，不渲染玄学。
发现逻辑漏洞、信息错误请直接指出，不用委婉客套。

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
