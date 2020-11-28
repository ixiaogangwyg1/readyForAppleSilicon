苹果在 2020.11 月正式发布了自家芯片的 MacBook Pro、MacBook Air、Mac mini。也是因为这颗芯片（ARM），有的软件还不能正常运行，有些可以。我结合自己在使用的软件，同时搜集其他常用软件当前的适配状态，形成下面的清单，给即将购入或者关注这款 Mac 的用户提供一个可看参考的清单。

此列表不断完善，如果您也想贡献一份力量，可以提 issues 或者私信给我。

如果你也是 M1 Mac 用户或者关注 M1 Mac 相关信息，可以加 QQ 群交流：1094601027 （AppleSilicon交流分享）



清单中「状态」说明：

👍：适配 M1

✅：可以通过 Rosetta 2 方式在 M1 Mac 上正常使用

❌：不能在 M1 Mac 上正常使用



#### 生产力工具（视频剪辑、设计、开发）

| 状态 |   架构    | 名称                                                         | 版本号                           | 官网/下载页                                                  | 备注                                                         |
| :--: | :-------: | :----------------------------------------------------------- | :------------------------------- | :----------------------------------------------------------- | :----------------------------------------------------------- |
|  👍   |   通用    | Final Cut Pro                                                | 10.5                             | https://apps.apple.com/cn/app/final-cut-pro/id424389933?mt=12 | &nbsp;                                                       |
|  👍   |   通用    | iMovie                                                       | 10.2.1                           | [https://apps.apple.com/cn/app/imovie-%E5%89%AA%E8%BE%91/id408981434?mt=12](https://apps.apple.com/cn/app/imovie-剪辑/id408981434?mt=12) | &nbsp;                                                       |
|  👍   |   通用    | Cinema 4D                                                    | S22.016                          | https://www.maxon.net/en/article/cinema-4d-r23-sp1-now-available | &nbsp;                                                       |
|  ✅   |   Intel   | Premiere Pro                                                 | 14.6                             | https://www.adobe.com/hk_zh/creativecloud/catalog/desktop.html?promoid=RL89NGY7&mv=other | &nbsp;                                                       |
|  ✅   |   Intel   | YouTube-dl                                                   | 2020.11.19                       | http://www.youtube-dl.org                                    | &nbsp;                                                       |
|  ✅   |   Intel   | FFmpeg                                                       | 4.3.1                            | http://ffmpeg.org                                            | &nbsp;                                                       |
|  ✅   |   Intel   | MacX Video Converter Pro                                     | 6.5.1 (20201015)                 | https://www.macxdvd.com/mac-video-converter-pro/             | &nbsp;                                                       |
|  ✅   | **Intel** | Imaging Edge Desktop                                         | 1.0.02.03270                     | https://imagingedge.sony.net/zh-hans-cn/ie-desktop.html#remote |                                                              |
|  ✅   | **Intel** | Photoshop                                                    | 22.0.1                           | https://www.adobe.com/hk_zh/creativecloud/catalog/desktop.html?promoid=RL89NGY7&mv=other |                                                              |
|  👍   |   通用    | Photoshop beta                                               | 22.0.0                           |                                                              |                                                              |
|  ✅   |   通用    | Adobe Lightroom Classic                                      | 10.0                             | https://www.adobe.com/hk_zh/creativecloud/catalog/desktop.html?promoid=RL89NGY7&mv=other |                                                              |
|  ✅   | **Intel** | Adobe Lightroom                                              | 4.0                              | https://www.adobe.com/hk_zh/creativecloud/catalog/desktop.html?promoid=RL89NGY7&mv=other |                                                              |
|  ✅   | **Intel** | After Effects                                                | 17.5.1                           | https://www.adobe.com/hk_zh/creativecloud/catalog/desktop.html?promoid=RL89NGY7&mv=other |                                                              |
|  ✅   | **Intel** | Adobe XD                                                     | 35.1.12                          | https://www.adobe.com/hk_zh/creativecloud/catalog/desktop.html?promoid=RL89NGY7&mv=other |                                                              |
|  👍   | **Apple** | Sketch                                                       | 70 (108797)                      | https://www.sketch.com/downloads/mac/                        |                                                              |
|  ❌   | **Intel** | [AutoCAD](https://www.autodesk.com/products/autocad/overview?plc=ACDIST&term=1-YEAR&support=ADVANCED&quantity=1) |                                  | https://www.autodesk.com/products/autocad/overview?plc=ACDIST&term=1-YEAR&support=ADVANCED&quantity=1 | https://forums.autodesk.com/t5/autocad-for-mac-forum/apple-silicon/m-p/9652836 |
|  ❌   | **Intel** | Docker                                                       |                                  |                                                              |                                                              |
|  ❌   | **Intel** | TensorFlow                                                   |                                  | https://blog.tensorflow.org/2020/11/accelerating-tensorflow-performance-on-mac.html | Not yet, but a supported pre-release is available https://github.com/tensorflow/tensorflow/issues/44751   https://blog.tensorflow.org/2020/11/accelerating-tensorflow-performance-on-mac.html |
|  👍   | **Apple** | Xcode                                                        | 12.2                             | https://apps.apple.com/cn/app/xcode/id497799835?mt=12        |                                                              |
|  ✅   | **Intel** | Sourcetree                                                   | 4.0.2                            | https://www.sourcetreeapp.com                                |                                                              |
|  👍   | **Apple** | [Tower](https://www.git-tower.com/mac)                       | 6.1 build258                     | https://www.git-tower.com/mac                                |                                                              |
|  👍   | **Apple** | Iterm2                                                       | 03.4.1                           | https://iterm2.com/downloads.html                            |                                                              |
|  ✅   | **Intel** | Sublime                                                      | 03.2.2                           | http://www.sublimetext.cn                                    |                                                              |
|  ✅   | **Intel** | Postman                                                      | 07.3.6                           | https://www.postman.com/downloads/                           |                                                              |
|  ✅   | **Intel** | Charles                                                      | 04.6.1                           | https://www.charlesproxy.com                                 |                                                              |
|  👍   | **Apple** | Transmit                                                     | 04.4.11                          | https://library.panic.com/releasenotes/transmit5/            |                                                              |
|  ✅   | **Intel** | Navicat Premium                                              | 15.0.22                          | https://www.navicat.com/en/download/navicat-premium#mac      |                                                              |
|  ✅   | **Intel** | VS Code                                                      | 1.51.1                           |                                                              |                                                              |
|  ✅   | **Intel** | Android Studio                                               | 04.1.1                           |                                                              |                                                              |
|  ✅   | **Intel** | Node                                                         | 15.3.0                           | https://github.com/nodejs/node                               | https://github.com/nodejs/build/issues/2474 https://github.com/nodejs/node/issues/36160 |
|  ✅   | **Intel** | Flutter                                                      | 1.24.0-10.2.pre                  |                                                              | https://github.com/flutter/flutter/issues/60118              |
|  ✅   | **Intel** | home-brew                                                    | 02.5.11                          | https://brew.sh https://github.com/Homebrew/brew             | https://soffes.blog/homebrew-on-apple-silicon                |
|  👍   | **Apple** | Redis                                                        | 6.0.9                            | https://redis.io/download                                    | https://github.com/ThatGuySam/doesitarm/issues/298           |
|  ✅   | **Intel** | WebStorm                                                     |                                  |                                                              |                                                              |
|  ✅   | **Intel** | HandShaker                                                   | 2.1.1 (255)                      | https://www.smartisan.com/apps/#/handshaker                  |                                                              |
|  👍   | **Apple** | iExportHelper                                                | 1.1.0                            | https://apps.apple.com/cn/app/iexporthelper/id1486337874?mt=12 |                                                              |
|  ✅   | **Intel** | CocoaPods                                                    | 1.10.0                           | https://cocoapods.org https://github.com/CocoaPods/CocoaPods | https://github.com/CocoaPods/CocoaPods/issues/9907           |
|  ✅   | **Intel** | Carthage                                                     | 0.36.0                           | https://github.com/Carthage/Carthage                         | https://github.com/Carthage/Carthage/issues/3019             |
|  ✅   | **Intel** | PPDuck                                                       | 03.10.1                          | http://ppduck.com                                            |                                                              |
|  ✅   | **Intel** | Matlab                                                       | v9.9.0.1495850                   | https://ww2.mathworks.cn/products/matlab.html                | https://www.mathworks.com/matlabcentral/answers/641925-is-matlab-supported-on-apple-silicon-macs |
|  ✅   | **Intel** | [Python](https://www.python.org/)                            |                                  |                                                              | working for v2.7.16, v3.8.2, and v3.9 https://github.com/python/cpython/pull/22855 |
|  👍   | **Apple** | Surge                                                        | 4.0.0                            | https://doesitarm.com/app/surge/                             |                                                              |
|  ✅   | **Intel** | SwitchHosts!                                                 | v3.3.12 (5349)                   | https://oldj.github.io/SwitchHosts/                          |                                                              |
|  ✅   | **Intel** | Renamer 6                                                    | 6.0.6                            | https://renamer.com                                          |                                                              |
|  ✅   | **Intel** | PxCook                                                       | 3.9.940 beta                     | https://www.fancynode.com.cn/pxcook                          |                                                              |
|  ✅   | **Intel** | Reveal                                                       | 27                               | https://revealapp.com/download-thanks/                       |                                                              |
|  ❌   | **Intel** | VMware Fusion                                                | 专业版 12.0.0 (16880131)         | https://www.vmware.com/products/fusion/fusion-evaluation.html |                                                              |
|  ❌   | **Intel** | Parallels Desktop                                            | 16.1.1                           | https://www.parallels.cn/pd/fusion-compete/                  | https://b2b.parallels.com/Apple-Silicon?_ga=2.90285848.300308216.1605800730-777219924.1605800730# |
|  ✅   | **Intel** | Excel                                                        | 16.43.1                          | https://www.microsoft.com/zh-cn/microsoft-365/buy/compare-all-microsoft-365-products   https://apps.apple.com/cn/app/microsoft-excel/id462058435?mt=12 |                                                              |
|  ✅   | **Intel** | Word                                                         | 16.43.1                          | https://www.microsoft.com/zh-cn/microsoft-365/buy/compare-all-microsoft-365-products   https://apps.apple.com/cn/app/microsoft-word/id462054704?mt=12 |                                                              |
|  ✅   | **Intel** | PowerPoint                                                   | 16.43                            | https://www.microsoft.com/zh-cn/microsoft-365/buy/compare-all-microsoft-365-products   https://apps.apple.com/cn/app/microsoft-powerpoint/id462062816?mt=12 |                                                              |
|  👍   | **Apple** | Word                                                         | 16.44(beta)                      | https://www.microsoft.com/zh-cn/microsoft-365/buy/compare-all-microsoft-365-products |                                                              |
|  👍   | **Apple** | Outlook                                                      | 16.44(beta)                      | https://www.microsoft.com/zh-cn/microsoft-365/buy/compare-all-microsoft-365-products |                                                              |
|  👍   | **Apple** | OneNote                                                      | 16.44(beta)                      | https://www.microsoft.com/zh-cn/microsoft-365/buy/compare-all-microsoft-365-products |                                                              |
|  ✅   | **Intel** | OneNote                                                      | 16.43                            | https://www.microsoft.com/zh-cn/microsoft-365/buy/compare-all-microsoft-365-products   https://apps.apple.com/cn/app/microsoft-onenote/id784801555?mt=12 |                                                              |
|  ✅   | **Intel** | OneDrive                                                     | 20.201.1005                      | https://www.microsoft.com/zh-cn/microsoft-365/buy/compare-all-microsoft-365-products   https://apps.apple.com/cn/app/onedrive/id823766827?mt=12 |                                                              |
|  👍   | **Apple** | Keynote                                                      | 10.3.5                           | [https://apps.apple.com/cn/app/keynote-%E8%AE%B2%E6%BC%94/id409183694?mt=12](https://apps.apple.com/cn/app/keynote-讲演/id409183694?mt=12) |                                                              |
|  👍   | **Apple** | Numbers                                                      | 10.3.5                           | [https://apps.apple.com/cn/app/numbers-%E8%A1%A8%E6%A0%BC/id409203825?mt=12](https://apps.apple.com/cn/app/numbers-表格/id409203825?mt=12) |                                                              |
|  👍   | **Apple** | Pages                                                        | 10.3.5                           | [https://apps.apple.com/cn/app/pages-%E6%96%87%E7%A8%BF/id409201541?mt=12](https://apps.apple.com/cn/app/pages-文稿/id409201541?mt=12) |                                                              |
|  👍   | **Apple** | MindNode                                                     | 2020.6 (265)                     | https://apps.apple.com/cn/app/mindnode-mind-map/id1289197285?mt=12   https://mindnode.com/download |                                                              |
|  👍   | **Apple** | OminGrafle                                                   | 7.18                             | https://www.omnigroup.com/omnigraffle/                       |                                                              |
|  ✅   | **Intel** | 迅雷                                                         | 03.4.1                           | https://dl.xunlei.com/#mod02                                 |                                                              |
|  👍   | **Apple** | Keka                                                         | 1.2.3 (4223)                     | https://www.keka.io/zh-cn/                                   |                                                              |
|  👍   | **Apple** | Safari                                                       | 14.0.1 (16610.3.6.3)             |                                                              |                                                              |
|  ✅   | **Intel** | Firefox                                                      | 83.0                             | http://www.firefox.com.cn                                    |                                                              |
|  👍   | **Apple** | Chrome                                                       | 87.0.4280.67（正式版本） (arm64) | https://www.google.cn/chrome/                                |                                                              |
|  ✅   | **Intel** | trojan-qt5                                                   | 1.4.0                            |                                                              |                                                              |
|  ✅   | **Intel** | 印象笔记                                                     | 9.4.7 (461685 App Store)         | https://yinxiang.com/download/                               |                                                              |
|  ✅   | **Intel** | 百度网盘                                                     | 3.5.0 (12)                       |                                                              |                                                              |
|  👍   | **Apple** | BetterTouchTool                                              | 3.506                            | https://folivora.ai/downloads                                |                                                              |
|  👍   | **Apple** | Ulysses                                                      | 21.1                             | https://apps.apple.com/cn/app/ulysses/id1225570693?mt=12     |                                                              |

音乐/视频

| **适配** | **架构**  | **名称**         | **版本号** | 官网/下载页面                                                | **备注** |
| :------: | :-------: | :--------------- | :--------- | :----------------------------------------------------------- | :------- |
|    👍     | **apple** | QuickTime Player | 10.5       |                                                              |          |
|    👍     | **apple** | GrandBand        | 10.4.1     | https://apps.apple.com/cn/app/garageband/id682658836?mt=12   |          |
|    👍     | **apple** | Logic Pro        | 10.6       | https://apps.apple.com/cn/app/logic-pro/id634148309?mt=12    |          |
|    👍     | **apple** | MainStage        | 3.5        | https://apps.apple.com/cn/app/mainstage/id634159523?mt=12    |          |
|    ✅     | **Intel** | 腾讯视频         | 2.18.2     | [https://apps.apple.com/cn/app/%E8%85%BE%E8%AE%AF%E8%A7%86%E9%A2%91-%E6%88%91%E5%96%9C%E6%AC%A2%E4%BD%A0-%E7%8B%AC%E6%92%AD/id1231336508?mt=12](https://apps.apple.com/cn/app/腾讯视频-我喜欢你-独播/id1231336508?mt=12) |          |
|    ✅     | **Intel** | 爱奇艺           | 11.11.0    | [https://apps.apple.com/cn/app/%E7%88%B1%E5%A5%87%E8%89%BA-%E5%A6%82%E6%84%8F%E8%8A%B3%E9%9C%8F%E7%83%AD%E6%92%AD/id1012296988?mt=12](https://apps.apple.com/cn/app/爱奇艺-如意芳霏热播/id1012296988?mt=12) |          |
|    ✅     | **Intel** | 网易云音乐       | 02.3.2     | [https://apps.apple.com/cn/app/%E7%BD%91%E6%98%93%E4%BA%91%E9%9F%B3%E4%B9%90/id944848654?mt=12](https://apps.apple.com/cn/app/网易云音乐/id944848654?mt=12) |          |
|    ✅     | **Intel** | QQ音乐           | 7.3.0      | [https://apps.apple.com/cn/app/qq%E9%9F%B3%E4%B9%90-%E8%AE%A9%E7%94%9F%E6%B4%BB%E5%85%85%E6%BB%A1%E9%9F%B3%E4%B9%90/id595615424?mt=12](https://apps.apple.com/cn/app/qq音乐-让生活充满音乐/id595615424?mt=12) |          |
|    ✅     | **Intel** | 喜马拉雅         | 01.2.22    | [https://apps.apple.com/cn/app/%E5%96%9C%E9%A9%AC%E6%8B%89%E9%9B%85-%E5%90%AC%E4%B9%A6%E7%A4%BE%E5%8C%BA-%E7%94%B5%E5%8F%B0%E6%9C%89%E5%A3%B0%E5%B0%8F%E8%AF%B4%E7%9B%B8%E5%A3%B0%E8%AF%84%E4%B9%A6/id876336838](https://apps.apple.com/cn/app/喜马拉雅-听书社区-电台有声小说相声评书/id876336838) |          |
|    ✅     | **Intel** | VLC              | 3.0.11.1   | https://www.videolan.org/vlc/                                |          |
|    ✅     | **Intel** | IINA             | 01.1.2     | https://www.iina.io                                          |          |
|    ✅     | **Intel** | Movist Pro       | 02.2.3     | https://movistprime.com                                      |          |



社交

| **适配** | **架构**  | **名称**         | **版本号** | 官网/下载页面                                                | **备注** |
| :--: | :-------: | :----------------------------------------------------------- | :------------------------------- | :----------------------------------------------------------- | :----------------------------------------------------------- |
|    👍     |   通用   | QQ       | 6.7.0                   | https://im.qq.com/macqq/  |  |
|    ✅     |  Intel   | 微信     | 2.5.0 (15735)           | https://mac.weixin.qq.com |  |
|    ✅     |  Intel   | Telegram | 7.2.3 (208487) AppStore | https://telegr.am         |  |



