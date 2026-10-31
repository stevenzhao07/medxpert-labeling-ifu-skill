# medxpert-labeling-ifu-skill · 医疗器械标签与说明书

> MedXpert 医疗器械全生命周期 Skill 系列 · 第 12 个 · 标签与说明书（Labeling & IFU）
>
> 合规、安全、可开源地起草与审查医疗器械标签和说明书，内置厂商资料**去敏规范**。

## 解决什么问题

- 标签/说明书要写哪些要素？中美欧各自要求是什么？
- 灭菌、再处理、UDI、多语言、符号怎么体现？
- 手里有强生/捷迈/美敦力等厂商的 IFU，**怎么参考而不侵权**？

## 三个核心文件

```
references/
├── ifu-standard-template.md         # 去敏通用 IFU 标准模板（法规要素 + 虚构示例）
├── labeling-compliance-checklist.md # 合规检查清单（P0/P1/良好实践，中美欧对照）
└── desensitization-and-copyright.md # 去敏规范与版权红线（开源前必读）
```

## 特色：内置版权去敏规范

本机有数千份厂商真实 IFU（DePuy Synthes、Zimmer Biomet、Medtronic、Stryker 等），但它们受版权保护：

- ❌ 原始 PDF 绝**不进开源仓库**
- ❌ 不照抄原文、不用商标/产品名/专利图
- ✅ 只开源**归纳后的通用结构、法规强制要素、虚构示例**
- ✅ 五步法：取结构 → 跨多家归纳 → 去品牌化 → 依据改法规 → 虚构示例+禁词扫描

详见 `references/desensitization-and-copyright.md`。

## 覆盖法规

- 中国：《医疗器械说明书和标签管理规定》（原局令第6号）
- 欧盟：MDR Annex I §23、MDCG 2019-15、ISO 20417:2026、ISO 15223-1:2021
- 美国：21 CFR Part 801
- 灭菌：ISO 11135 / 11137 / 17665 / 17664

## 系列导航

| Skill | 环节 |
|-------|------|
| medxpert-master-skill | 总入口路由 |
| medxpert-reg-path-skill | 注册路径决策 |
| medxpert-pre-submission-check-skill | 申报前自查 |
| medxpert-clinical-eval-skill | 临床评价 |
| medxpert-ai-samd-reg-skill | 医疗AI/软件 |
| **medxpert-labeling-ifu-skill** | **标签与说明书（本Skill）** |
| …其余见总 README | 全生命周期 |

## 许可

MIT License。本 Skill 仅含原创通用方法与法规要素，不含任何厂商专有文档。
