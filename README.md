## 背景

苹果在 2020.11 月正式发布了 Apple Silicon 的 MacBook Pro、MacBook Air、Mac mini。也是因为这颗芯片，原本运行在 Intel 芯片 Mac 上的应用大部分可以运行，但也有些不可以。

我结合自己在使用的软件，同时搜集其他常用软件当前的适配状态，形成下面的清单，给即将购入或者关注这款 Mac 的用户提供一个可看参考的清单。

此列表不断完善，如果您也想贡献一份力量，可以提 issues 或者私信给我。

如果你也是 Apple 芯片的 Mac 用户或者关注 Apple Silicon Mac 相关信息，可以加 QQ 群交流：1094601027 （AppleSilicon交流分享）



#### 清单中「状态」说明：

- 👍：完美适配 Apple 芯片的 Mac

- ✅：可以通过 Rosetta 2 方式在 Apple 芯片的 Mac 运行使用

- ❌：不能在 Apple 芯片的 Mac 上正常使用



#### 清单中「架构」说明：

- **通用（Universal ）**：这个应用在编译时选择的是 Apple Silicon 和 Intel 两个架构，那么这个应用既可以在 Apple 芯片的 Mac 上安装运行，也可以在 Intel Mac 上安装运行

- **Apple（Apple SIlicon Only）**：这个应用在编译时只选择了 arm64，仅能在 Apple 芯片的 Mac 安装运行，在 Intel Mac 是不能安装的

- **Intel**：这个应用是在 Intel Mac 编译，可以在 Apple 芯片的 Mac 通过 Rosetta 2 运行

------

#### 生产力工具（视频剪辑、设计、开发）

| 状态 | 架构  | 名称                     | 版本号                           | 官网/下载页                                                  | 备注                                                         |
| :----: | :-----: | :----------------------- | :------------------------------- | :----------------------------------------------------------- | :----------------------------------------------------------- |
|  👍   | 通用  | Final Cut Pro            | 10.5                             | https://apps.apple.com/cn/app/final-cut-pro/id424389933?mt=12 | &nbsp;                                                       |
|  👍   | 通用  | iMovie                   | 10.2.1                           | [https://apps.apple.com/cn/app/imovie-%E5%89%AA%E8%BE%91/id408981434?mt=12](https://apps.apple.com/cn/app/imovie-剪辑/id408981434?mt=12) | &nbsp;                                                       |
|  👍   | 通用  | Cinema 4D                | S22.016                          | https://www.maxon.net/en/article/cinema-4d-r23-sp1-now-available | &nbsp;                                                       |
|  ✅   | Intel | Premiere Pro             | 14.6                             | https://www.adobe.com/hk_zh/creativecloud/catalog/desktop.html?promoid=RL89NGY7&mv=other | &nbsp;                                                       |
|  ✅   | Intel | YouTube-dl               | 2020.11.19                       | http://www.youtube-dl.org                                    | &nbsp;                                                       |
|  ✅   | Intel | FFmpeg                   | 4.3.1                            | http://ffmpeg.org                                            | &nbsp;                                                       |
|  ✅   | Intel | MacX Video Converter Pro | 6.5.1 (20201015)                 | https://www.macxdvd.com/mac-video-converter-pro/             | &nbsp;                                                       |
|  ✅   | Intel | Imaging Edge Desktop     | 1.0.02.03270                     | https://imagingedge.sony.net/zh-hans-cn/ie-desktop.html#remote |                                                              |
|  ✅   | Intel | Photoshop                | 22.0.1                           | https://www.adobe.com/hk_zh/creativecloud/catalog/desktop.html?promoid=RL89NGY7&mv=other |                                                              |
|  👍   | Apple | Photoshop beta           | 22.0.0                           |                                                              |                                                              |
|  ✅   | 通用  | Adobe Lightroom Classic  | 10.0                             | https://www.adobe.com/hk_zh/creativecloud/catalog/desktop.html?promoid=RL89NGY7&mv=other |                                                              |
|  ✅   | Intel | Adobe Lightroom          | 4.0                              | https://www.adobe.com/hk_zh/creativecloud/catalog/desktop.html?promoid=RL89NGY7&mv=other |                                                              |
|  ✅   | Intel | After Effects            | 17.5.1                           | https://www.adobe.com/hk_zh/creativecloud/catalog/desktop.html?promoid=RL89NGY7&mv=other |                                                              |
|  ✅   | Intel | Adobe XD                 | 35.1.12                          | https://www.adobe.com/hk_zh/creativecloud/catalog/desktop.html?promoid=RL89NGY7&mv=other |                                                              |
|  👍   | 通用  | Sketch                   | 70.2 (109071)             | https://www.sketch.com/downloads/mac/                        | Flavor-.sketchplugin 不支持这个版本 |
|  ❌   | Intel | AutoCAD                  |                                  | https://www.autodesk.com/products/autocad/overview?plc=ACDIST&term=1-YEAR&support=ADVANCED&quantity=1 | https://forums.autodesk.com/t5/autocad-for-mac-forum/apple-silicon/m-p/9652836 |
|  ❌   | Intel | Docker                   |                                  | https://www.docker.com                                       |                                                              |
|  ❌   | Intel | TensorFlow               |                                  | https://blog.tensorflow.org/2020/11/accelerating-tensorflow-performance-on-mac.html | Not yet, but a supported pre-release is available https://github.com/tensorflow/tensorflow/issues/44751   https://blog.tensorflow.org/2020/11/accelerating-tensorflow-performance-on-mac.html |
|  👍   | 通用  | Xcode                    | 12.2                             | https://apps.apple.com/cn/app/xcode/id497799835?mt=12        |                                                              |
|  ✅   | Intel | Sourcetree               | 4.0.2                            | https://www.sourcetreeapp.com                                |                                                              |
|  👍   | 通用  | Tower                    | 6.1 build258                     | https://www.git-tower.com/mac                                |                                                              |
|  👍   | 通用  | Iterm2                   | 03.4.1                           | https://iterm2.com/downloads.html                            |                                                              |
|  ✅   | Intel | Sublime                  | 03.2.2                           | http://www.sublimetext.cn                                    |                                                              |
|  ✅   | Intel | Postman                  | 07.3.6                           | https://www.postman.com/downloads/                           |                                                              |
|  ✅   | Intel | Charles                  | 04.6.1                           | https://www.charlesproxy.com                                 |                                                              |
|  👍   | 通用  | Transmit                 | 04.4.11                          | https://library.panic.com/releasenotes/transmit5/            |                                                              |
|  ✅   | Intel | Navicat Premium          | 15.0.22                          | https://www.navicat.com/en/download/navicat-premium#mac      |                                                              |
|  👍 | Apple | Visual Studio Code       | 1.54                          | https://code.visualstudio.com/updates/v1_54 |                                                              |
|  ✅   | Intel | Android Studio           | 4.1.1                            | https://developer.android.google.cn/studio/                  |                                                              |
|  ✅   | Intel | Node                     | 15.3.0                           | https://github.com/nodejs/node                               | https://github.com/nodejs/build/issues/2474 https://github.com/nodejs/node/issues/36160 |
|  ✅   | Intel | Flutter                  | 1.24.0-10.2.pre                  | https://flutter.dev/docs/get-started/install/macos           | https://github.com/flutter/flutter/issues/60118              |
|  ✅   | Intel | home-brew                | 2.5.11                           | https://brew.sh https://github.com/Homebrew/brew             | https://soffes.blog/homebrew-on-apple-silicon                |
|  👍   | 通用  | Redis                    | 6.0.9                            | https://redis.io/download                                    | https://github.com/ThatGuySam/doesitarm/issues/298           |
|  ✅   | Intel | HandShaker               | 2.1.1 (255)                      | https://www.smartisan.com/apps/#/handshaker                  |                                                              |
|  👍   | 通用  | iExportHelper            | 1.1.0                            | https://apps.apple.com/cn/app/iexporthelper/id1486337874?mt=12 |                                                              |
|  ✅   | Intel | CocoaPods                | 1.10.0                           | https://cocoapods.org https://github.com/CocoaPods/CocoaPods | https://github.com/CocoaPods/CocoaPods/issues/9907           |
|  ✅   | Intel | Carthage                 | 0.36.0                           | https://github.com/Carthage/Carthage                         | https://github.com/Carthage/Carthage/issues/3019             |
|  ✅   | Intel | PPDuck                   | 03.10.1                          | http://ppduck.com                                            |                                                              |
|  ✅   | Intel | Matlab                   | v9.9.0.1495850                   | https://ww2.mathworks.cn/products/matlab.html                | https://www.mathworks.com/matlabcentral/answers/641925-is-matlab-supported-on-apple-silicon-macs |
|  ✅   | Intel | Python                   | 2.7                              |                                                              | working for v2.7.16, v3.8.2, and v3.9 https://github.com/python/cpython/pull/22855 |
|  👍   | 通用  | Surge                    | 4.0.0                            | https://nssurge.com          |                                                              |
|  ✅   | Intel | SwitchHosts!             | v3.3.12 (5349)                   | https://oldj.github.io/SwitchHosts/                          |                                                              |
|  ✅   | Intel | Renamer 6                | 6.0.6                            | https://renamer.com                                          |                                                              |
|  ✅   | Intel | PxCook                   | 3.9.940 beta                     | https://www.fancynode.com.cn/pxcook                          |                                                              |
|  ✅   | Intel | Reveal                   | 27                               | https://revealapp.com/download-thanks/                       |                                                              |
|  ❌   | Intel | VMware Fusion            | 专业版 12.0.0 (16880131)         | https://www.vmware.com/products/fusion/fusion-evaluation.html |                                                              |
|  👍 | 通用 | Parallels Desktop        | 16.3.0 （50385） | https://my.parallels.com/desktop/beta | https://my.parallels.com/desktop/beta |
|  👍   | 通用 | Excel                    | 16.44                         | https://apps.apple.com/cn/app/microsoft-excel/id462058435?mt=12 |                                                              |
|  👍   | 通用 | PowerPoint               | 16.44                           | https://apps.apple.com/cn/app/microsoft-powerpoint/id462062816?mt=12 |                                                              |
|  👍   | 通用  | Word                     | 16.44                    | https://apps.apple.com/cn/app/microsoft-word/id462054704?mt=12 |                                                              |
|  👍   | 通用  | Outlook                  | 16.43                   | https://apps.apple.com/cn/app/microsoft-outlook/id985367838?mt=12 |                                                              |
|  👍   | 通用  | OneNote                  | 16.44                    | https://apps.apple.com/cn/app/microsoft-onenote/id784801555?mt=12 |                                                              |
|  👍   | 通用  | Keynote                  | 10.3.5                           | [https://apps.apple.com/cn/app/keynote-%E8%AE%B2%E6%BC%94/id409183694?mt=12](https://apps.apple.com/cn/app/keynote-讲演/id409183694?mt=12) |                                                              |
|  👍   | 通用  | Numbers                  | 10.3.5                           | [https://apps.apple.com/cn/app/numbers-%E8%A1%A8%E6%A0%BC/id409203825?mt=12](https://apps.apple.com/cn/app/numbers-表格/id409203825?mt=12) |                                                              |
|  👍   | 通用  | Pages                    | 10.3.5                           | [https://apps.apple.com/cn/app/pages-%E6%96%87%E7%A8%BF/id409201541?mt=12](https://apps.apple.com/cn/app/pages-文稿/id409201541?mt=12) |                                                              |
|  👍   | 通用  | MindNode                 | 2020.6 (265)                     | https://apps.apple.com/cn/app/mindnode-mind-map/id1289197285?mt=12   https://mindnode.com/download |                                                              |
|  👍   | 通用  | OminGrafle               | 7.18                             | https://www.omnigroup.com/omnigraffle/                       |                                                              |
|  ✅   | Intel | 迅雷                     | 03.4.1                           | https://dl.xunlei.com/#mod02                                 |                                                              |
|  👍   | 通用  | Keka                     | 1.2.3 (4223)                     | https://www.keka.io/zh-cn/                                   |                                                              |
|  👍   | 通用  | Safari                   | 14.0.1 (16610.3.6.3)             |                                                              |                                                              |
|  👍 | 通用 | Firefox                  | 84.0.1                        | http://www.firefox.com.cn                                    |                                                              |
|  👍   | 通用  | Chrome                   | 87.0.4280.67（正式版本） (arm64) | https://www.google.cn/chrome/                                |                                                              |
|  ✅   | Intel | trojan-qt5               | 1.4.0                            |                                                              |                                                              |
|  ✅   | Intel | 印象笔记                 | 9.4.7 (461685 App Store)         | https://yinxiang.com/download/                               |                                                              |
|  ✅   | Intel | 百度网盘                 | 3.5.0 (12)                       | https://pan.baidu.com/download#pan |                                                              |
|  👍   | 通用  | BetterTouchTool          | 3.506                            | https://folivora.ai/downloads                                |                                                              |
|  👍   | 通用  | Ulysses                  | 21.1                             | https://apps.apple.com/cn/app/ulysses/id1225570693?mt=12     |                                                              |
| 👍 | 通用 | Typora | 0.9.9.36.2 | https://typora.io | |
| 👍 | 通用 | TeamViewer | 15.12.4 | https://www.teamviewer.cn/cn/teamviewer-automatic-download/?utm_source=baidu&utm_medium=cpc&utm_campaign=CN%7CB%7CPR%7C20%7Cnov%7Cbrand-words%7Cnew%7Ct0%7C0 | |
| 👍 | 通用 | PDF Viewer | 5.1.0 | https://apps.apple.com/cn/app/pdf-viewer-pro-by-pspdfkit/id1120099014 | |
| 👍 | 通用 | iStat Menus | 6.51 | https://bjango.com/mac/istatmenus/ | |
| 👍 | 通用 | Blackmagic Disk Speed Test | 3.3 | https://apps.apple.com/cn/app/blackmagic-disk-speed-test/id425264550?mt=12 | |
| ✅ | Intel | Capture One | 13.1.3.9 | https://www.captureone.com/en/products-plans/single-user | https://support.captureone.com/hc/en-us/community/posts/360013922417-Support-for-New-Apple-M1-Chip- |
| 👍 | 通用 | WPS Office | 3.0.1 | https://apps.apple.com/cn/app/wps-office/id1443749478?mt=12 |  |
| 👍 | 通用 | Geekbench | 5.3 | https://www.geekbench.com/download/mac |  |
| ✅ | Intel | Wireshark | 3.4.0 | https://www.wireshark.org/ |  |
| ✅ | Intel | Filezilla | 3.51.0 | https://filezilla-project.org/ |  |
| 👍 | 通用 | Nova | 3.1 | https://nova.app/ |  |
| 👍 | Apple | Premiere Pro beta | 14.9 |  | |
| 👍 | Apple | Premiere Rush beta | 15.5.0 |  | |
| 👍 | Apple | Audition beta | 13.0.14 |  | |
| 👍 | 通用 | 剪映专业版 | 1.2.0 | https://apps.apple.com/cn/app/%E5%89%AA%E6%98%A0%E4%B8%93%E4%B8%9A%E7%89%88/id1529999940?mt=12 | |
| 👍 | 通用 | iMazing | 2.13.4 (14707) | https://imazing.com/download | |
| 👍 | 通用 | Microsoft Edge | 88.0.705.63 | https://microsoft-edge.en.softonic.com/mac | |
| ✅ | Intel | Skype | 8.66.0.74 | https://skype.gmw.cn/down/skype-for-computers.html | |
| 👍 | 通用 | Things | 3.13.8 | https://apps.apple.com/cn/app/things-3/id904280696?mt=12 | |
| 👍 | 通用 | Paragon NTFS | 15.8.105 | https://www.paragon-software.com/home/ntfs-mac/ | |
| 👍 | 通用 | DisplayLink Manager | 1.3 | https://www.displaylink.com/downloads/macos | |
|  |  |  |  | https://code.visualstudio.com/insiders/ | |



------

#### 音乐/视频

| **适配** | **架构** | **名称**         | **版本号** | 官网/下载页面                                                | **备注** |
| :------: | :--------: | :--------------- | :--------- | :----------------------------------------------------------- | :------- |
|    👍     |   通用   | QuickTime Player | 10.5       |                                                              |          |
|    👍     |   通用   | GrandBand        | 10.4.1     | https://apps.apple.com/cn/app/garageband/id682658836?mt=12   |          |
|    👍     |   通用   | Logic Pro        | 10.6       | https://apps.apple.com/cn/app/logic-pro/id634148309?mt=12    |          |
|    👍     |   通用   | MainStage        | 3.5        | https://apps.apple.com/cn/app/mainstage/id634159523?mt=12    |          |
|    ✅     |  Intel   | 腾讯视频         | 2.18.2     | [https://apps.apple.com/cn/app/%E8%85%BE%E8%AE%AF%E8%A7%86%E9%A2%91-%E6%88%91%E5%96%9C%E6%AC%A2%E4%BD%A0-%E7%8B%AC%E6%92%AD/id1231336508?mt=12](https://apps.apple.com/cn/app/腾讯视频-我喜欢你-独播/id1231336508?mt=12) |          |
|    👍   |  通用 | 爱奇艺           | 11.12.0 (20201214162000) | [https://apps.apple.com/cn/app/%E7%88%B1%E5%A5%87%E8%89%BA-%E5%A6%82%E6%84%8F%E8%8A%B3%E9%9C%8F%E7%83%AD%E6%92%AD/id1012296988?mt=12](https://apps.apple.com/cn/app/爱奇艺-如意芳霏热播/id1012296988?mt=12) |          |
|    👍   |  通用 | 网易云音乐       | 2.3.4 | https://music.163.com/st/download?market=baidupz201901 |          |
|    ✅     |  Intel   | QQ音乐           | 7.4.0     | [https://apps.apple.com/cn/app/qq%E9%9F%B3%E4%B9%90-%E8%AE%A9%E7%94%9F%E6%B4%BB%E5%85%85%E6%BB%A1%E9%9F%B3%E4%B9%90/id595615424?mt=12](https://apps.apple.com/cn/app/qq音乐-让生活充满音乐/id595615424?mt=12) |          |
|    ✅     |  Intel   | 喜马拉雅         | 01.2.22    | [https://apps.apple.com/cn/app/%E5%96%9C%E9%A9%AC%E6%8B%89%E9%9B%85-%E5%90%AC%E4%B9%A6%E7%A4%BE%E5%8C%BA-%E7%94%B5%E5%8F%B0%E6%9C%89%E5%A3%B0%E5%B0%8F%E8%AF%B4%E7%9B%B8%E5%A3%B0%E8%AF%84%E4%B9%A6/id876336838](https://apps.apple.com/cn/app/喜马拉雅-听书社区-电台有声小说相声评书/id876336838) |          |
|    👍   |  Apple  | VLC              | 3.0.12.1  | https://www.videolan.org/vlc/                                |          |
|    ✅     |  Intel   | IINA             | 01.1.2     | https://www.iina.io                                          |          |
|    👍   |  通用 | Movist Pro       | 2.6.3 | https://movistprime.com                                      |          |

------

#### 社交

| **适配** | **架构**  | **名称**         | **版本号** | 官网/下载页面                                                | **备注** |
| :----: | :-------: | :----------------------------------------------------------- | :------------------------------- | :----------------------------------------------------------- | :----------------------------------------------------------- |
|    👍     |   通用   | QQ       | 6.7.0                   | https://im.qq.com/macqq/  |  |
|    ✅     |  Intel   | 微信     | 2.5.0 (15735)           | https://mac.weixin.qq.com |  |
|    👍   |  通用 | Telegram | 7.2.4 | https://telegr.am<br />https://apps.apple.com/cn/app/telegram/id747648890?mt=12 |  |




------

**其他参考：**https://github.com/ThatGuySam/doesitarm

