BabyGrowthRecord - 宝宝成长记录 (纯净隐私版)

🌐 Languages / 语言
English | 中文

<a name="english"></a>

Baby Growth Tracker (Pure Privacy Edition)
🛡️ Core Security Statement:
This tool adopts a 100% pure frontend architecture design, committed to "zero data upload." All photos, names, birth dates, milestone events, and other information are saved only in your current mobile/computer browser cache. They will never pass through any server, nor will they be accessed by developers or third parties. Your data belongs solely to you.

📖 Project Introduction
This is a lightweight web application specifically designed for new parents. It abandons the cumbersome processes of traditional apps that require registration, login, and data uploading. It provides an instant-use baby age calculator accurate to the minute. Featuring a warm cherry blossom pink interface, it not only displays your baby's precise age (years/months/days/hours/minutes) in real-time but also automatically calculates "total days since birth," full-month/100-day/first-birthday anniversaries, living photo carousels, and major growth event records.

✨ Core Features
📸 Local Photo Memories
Supports uploading baby photos (avatar) and a carousel of 5 living photos. The system intelligently compresses images based on device performance.

Technical Highlight: Uses HTML5 Canvas technology to compress images locally and encode them into Base64 strings stored in browser localStorage. Your images never leave your device.

⏱️ Precise Time Calculation
Automatically handles leap years and varying month lengths. Real-time calculation and display: X years X months X days X hours X minutes. Special features: Cumulative days since birth, intelligent display of achieved full-month, 100-day, and 1st birthday anniversaries.

📅 Growth Milestones
Record every "first" for your baby, supports accuracy to the minute, automatically sorts in reverse chronological order (most recent first). Supports "date-only" mode. Supports secondary editing and correction of events.

★ Anniversary Pinning
Click the "☆" button to the right of any event in the list to set it as an anniversary, displayed in the top capsule area (text automatically truncated to first 5 characters).

💾 Full Data Sync
Supports generating comprehensive backup files containing photos, events, and information, facilitating data migration between devices.

🔒 Data Security & Privacy Details
Many parents worry about their baby's photos being leaked when uploaded online. This project fundamentally solves this problem at the technical level:

🚫 No Backend Server
This project has no backend database and no server receives data. It's like the "Calculator" app on your phone - a pure tool.

🔒 Sandbox Storage Mechanism
Data storage uses the browser's Local Storage technology. This means:

Data Isolation: Only the device you're currently using can see this information.

No Sharing: Even if you share the generated URL with family/friends, they will see a blank page when they open it (because the data is on your device, not in the URL).

Absolute Privacy: Unless someone physically accesses and unlocks your phone, no one can see this data.

📱 How to Use
Enter Information: Fill in your baby's nickname, birth date and specific time, upload an avatar.

Carousel Album: Click the image box below to select up to 5 photos at once.

Record Events: In the "Major Growth Events" section below, select the time and enter content. Click "+" to add. Click "✎" to modify content.

Set as Anniversary: In the event list, click the star icon "☆" to the right of any event content; a solid "★" indicates it's set as an anniversary.

Cross-Device Sync: Click "☁️ Backup All Data" to generate a .json file. Send this file to your new device; on the new device, click "📥 Restore All Data" and load this file to restore all content.

⚠️ Important Notes
Since data is saved in the browser's local cache, please note the following situations may cause data loss (requiring re-entry):

Manually clearing browser cache/history.

Using "Incognito/Private Mode" to open the webpage.

Uninstalling and reinstalling the browser app.

🛠️ Technology Stack
Core Languages: HTML5, CSS3, JS (ES6+)

Storage Technology: Web Storage API (localStorage)

Image Processing: Canvas API (for frontend image compression and encoding)

Deployment Method: Static Page Deployment (Static Hosting)

Developer: Don-cy

<a name="中文"></a>

宝宝成长记录 (纯净隐私版)

🛡️ 项目安全核心声明：
本工具采用 100% 纯前端架构设计，承诺"数据零上传"。所有照片、姓名、出生日期、大事件等信息仅保存在用户当前的手机/电脑浏览器缓存中，绝不会经过任何服务器，也不会被开发者或第三方获取。您的数据，只属于您自己。

📖 项目简介
这是一个专为新手父母设计的轻量级网页应用。它摒弃了传统 App 需要注册登录、上传数据的繁琐流程，提供了一个即开即用、精确到分钟的宝宝年龄计算器。界面采用温馨的樱花粉色调，不仅能实时显示宝宝的精确年龄（岁/月/天/时/分），还能自动计算"已出生总天数"、满月/百天/周岁纪念日、生活照轮播以及成长大事件记录。

✨ 核心功能
📸 本地化照片记忆
支持用户上传宝宝照片（头像）以及 5 张生活照轮播。系统根据设备性能智能压缩图片。

技术亮点：使用 HTML5 Canvas 技术在本地压缩图片，并转码为 Base64 字符串存入浏览器 localStorage。图片从未离开过您的设备。

⏰ 精准时光计算
自动处理闰年、大小月逻辑。实时计算并显示：X岁 X个月 X天 X小时 X分。特别呈现：累计出生天数，智能显示已达成的满月、百天、1周岁纪念日。

📝 成长大事件
记录宝宝的每一个第一次，支持精确到分钟，自动按时间倒序排列（最近发生的在最前）。支持"只记日期"模式。支持事件二次编辑与修正。

★ 纪念日置顶
在事件列表点击右侧"☆"按钮，可将该事件设为纪念日，显示在顶部胶囊区（文字自动截取前5个字）。

👾 全数据同步
支持生成包含照片、事件、信息的全量备份文件，方便换机数据迁移。

🔒 数据安全与隐私详解
很多家长担心宝宝的照片上传到网络会被泄露，本项目从技术底层彻底解决了这个问题：

🚫 无后端服务器
本项目没有后台数据库，没有服务器接收数据。它就像您手机里的"计算器"App 一样，是一个纯粹的工具。

🔒 沙盒存储机制
数据存储使用浏览器的 Local Storage 技术。这意味着：

数据隔离： 只有您当前使用的这台手机能看到这些信息。

无法共享： 即使您把生成的网址发给亲友，他们打开也是空白的（因为数据在您的手机里，不在网址里）。

绝对私密： 除非有人物理接触并解锁您的手机，否则没人能看到这些数据。

📱 如何使用
输入信息： 填写宝宝的小名、出生日期和具体时间，上传头像。

轮播相册： 点击下方的图片框，可一次性选择 5 张照片上传。

记录事件： 在下方"成长大事件"框中选择时间，输入内容。点击"+"号添加。点击"✎"可修改内容。

设为纪念日： 在事件列表中，点击某条记录内容右侧的星星图标，实心"★"代表已设为纪念日。

跨设备同步： 点击"☁️ 备份全部数据"生成 .json 文件，将文件发送给新设备；在新设备点击"📥 恢复全部数据"并加载该文件即可还原所有内容。

⚠️ 注意事项
由于数据保存在浏览器的本地缓存中，请注意以下情况可能会导致数据丢失（需重新输入）：

手动清理了浏览器的缓存/历史记录。

使用了"无痕浏览/隐私模式"打开网页。

卸载并重新安装了浏览器 App。

🛠️ 技术栈
核心语言： HTML5, CSS3, JS (ES6+)

存储技术： Web Storage API (localStorage)

图像处理： Canvas API (用于前端图片压缩与转码)

部署方式： 静态页面部署 (Static Hosting)

开发者： Don-cy

📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

⭐ Support
If you find this project helpful, please give it a star!
