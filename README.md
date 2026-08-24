<p align="center">
  <img src="./assets/banner.svg" alt="XXD Panel 003 项目横幅" width="1200">
</p>

<div align="center">

# 🦁 XXD Panel 003

### 把照片里的方向、连接、压力与转机压缩成安静而紧张的黑色观念线条

[![Codex Skill](https://img.shields.io/badge/Codex-Skill-000000?style=flat-square)](./SKILL.md)
[![Four Modes](https://img.shields.io/badge/Modes-4-d75d32?style=flat-square)](#四种输出共享同一种手绘逻辑)
[![Raster Output](https://img.shields.io/badge/Output-PNG-3c6f67?style=flat-square)](#边界与信任)

<strong>简体中文</strong> · <a href="README.en.md">English</a> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a>

</div>

> 连续黑线 · 公共议题 · 受力结点 · 留白沉默 · 向外释放

XXD Panel 003 是一个面向 Codex 与兼容 Agent 的图像生成 Skill。它不描摹照片表面，而是锁定主体身份与关系，把源图中的方向、连接、矛盾、压力和转机压缩成一组连续黑色手绘线。线从边缘进入，在低位或侧位盘绕、交错、回折、收紧，再向上或向外释放；原主体的象征轮廓从运动与负形中浮现，却不被完整解释。

画面不复制照片表面，而是从源图事实中找到一个聪明、轻巧、可回看的视觉转化。它融合现代主义编辑插画、包豪斯秩序、绘本温度和时装速写的松弛感；文字像画者顺手留下的克制手写注记，而不是后来贴上去的广告标题。

## 为什么需要 003

普通“极简线条”很容易退化成漂亮但空洞的装饰曲线、机械一笔画，或套用拳头、牢笼、泪滴、铁链等公共议题图标。

003 的顺序完全相反：

```text
锁定源图身份与受力事实 → 规划线条进入、缠绕与收紧 → 让源图轮廓从交叉和负形中显露 → 在转机处向上或向外释放 → 只在真实力点加入结、刺或倒钩 → 让文字缩成线旁的微小痕迹
```

如果换成一张无关照片，线条路线、交叉点、受力点、浮现轮廓和文字仍然成立，这张图就不属于 003。

## 003 的视觉契约

- **源图受力事实：** 至少保留三个身份线索，并分别判断有证据的方向、连接、矛盾、压力和转机，不虚构议题。
- **连续黑线路线：** 线从边缘进入，在偏下、偏侧或靠边处盘绕、交错、回折与收紧，再向上或向外释放。
- **浮现而非描边：** 主体轮廓从线路运动、交叉与负形中显露，可以不闭合，但必须一眼可感知原物。
- **有压力的手工线：** 黑色或近黑细线带轻微粗细变化、摩擦、迟疑、断裂和重新接续，不做光滑贝塞尔曲线。
- **力点标记：** 尖刺、结点、倒钩或短横只放在真实受力、交叉和转向处，不能均匀装饰。
- **留白作为沉默：** 冷白、米白或低饱和浅底占主导，线条系统偏下或偏侧，不居中、不铺满。
- **微型议题文字：** 只保留一个极短主题词或短句，像线条旁的微小痕迹，不成为口号或解释。

## 样张 · 来自 X

> [小小东（@xiaoxiaodong01）](https://x.com/xiaoxiaodong01/status/2089959872876228689) · 2026-08-19<br>
> GPT2 x 转绘 x 带刺 x 线条 x 美学提示词 x VOL.003

<table>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2089959872876228689"><img src="./assets/examples/sample-01.jpg" alt="XXD Panel 003 样张 1"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2089959872876228689"><img src="./assets/examples/sample-02.jpg" alt="XXD Panel 003 样张 2"></a></td>
  </tr>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2089959872876228689"><img src="./assets/examples/sample-03.jpg" alt="XXD Panel 003 样张 3"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2089959872876228689"><img src="./assets/examples/sample-04.jpg" alt="XXD Panel 003 样张 4"></a></td>
  </tr>
</table>

<p align="center"><a href="https://x.com/xiaoxiaodong01/status/2089959872876228689">查看原推文与完整提示词 →</a></p>

这些样张用于展示 003 的美学动机，不会把样张中的主体、构图、配色、文案或旧画幅变成生成参考或当前默认值。

## 四种可组合输出模式

可用 `1`、`1+3`、`1、2、4` 或 `全部` 选择一个或多个模式；`全部` 每张源图输出 7 个独立 PNG。模式确定后，Skill 会在生图前继续询问整张最终成品的画幅：`3:4` 原提示词画幅、明确跟随原图、常用比例，或自定义比例／准确像素。不会再静默套用源图尺寸。

| 模式 | 画幅逻辑 | 成品 |
| --- | --- | --- |
| `top-bottom` | 用户确认的整张成品画幅 | 一次生成完整画布：高保真原图在上，003 设计在下，约 50/50 |
| `left-right` | 用户确认的整张成品画幅 | 一次生成完整画布：高保真原图在左，003 设计在右，约 50/50 |
| `design-only` | 用户确认的整张成品画幅 | 003 设计铺满画布，不显示原照片 |
| `wallpaper-pack` | 逐设备确认 | 手机、iPad、电脑、儿童手表四张独立 PNG |

双联默认把原图作为高保真垫图／编辑参考，用一套完整提示词直接生成一张整体成品，让摄影、设计、色彩、光线、文字与含义自然呼应。只有完整画布针对性重试仍失败、用户要求原片逐像素不变、当前通道无法实现目标画幅，或需要无创像素校准时，才启用确定性拼合兜底。

壁纸可选连贯或独立。连贯套装先批准一张 iPad 定调图，另外三张分别参考原图＋同一定调图重新构图；独立套装的四张都只参考原图。两者都不会裁切其他设备成品或串联衍生图。

## 文字只能是线条系统里的痕迹

正式生图前，先选择自动文案、自定义文案或无文字。有文字时还要指定目标语言或地区。

自动文案从源图可证实的关系、压力、穿越、转机或释放中提炼一个极短主题词或短句，但不替用户建立公共议题或倡议立场。

默认只有一个标题；只有确有信息价值时才增加零至两条短注释，不会为了显得高级而编造编号、年份、坐标或档案标签。文案仍需通过换图测试。

用户提供最终成稿时逐字保留。用户提供的是方向或可编辑草稿时，才会在保留受众、目的、必备词、语气和潜台词的前提下专业深化。

语言遵循目标受众，而不是用户下指令时使用的语言：

```text
目标市场或受众 > 指定成品语言 > 用户方向语言；都不明确时生图前询问
```

日本版使用自然日语，韩国受众使用自然韩语与正确空格，英国版使用英式英语，阿拉伯语版默认使用自然的现代标准阿拉伯语和真正的从右到左排版。字体也会转译为当地文字系统中自然、略带手写温度的字形，而不是把拉丁字体规则生硬套过去。

## 完整画布优先与位图边界

图像模型负责整张成品的审美重构，双联也默认一次直出完整画布。`scripts/compose_panel.py` 只保留为条件明确的兜底、无创尺寸校准和只读审计工具，不再预先规划每次任务，也不评价审美是否成功。

全部交付为 PNG 位图。每次调用都在 `~/Desktop/xxd/` 下创建新任务；已配置图像通道只返回脱敏状态，不公开供应商、端点、凭据、请求头、提示词、响应或账户信息。SVG、HTML、Canvas、图表和程序绘图不能替代最终作品。

## 开始使用

```bash
git clone https://github.com/nevertoday/xxd-panel-003.git
mkdir -p ~/.codex/skills
ln -s "$(pwd)/xxd-panel-003" ~/.codex/skills/xxd-panel-003
```

Claude Code 用户可以把同一目录链接到 `~/.claude/skills/xxd-panel-003`。安装后重新启动 Agent 会话。

```text
$xxd-panel-003
把这张照片做成左右双联，文案由你根据照片内涵创作，使用自然韩语。
```

只上传照片也可以调用。Skill 会先用分行编号菜单询问一个或多个模式，再询问文字设置；选择壁纸时还会确认连贯或独立以及设备尺寸。

完整规范：

- [Skill 工作流](SKILL.md)
- [中文完整提示词](references/xxd-panel-003-prompt.zh-CN.md)
- [英文完整提示词](references/xxd-panel-003-prompt.en.md)
- [原始风格提示词](references/003-source.md)

## 边界与信任

- 每张照片只在自己的任务中使用，不借用其他输入、旧成品或样张里的主体、颜色、文案和构图。
- 每次调用都创建新的任务子文件夹；相同原图和参数也要重新生成，旧成品不能冒充当前任务。
- 最终交付为 PNG 位图，不是 SVG、HTML、Canvas 或程序绘图替代品。
- 已配置位图桥接只返回脱敏状态，不显示供应商、端点、请求头、凭据、提示词或服务器响应正文。
- 每个所选普通模式各返回一张；若选择 `wallpaper-pack`，再返回四张独立壁纸。选择 `全部` 时每张原图共返回 7 个 PNG，分处四个同级模式文件夹，绝不生成拼贴总览。

本地拼版需要 Python 3 和 Pillow。安全位图桥接使用 Python 3.11+ 的 `tomllib`。图像生成仍需要主机 Agent 的内置位图能力或已经配置好的兼容位图路径。

## 项目结构

```text
xxd-panel-003/
├── SKILL.md
├── README.md / README.en.md / README.ja.md / README.ko.md / README.ar.md
├── agents/openai.yaml
├── assets/
│   ├── banner.svg
│   └── examples/（未来本地样张占位）
├── scripts/
│   ├── compose_panel.py
│   └── configured_imagegen.py
└── references/
    ├── xxd-panel-003-prompt.zh-CN.md
    ├── xxd-panel-003-prompt.en.md
    └── 003-source.md
```

## 关于 XXD

XXD 是小小东的品牌名称缩写。项目由 [@xiaoxiaodong01](https://x.com/xiaoxiaodong01) 创建并维护。

## 服务与会员

### 深度咨询 · 299 元/小时

Skills 使用的一对一深度咨询按 299 元/小时收费。请通过下方微信二维码联系小小东预约。

### 小小东 Skills 用户交流群 · 入群 99 元

一次支付 99 元加入用户交流群，用于交流工作流、作品与互助；不包含按小时的一对一深度咨询。扫码后请备注“Skills 用户交流群”。

### 知识星球＋成员提示词库 · 699 元/年

[知识星球](https://wx.zsxq.com/group/15554814142882)与[小小东成员提示词库](https://vip.xiaoxiaodong.ai/)是同一份会员权益：**一次年费同时开通两边，无需重复付费。**

1. 在[知识星球](https://wx.zsxq.com/group/15554814142882)开通后，微信联系小小东领取成员提示词库兑换码。
2. 在[成员提示词库](https://vip.xiaoxiaodong.ai/)自助开通后，微信联系小小东邀请进入知识星球。

<p align="center">
  <a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="小小东付费服务微信二维码" width="320"></a>
</p>

<div align="center">

**不替照片喊口号，只让那根线把压力、穿越与释放留下来。**

</div>

---

<div align="center">
  <h2>☕ 为开源项目赞助算力</h2>
  <p>如果这个项目为你节省了时间，可以通过微信或支付宝赞助后续测试与生成算力。</p>
  <table>
    <tr>
      <td align="center" width="240">
        <a href="https://colors.xiaoxiaodong.ai/docs/images/wechat-reward-qr.png"><img src="https://colors.xiaoxiaodong.ai/docs/images/wechat-reward-qr.png" alt="小小东微信算力赞助二维码" width="180"></a><br>
        <strong>微信算力赞助</strong>
      </td>
      <td align="center" width="240">
        <a href="https://colors.xiaoxiaodong.ai/docs/images/alipay-reward-qr.png"><img src="https://colors.xiaoxiaodong.ai/docs/images/alipay-reward-qr.png" alt="小小东支付宝算力赞助二维码" width="180"></a><br>
        <strong>支付宝算力赞助</strong>
      </td>
    </tr>
  </table>
  <p><sub>赞助完全自愿，不会改变这个开源项目的使用权限。</sub></p>
</div>
