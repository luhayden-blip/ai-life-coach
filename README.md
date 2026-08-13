# AI人生教练（ai-life-coach）

<p align="center">
  <img src="https://img.shields.io/badge/version-2.1.3-blue" alt="version">
  <img src="https://img.shields.io/badge/license-MIT-green" alt="license">
  <img src="https://img.shields.io/badge/platform-WorkBuddy%20Skill-orange" alt="platform">
  <a href="https://clawhub.ai"><img src="https://img.shields.io/badge/available%20on-ClawHub-blueviolet" alt="ClawHub"></a>
  <a href="https://skillhub.workbuddy.ai"><img src="https://img.shields.io/badge/available%20on-SkillHub-blueviolet" alt="SkillHub"></a>
</p>

一个只会提问、不替你做决定的陪伴型 AI 教练技能。基于斯坦福人生设计课（d.school）、积极心理学与心流理论，融合焦点解决短期疗法（SFBT）、叙事外化、奥德赛计划等教练方法。

> 有时候不是你不努力，是你还没看清自己真正想要什么。

## 它做什么

- **自我觉察**：四仪表盘（健康/工作/娱乐/爱）看清真实位置
- **明确目标**：区分重力问题与真问题，工作观×人生观一致性诊断
- **行动计划**：奥德赛三版本 + 可立即开始的原型小步
- **越用越懂你**：跨会话记忆，第二次来记得你上次的卡点；多人共用自动分流
- **危机优先**：当你说出"活着没意思"等求助信号，它先停下来确认你的安全，把 400-161-9995 全国心理援助热线递给你
- **黑盒原则（v2.1.3+）**：框架名/方法名/路由步骤对用户完全透明不可感知——你只感觉到"被听懂了"，不会感觉"在被一套流程操作"

## 怎么装

| 方式 | 操作 |
|---|---|
| **WorkBuddy**（推荐） | 技能广场搜索 `ai-life-coach` → 安装 |
| **ClawHub** | clawhub.ai 搜索 `ai-life-coach` → 安装 |
| **手动** | 把 `ai-life-coach/` 目录拷到你的 skills 目录（`~/.workbuddy/skills/`） |

## 怎么用

直接说这些就能唤起它：

> 「我想做一次人生教练对话」「我现在很迷茫」「最近提不起劲」「想找人聊聊」「帮我理一下方向」「想定个目标」

## 隐私承诺（三条铁律）

1. 你的记忆**只存在你自己电脑上**，绝不上传云端、脚本零网络请求
2. 你说过的最重的话（求助信号）**永不进入优化流程**
3. **自动上传一律不做**——即使数据已脱敏；分享只走你主动、自愿的通道

## 版本

当前版本 **v2.1.3**。完整设计理念与版本记录见《设计理念与版本记录》。

### 近期更新

- **v2.1.3** — 黑盒原则（用户不可感知框架/方法名/路由步骤/状态变量/文件操作）+ 自然度自检；多文件结构拆分（SKILL + 4 references + FAQ）
- **v2.1.2** — 论文评估 P0+P1 落地
- **v2.1.1** — 多文件结构拆分（零功能变更）
- **v2.1.0** — 论文评估能力
- **v2.0.9** — 横纵分析 NOW 四点：问责闭环 + 反谄媚协议 + 主动追问 + 未成年人红线

## License

MIT
