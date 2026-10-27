# PockiPic

![PockiPic: photos, ready to print](feature-graphic.png)

[English](#english) | [简体中文](#简体中文)

## English

PockiPic is an independent Android photo browser and print-queue app for a compatible Xiaomi photo printer. It runs locally without Mi Home, a Xiaomi account, or an app-operated cloud service. PockiPic is not affiliated with or endorsed by Xiaomi.

### Download and compatibility

- **[Download PockiPic 0.5.5 APK](PockiPic-0.5.5-release.apk)** (signed release; Android 11 or later).
- Printing is enabled only for printer model `xiaomi.printer.ricott` with firmware `2.1.2_0039`. Other models and firmware are not supported by this release.
- The app interface is currently in English.
- The release has passed automated checks, but physical printing and FTP with this Android release have not yet been verified. Test the workflow with your own devices before relying on it.

To install, download the APK to your Android device, open it, and allow installation from that source if Android asks. An existing debug build signed with a different key cannot be updated in place. Removing that installation erases its app-private data, so preserve anything important first.

### Features

- **Browse and organize:** Browse an app inbox or a selected writable photo folder, including subfolders. Select photos, filter by rating or print status, and sort the gallery.
- **Frame photos:** View photos full screen, zoom, and adjust the crop before printing. Rate photos from one to five stars.
- **Manage printing:** Add photos to a persistent queue, choose 1–999 copies, pause or start the queue, view progress and history, and reprint previous jobs. Supply counts are estimates that you can correct.
- **Receive photos:** Start the optional local FTP server and send files from a compatible FTP client or camera. Choose a watched folder and enable automatic printing if desired. The built-in local-only hotspot does not provide internet access.
- **Keep originals:** Queued prints use prepared private copies; original photos are preserved.

### Quick start

1. Pair the printer in Android Bluetooth settings. In PockiPic, open **Connections**, choose the printer, and check its status.
2. Select or import photos in **Photos**, adjust the framing, and add them to the queue.
3. Review the queue and select **Start queue** when ready to print.
4. To receive files over FTP, connect the sender to the same trusted network, start FTP in **Connections**, and use the displayed address, port, username, and password with passive FTP. Automatic printing is optional and must be enabled separately.

**FTP security:** FTP does not encrypt credentials or files. Use it only on a trusted private network and stop it when finished. Authenticated FTP clients can browse, upload, download, rename, and delete files within the selected folder, subject to storage-provider permissions. Anyone who obtains the credentials may gain that access.

APK SHA-256: `C670EF80DC03E6081288D846E752C9B03DD19976FD0A9DAE44EC43E48ECD0718`.

## 简体中文

PockiPic 是一款独立开发的 Android 照片浏览与打印队列应用，适用于兼容的小米照片打印机。应用在本地运行，无需米家、小米账号或应用运营方的云服务。PockiPic 与小米没有关联，也未获得小米官方背书。

### 下载与兼容性

- **[下载 PockiPic 0.5.5 APK](PockiPic-0.5.5-release.apk)**（已签名的正式版本；需要 Android 11 或更高版本）。
- 本版本仅允许连接型号为 `xiaomi.printer.ricott`、固件为 `2.1.2_0039` 的打印机进行打印，不支持其他型号或固件。
- 应用界面目前为英文。
- 此版本已通过自动化检查，但尚未完成 Android 版本的实际打印和 FTP 测试。正式依赖之前，请先使用自己的设备验证流程。

将 APK 下载到 Android 设备并打开；如果系统提示，请允许从该来源安装。使用不同签名密钥的旧调试版无法直接升级为此版本。卸载旧版会删除其应用私有数据，请先保存重要内容。

### 功能介绍

- **浏览与整理：** 浏览应用收件箱或自行选择的可写照片文件夹（包括子文件夹）；选择照片，并按评分或打印状态筛选、排序。
- **调整画面：** 全屏查看、缩放照片，打印前调整裁剪范围，并为照片设置 1 至 5 星评分。
- **管理打印：** 将照片加入持久保存的队列，选择 1–999 份，启动或暂停队列，查看进度与历史记录，并重新打印。耗材数量为估算值，可手动修正。
- **接收照片：** 可选开启本地 FTP 服务器，通过兼容的 FTP 客户端或相机传输文件；也可选择监视的文件夹并启用自动打印。应用内的本地热点不提供互联网连接。
- **保留原图：** 打印队列使用准备好的应用私有副本，不会修改原始照片。

### 快速开始

1. 在 Android 蓝牙设置中配对打印机。在 PockiPic 中打开 **Connections**，选择打印机并检查状态。
2. 在 **Photos** 中选择或导入照片，调整画面，然后加入队列。
3. 检查打印队列，准备好后选择 **Start queue** 开始打印。
4. 如需通过 FTP 接收文件，请将发送设备连接到同一可信网络，在 **Connections** 中开启 FTP，并在客户端使用显示的地址、端口、用户名和密码，以被动 FTP 模式连接。自动打印需要另行启用。

**FTP 安全提示：** FTP 不会加密用户名、密码或文件。请仅在可信的私人网络中使用，并在完成后关闭。通过认证的 FTP 客户端可在所选文件夹内浏览、上传、下载、重命名和删除文件，具体取决于存储提供方的权限。获得凭据的人可能取得相同访问权限。

