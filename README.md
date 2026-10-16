# 跨年快乐 · Happy New Year 🎆

**在线体验 / Live demo：<https://yanggu11.github.io/Happy_new_year/>**

一个跨年祝福网页：打开后显示新年倒计时与祝福语，点击屏幕任意位置即可放烟花，并配有背景音乐。

A New Year's greeting page with a countdown and greeting text. Click anywhere to launch interactive canvas fireworks, with background music.

## 功能 / Features

- 新年倒计时与祝福文字 · Countdown and greeting text
- 点击屏幕发射烟花，支持自动发射 · Click to launch fireworks, or turn on auto-launch
- 设置面板：烟花类型、大小、画质、天空照明、全屏等 · Settings panel for shell type, size, quality, sky lighting, fullscreen and more
- 首次点击后播放背景音乐 · Background music starts on the first click
- 自动适配手机和桌面端 · Works on mobile and desktop

## 技术 / Tech

HTML · CSS · JavaScript · Canvas 2D · jQuery

## 本地运行 / Run locally

```bash
git clone https://github.com/Yanggu11/Happy_new_year.git
cd Happy_new_year
python3 -m http.server 8000   # 然后访问 http://localhost:8000
```

## 致谢 / Credits

烟花动画引擎（`files/js/script.js`、`Stage`、`MyMath`）来自 Caleb Miller 在 CodePen 上开源的 *Fireworks* 作品，版权归原作者所有。

The fireworks engine (`files/js/script.js`, `Stage`, `MyMath`) comes from Caleb Miller's open-source *Fireworks* pen on CodePen; all rights to it belong to the original author.
