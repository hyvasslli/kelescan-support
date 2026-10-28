# KeLeScan 隐私政策 / Privacy Policy

生效日期 / Effective date: 2026-10-28

应用 / App: KeLeScan（可乐扫描）  
Bundle ID: `com.hany.kelescan`  
开发者 / Developer: Hany (Yang Han)

## 简体中文

### 1. 适用范围

本政策说明 KeLeScan 当前版本如何处理扫描文件、图片、识别结果及相关设置。它不替代 Apple、GitHub 或用户选择的分享服务各自的隐私政策。

### 2. 设备内处理与存储

KeLeScan 在设备上进行核心图像增强、页面裁剪、透视校正、展平、文字识别、表格识别及页面编辑。正常扫描和识别流程不需要将文档发送到开发者运营的服务器。图片转表格使用系统能力，要求 iOS 26 或更新版本，结果可导出为 Excel 或 CSV。

为实现编辑和重开，App 会在本机保存用户导入或拍摄的原图、处理结果、缩略图、PDF、文字和表格识别结果、页面标记、插入的签名及文档编辑信息。滤镜、外观等偏好也保存在设备上。参考扫描及部分处理过程可能产生本地临时文件或缓存。

当前版本不要求创建开发者账号，未集成用于广告投放、跨 App 跟踪或第三方使用统计的 SDK。这些事实不表示系统服务、用户启用的备份或主动分享不会使用网络。

部分设备内模型经 Apple 加密。首次使用页面展平等功能时，设备需要联网，从 Apple 获取解密模型所需的密钥；此后可离线使用。此过程只在设备与 Apple 之间进行，不发送用户的扫描图像或文档，开发者也不会收到相关数据。

### 3. 权限

- **相机**：仅用于用户发起的文档拍摄或系统参考扫描。
- **照片图库**：App 在自己的导入页面中按时间顺序显示照片，以便用户选择要导入的页面。照片只在设备上读取和显示，只有用户选中的照片才会导入 App；未选中的照片不会被复制或上传。用户可以在系统设置中选择仅允许访问部分照片，或使用系统照片选择器。
- **添加照片**：用户选择保存图片到相册时，申请相应权限并写入所选结果。
- **文件访问**：使用系统文件选择、导入、导出和分享功能处理用户指定的文件或位置。

用户可以在系统设置中管理相关权限；关闭权限可能使对应功能不可用。

### 4. iCloud、导出与分享

如果用户启用 App 的 iCloud 存储，相关 PDF 会写入用户的 iCloud 容器，由 Apple 根据账号、设备和网络设置处理上传及同步。系统设备备份也可能按用户设置包含 App 数据。开发者不因此取得用户的 Apple ID 密码或访问其 iCloud 账号的权限。

用户主动保存到相册、文件、打印或分享给其他 App 时，所选资料会交给相应系统服务、存储位置或接收方，后续处理适用这些服务的规则。核心处理在本地运行不等于整个 App 完全离线。

### 5. App 内购买

KeLeScan 高级版为一次性 App 内购买（非订阅）。购买、付款、恢复购买、退款及家人共享均由 Apple 处理，开发者不会收到用户的付款卡信息、Apple ID 或密码。App 在设备上通过 Apple 的 StoreKit 核验交易，以决定是否开放高级功能，并在本机保存核验结果。开发者不运营购买服务器，也不收集购买记录。

### 6. 支持与诊断

用户选择通过本仓库 GitHub Issues 联系支持时，提交的文字、账号名称及附件由 GitHub 托管，且公开 Issue 内容可被他人访问。请不要提交个人文档、签名原图、账号密码或其他敏感资料；示例应先脱敏。我们会使用用户主动提供的信息排查和回复问题，不要求提供 Apple ID 密码。

Apple 可能依据用户的系统设置处理崩溃、诊断或使用信息；具体范围和共享方式由 Apple 的服务与用户设置决定。App 的处理流程也可能生成用于排错的设备日志；请在主动分享日志前检查其中的文件名和其他信息。

### 7. 保留、删除与数据副本

App 中的文档及编辑信息保留以便继续使用，用户可通过 App 提供的操作管理和删除文档。缓存或临时文件可能由 App 或系统清理，不应作为唯一备份。

删除 App 内记录不保证同时删除此前导出、分享、打印、相册、iCloud 或系统备份中的所有副本。请在对应服务中单独检查、管理或删除这些副本。删除或卸载前，请先导出需要保留的资料。

### 8. 安全、变更与联系

请妥善管理设备解锁、Apple 账号、备份和文件分享权限。没有任何存储或传输方式可以承诺绝对安全。

如果数据处理方式改变，我们会更新本页面及生效日期。隐私问题可通过 [GitHub Issues](https://github.com/hyvasslli/kelescan-support/issues) 提出；该渠道公开可见，请仅提交不含敏感信息的一般问题。

## English

### 1. Scope

This policy describes how the current version of KeLeScan handles scans, images, recognition results and settings. Apple, GitHub and services you choose for sharing have their own privacy policies.

### 2. Processing and storage on your device

Core image enhancement, cropping, perspective correction, page flattening, text/table recognition and page editing run on your device. Normal scanning and recognition do not require sending documents to a developer-operated server. Table extraction uses system capabilities, requires iOS 26 or later, and exports to Excel or CSV.

To support editing and reopening, the app stores imported/captured originals, processed images, thumbnails, PDFs, text/table recognition results, markup, inserted signatures and document-editing information locally. Preferences such as filters and appearance are also stored locally. Reference scans and processing can create local temporary files or caches.

The current version does not require a developer account and does not integrate advertising, cross-app tracking or third-party usage analytics SDKs. This does not mean that system services, enabled backups or sharing you initiate never use a network.

Some on-device models are encrypted by Apple. The first time you use features such as page flattening, the device needs an internet connection to obtain the model decryption key from Apple; afterwards the feature works offline. This exchange is between your device and Apple only. It does not send your scans or documents, and the developer receives no data from it.

### 3. Permissions

- **Camera:** for document capture or system reference scanning you initiate.
- **Photo library:** the app shows your photos in date order on its own import screen so you can choose pages to import. Photos are read and displayed on your device only. Only the photos you select are imported into the app; others are not copied or uploaded. You can allow access to selected photos only in system Settings, or use the system photo picker.
- **Add to Photos:** requested when you choose to save image results to your library.
- **Files:** system import, export and sharing tools handle files and locations you choose.

Manage permissions in system Settings. Denying a permission may disable its associated feature.

### 4. iCloud, export and sharing

If you enable iCloud storage in the app, relevant PDFs are written to your iCloud container. Apple manages uploading and synchronization according to your account, device and network settings. System device backups may also include app data according to your settings. This does not give the developer your Apple ID password or access to your iCloud account.

When you save to Photos or Files, print, or share with another app, the selected content is passed to that service, location or recipient and its rules apply. Local core processing is not a promise that the entire app works without any network use.

### 5. In-App Purchase

KeLeScan Pro is a one-time In-App Purchase (not a subscription). Apple handles purchases, payment, restoring purchases, refunds and Family Sharing. The developer does not receive your payment-card details, Apple ID or password. The app verifies transactions on your device with Apple's StoreKit to decide whether Pro features are available, and stores that result locally. The developer runs no purchase server and does not collect purchase records.

### 6. Support and diagnostics

If you contact support through this repository's GitHub Issues, GitHub hosts your text, account name and attachments. Public issues can be viewed by others. Do not post private documents, signature images, credentials or sensitive information. Redact examples first. We use information you voluntarily provide to investigate and respond; we do not request your Apple ID password.

Apple may process crash, diagnostic or usage information according to your system settings and its services. Processing can also produce device logs for troubleshooting. Check filenames and other information before voluntarily sharing logs.

### 7. Retention, deletion and copies

Documents and editing information remain available for continued use until managed or deleted through app controls. The app or system may clear temporary files and caches; do not rely on them as your only backup.

Deleting an in-app record does not guarantee deletion of every copy previously exported, shared, printed, saved to Photos or iCloud, or included in system backups. Review and manage copies in those services separately. Export anything you need to keep before deleting data or uninstalling the app.

### 8. Security, updates and contact

Protect device access, your Apple account, backups and sharing permissions. No storage or transmission method can guarantee absolute security.

We will update this page and its effective date if processing practices change. For general privacy questions, use [GitHub Issues](https://github.com/hyvasslli/kelescan-support/issues). This is a public channel; do not include sensitive information.
