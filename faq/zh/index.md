# BossAI Desktop 常见问题（FAQ）

## 产品基础

### 1. BossAI Desktop 是什么？
BossAI Desktop 是一款 AI 原生内容工作台。使用你自己的 API Key，一句话即可完成聊天、图片、视频、音频创作。所有数据保存在本地，无需云依赖。

### 2. 和 ChatGPT 有什么区别？
ChatGPT 是一个聊天界面。BossAI 是一个内容工作台——支持多步骤自动工作流（Director）、多 Provider 统一管理、本地资产库、项目记忆。你可以在一个工具里完成文案、配图、视频、配音的全部创作。

### 3. BossAI 和 Midjourney 有什么区别？
BossAI 内置图片生成能力（通过 GPT Image、即梦等 Provider），同时还能写文案、做视频、配音。不需要在多个工具之间切换。

### 4. BossAI 是 SaaS 吗？
不是。BossAI Desktop 是本地桌面应用。所有数据保存在你的电脑。V2 会提供可选的 SaaS 同步。

### 5. 需要联网吗？
需要。BossAI 本身是本地应用，但 AI 生成需要调用云端的 AI Provider API。

### 6. 支持 Mac 吗？
当前版本仅支持 Windows 10+。Mac 版本在路线图中。

### 7. 支持手机吗？
V1 仅支持 Windows Desktop。Mobile 在 V2 路线图中。

### 8. BossAI 支持哪些语言？
界面支持中文和 English。AI 生成内容支持所有语言（取决于你使用的 Provider 的能力）。

### 9. BossAI 是开源的吗？
BossAI Desktop 是闭源商业软件。我们相信好的产品值得付费。

### 10. 有云端版吗？
V1 是纯本地桌面版。SaaS 版本在 V2 路线图中。

## 安装

### 11. 如何安装？
下载安装程序，双击运行，按照提示完成安装。详见安装教程。

### 12. 系统要求？
Windows 10 或更高版本（64 位），4GB 内存，500MB 磁盘空间。

### 13. 安装被安全软件拦截怎么办？
BossAI 是正规桌面应用。如果被拦截，选择"仍要运行"或将程序加入白名单。

### 14. 安装后无法启动？
确保系统为 Windows 10 64 位以上。尝试以管理员身份运行。

### 15. 提示缺少 DLL？
安装 Visual C++ Redistributable for Visual Studio 2015-2022。

### 16. 如何卸载？
通过 Windows 设置 → 应用 → BossAI Desktop 卸载。

### 17. 如何更新？
V1.x 更新免费。下载最新版本安装程序覆盖安装即可。

## API

### 18. 需要什么 API Key？
至少需要一个 LLM Provider 的 API Key。推荐 DeepSeek（注册送额度）或 OpenAI。在 API Center 配置。

### 19. 如何获取 DeepSeek API Key？
访问 platform.deepseek.com，注册账号，在 API Keys 页面创建。

### 20. 如何获取 OpenAI API Key？
访问 platform.openai.com，注册账号，在 API Keys 页面创建。

### 21. API Key 安全吗？
所有 API Key 仅保存在你的电脑本地存储中。它们不会被发送到除对应 Provider 官方 API 端点之外的任何服务器。

### 22. 可以用自己的模型吗？
当前版本不支持本地模型。如果 Provider Framework 不支持你的模型，可以通过 OpenAI 兼容接口接入。

### 23. 支持 Azure OpenAI 吗？
支持。在 API Center 配置 OpenAI Provider 时修改 Base URL 为你的 Azure 端点即可。

### 24. 支持国内模型吗？
支持。通义千问、Kimi、GLM、MiniMax、豆包、即梦、可灵等都支持。

## 收费

### 25. BossAI 怎么收费？
一次性购买，永久使用。当前 Early Access 优惠价。

### 26. 有免费试用吗？
有。新用户有 10 次免费生成，无需激活码即可体验全部功能。

### 27. 买断后需要再付费吗？
V1.x 更新免费。V2 升级需单独购买。

### 28. API 调用费用谁出？
用户自行承担。API 费用直接付给 DeepSeek、OpenAI 等 Provider，BossAI 不收取任何 API 中间费用。

### 29. 可以退款吗？
Early Access 期间提供满意保证。如有问题请联系我们。

### 30. 有教育优惠吗？
目前没有。未来可能提供。

## 授权

### 31. 如何激活？
在 License 页面输入激活码即可。激活码格式：BOSSAI-xxxx。

### 32. 激活码可以转移吗？
当前版本为设备锁定。建议在主要工作电脑上激活。

### 33. 可以多台电脑用吗？
Starter 和 Professional 为单设备授权。Business 计划支持多设备。

### 34. 激活码丢失怎么办？
联系客服，提供购买凭证可重新获取。

### 35. 换电脑了怎么办？
联系客服协助迁移。V2 将支持账户绑定。

## 数据

### 36. 数据保存在哪里？
所有数据保存在你的电脑本地。不上传任何云端。

### 37. BossAI 会收集我的数据吗？
不会。BossAI 不收集使用数据、不遥测、不上传任何文件。

### 38. 生成的内容版权归谁？
归你。你拥有所有生成内容的完整知识产权。

### 39. 可以删除所有数据吗？
可以。Asset Library 支持删除。卸载应用时数据不会自动删除，需要手动清理。

### 40. 数据可以迁移到其他电脑吗？
当前版本不提供自动迁移。可以手动复制 localStorage 中的配置数据。

## 功能

### 41. Director 是什么？
Director 是 BossAI 的智能工作流引擎。你输入一句自然语言描述，Director 自动规划步骤、执行、保存结果。

### 42. Professional Mode 和 Director Mode 有什么区别？
Professional Mode 让你直接使用 AI Chat、Image、Video、Audio。Director Mode 自动处理多步骤工作流。两者共存。

### 43. 支持批量生成吗？
V1 通过 Director 可连续执行任务。批量生成在 V1.1 中增强。

### 44. 支持团队协作吗？
V1 为单人使用。团队协作在 V2 路线图中。

### 45. 支持导出吗？
支持。生成的内容可以查看和导出。视频可通过渲染功能导出为 MP4。

### 46. 支持哪些平台的内容？
AI 生成的内容适用于任何平台：抖音、小红书、TikTok、YouTube、Instagram、微信公众号等。

## 更新

### 47. 更新频率？
V1.0 Early Access 阶段按需更新。V1.1 计划每月更新。

### 48. 如何获取更新？
关注官网和 GitHub Releases 页面。

### 49. 大版本升级收费吗？
V1.x 免费。V2 升级需单独购买。

### 50. 反馈问题渠道？
通过 GitHub Issues 或联系客服提交反馈。
