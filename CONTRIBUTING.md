# Contributing

> 🇨🇳 中文版见文末 / Chinese version at the bottom.

Thank you for helping keep this record accurate and fair. The whole point
of this repository is to be **source-backed** — an entry without verifiable
sources is worse than no entry.

## Submitting a new case (blacklist)

1. **Check it qualifies** — see [METHODOLOGY](METHODOLOGY.md) §2. One
   authoritative outlet or one official document minimum; core facts
   corroborated.
2. **Create the files**
   - `cases/<entity-slug>/en.md` and `cases/<entity-slug>/zh.md`
     (mirror translations, both required),
   - slug = romanised short name + ticker, e.g. `xingyu-601799`.
3. **Use the template** below. Keep the metadata block at the top identical
   in both files.
4. **Evidence levels** — tag claims [OFFICIAL]/[MEDIA]/[PARTY]/[MARKET]
   (see METHODOLOGY §3). Open with official/media facts only.
5. **Downstream responses** — if the entity is a supplier, the
   *Downstream customer & partner responses* section is **mandatory**;
   if you searched and found none, write "None found as of <date>".
6. **Sources** — numbered `[1]…[n]`: outlet, title, date, URL. In both
   language versions.
7. **Update the index** — add a row to README.md and README.zh-CN.md.

### Case template

```markdown
# <Entity legal name (EN)> (<中文全称>, <TICKER>)

> 🇨🇳 [中文版](zh.md) · 🇬🇧 [English](en.md)

**Entity:** <full legal name; Chinese + English>
**Industry:** <industry / tier in chain>
**Board:** ⚫ Black — <one-line reason, event description not legal label>
**First public:** <YYYY-MM-DD>
**Status:** ⏳/🛑/✅/⚪ <description>
**Last updated:** <YYYY-MM-DD>

## Summary
## Key facts
## Timeline
## Company's own response
## Downstream customer & partner responses   <!-- mandatory for suppliers -->
## Regulatory involvement
## Implications for workers
## Sources
1. <outlet>, "<title>", <YYYY-MM-DD>, <URL>
## Corrections
```

## Red-list cases (future)

Once the red list opens, same schema; `Board:` becomes ⚪ Red with the
documented positive record and its sources. Watch this space.

## Correcting an error

- Open an issue describing exactly what is wrong and what the correct
  fact + source is, **or** submit a PR.
- Maintainers verify against the source, fix, and append a line to the
  case's *Corrections* section: `YYYY-MM-DD — fixed <X> (source: <URL>).`

## A company wants to respond

You are welcome to reply. Open an issue titled `Response: <entity>` or
email-address visible on the repository owner's profile page. Provide:

- who you are and your role at the company,
- the specific statements you dispute, and
- documentary support (company announcements, filings, court documents).

Substantiated responses are appended to the case file's *Company response*
section with their sources. Unsubstantiated denials without documentation
are recorded as "company disputes the account without providing documents".

## Ground rules

- No personal data of individuals (addresses, ID numbers, phones, private
  photos). Affected workers appear as the reporting outlets named them.
- No harassment. This is a documentation project, not a doxxing one.
- Chinese and English versions must not diverge in facts; only in language.

---

# 贡献指南(中文)

目标:让这份记录准确、公平。本仓库的灵魂是**有信源**——没有可核实信源的
条目比没有更糟。

## 提交新案件(黑榜)

1. **先核对资格** — 见[方法论](METHODOLOGY.zh-CN.md)§2:至少一家权威媒体
   或一份官方文件;核心事实需交叉印证。
2. **创建文件** — `cases/<slug>/en.md` 与 `zh.md`(双语互译,两份都要),
   slug = 罗马音简称 + 代码,如 `xingyu-601799`。
3. **用下方模板**,两份文件的元信息块保持一致。
4. **标注证据等级** [官方]/[媒体]/[当事方]/[市场](方法论 §3),
   开头只能用官方/媒体级事实。
5. **下游应对必填** — 主体是供应商时,"下游客户与合作伙伴的应对"为必填节;
   查过但没有,就写"截至 <日期> 未发现公开应对"。
6. **信源编号** `[1]…[n]`:媒体、标题、日期、URL,中英两份都要。
7. **更新索引** — 在 README.md 和 README.zh-CN.md 各加一行。

### 案件模板

```markdown
# <主体法定全称(EN)>(<中文全称>, <代码>)

> 🇬🇧 [English](en.md) · 🇨🇳 [中文版](zh.md)

**主体:** <法定全称(中英)>
**行业:** <行业 / 产业链位置>
**榜单:** ⚫ 黑榜 — <一句话事由(描述事件,不作法律定性)>
**首次公开:** <YYYY-MM-DD>
**状态:** ⏳/🛑/✅/⚪ <说明>
**最后更新:** <YYYY-MM-DD>

## 摘要
## 关键事实
## 时间线
## 企业自身回应
## 下游客户与合作伙伴的应对   <!-- 供应商必填 -->
## 监管介入
## 对求职者的提示
## 信源
1. <媒体>, "<标题>", <YYYY-MM-DD>, <URL>
## 更正记录
```

## 红榜(未来)

红榜开放后同一套结构,`榜单:` 改为 ⚪ 红榜 + 有信源的正面记录。

## 纠错

- 开 Issue 说明哪里错、正确事实+信源是什么;或直接提 PR。
- 维护者核对信源后修正,并在档案"更正记录"追加一行:
  `YYYY-MM-DD — 更正 <事项>(信源: <URL>)。`

## 企业想回应

欢迎回应。开一个标题为 `Response: <主体>` 的 Issue,或邮件至仓库主页所示
联系方式,提供:你的身份与职位、你质疑的具体表述、书面证据
(公司公告、文件、法院文书)。有依据的回应将连同信源追加到档案
"企业自身回应"一节;无凭据的否认会记录为"企业否认该说法但未提供文件"。

## 底线

- 不收录个人隐私数据(住址、证件号、电话、私人照片);受影响员工一律按
  报道媒体的称呼(通常为化名)。
- 不骚扰、不人肉。这是文档项目,不是开盒项目。
- 中英版本事实必须一致,只允许语言不同。
