# T-28Block
T-28戰術方塊 Tactical Block: Double-28 Tactical System (28 Blocks & 28 Treasures). Hardcore falling-block puzzle and line-clearing game. Features GAU-8 Cannon, Thor's Hammer, and AI automation. <1MB Vanilla JS+HTML+CSS. | 雙 28 戰術體系：28 種方塊 (2-5格) 堆疊消行遊戲 ＋ 28 種戰術寶物。搭載 GAU-8 機砲、雷神之槌、流星雨與 AI 自動化，<1MB 原生代碼鑄造。 | 双 28 战术体系：28 种方块 (2-5格) 堆叠消行游戏 ＋ 28 种战术宝物。搭载 GAU-8 机炮、雷神之锤、流星雨与 AI 自动化，<1MB 原生代码铸造。

---

## 🕹️ Project Overview | 專案總覽 | 项目总览

**[ EN ]** T-28Block is a hardcore **falling-block puzzle and line-clearing game** forged with <1MB of pure Vanilla JS+HTML+CSS. 

**[ 繁中 ]** T-28Block 是一款由 <1MB 原生 JS+HTML+CSS 鑄造的硬核**下落式方塊消行遊戲**。

**[ 简中 ]** T-28Block 是一款由 <1MB 原生 JS+HTML+CSS 铸造的硬核**下落式方块消行游戏**。

---

## 🛡️ The Double-28 Architecture | 雙 28 戰術體系 | 双 28 战术体系

### 28 Tactical Blocks | 28 種戰術方塊 | 28 种战术方块
**[ EN ]**
* **Diversity**: From **2-cell extending rods** to 5-cell "P5" heavy dreadnoughts. Includes all 2-5 cell geometric variants.
* **Block Inventory**: Fully customizable block pool. You decide the variety and quantity of blocks to use.
* **Tactical Grid**: Supports **12x20 basic** and **14x24 heavy-duty** (Optimized for P5 units) grids.

**[ 繁中 ]**
* **多樣性**：收錄從**兩格伸縮棒**到 5 格「P5」重裝型單位，涵蓋 2-5 格全系列幾何變體方塊。
* **方塊庫存**：自定義方塊池，由你決定要使用多少種、哪些種類的方塊進行遊戲。
* **戰術網格**：提供 **12x20 基礎網格** 與 **14x24 P5 專用重裝網格**。

**[ 简中 ]**
* **多样性**：收录从**两格伸缩棒**到 5 格「P5」重装型单位，涵盖 2-5 格全系列几何变体方块。
* **方块库存**：自定义方块池，由你决定要使用多少种、哪些种类的方块进行游戏。
* **战术网格**：提供 **12x20 基础网格** 与 **14x24 P5 专用重装网格**。

### 28 Tactical Treasures | 28 種戰術寶物 | 28 种战术宝物
**[ EN ]** A diverse arsenal of 28 items and gear. (See [Item Compendium](#-item-compendium--道具圖鑑) for details). 
**[ 繁中 ]** 具備 28 種功能各異的武裝與裝備。（詳見下文 [道具圖鑑](#-item-compendium--道具圖鑑)）。 
**[ 简中 ]** 具备 28 种功能各异的武装与装备。（详见下文 [道具图鉴](#-item-compendium--道具图鉴)）。 

---

## 🧠 Intelligence & Mechanics | 智能與機制 | 智能与机制

**[ EN ]** * **2-Ply AI Automation**: Features a high-performance **2-ply lookahead algorithm**.
* **Progress Control**: Integrated **Save/Load** system.
* **Dual-Pilot**: Optimized for local P1/P2 combat.
* **Visual Styles**: **Dark, Light, Extra-light and LCD Retro modes**.

**[ 繁中 ]** * **2-Ply AI 自動化**：內建高性能 **2-ply 預測演算法**，能同時運算當前與下一手方塊的最佳位置。
* **進度掌控**：支援**儲存/載入 (Save/Load)** 遊戲進度，並可**隨時調整速度與難度**。
* **雙人對戰**：專為 P1/P2 本地對戰優化，支援互丟**垃圾行、字元與骰子隨機攻擊**。
* **視覺風格**：提供**深色、淺色、極淺、LCD 復古**四種模式。

**[ 简中 ]** * **2-Ply AI 自动化**：内建高性能 **2-ply 预测算法**，能同时运算当前与下一手方块的最佳位置。
* **进度掌控**：支持**存档/载入 (Save/Load)** 游戏进度，并可**随时调整速度与难度**。
* **双人对战**：专为 P1/P2 本地对战优化，支持互丢**垃圾行、字符与骰子随机攻击**。
* **视觉风格**：提供**深色、浅色、极浅、LCD 复古**四种模式。

---

## 🎮 Operation Manual | 操作指南 | 操作指南

### ⌨️ Keyboard Controls | 鍵盤操作 | 键盘操作

**[ EN ]**
| Action | 👤 P1 Player (Left/Right Hand) | 👥 P2 Player (Numpad) |
| :--- | :--- | :--- |
| **⬅️➡️ Move** | Arrow Keys / A, D | 4, 6 |
| **⬇️ Soft Drop** | Down / S | 2, 5 |
| **⏬ Hard Drop** | Space (If swapped: Enter) | Enter (Bottom Right) |
| **↻ Rotate CW** | Enter, Up, X (If swapped: Space) | 8, 9, + |
| **↺ Rotate CCW** | Ctrl, Z | 7 |
| **📥 Hold** | Shift, C | 0 |

**[ 繁中 ]**
| 功能 | 👤 P1 玩家 (左手/右手) | 👥 P2 玩家 (數字鍵盤) |
| :--- | :--- | :--- |
| **⬅️➡️ 移動** | 方向鍵 / A, D | 4, 6 |
| **⬇️ 軟降** | 下 / S | 2, 5 |
| **⏬ 瞬降** | Space (互換開啟時: Enter) | Enter (右下) |
| **↻ 順轉** | Enter, 上, X (互換開啟時: Space) | 8, 9, + |
| **↺ 逆轉** | Ctrl, Z | 7 |
| **📥 暫存** | Shift, C | 0 |

**[ 简中 ]**
| 功能 | 👤 P1 玩家 (左手/右手) | 👥 P2 玩家 (数字键盘) |
| :--- | :--- | :--- |
| **⬅️➡️ 移动** | 方向键 / A, D | 4, 6 |
| **⬇️ 软降** | 下 / S | 2, 5 |
| **⏬ 瞬降** | Space (互换开启时: Enter) | Enter (右下) |
| **↻ 顺转** | Enter, 上, X (互换开启时: Space) | 8, 9, + |
| **↺ 逆转** | Ctrl, Z | 7 |
| **📥 暂存** | Shift, C | 0 |

---

### 🖱️ UI & Navigation | 介面與導航 | 界面与导航

**[ EN ]**
* 📝 **Base Scoring**: 20 pts per line, +10 pts per combo, 1 pt per block destroyed by bombs/weapons.
* ↕️ **Gesture Navigation**: Swipe **up/down** on the game area to switch between P1/P2 views (Portrait mode on mobile/tablet).
* 🔵 **Control Switch**: Tap the score bar to switch control. The lit **Blue Dot (P1)** or **Purple Dot (P2)** indicates the currently controlled player.
* 🤖 **AI Automation**: When enabled, the AI automatically stacks and clears blocks based on the set level (from Turtle to God-tier).
* ▶️ **Play/Pause**: Start or pause the game. You can **Save** the game while paused.
* ⌨️ **Layout Switch**: Cycle through 5 virtual button layouts (**Type A~E**) to suit your grip style.
* 📊 **Stats & Speed**: Displays cleared lines and total blocks. Use the **Speed** slider to adjust drop speed in real-time (Levels 1-20).

**[ 繁中 ]**
* 📝 **基本計分**：消行 20 分，連擊 +10 分/次，炸彈/武器破壞 1 分/格。
* ↕️ **手勢導航**：手機垂直畫面下，在遊戲區域**上/下滑**切換 P1/P2 畫面。
* 🔵 **控制權切換**：點擊分數欄切換控制對象，**藍點(P1)** 或 **紫點(P2)** 代表目前受控者。
* 🤖 **AI 自動化**：開啟後 AI 將根據等級（龜速到神級）自動進行堆疊與消除。
* ▶️ **開始/暫停**：啟動遊戲或暫停。暫停時可進行**存檔**操作。
* ⌨️ **操作切換**：循環切換 **Type A~E** 五種虛擬按鍵佈局。
* 📊 **數據與速度**：顯示消行數、方塊總數；**Speed** 滑桿可即時調整速度 (1-20級)。

**[ 简中 ]**
* 📝 **基本计分**：消行 20 分，连击 +10 分/次，炸弹/武器破坏 1 分/格。
* ↕️ **手势导航**：手机垂直画面下，在游戏区域**上/下滑**切换 P1/P2 画面。
* 🔵 **控制权切换**：点击分数栏切换控制对象，**蓝点(P1)** 或 **紫点(P2)** 代表目前受控者。
* 🤖 **AI 自动化**：开启后 AI 将根据等级（龟速到神级）自动进行堆叠与消除。
* ▶️ **开始/暂停**：启动游戏或暂停。暂停时可进行**存档**操作。
* ⌨️ **操作切换**：循环切换 **Type A~E** 五种虚拟按键布局。
* 📊 **数据与速度**：显示消行数、方块总数；**Speed** 滑杆可实时调整速度 (1-20级)。

---

### ⚙️ Detailed Settings | 詳細設定說明 | 详细设置说明

**[ EN ]**
* **🔹 Preview & Predict**: Enable the Next+ window (preview 3 upcoming blocks), AI drop shadows, and AI decision logic messages.
* **🔹 Swap & Aim**: Swap the positions of Hard Drop / Soft Drop buttons; Show the predicted drop shadow for blocks.
* **🔹 Bombs & Hold**: Enable dropping tactical bombs for multi-line clears; AI will automatically use the Hold (Swap) strategy on Medium difficulty or above.
* **🔹 Item Drop Rate**: Adjusts the spawn weight and probability of Number Blocks and Enchanted Blocks.
* **🔹 Block Inventory**: Monitor the percentage of the 28 block types and manually toggle specific blocks on/off.

**[ 繁中 ]**
* **🔹 預覽/預判**：開啟 Next+ 視窗（預看 3 個方塊）及 AI 落點虛影與決策邏輯訊息。
* **🔹 互換/瞄準**：螢幕瞬降/緩降位置互換；顯示方塊落點預測虛影 (Shadow)。
* **🔹 炸彈/換牌**：開啟消除多行掉落炸彈功能；AI 在中等以上等級會自動執行換牌策略。
* **🔹 寶物機率**：決定數字方塊與附魔方塊生成的權重。
* **🔹 方塊庫存**：監測 28 種方塊的數量百分比，並可手動開關特定方塊。

**[ 简中 ]**
* **🔹 预览/预判**：开启 Next+ 窗口（预看 3 个方块）及 AI 落点虚影与决策逻辑信息。
* **🔹 互换/瞄准**：屏幕瞬降/缓降位置互换；显示方块落点预测虚影 (Shadow)。
* **🔹 炸弹/换牌**：开启消除多行掉落炸弹功能；AI 在中等以上等级会自动执行换牌策略。
* **🔹 宝物概率**：决定数字方块与附魔方块生成的权重。
* **🔹 方块库存**：监测 28 种方块的数量百分比，并可手动开关特定方块。

---

## 🛠️ Item Compendium | 道具圖鑑 | 道具图鉴

### 💎 How to Obtain | 寶物獲取途徑 | 宝物获取途径

**[ EN ]**
* 🔥 **Combo**: Increases score and item drop chance. Combo 4+ massively boosts the drop rate.
* 💣 **Multi-line Clear**: Clear 2/3/4 lines for a chance to get **B2/B3/B4 Tactical Bombs**.
* 📈 **Accumulated Reward**: Accumulate cleared lines or blocks for a high chance to trigger ultimate moves.

**[ 繁中 ]**
* 🔥 **連擊 (Combo)**：分數增加、機率掉寶，Combo 4+ 掉寶率大幅提升。
* 💣 **多行消除**：消除 2/3/4 行，機率獲得 **B2/B3/B4 戰術炸彈**。
* 📈 **累積獎勵**：累積消行或方塊數，高機率獲得強力大招。

**[ 简中 ]**
* 🔥 **连击 (Combo)**：分数增加、概率掉宝，Combo 4+ 掉宝率大幅提升。
* 💣 **多行消除**：消除 2/3/4 行，概率获得 **B2/B3/B4 战术炸弹**。
* 📈 **累计奖励**：累计消行或方块数，高概率获得强力大招。

---

### 🚀 Tactical Arsenal | 戰術武裝清單 | 战术武装清单

**[ EN ]**
| Item Name | Description |
| :--- | :--- |
| 🧨 **Dud Bomb** | Requires a line clear to detonate. |
| 💣 **B2 Bomb** | Small area explosion. |
| 🗡︎ **B3 Bomb** | Medium area explosion. |
| 💥 **B4 Heavy Bomb** | Crushes and causes a massive explosion. |
| 🔩 **Drill** | Drills vertically to the bottom. |
| ⏱️ **Slowdown** | Slows time for 15 seconds + grants defense. |
| 🍾 **Napalm** | Burns and spreads downwards. |
| ❗ **GAU-8 Cannon** | Strafes blocks vertically downwards. |
| ☢️ **Chain Reactor** | Massive blast, horizontal shockwave + vertical beam. |
| 🔨 **Thor's Hammer** | Strikes before landing, smashes on impact, pierces 2 columns. |
| ⬇️ **Piercing Block** | Ignores obstacles, drops directly to the lowest gap. |
| ☄️ **Meteor Shower** | Randomly bombards 5 spots on the board. |
| ⬜ **Gravity Block** | 10-ton weight, crushes all empty spaces below it. |
| ❇️ **Cross Laser** | Clears the entire row + column, emergency rescue mechanism. |
| 🐦 **Repair Bird** | Press rotate to fill gaps below. |
| 🌑 **Color Wipe** | Clears all blocks of the same color + shakes down. |

**[ 繁中 ]**
| 道具名稱 | 功能說明 |
| :--- | :--- |
| 🧨 **未引爆彈** | 需消行才啟動。 |
| 💣 **B2 炸彈** | 小範圍消除。 |
| 🗡︎ **B3 炸彈** | 中範圍爆破。 |
| 💥 **B4 重型炸彈** | 壓碎 + 大爆破。 |
| 🔩 **鑽頭** | 垂直鑽孔到底部。 |
| ⏱️ **減速器** | 時間減緩 15 秒 + 防禦。 |
| 🍾 **汽油反應彈** | 燃燒並向下擴散。 |
| ❗ **GAU-8 機砲** | 向下掃射方塊。 |
| ☢️ **連鎖反應器** | 大規模爆炸、橫向衝擊波 + 縱向通天。 |
| 🔨 **雷神之槌** | 未到先轟，落地再砸，縱向貫穿兩列。 |
| ⬇️ **穿透方塊** | 無視障礙，直達最底層空洞。 |
| ☄️ **流星雨** | 隨機轟炸場地 5 個點。 |
| ⬜ **重力塊** | 10 噸重壓，將下方空隙全部壓實。 |
| ❇️ **十字雷射** | 消除整行 + 整列，高空緊急救援機制。 |
| 🐦 **修補鳥** | 按旋轉鍵可向下補洞。 |
| 🌑 **同色毀滅** | 消除全場同色方塊 + 震落。 |

**[ 简中 ]**
| 道具名称 | 功能说明 |
| :--- | :--- |
| 🧨 **未引爆弹** | 需消行才启动。 |
| 💣 **B2 炸弹** | 小范围消除。 |
| 🗡︎ **B3 炸弹** | 中范围爆破。 |
| 💥 **B4 重型炸弹** | 压碎 + 大爆破。 |
| 🔩 **钻头** | 垂直钻孔到底部。 |
| ⏱️ **减速器** | 时间减缓 15 秒 + 防御。 |
| 🍾 **汽油反应弹** | 燃烧并向下扩散。 |
| ❗ **GAU-8 机炮** | 向下扫射方块。 |
| ☢️ **连锁反应器** | 大规模爆炸、横向冲击波 + 纵向通天。 |
| 🔨 **雷神之锤** | 未到先轰，落地再砸，纵向贯穿两列。 |
| ⬇️ **穿透方块** | 无视障碍，直达最底层空洞。 |
| ☄️ **流星雨** | 随机轰炸场地 5 个点。 |
| ⬜ **重力块** | 10 吨重压，将下方空隙全部压实。 |
| ❇️ **十字雷射** | 消除整行 + 整列，高空紧急救援机制。 |
| 🐦 **修补鸟** | 按旋转键可向下补洞。 |
| 🌑 **同色毁灭** | 消除全场同色方块 + 震落。 |

---

### ⚡ Special Units | 特殊武裝與附魔 | 特殊武装与附魔

**[ EN ]**
* ⚔️ **Tactical Cross**: Transformable, fires pistons when fully charged.
* 📏 **Extending Rod**: Transforms when rotated (Horizontal 2 ↔ Vertical 4) to fill gaps.
* 🪃 **Boomerang**: Armor-piercing and horizontal slash when fully charged.
* 🟪 **Square Block**: Transforms into a Horizontal 4 block when rotated.
* 🔢 **Number Block**: Clears the corresponding number of lines (e.g., 3 clears 3 lines).
* 🎁 **Mystery Chest**: Obtain a random item upon line clear.
* 🎲 **Random Attack**: Fires a homing red dot to destroy a random block.
* 🅿️ **Enchanted Block P**: Triggers **"Holy Heal"** to fill gaps on the battlefield.
* 🅰️ **Char Attack**: Drops massive pixel-art characters, applying terrain pressure.

**[ 繁中 ]**
* ⚔️ **戰術十字**：可變形，充能滿後發射活塞。
* 📏 **伸縮桿**：旋轉時可變形 (橫2 ↔ 直4) 填補縫隙。
* 🪃 **迴旋鏢**：充能滿後執行破甲與橫向斬擊。
* 🟪 **田字方塊**：旋轉時可變形為橫向 4 格方塊。
* 🔢 **數字方塊**：消除對應數量的行數 (例: 3 即消 3 行)。
* 🎁 **神秘寶箱**：消行獲得隨機道具。
* 🎲 **隨機攻擊**：發射追蹤紅點破壞隨機方塊。
* 🅿️ **附魔方塊 P**：觸發 **「聖光修復」**，填補戰場空洞。
* 🅰️ **字元攻擊**：降落巨大的點陣字元，造成地形壓力。

**[ 简中 ]**
* ⚔️ **战术十字**：可变形，充能满后发射活塞。
* 📏 **伸缩杆**：旋转时可变形 (横2 ↔ 直4) 填补缝隙。
* 🪃 **回旋镖**：充能满后执行破甲与横向斩击。
* 🟪 **田字方块**：旋转时可变形为横向 4 格方块。
* 🔢 **数字方块**：消除对应数量的行数 (例: 3 即消 3 行)。
* 🎁 **神秘宝箱**：消行获得随机道具。
* 🎲 **随机攻击**：发射追踪红点破坏随机方块。
* 🅿️ **附魔方块 P**：触发 **「圣光修复」**，填补战场空洞。
* 🅰️ **字符攻击**：降落巨大的点阵字符，造成地形压力。

---

## 📜 Project Notes & Ethics | 開發者守則 | 开发者守则

**Personal Non-Profit Research | 個人非營利研究 | 个人非营利研究**

* **[ EN ]** This is a personal project for technical research. Please do not use it for commercial profit or advertisements.
* **[ 繁中 ]** 本專案為個人技術研究與邏輯實驗。請勿將其用於任何商業盈利行為或廣告推廣。
* **[ 简中 ]** 本项目为个人技术研究与逻辑实验。请勿将其用于任何商业盈利行为或广告推广。

---
淺色模式+Type E按鍵
![淺色模式](./images/F1.png)

深色模式+Type E按鍵
![深色模式](./images/F2.png)

LCD 模式+Type D按鍵
![LCD 模式](./images/F3.png)

---

> **I layout the logic; AI outlines the strokes.**
> **我佈局邏輯願景，AI 勾勒細節筆觸。**
> **我布局逻辑愿景，AI 勾勒细节笔触。**

---

## ☕ Support Me | 贊助支持 | 赞助支持

👉 **[Support me on Portaly | 前往 Portaly 贊助我](https://portaly.cc/skyuns)**

---
*T-28 Tactical Block: Stacking with logic, clearing with fire.*
