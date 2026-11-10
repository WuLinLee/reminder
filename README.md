### E:\ffmpeg-gs 目录结构 [WuLinLee/bat 我的bat](https://github.com/WuLinLee/bat)

```
 E:\ffmpeg-gs
 ├── ffmpeg.exe
 ├── fpcalc.exe
 ├── gsdll64.dll
 ├── gswin64c.exe
 ├── img2pdf-gui.exe（Python）
 ├── img2pdf.exe（Python）
 └── TagLibSharp.dll
```

### 游戏存档位置（drtli是我固定的名字） [mtkennerly/ludusavi: 我用的游戏存档备份](https://github.com/mtkennerly/ludusavi)

```
C:\Users\drtli\AppData\LocalLow\...
C:\Users\drtli\AppData\Local\...
C:\Users\drtli\AppData\Roaming\...
C:\Users\drtli\Documents\...（我自己固定的路径）
C:\Users\drtli\Saved Games\...
D:\steam\userdata\... （我自己的安装位置）
D:\steam\steamapps\common\...
D:\-01-gamess\...（我自己固定的路径）
D:\WpSystem\...
- 少量注册表数据（registry.reg）
```

****



### 截图类

| 快捷键        | 功能       |
| :------------ | :--------- |
| `PrtSc SysRq` | 全屏截图   |
| `Win Shift S` | 区域截图   |
| `F12`         | Steam截图  |
| `Win Shift T` | 文本提取器 |

### 浏览器专用

| 快捷键         | 功能                                                         |
| :------------- | :----------------------------------------------------------- |
| `F11`          | 浏览器全屏                                                   |
| `Ctrl Tab`     | 浏览器内切换                                                 |
| `Ctrl shift T` | 恢复删除标签                                                 |
| `Ctrl W`       | 关闭选中标签页（shift 选择范围 Ctrl 取消选中）/关闭当前标签页 |

### 页面导航

| 快捷键     | 功能       |
| :--------- | :--------- |
| `Home End` | 最上最下   |
| `Alt ↑`    | 返回上一层 |

### 窗口切换与关闭

| 快捷键    | 功能                                               |
| :-------- | :------------------------------------------------- |
| `Alt Esc` | 切换                                               |
| `Alt tab` | 切换                                               |
| `Win Tab` | 切换                                               |
| `Alt F4`  | 关闭当前活动窗口<br>也可以按alt不放 按F4一个一个关 |
| `Ctrl N`  | 新增相同页面                                       |

### 桌面与布局管理

| 快捷键         | 功能                       |
| :------------- | :------------------------- |
| `Win D`        | 回到桌面<br>再点恢复       |
| `Win Home`     | 只保留当前页面<br>再点恢复 |
| `Win ↑↓← →`    | 切换页面布局               |
| `Win Z 加数字` | 切换页面布局               |
| `Win Ctrl D`   | 新增虚拟桌面               |
| `Win Ctrl ← →` | 切换虚拟桌面               |

### 其他辅助操作

| 快捷键                                                       | 功能                                                         |
| :----------------------------------------------------------- | :----------------------------------------------------------- |
| `Ctrl ↖ (点击)取消选中`   ` shift↖(点击)   ↖(点击) 选择范围` | 取消选中   选择范围                                          |
| `Win R Win V Enter`                                          | steam快速打开复制网站                                        |
| `Win Alt B `（支持游戏内也需打开HDR开关） <br/>  Windows HDR Calibration ＋（英伟达控制面板设置） | 打开HDR（视频HDR查看：MPV - Shift+i - Video - Transfer)<br/>(`bt.1886 和 gamma` = SDR) (`pq 和 hlg` = HDR) |
| `5`（自定义快捷键设置）                                      | 微型小飞机-OSD显示-OSD功能启动切换（汉化）                   |
| `Win P`                                                      | 投影（切屏幕）                                               |
| `Shift 1（!）`                                               | MPV插帧(快速)                                                |
| `Win + -`                                                    | 放大镜                                                       |
| `Ctrl Shift Esc`                                             | 资源管理器                                                   |
| Ctrl+z Ctrl+x  j上移字幕 下移字幕 开弹幕(MPV自定义）<br/>导出字幕: 使用时按 ` 键打开控制台---→ | Shift+z  Shift+x   j缩小字幕 放大字幕 开弹幕(MPV自定义) <br/>---输入：script-message-to sub_export export-selected-subtitles |

****

### 日语快捷键

 **Shift + Caps Lock**：切到半角英数/英文
 **Ctrl + Caps Lock**：切回平假名
 **Alt + Caps Lock**：切到片假名          按x或l  打出小写 

****

### 系统设置

**| 系统→多任务管理 不显示选项卡 标题栏窗口晃动 |**

方便Alt Tab 以及 Win home

### 换电脑时 文档改名Documents  ludusavi先备份后恢复游戏存档  

### E盘建  0PORTABLE 文件夹装便携版exe/直接加portable前缀也可以

****

### 用软件让耳机左右声音一样大

### 一、下载安装

1. 下载 Equalizer APO：https://sourceforge.net/projects/equalizerapo/
2. 安装时，在设备列表里勾选你的耳机。
   - 蓝牙耳机选“立体声”那个，不要选带“Hands-Free”的。
3. 安装完，重启电脑。

### 二、调整

1. 开始菜单搜 Equalizer APO，打开 Configuration Editor。
2. 右上角“设备”选你的耳机。
3. 点左上角“+”，选“控制” → “声道”。
4. 在“声道”模块里，点亮声音**大**的那边：
   - 左边声音大就点亮 L
   - 右边声音大就点亮 R
5. 再点“+”，选“基本滤波器” → “预放大”。
6. 把预放大数值改成负数，比如 -10 dB。边听边调，直到两边一样大。
7. 按 Ctrl+S 保存。
8. 重启电脑。

### 三、记住

- 只把声音大的那边调小，不要给声音小的那边加正数。
- 如果整体声音变小了，直接把电脑右下角音量拉高。
- 如果调了没反应：检查蓝牙是不是选了 Hands-Free，或者播放器开了独占模式。

****

# Typora 区分 0 和 O

只改数字，不换默认字体。

## 步骤

1. Typora → 偏好设置 → 外观 → 打开主题文件夹
2. 编辑或新建 `base.user.css`
3. 粘贴以下代码，保存
4. 重启 Typora

## CSS

```css
@font-face {
  font-family: 'NumericOnly';
  src: local('Consolas'), local('Menlo'), local('Monaco'), local('SF Mono');
  unicode-range: U+0030-0039;
}

#write,
#write * {
  font-family: 'NumericOnly', "你的默认字体", sans-serif !important;
}
```

****

**电脑有线耳机不识别 下载这个驱动 Realtek High Definition Audio Driver**

****

**steam → 设置 → 控制器 → 显示高级设置  <br/>开启 `按下导航键将steam置于前端`  `启动控制器的导航键组合键` <br/>安装`xbox扩展功能支持驱动`<br/>即可 双击西瓜键/home键 打开steam大屏幕模式** 

****

**Everything 1.5以上有黑色模式<br/>（工具 → 选项 → 界面 → 关闭后台运行）**

****

**Windows SMB 共享给手机 mpvEx 播放<br/>设置 → 网络和internet → 高级网络设置 → 高级共享设置 → 专用网络 → 打开文件和打印机共享<br/>点击文件夹 右键 → 属性 → 共享 → 高级共享 → 共享此文件夹 → 编辑其他设置 → 确定**



****

Syncthing 手机下载文件夹 ⇄ 电脑 本地双向同步

### 工具（github）

- Windows：SyncTrayzor
- Android：Syncthing-Fork
- 同步路径：手机 `/storage/emulated/0/Download` → 电脑 `D:\-01- phone downloads`

```text
// ============================================================
// Android /storage/emulated/0/Download
// 目的：临时下载文件不要同步到 Windows
// 第一条匹配规则生效
//
// (?i) = 忽略大小写
// (?d) = 被忽略文件不阻碍目录删除
// ============================================================


// --- 1. 下载进行中的临时文件 ---
// Chrome / Chromium：.crdownload
// Firefox / 部分下载器：.part
// 部分下载器：.download / .partial
(?d)(?i)**/*.crdownload
(?d)(?i)**/*.part
(?d)(?i)**/*.download
(?d)(?i)**/*.partial

// --- 2. 常见临时工作文件 ---
(?d)(?i)**/*.tmp
(?d)(?i)**/*.temp

// --- 3. 常见下载器辅助文件 ---
// aria2 下载未完成时常见：.aria2
// Opera 等下载器可能使用：.opdownload
(?d)(?i)**/*.aria2
(?d)(?i)**/*.opdownload

// --- 4. 编辑器 / 程序临时文件 ---
(?d)(?i)**/*.swp
(?d)(?i)**/*.swo
(?d)(?i)**/*~

// --- 5. 系统自动产生的垃圾文件 ---
(?d)(?i)Thumbs.db
(?d)(?i)desktop.ini
(?d)(?i).DS_Store
(?d)(?i).thumbnails
(?d)(?i)_thumbnails
(?d)(?i).thumbs
```

****

相关链接

- [SyncTrayzor](https://github.com/GermanCoding/SyncTrayzor)
- [Syncthing-Fork](https://github.com/researchxxl/syncthing-android)
- [MPV Lazy 2026 Custom](https://github.com/luoxue03/mpv-lazy-2026-custom)
- [mpvEx-CN](https://github.com/azxcvn/mpvEx-CN)
- [MPV 字幕导出脚本](https://github.com/dyphire/mpv-scripts/blob/main/sub_export.lua)
- [我的BAT](https://github.com/WuLinLee/bat)
- [Ludusavi](https://github.com/mtkennerly/ludusavi)
- [FFmpeg](https://github.com/FFmpeg/FFmpeg)
- [FFmpeg Windows Builds](https://github.com/GyanD/codexffmpeg)
- [Chromaprint](https://github.com/acoustid/chromaprint)
- [Ghostscript](https://github.com/ArtifexSoftware/ghostpdl)
- [Ghostscript Downloads](https://github.com/ArtifexSoftware/ghostpdl-downloads)
- [img2pdf](https://github.com/josch/img2pdf)
- [pikepdf](https://github.com/pikepdf/pikepdf)
- [TagLibSharp](https://github.com/mono/taglib-sharp)
- 下面是非github网址
- [Equalizer APO](https://sourceforge.net/projects/equalizerapo/)
- [Typora](https://typora.io/)
- [Everything](https://www.voidtools.com/)
- [Steam](https://store.steampowered.com/)
