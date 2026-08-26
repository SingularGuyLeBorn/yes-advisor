<div align="center">

# 是,导师(Yes, Advisor)

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/en/2/2f/Administrative_Affairs.jpg" alt="Yes Minister" width="480" />
  <br/>
  <sub>半步英剧治天下.</sub>
</p>

> *「我们是为了让导师认为我们实事求是,而我们自己都知道并没有.」*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![事实上](https://img.shields.io/badge/事实上-假的-red)](#)
[![统计上](https://img.shields.io/badge/统计上-真的-green)](#)
[![宋体](https://img.shields.io/badge/本文件不是-宋体-lightgrey)](#)

<br>

**一个科研笑话集.文体上不幸与某部英国电视剧雷同,纯属巧合.**

<br>

全部内容均为虚构:<br>
在事实上是假的,在统计上是真的.

[看段子](#效果示例) · [仓库结构](#仓库结构) · [科研Joker.skill](#科研jokerskill) · [开源许可](#开源许可)

</div>

---

## 效果示例

```
我      ❯ 师兄,你觉得做科研扯淡吗?

师兄    ❯ 吐槽科研是世界上倒数第二无聊的事情.

我      ❯ 那第一呢?

师兄    ❯ 做科研.
```

```
我      ❯ 师兄,组会汇报有什么技巧?

师兄    ❯ 记住,组会只有一个正确答案:「快了」.

我      ❯ 那要是真做完了呢?

师兄    ❯ 那你的麻烦就大了.
```

```
我      ❯ 导师说我的报销单他「会考虑一下」,都三个月了.

师兄    ❯ 你不懂导师的措辞体系.「我考虑一下」,意思是单子
        已经找不到了;「我认真考虑一下」,意思是他正在找.

我      ❯ 那「我已经考虑过了」呢?

师兄    ❯ 意思是你再也见不到它了.
```

> 更多见 [`正篇/`](正篇/) 目录.每篇独立成章:公文戏仿开头 + 正文 + 公文戏仿结尾 + 注释.

---

## 仓库结构

```
yes-advisor/
├── README.md           # 你正在看的这份门面
├── 正篇/               # 笑话本体,每篇独立成章
│   ├── 01-我们是为了让导师认为我们实事求是.md
│   ├── 02-仪器只有两个状态.md
│   ├── 03-组会只有一个正确答案.md
│   ├── 04-四幕.md
│   ├── 05-国自然标书与预实验伦理.md
│   ├── 06-学术道德真空.md
│   ├── 07-毕业是一个吸收态.md
│   ├── 08-学术会议的主要成果是下一次学术会议.md
│   └── 09-本表用于证明本表.md
├── 开头结尾/            # 备用公文模板库(开题/结题未使用版本)
│   ├── 开题-版本J-采购申请.md
│   ├── 结题-版本J-入库验收单.md
│   ├── 开题-版本K-请假条.md
│   ├── 结题-版本K-销假证明.md
│   ├── 开题-版本L-门诊病历.md
│   └── 结题-版本L-出院小结.md
├── .agents/skills/
│   └── 科研Joker/       # 让 AI 继续写这个风格的 skill
└── LICENSE             # MIT
```

---

## 科研Joker.skill

本仓库内置一个可安装的 Agent Skill:[`.agents/skills/科研Joker/`](.agents/skills/科研Joker/).

不是语录合集,是可运行的讽刺框架:13 条核心技法,24 条原剧典故,公式笑话五步配方,4 条失败案例,12 项质检清单.

```bash
git clone https://github.com/SingularGuyLeBorn/yes-advisor
cp -r yes-advisor/.agents/skills/科研Joker <你的 runtime 的 skills 目录>
```

装好后对你的 agent 说:

```
> 用科研Joker写一篇,主题是盲审
```

详细说明见 [科研Joker/README.md](.agents/skills/科研Joker/README.md).

---

## 开源许可

本项目以 MIT License 开源.

翻译过来就是:随便用,别赖我.

---

<div align="center">

<br>

| 「这个世界太他妈的扯淡了,但是也不是一无是处.」 |
|:---:|

<br>

<sub>本项目不存在.如你认为自己看到过本项目,请参照结题报告处理.</sub>

<br>

MIT License © [SingularGuyLeBorn](https://github.com/SingularGuyLeBorn)

</div>
