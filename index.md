# SlyMask 棒球 / SlyMask Baseball 隐私政策

生效日期 / Effective Date: 2026 年 8 月 1 日 / August 1, 2026  
最后更新 / Last Updated: 2026 年 8 月 1 日 / August 1, 2026

---

# 中文版

## 1. 概述

SlyMask 棒球（以下简称“本应用”）由个人开发者开发和维护。我们重视你的隐私，本政策说明本应用在你使用比赛记录、本地 AI 动作分析、教练指导、训练计划、AR 测距及其他功能时如何处理信息。

- 本应用不要求注册账号。
- 你导入或创建的视频、照片、语音录音、动作分析结果、比赛记录和教练标注均在设备本地处理和保存；我们不运营用于接收这些内容的开发者服务器，也不保存服务器副本。
- 本应用不接入 HealthKit，不读取或收集健康数据、心率数据或体能数据。
- 本应用不包含第三方广告 SDK、第三方分析 SDK或第三方追踪 SDK，不使用 IDFA，不进行跨应用或跨网站追踪，也不出售个人信息。

## 2. 设备权限

本应用仅在你主动使用对应功能时申请必要权限。你可以随时在 iOS“设置”中关闭权限；关闭后只会影响对应功能。

### 2.1 相机

本应用仅在你使用 AR 测距时申请相机权限。相机画面在设备本地实时处理，不会保存或上传至开发者服务器。

### 2.2 相册读取

本应用使用 Apple 提供的系统选择器，让你主动选择投球或挥棒视频、球员图片及其他媒体，用于本地动作分析、教练指导或记录。未由你选择的相册内容不会被本应用读取。

### 2.3 相册写入

仅当你主动点击保存或导出时，本应用才会把报告卡、图片、教练指导视频或合作方二维码写入系统相册。

### 2.4 麦克风

仅当你在教练指导中主动点击开始录音时，本应用才会使用麦克风录制语音讲解。录音期间，界面会显示明确的录制状态和录音时长。

语音录音会与视频播放位置及画面标注的时间信息一起保存在设备本地，用于预览、继续编辑和导出同步的指导视频。除非你主动导出或分享，否则录音不会离开你的设备。

### 2.5 通知

仅当你主动开启训练提醒时，本应用才会申请通知权限，并在设备本地安排通知。提醒内容和时间不会发送至开发者服务器。

本应用不会申请健康、通讯录或精确位置权限。

## 3. 我们在设备本地处理的信息

为提供你主动选择的功能，本应用可能在设备本地处理和保存：

- 棒球或垒球比赛记录、球队、球员、打击、投球、跑垒、防守及统计数据；
- 投球九宫格、击球训练、训练计划、训练进度、能力评估、装备清单和战术板内容；
- 你选择的视频、照片及由其产生的姿态关键点、动作指标、关键帧、分析结果和训练建议；
- 教练指导项目中的源视频、语音录音、画圈、直线、自由绘制等标注，以及语音、视频和标注的同步时间信息；
- 应用语言、提醒时间、界面偏好、免费分析额度、升级提示状态和本地分享奖励状态；
- Apple StoreKit 返回的产品、交易验证结果和会员权益状态。

这些内容只用于提供应用内记录、分析、训练、统计、回顾、编辑、导出和分享功能，不用于广告画像或追踪你在其他应用或网站中的活动。

## 4. AI 与动作分析

投球和挥棒分析使用 Apple 系统框架、随应用提供的姿态模型及 ONNX Runtime 在你的设备上完成。原始视频、照片、姿态关键点、动作指标和分析报告不会发送至开发者服务器，也不会因为使用 ONNX Runtime 而上传给 Microsoft。

动作分析属于训练辅助信息，可能受到拍摄角度、距离、光线、遮挡、帧率、背景人物及设备性能影响，不构成医疗建议、伤病诊断或对专业教练意见的替代。

## 5. 教练指导

你可以从自己的相册选择投球或挥棒视频，直接建立教练指导项目，无需先提交 AI 分析。你也可以从已有的本地分析结果进入教练指导。

教练指导项目可能包含：

- 源视频及其播放方向和显示设置；
- 是否显示 AI 骨架、球棒、球或挥棒轨迹等本地分析图层；
- 语音讲解；
- 画圈、直线、自由绘制等画面标注；
- 视频播放、暂停、拖动进度条、语音及每一笔标注之间的同步时间信息。

项目保存在设备本地，可以继续预览和编辑。只有当你主动导出或通过系统分享面板发送时，完成的指导视频才会进入系统相册、文件位置或你选择的第三方应用。

## 6. 本地额度、奖励和购买状态

为提供免费体验次数、会员权益、训练计划和合理的升级提示，本应用会在设备本地保存必要状态，例如免费 AI 分析使用次数、分享奖励状态、会员权益状态、购买恢复结果以及提示频率。

这些状态不会上传至开发者服务器，本应用没有接入线上广告转化追踪。

月度订阅、年度订阅、永久会员、购买和恢复购买均由 Apple StoreKit 处理。本应用只读取 Apple 返回的产品、已验证交易和当前权益状态，用于解锁对应功能。

我们无法访问你的 Apple ID 密码、银行卡号、支付密码或完整支付凭证。Apple 对相关数据的处理受 Apple 自身条款与隐私政策约束。

## 7. 数据保存与删除

### 7.1 保存期限

应用数据默认保存在你的设备，直至你主动删除相关内容或卸载本应用。数据可能保存在 UserDefaults、应用沙盒文件或本地数据库中。

### 7.2 删除方式

- 你可以在相应记录、分析历史或教练指导项目页面删除单条内容。
- 你可以在“我的—数据管理”中清除本应用保存的本地数据，包括教练指导项目及其视频、语音和标注。
- 卸载本应用通常会删除其应用容器中的本地数据。
- 订阅和永久购买记录由 Apple 管理，不会因为卸载应用或清除本地数据而自动取消；重新安装后可以通过 Apple 恢复购买。
- 为防止免费额度或分享奖励被异常重复领取，少量本地计数可能与普通内容分开管理，但仍只保存在本地设备上。

### 7.3 缓存和导出副本

视频分析、关键帧、导出和分享过程中可能产生缓存或临时文件，系统或应用会按功能需要清理。

已保存到系统相册、文件 App，或已发送到微信等第三方应用的导出副本，不再由本应用控制。如需删除，请在相应位置或第三方应用中自行操作。

## 8. 导出与分享

本应用不会主动把你的本地内容发送给第三方。只有当你主动点击保存、导出或系统分享时，所选报告、图片、表格或视频才会发送到你选择的相册、文件位置、联系人或第三方应用。分享对象和范围由你决定。

内容离开本应用后，由接收方或第三方平台的隐私政策约束。

当你主动分享已完成的训练报告时，本应用可能仅在设备本地记录一次分享奖励。该状态不会上传，也不用于线上转化追踪；取消系统分享不会获得奖励。

## 9. 使用的系统服务和本地组件

本应用主要使用：

- Apple Vision：在设备本地进行人体姿态与关键点识别；
- Apple ARKit：在设备本地实现 AR 测距；
- Apple Photos / PhotosUI 和系统文件选择器：访问你主动选择或保存的媒体和文件；
- Apple UserNotifications：安排设备本地训练提醒；
- Apple StoreKit：处理应用内购买、订阅和恢复购买；
- iOS 系统分享面板：执行由你主动发起的导出和分享；
- ONNX Runtime（Microsoft）：在设备本地运行随应用提供的姿态识别模型。

这些系统服务和本地组件不用于广告追踪。本应用当前不请求或使用 HealthKit、WatchConnectivity、Game Center、App Group 或 iCloud Key-Value Store 权限。

## 10. 数据共享与依法披露

我们不会出售、出租或交易你的个人信息，也不会为广告目的向数据经纪商、广告平台或第三方分析平台提供你的应用内内容。

仅在以下情形可能处理或披露必要信息：

1. 你主动通过系统分享面板、电子邮件或微信发送内容；
2. Apple 为处理购买、订阅、系统权限和平台服务而进行必要处理；
3. 适用法律、法院或监管机构依法要求；
4. 为保护用户、开发者或公众的合法权益和安全所必需。

由于本应用不运营用户内容服务器，通常不存在可向第三方提供的云端视频、录音、标注或分析数据。

## 11. 你主动联系我们时提供的信息

如果你通过电子邮件或微信联系我们，我们会收到你主动提供的联系方式、消息内容及附件，仅用于回复、提供支持和处理相关问题。除法律要求或解决支持事项所必需外，我们不会将这些信息用于广告营销，也不会出售给第三方。

## 12. 未成年人保护

本应用面向棒球和垒球训练、记录与学习场景，不通过开发者服务器主动收集儿童个人信息。

教练、家长或监护人在导入、录制、标注、导出或分享含有未成年人影像、声音或比赛资料的内容前，应取得必要的监护人同意，并仅在训练指导所需范围内使用和分享。未成年人应在监护人指导下使用购买、分享和对外联系功能。

## 13. 信息安全

本应用通过 iOS 应用沙盒、本地文件保护和最小权限原则保护本地数据。请妥善保管设备，并谨慎选择导出或分享对象。任何存储方式都无法保证绝对安全，但我们不会建立用于接收你的视频、录音、标注或动作分析数据的业务服务器。

## 14. 政策更新

我们可能根据功能、法律法规或 Apple 平台要求更新本政策。更新后的生效日期会显示在本页，并可能通过应用内页面、版本更新说明或其他合理方式提示。

## 15. 联系方式

- 开发者：刘肖龙
- 电子邮箱：shawlion@qq.com
- 微信：shawlion

如不同语言版本存在差异，以中文版本为准。

---

# English Version

## 1. Overview

SlyMask Baseball (the “App”) is developed and maintained by Xiaolong Liu, an independent developer. We respect your privacy. This Policy explains how information is handled when you use game recording, on-device AI motion analysis, coach reviews, training plans, AR measurement, and other App features.

- The App does not require account registration.
- Videos, photos, voice recordings, motion-analysis results, game records, and coach annotations that you import or create are processed and stored on your device. We do not operate developer servers that receive this content or keep server copies.
- The App does not integrate with HealthKit and does not read or collect health, heart-rate, or fitness data.
- The App contains no third-party advertising, analytics, or tracking SDKs. It does not use IDFA, perform cross-app or cross-site tracking, or sell personal information.

## 2. Device Permissions

The App requests a permission only when you actively use the related feature. You can disable permissions at any time in iOS Settings; doing so affects only the corresponding feature.

### 2.1 Camera

The App requests camera access only when you use AR distance measurement. Camera content is processed locally in real time and is not saved or uploaded to developer servers.

### 2.2 Photo Library Read Access

The App uses Apple-provided system pickers so that you can choose pitching or batting videos, player images, and other media for on-device motion analysis, coach reviews, or records. The App does not read photo-library content that you have not selected.

### 2.3 Photo Library Add Access

The App writes a report card, image, coach-review video, or partner QR code to the photo library only after you actively choose Save or Export.

### 2.4 Microphone

The App uses the microphone only after you actively start narration recording in a coach review. While recording, the interface displays a clear recording status and elapsed recording time.

The voice recording is stored locally together with the video playback position and annotation timing information so that you can preview, continue editing, and export a synchronized review video. The recording does not leave your device unless you actively export or share it.

### 2.5 Notifications

The App requests notification permission only when you enable training reminders and schedules those notifications locally. Reminder content and times are not sent to developer servers.

The App does not request access to Health, Contacts, or precise location.

## 3. Information Processed Locally on Your Device

To provide features you actively choose, the App may process and store locally:

- Baseball or softball game records and team, player, batting, pitching, baserunning, fielding, and statistics data;
- Pitch charts, hitting training, training plans, training progress, player assessments, equipment lists, and tactics-board content;
- Videos and photos you select, together with generated pose keypoints, motion metrics, key frames, analysis results, and training suggestions;
- Source video, voice narration, circles, lines, freehand drawings, and synchronized voice, video, and annotation timing in coach-review projects;
- App language, reminder time, interface preferences, free-analysis quota, upgrade-prompt state, and local share-reward state; and
- Product, verified-transaction, and entitlement information returned by Apple StoreKit.

This information is used only to provide recording, analysis, training, statistics, review, editing, export, and sharing features. It is not used to build advertising profiles or track your activity in other apps or websites.

## 4. AI and Motion Analysis

Pitching and batting analysis runs on your device using Apple system frameworks, a pose model bundled with the App, and ONNX Runtime. Raw videos, photos, pose keypoints, motion metrics, and analysis reports are not sent to developer servers and are not uploaded to Microsoft merely because ONNX Runtime is used.

Motion analysis is training-support information. Results may be affected by camera angle, distance, lighting, occlusion, frame rate, people in the background, and device performance. The results are not medical advice, an injury diagnosis, or a substitute for professional coaching.

## 5. Coach Reviews

You can select your own pitching or batting video from the photo library and create a coach-review project without first submitting the video for AI analysis. You can also enter coach review from an existing on-device analysis result.

A coach-review project may contain:

- The source video and its playback-orientation and display settings;
- Local analysis layers such as the AI skeleton, bat, ball, or swing path;
- Voice narration;
- Circles, lines, and freehand annotations; and
- Timing information that synchronizes video playback, pauses, timeline seeking, narration, and each annotation stroke.

Projects are stored locally and can be previewed and edited again. A completed review video is sent to the photo library, a file location, or a third-party app only when you actively export or share it through the system share sheet.

## 6. Local Quota, Reward, and Purchase State

To provide free trials, membership entitlements, training plans, and controlled upgrade prompts, the App stores necessary state locally, such as free AI-analysis usage, share-reward state, membership entitlement, purchase-restore result, and prompt frequency.

This state is not uploaded to developer servers. The App does not use online advertising-conversion tracking.

Monthly and yearly subscriptions, lifetime access, purchases, and restore are handled by Apple StoreKit. The App reads only product information, verified transactions, and current entitlement state returned by Apple to unlock the corresponding features.

We cannot access your Apple ID password, card number, payment password, or complete payment credentials. Apple's processing is governed by Apple's terms and privacy policy.

## 7. Storage and Deletion

### 7.1 Retention

App data remains on your device by default until you delete the relevant content or uninstall the App. Data may be stored in UserDefaults, App sandbox files, or a local database.

### 7.2 Deletion

- You can delete individual records, analysis history, or coach-review projects from the relevant screen.
- You can use Profile — Data Management to clear locally stored App data, including coach-review projects and their videos, narration, and annotations.
- Uninstalling the App normally removes data in its local container.
- Subscriptions and lifetime-purchase records are managed by Apple and are not automatically cancelled when you uninstall the App or clear local data. You can restore purchases through Apple after reinstalling.
- To prevent abnormal repeated redemption of free quotas or share rewards, a small number of local counters may be managed separately from ordinary content, but they still remain only on the device.

### 7.3 Cache and Exported Copies

Video analysis, key-frame extraction, export, and sharing may create cache or temporary files. The system or App removes those files as needed.

Copies saved to the photo library or Files app, or sent to WeChat or another third-party app, are no longer controlled by the App. Delete those copies from the corresponding location or third-party app when necessary.

## 8. Export and Sharing

The App does not send your local content to third parties automatically. Only after you actively choose Save, Export, or Share is the selected report, image, spreadsheet, or video sent to the photo library, file location, contact, or third-party app you choose. You control the recipient and scope of sharing.

After content leaves the App, it is governed by the recipient's or third-party platform's privacy policy.

When you actively share a completed training report, the App may record one share reward locally. That state is not uploaded or used for online conversion tracking, and cancelling the system share sheet does not grant a reward.

## 9. System Services and Local Components

The App primarily uses:

- Apple Vision for on-device body-pose and keypoint recognition;
- Apple ARKit for on-device AR distance measurement;
- Apple Photos / PhotosUI and system file pickers for media and files you choose to read or save;
- Apple UserNotifications for local training reminders;
- Apple StoreKit for in-app purchases, subscriptions, and restore;
- The iOS share sheet for exports and sharing initiated by you; and
- ONNX Runtime (Microsoft) to run the bundled pose model locally on your device.

These services and local components are not used for advertising tracking. The current App does not request or use HealthKit, WatchConnectivity, Game Center, App Group, or iCloud Key-Value Store entitlements.

## 10. Disclosure and Sharing of Information

We do not sell, rent, or trade personal information and do not disclose in-App content to data brokers, advertising platforms, or third-party analytics platforms for advertising purposes.

Necessary information may be handled or disclosed only when:

1. You actively send content through the system share sheet, email, or WeChat;
2. Apple performs necessary processing for purchases, subscriptions, system permissions, or platform services;
3. Applicable law, a court, or a regulator lawfully requires it; or
4. It is necessary to protect the rights and safety of users, the developer, or the public.

Because the App does not operate user-content servers, there normally are no cloud copies of your videos, narration, annotations, or analysis data for us to disclose.

## 11. Information You Provide When Contacting Us

If you contact us by email or WeChat, we receive the contact details, messages, and attachments that you voluntarily provide. We use them only to reply, provide support, and resolve the relevant issue. Except where required by law or necessary to provide support, we do not use this information for advertising or sell it to third parties.

## 12. Children's Privacy

The App is intended for baseball and softball training, recording, and learning. We do not actively collect children's personal information through developer servers.

Before a coach, parent, or guardian imports, records, annotates, exports, or shares content containing a minor's image, voice, or game information, they should obtain any required guardian consent and use or share the content only as necessary for training. Minors should use purchase, sharing, and external-contact features with guardian guidance.

## 13. Information Security

The App uses the iOS sandbox, local file protection, and data-minimization principles to protect local data. Keep your device secure and choose export or sharing recipients carefully. No storage method can guarantee absolute security, but we do not operate business servers that receive your videos, narration, annotations, or motion-analysis data.

## 14. Policy Updates

We may update this Policy due to feature, legal, regulatory, or Apple platform changes. The effective date will be shown on this page, and changes may also be communicated in the App, release notes, or another reasonable method.

## 15. Contact

- Developer: Xiaolong Liu
- Email: shawlion@qq.com
- WeChat: shawlion

If language versions differ, the Chinese version controls.
