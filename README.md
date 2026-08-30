<p align="center">
  <img src="logo.png" alt="铸言企业用工文书助手" width="180">
</p>

# 铸言企业用工文书助手

**Zhuyan Enterprise Employment Document Assistant**

面向中国境内企业用工场景的专业文书生成 Skill。用户用日常语言说明问题后，系统优先在首轮直接生成可填写、可继续优化的劳动合同、协议、通知、制度、申请、确认书、承诺书、答辩等完整文书，并在正文之后提示主要风险和替代方案。

## 下载与安装

请从本仓库的 **Releases** 页面下载：

`zhuyan-employment-document-assistant-v1.9.1-github.zip`

解压后，将完整目录安装到：

- Windows：`%USERPROFILE%\.codex\skills\china-employment-document-advisor`
- macOS / Linux：`~/.codex/skills/china-employment-document-advisor`

重新打开 Codex 后，可调用 `$china-employment-document-advisor`，也可直接提出企业用工文书需求。

## 核心特点

- 覆盖 235 份基础文书能力卡及扩展文书能力卡，按企业用工场景、证据、程序和文书类型匹配。
- 明确要求文书时，首轮优先交付完整正文；姓名、日期、工资等缺失信息使用占位符。
- 库内文书采用快速路径；库外文书按最接近的同类结构起草，外部模板和法规核验后置。
- 对可能不合规的经营要求进行实质风险分析：形成可审阅文本，再说明效力、后果和更稳妥方案；不伪造事实、签字、证据或历史日期。
- 支持 DOCX、Markdown 和 JSON 交付；DOCX 自动加入“铸言 企业用工文书”页眉、页码和免责声明。

## 完整性校验

发布包 SHA-256：

`3AD73F628E3A370BABFFA31F7AE1B6A1A94310C5D666A7A381138677C26E3059`

完整程序共 86 个文件，目录结构保存在发布 ZIP 中。发布前已通过 87 项测试、Skill 结构校验、ZIP 路径安全检查和解压运行冒烟测试。

## 隐私、安全与许可

本项目不公开八卷原始 DOCX 文书。请勿在 GitHub Issue、Discussion 或公开日志中提交真实身份证号、银行账户、病历、工资明细、客户资料或完整争议卷宗。

法律文书和风险提示不代表法律意见，内容仅供参考，使用应自行承担风险和责任。正式签署或实施前，应结合真实事实、证据、当地规则和裁判尺度复核。

本项目采用专有有限使用许可，详见 [`LICENSE`](LICENSE)。未经许可不得转售、公开再分发、提取文书能力库或用于建立竞争性文书产品。

---

## English

Zhuyan Enterprise Employment Document Assistant is a Chinese-language Skill for PRC employment-document drafting. Download the complete v1.9.1 program package from **Releases**, verify the SHA-256 checksum above, and extract it into your Codex skills directory.

It routes plain-language requests to a catalog of 235 document capabilities, produces a complete fillable first draft before optional follow-up questions, and places concise risk notes and safer alternatives after the document. Output is for reference only and is not legal advice.
