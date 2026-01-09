# 🏋️ Gym Guy

> 第一次进健身房，不应该是紧张的。  
> **Gym Guy 是你的随身健身说明书。**  
> （MVP 共创中：欢迎你把真实反馈变成下一版）

![status](https://img.shields.io/badge/status-MVP-informational)
![platform](https://img.shields.io/badge/platform-iOS%20%7C%20Android%20%7C%20Web-success)

---

## 🚀 立刻体验

- **在线体验（Web / PWA）**：`https://teamwang11.github.io/Gym-Guy-/`
- **进入 App**：`https://teamwang11.github.io/Gym-Guy-/app.html`

> 🌍 **自动中英切换（中文优先）**：会根据设备语言自动切换；右上角可手动切换并记住选择。

---

## ✨ 你能用它做什么？

Gym Guy 面向 **健身新手**，提供「现场立刻能用」的最基础信息：

- 📷 器材识别入口（MVP 版持续迭代）
- 🛡 新手安全提示（以“别受伤”为第一原则）
- 📱 可像原生 App 一样安装到手机（PWA，全屏运行）
- 💬 反馈闭环：你提的每条反馈都会进入 Issues，影响下一版

---

## 📱 安装到手机（像原生 App）

**iPhone（Safari）**
1. 打开：`https://teamwang11.github.io/Gym-Guy-/`
2. 点击「分享」
3. 选择「添加到主屏幕」
4. 桌面点击图标即可全屏运行 ✅

**Android（Chrome）**
1. 打开同上链接
2. 点击「安装应用 / Add to Home Screen」
3. 安装完成 ✅

---

## 💬 反馈与共创（最重要）

- 🐞 报告 Bug / 体验问题
- 💡 提功能点子（越具体越好：你当时在健身房遇到了什么？）
- 🧠 提新手困惑（你不知道的，就是我们要解决的）

👉 **提交反馈（GitHub Issues）**：  
`https://github.com/teamwang11/Gym-Guy-/issues`

---

## 🧩 Roadmap（规划中）

- [ ] 相机识别（Scan）
- [ ] 每个器材的“最短可执行动作建议”
- [ ] 动作示范（图片/短视频）
- [ ] 更强的新手计划生成

---

## 🛠 本地运行（开发者）

纯前端静态站，无需后端。

```bash
python -m http.server 8080
```

然后访问：

- `http://localhost:8080/`（Landing）
- `http://localhost:8080/app.html`（App）

> 注：PWA 安装一般需要 HTTPS；GitHub Pages 已支持。

---

## 📄 License

MIT (如果你还没加 License 文件，也可以先不加)
