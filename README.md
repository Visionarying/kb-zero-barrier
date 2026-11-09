# 知识库零门槛指南

给「从没用过知识库」的上班族的一份入门指南，以及一个可以动手的离线练习场。

**在线看**：<https://visionarying.github.io/kb-zero-barrier/>  
**仓库**：<https://github.com/Visionarying/kb-zero-barrier>

- 不移动、不重命名你的任何文件
- 不要求安装软件、不需要 API Key
- 例子全是上班场景：报销、报价、周会、年假、会议室

## 先看哪个

| 顺序 | 文件 | 是什么 | 时间 |
|---|---|---|---|
| 1 | [知识库零门槛指南](基础版/知识库零门槛指南-基础版.html) | 说明书：9 节 + 2 个附录 | 约 21 分钟 |
| 2 | [练习场](基础版/练习场.html) | 可操作：导入资料、检索、出处、拒答 | 10 分钟跑通 5 步 |

建议顺序：先花 30 秒看说明书开头的「两个回答」，再去练习场跑通 5 步，最后回来看「怎么接」。

## 说明书讲什么

1. 它到底是什么
2. 接进来能多做什么
3. 怎么接
4. 完整走一遍
5. 资料从哪来
6. 怎么和它配合
7. 怎么灵活查
8. 长期怎么养
9. 一页速查卡

附1：黑话翻译表  
附2：参考的开源项目

## 练习场能做什么

- **5 步引导**：看切片 → 提问 → 点出处 → 看拒答 → 试同义词
- **导入导出**：导入 txt / md，导出 / 导入 JSON
- **检索与出处**：关键词检索、逐句标出处、找不到就拒答
- **三档精度对比**：同一个问题，宽松 / 标准 / 严格并排看
- **错题本**：自动收集拒答和低置信度，导出「我还没搞懂的问题」
- **资料体检**：每份资料被命中、被用于回答的次数，以及从未命中的资料
- **随机练一题**：从 8 个问题里抽一个

练习场**不调用大模型**：检索是真的，答案由原文抽取拼成。它故意保留「笨」的样子，方便看清机制。

## 文件结构

```
.
├─ index.html                 # 入口页
├─ 基础版/
│  ├─ 知识库零门槛指南-基础版.html
│  └─ 练习场.html
└─ README.md
```

## 怎么打开

**本地**：下载后双击 HTML，不需要联网、不需要安装。

**在线**：<https://visionarying.github.io/kb-zero-barrier/>

## 它不是什么

- 不是知识库产品，不保存你的资料
- 不是 AI 应用，练习场不调用大模型
- 不能替代真实产品：真实产品还能连飞书、Notion、网盘，支持 PDF / Word / PPT

## 参考

做法参考了这些开源项目（只借鉴思路，未复制代码）：

- [RAGFlow](https://github.com/infiniflow/ragflow)
- [rag-from-zero](https://github.com/MisterBooo/rag-from-zero)
- [LLM Wiki](https://github.com/nashsu/llm_wiki)
- [WeKnora](https://github.com/Tencent/WeKnora)
- [MaxKB](https://github.com/1Panel-dev/MaxKB)
- [NoteGen](https://github.com/codexu/note-gen)

## 许可

MIT License。可以自由使用、修改、再发布，保留版权声明即可。
