<p align="center">
  <img src="logo.png" alt="铸言企业用工文书助手" width="180">
</p>

# 铸言企业用工文书助手

**Zhuyan Enterprise Employment Document Assistant**

为企业全流程用工场景打造，依托海量专业用工文书范本数据库，在深度智能推演与前置风险预防的基础上，定制生成录用条件、绩效考核、管理制度、调岗降薪及辞退通知书函及仲裁答辩等全套即用型文书。文本立场坚定维护企业利益，层层封堵管理漏洞，严控劳资纠纷隐患与合规成本。

面对复杂或敏感的用工诉求，技能既能紧扣企业经营目的输出务实文本，又同步提供深度的法律风险剖析与替代方案，助企业化被动应对为主动风控，筑牢用工安全屏障，是企业身边的专业级人资智能帮手。

## V1.9.2升级内容

- 根据表达完整度动态匹配基础、进阶和专业三档回复深度，并随多轮信息实时调整。
- 从自然表达识别HR、法务、企业主等职业倾向，不额外增加身份问卷。
- 补充适用边界、调用示例、实际文书样例及模型繁忙、文件缺失、生成失败等恢复提示。
- 文书需求坚持首轮优先生成完整正文；缺失信息使用占位符，不用冗长问卷阻断交付。
- 采用以崔凯为著作权人的免费内部使用限制性许可证。

## 下载与安装

请从本仓库的 **Releases** 页面下载：

`zhuyan-employment-document-assistant-v1.9.2-github.zip`

解压后，将完整目录安装到：

- Windows：`%USERPROFILE%\.codex\skills\china-employment-document-advisor`
- macOS / Linux：`~/.codex/skills/china-employment-document-advisor`

重新打开 Codex 后，可调用 `$china-employment-document-advisor`，也可直接提出企业用工文书需求。

## 核心特点

- 覆盖235份基础文书能力卡及扩展文书能力卡，按企业用工场景、证据、程序和文书类型匹配。
- 库内文书采用快速路径；库外文书按最接近的同类结构重构，外部模板和法规核验后置。
- 对可能不合规的经营要求进行实质风险分析：先形成可审阅文本，再说明效力、后果和替代方案；不伪造事实、签字、证据或历史日期。
- 支持DOCX、Markdown和JSON交付；DOCX自动加入“铸言 企业用工文书”页眉、页码和免责声明。

## 完整性校验

发布包 SHA-256：

`1E664F26999E024F158E23C00F3BF231A24016EC700754456D452F3DA7307EBA`

完整程序共91个文件。发布前已通过99项测试、Skill结构校验、ZIP路径安全检查和独立解压运行测试。

## 隐私、安全与许可

本项目不公开八卷原始DOCX文书。请勿在GitHub Issue、Discussion或公开日志中提交真实身份证号、银行账户、病历、工资明细、客户资料或完整争议卷宗。

法律文书和风险提示不代表法律意见，内容仅供参考，使用应自行承担风险和责任。正式签署或实施前，应结合真实事实、证据、当地规则和裁判尺度复核。

Copyright © 2026 崔凯。允许个人和企业免费内部使用；禁止商业转售、二次分发以及用于竞品训练、数据集、RAG知识库或竞争性产品开发。完整条件见 [`LICENSE`](LICENSE)。

---

## English

Zhuyan Enterprise Employment Document Assistant is a Chinese-language Skill for PRC employment-document drafting. Download the complete v1.9.2 program package from **Releases**, verify the SHA-256 checksum above, and extract it into your Codex skills directory.

It produces complete fillable first drafts before optional follow-up questions, adapts response depth to the user, and provides substantive risk analysis and practical alternatives. Copyright © 2026 Cui Kai. Free internal use is permitted under the restrictions stated in [`LICENSE`](LICENSE). Output is for reference only and is not legal advice.
