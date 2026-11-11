# 浮城 · Skybound

> 一座漂在云上的城市，从午后一直走到夜里。全部画面由 GLSL 着色器实时生成，没有用一张图片或视频素材。
> A floating city above a sea of clouds, from afternoon to night, drawn in real time by a GLSL shader. No images, no video, no 3D models.

![dusk to night](screenshots/dusk-to-night.gif)

**在线体验 / Live demo:** `https://<你的用户名>.github.io/fucheng-shader/`

| 午后 Afternoon | 傍晚 Golden hour |
|---|---|
| ![](screenshots/day.jpg) | ![](screenshots/golden.jpg) |
| **黄昏 Dusk** | **夜之城 Night city** |
| ![](screenshots/dusk.jpg) | ![](screenshots/night.jpg) |

---

## 中文

### 这是什么
《浮城》是一个单文件网页作品。打开 `index.html`，你会看到：

- 一层层会翻涌、生长、消散的手绘风积云
- 漂浮在云上的城市，有瀑布、推进器和漂浮的岩石
- 一列火车开过云海上的吊桥，一头鲸鱼在天上慢慢游过
- 时间从午后变到傍晚、黄昏，再到夜晚：落日沉进云海，城里的灯一盏一盏亮起来，入夜后变成霓虹夜之城，鲸鱼变成全息投影

所有东西都是着色器用数学函数一帧一帧算出来的。

### 怎么玩
- 双击 `index.html` 用浏览器打开（推荐 Chrome 或 Edge）
- 右边的面板可以拖动参数：时刻、云量、行进速度、视角缩放、笔触强度、光束、胶片颗粒、画质
- **按 H** 隐藏或显示面板，右上角可以切换中英文
- “换一片云”会随机生成一片新的云，“时间流动”会让画面自动从白天走到黑夜
- 电脑比较卡的话，把 **画质** 调到 50%–60%

### 设成桌面壁纸
壁纸模式会隐藏面板和标题，画面跟着你电脑的**真实时间**变化：白天是蓝天，傍晚六点多变成黄昏，晚上八点以后入夜。

**Windows：Lively Wallpaper（免费，微软商店可下载）**
- 方法一（离线，推荐）：下载本仓库（Code → Download ZIP），解压后把 `wallpaper.html` 拖进 Lively
- 方法二（在线）：在 Lively 里选择“添加网址”，填入
  `https://<你的用户名>.github.io/fucheng-shader/?wallpaper=1`

**Windows：Wallpaper Engine（Steam）**
- 新建网页壁纸，导入 `wallpaper.html`

**Mac：Plash（免费，App Store）**
- 添加网址 `https://<你的用户名>.github.io/fucheng-shader/?wallpaper=1`

> 壁纸会一直使用显卡，笔记本建议接电源使用。Lively 和 Wallpaper Engine 在你全屏玩游戏时会自动暂停壁纸。

### 灵感
- 手绘云和配色参考了《双城之战》背景的绘画感，以及《爱，死亡和机器人》的插画风
- 浮空城和夜之城的设计参考了 Apex Legends 的 Olympus 与 E-District 地图的气质

这里只借鉴了风格，没有使用任何原作的素材、角色或标志。代码由我和 AI（Claude）一起从零编写。

---

## English

### What is it
*Skybound* is a single-file web piece. Open `index.html` and you get:

- Painterly cumulus clouds that billow, grow and dissolve
- A floating city with waterfalls, thrusters and drifting rocks
- A train crossing a suspension bridge above the cloud sea, and a sky whale swimming overhead
- A full day cycle: the sun sets into the clouds, windows switch on one by one, and the city turns into a neon night city, with the whale becoming a hologram

Everything is computed per pixel, per frame by a fragment shader.

### Controls
- Open `index.html` in a browser (Chrome or Edge recommended)
- Use the panel on the right: time of day, cloud cover, speed, zoom, brushwork, light rays, grain, quality
- Press **H** to toggle the panel; switch language in the top-right corner
- On slower machines, set **Quality** to 50–60%

### Use as a desktop wallpaper
Wallpaper mode hides the UI and follows your computer's **real clock**.

- **Lively Wallpaper (Windows, free):** drag `wallpaper.html` in, or add the URL
  `https://<your-username>.github.io/fucheng-shader/?wallpaper=1`
- **Wallpaper Engine (Steam):** create a web wallpaper from `wallpaper.html`
- **Plash (macOS, free):** add the URL above

### Credits
Style inspired by the painted backgrounds of *Arcane*, the illustration look of *Love, Death & Robots*, and the Olympus / E-District maps of *Apex Legends*. No assets, characters or logos from those works are used. Written from scratch by Lan together with AI (Claude).

## License
[MIT](LICENSE) © 2026 Lan
