[README.md](https://github.com/user-attachments/files/35281617/README.md)# GummyLotl 🍬 · 软糖六角恐龙

An interactive 3D gummy axolotl web toy built with **Three.js** — featuring elastic squish physics, a **6-song pentatonic music box choir**, magic candies, and **3D zero-gravity firefly chasing**.

刚刚脱模的 Q 弹软糖六角恐龙手作展台。支持抓起拉扯抛飞、轻抚撸宠、双击盘面或半空投喂魔法糖豆，还可开启六首纯五声乐曲「果冻小乐团」与「失重 + 萤火」真 3D 全向追光。

> 在线体验：将仓库中的 `index.html` 开启 GitHub Pages 后即可直接访问（推荐在 Chrome / Edge / Safari 中打开以获得完整 3D 与 Web Audio 体验）。

---

## ✨ Core Features · 核心玩法

* **Elastic Jelly Physics & Controls · Q 弹物理与操控**
  * **Grab, Stretch & Fling · 抓取拉扯抛飞**：左键抓起软糖任意拉伸并抛飞，松手后按 Q 弹晃动度回弹，落地触发弹跳拟音与高落差五声音阶清音。
  * **Pet & Rub · 轻抚撸一撸**：非萤火模式下在软糖身上来回轻划，软糖会眯起眼睛、泛起害羞腮红、原地旋转小跳并飘出几何爱心。
  * **Camera & Zoom · 视角与缩放**：右键或空白处拖拽旋转视角，滚轮或双指捏合平滑缩放，支持复位视角与收起右侧图鉴面板获得更大视野。
* **Pentatonic Jelly Choir · 六首纯五声「果冻小乐团」**
  * 对应中国五声音阶（宫 C5 / 商 D5 / 角 E5 / 徵 G5 / 羽 A5）的五款风味软糖（樱花粉 / 蜜桃橙 / 柠檬黄 / 青苹果 / 菠萝白）。
  * 内置 6 首 32 拍循环纯五声曲目：**《茉莉微风》**、**《果冻接龙舞》**、**《星尘摇篮曲》**、**《青梅竹马》**、**《雨打青瓷》**、**《软糖狂想曲》**。
  * 奏响音符时指示灯与口味卡片同步脉冲亮起，对应软糖张开唱歌小圆嘴、外鳃绽放、全身泛光、头顶飘出 `♪` 音符并错峰合唱，空闲软糖随节拍伴舞；点击风味卡还可随时即兴加花。
* **Magic Candies · 魔法糖豆投喂**
  * 支持按钮投喂或在盘面/半空双击投喂，包含随机盲盒、🌈 彩虹头尾波纹变色、⚡ 跳跳糖狂欢与 ⭐ 奇趣大小变身。
* **3D Zero-Gravity Firefly Chase · 失重 + 萤火真 3D 追光**
  * 开启「失重悬浮」与「萤火逗宠」后，移动鼠标即可在立体太空舱内上下左右控制萤火光球（附瓷盘高度深度参考环），软糖将以球形队形围观并呈现抬头爬升、低头俯冲的真实 3D 游姿。
* **Lazy Ambient Ecosystem · 慵懒惬意自主生态**
  * 无操作时软糖会在瓷盘中惬意歇息与慢悠悠踱步，或在失重空间内缓慢巡游浮沉；鼠标悬停轻抚时会自动停步让路。

---

## 🛠️ Tech Stack · 技术栈

* **3D Engine**: Three.js (with multi-CDN fallback & offline local file support)
* **Audio Synthesis**: Web Audio API (dual-bus anti-clipping sound effects + pentatonic music box)
* **Architecture**: Self-contained single-file HTML (`index.html`), zero build step required

---

## 📸 Preview · 预览截图

> 可在本地或网页端截图后替换下方占位说明：
> * `preview-tray.png` — 水磨石工作台、香槟金边立体瓷盘与五味软糖合影
> * `preview-zerog-3d.png` — 失重太空舱下的 3D 萤火追光与漂浮软糖

---

## 📄 License

MIT License — feel free to fork, remix, and play!
