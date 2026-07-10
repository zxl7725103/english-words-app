# 小学英语单词学习

适合小学生的英语单词记忆 PWA 应用。

## 功能

- **102 个单词**：动物、食物、家庭、颜色四大分类
- **主动回忆学习**：先看释义回忆拼写，再揭晓答案
- **语音朗读**：基于 Web Speech API 自动发音
- **拼写挑战**：字母方块游戏，计时 + 三星评级
- **进度追踪**：学习统计、成就徽章、每周活动图
- **离线可用**：PWA + Service Worker，断网也能学
- **数据持久化**：localStorage 保存学习进度

## 部署到 GitHub Pages

1. 在 GitHub 上创建一个新仓库 `english-words-app`
2. 执行以下命令：

```bash
cd app
git remote add origin https://github.com/zxl7725103/english-words-app.git
git push -u origin main
```

3. 在仓库 Settings → Pages 中，Source 选 `main` 分支，目录选 `/ (root)`
4. 几分钟后访问 `https://zxl7725103.github.io/english-words-app/`

## 在手机上安装

用安卓 Chrome 打开上面的网址，点击菜单 → "安装应用" 或 "添加到主屏幕"即可。