# WWMscreensaver
Wherewindsmeetscreensaver
# 燕雲十六聲｜武俠風螢幕保護程式（Windows Screensaver）

> 一起在螢幕上重現「雪落燕雲」與「橋上孤影」的武俠氛圍 🌨️🌉  

這是一個以《燕雲十六聲》風格為靈感製作的 **Windows 螢幕保護程式**，  
使用 **C# + WPF** 實作成 `.scr`，安裝後即可在 Windows 中選擇使用。

> ⚠️ 注意：本專案為個人粉絲向創作，與官方無任何關係，  
> 所有遊戲相關名稱、世界觀等智慧財產權屬原權利人所有。

---

## 🎨 功能特色

- 兩個武俠主題場景：
  - **雪落燕雲**：風雪中的邊塞城樓與飄落雪花
  - **橋上孤影**：河面倒影、孤身剪影立於橋上
- 緩慢流動的 **雪花粒子特效**
- 場景之間會 **淡入淡出切換**
- 右下角武俠資訊框：
  - 「燕雲十六聲」標題
  - 隨機輪播的武俠風句子
  - 24 小時制現在時間（HH:mm）
- 滑鼠移動 / 任意按鍵 → 結束螢幕保護程式

---

## 🧩 專案結構

```text
YanYunScreensaver/
  Assets/
    SnowScene.jpg        # 雪落燕雲 場景底圖
    BridgeScene.jpg      # 橋上孤影 場景底圖
    Logo.png             # 遊戲或自製 Logo（可選）
  YanYunScreensaver.sln  # Visual Studio 解決方案
  YanYunScreensaver/
    App.xaml
    App.xaml.cs
    MainWindow.xaml
    MainWindow.xaml.cs
    ...
  README.md
