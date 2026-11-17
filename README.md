# 陈斌

平时主要做两件事：给内容团队做数据采集工具，以及帮国内重度用户把满血版 Claude 稳稳当当地落地到本机工作流里。

## 1. 国内稳定使用 Claude（实操系列与原生环境部署）

现在在国内长期用 Claude，光靠挂个普通节点已经行不通了：邮箱属性、网络纯净度、本机历史残留、支付渠道四个环节只要有一处踩坑，账号就容易被清退或连坐。

我把实测有效的经验、自检工具以及市面上 6 种主流方案（含海外 VPS、远程 Mac Mini 与本机部署）的对比拆成了下面四个公开仓库：

| 仓库 | 主要帮你解决什么问题 |
|---|---|
| **[get-claude-in-china](https://github.com/sobadgirl/get-claude-in-china)** | **市面上 6 种用法深度对比 + 1 对 1 本机原生环境整包部署服务（省心首选）** |
| **[use-claude-in-china](https://github.com/sobadgirl/use-claude-in-china)** | 想自己动手折腾？从旧机清痕、美区 Apple ID 免税州到礼品卡内购的完整步骤 |
| **[claude-fangfen](https://github.com/sobadgirl/claude-fangfen)** | 账号为什么突然被封？四维联合校验、72 小时观察期与连坐止损排查手册 |
| **[awesome-claude-cn](https://github.com/sobadgirl/awesome-claude-cn)** | 开号前必跑的 4 个环境小测试、终端一键只读自检脚本与精选中文资料 |

> [!TIP]
> **不想花几天时间自己试错踩坑？**
> 如果你想省心、无痛地在自己电脑和手机上长期稳定用上官方满血 Claude，可以直接看 **[get-claude-in-china](https://github.com/sobadgirl/get-claude-in-china)**：1 对 1 远程配齐**美国独享静态住宅 IP + 专属国际企业域名邮箱 + 本机深度清痕与防关联配置**，**6 个月内官方封号全额退部署费**（直接加微信：**`cjdb2026`**，备注 `Claude`）。

## 2. 抄级对标（内容采集与整理工具链）

给内容研究者和自媒体团队做的一套多平台内容采集工具。

浏览器插件支持手动采集小红书和抖音的搜索结果、作品正文、高赞评论与作者主页信息，一键同步进 Notion、飞书多维表格或导出本地 Markdown / CSV；不做后台暴力轮询，保护账号安全。配套管理端支持统一跟进多平台对标账号更新。

- 开源仓库：[浏览器采集插件（cjdb-web-crawler）](https://github.com/ChaoJiDuiBiao/cjdb-web-crawler) · [采集与管理端（cjdb-collectors）](https://github.com/ChaoJiDuiBiao/cjdb-collectors)

## 联系我

- **微信**：**`cjdb2026`**
- 通用技术问题可以直接在对应仓库提 Issue；涉及 Claude 本机环境部署咨询、企业多账号配置或个人隐私细节，请直接加微信沟通。
