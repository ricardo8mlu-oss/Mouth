# Mouth

把懂的英语，说出来。面向长期日常交流的 macOS 桌面练习软件。

## 下载

在本仓库的 **Releases** 页面下载最新预览安装包。支持 macOS 14 及以上，包含 Apple Silicon 和 Intel 两种架构。

当前为 **2.1.0-rc1 公开预览版**，尚无 Developer ID 签名和 Apple 公证；其他 Mac 首次运行可能被 Gatekeeper 阻止。此包供自愿预览，不是已完成 Apple 公证的正式版，不要求关闭系统安全保护。

## 功能

- 20,000 个英汉词条，支持中英文离线查询和加入背诵。
- 358 条短语、358 条句子和 36 个基础单词卡；新短语配有双语完整例句，例句可独立练习。
- 13 个可反复练习的主题、词句近义星图和 60 条俚语表达。
- 阶段目标：自选天数、每天时间、当前基础及词句数量，先计算方案，再启用每日任务与间隔复习。
- 主动回忆、日常互动、手动打卡、实际计时、阶段回顾与本机备份。

雅思相关话题和训练功能参考 [IELTS 官方说明](https://ielts.org/news-and-insights/three-parts-of-ielts-speaking-and-what-to-look-out-for) 与 [British Council](https://takeielts.britishcouncil.org/teach-ielts/teaching-resources/lesson-plans-speaking)。新增例句为原创，不是官方真题、范文或雅思官方产品。规划是估算，不承诺固定天数学会英语、流利程度、排名或考试分数。

## 安装与隐私

打开 DMG 后将 Mouth.app 拖入“应用程序”。已有版本更新前建议在设置中导出 JSON 备份。公开版学习数据位于 `~/Library/Application Support/MouthPublic`，卸载软件不会自动删除记录。

学习记录只存本机，不注册账号、不录音、不上传学习记录，不含广告或分析追踪。朗读由 macOS 系统语音提供，不自动识别口语或评分。点击外部资料链接时会打开相应网站。

词典数据来自 [ECDICT](https://github.com/skywind3000/ECDICT)，完整 MIT 许可随应用提供。20,000 为源词头数量，并非能力等级或 20,000 个词根；源释义没有逐条人工重写。星图覆盖已收录表达，不对全部词典自动生成。

此仓库用于安装包下载、版本说明和问题反馈；未附带个人学习记录或测试数据。下载后可对照 `SHA256SUMS.txt` 核验文件。
