# 陈斌

做两件事：把散落的内容变成能用的数据，再把 AI 接进这条链路。

## 采集与整理

我做的是「进得来、存得住、找得到」这条链路。

**抖音采集。** 关键词搜作品、批量采详情、拉评论和作者数据，结果直接写进 Obsidian Base，不用手工复制粘贴。翻页、去重、字段映射都在脚本里。

**视频转写。** ffmpeg 抽音频，FunASR 出带标点的中文文本，全程本地跑，不上传云端。

**内容摘要。** 把转写稿压成结构化条目，服务于后面的选题聚类和账号拆解。这一步最难，因为要保真，不能让模型替你重新创作一遍。

**WeFlow。** 微信聊天记录本地导出与年度报告，[公开仓库](https://github.com/sobadgirl/WeFlow)。

这条链路上我攒了近千条对标作品，工具还在整理，会陆续放出来。

## Claude 在国内怎么稳定用

2026 年卡人的不是技术，是四个环节的联合校验：邮箱属性、网络纯净度、设备历史痕迹、支付渠道。任何一环不达标，其余三环做得再好都会被打回原点。

大部分教程只讲一环。这四个仓库把四环串起来。

| 仓库 | 解决什么 |
|---|---|
| [use-claude-in-china](https://github.com/sobadgirl/use-claude-in-china) | 从零到能用，每一步怎么操作 |
| [claude-fangfen](https://github.com/sobadgirl/claude-fangfen) | 什么行为会炸，为什么炸 |
| [awesome-claude-cn](https://github.com/sobadgirl/awesome-claude-cn) | 中文圈资源合集，附一份环境体检表 |
| [get-claude-in-china](https://github.com/sobadgirl/get-claude-in-china) | 不想自己折腾的，看这个 |

想自己动手，按教程一步步来。想省事，直接看最后一个。

## 底子

Python 出身，写 Django、DRF、FastAPI，数据库常用 PostgreSQL 加 PostGIS。现在大部分时间花在 AI 工作流和数据链路上。

## 联系

微信：cjdb2026

有共性问题开 Issue，答一次后面的人都能看到。涉及账号和支付的细节走微信，别贴在公开区。
