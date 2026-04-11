---
title: '【作品紹介】自作のゲーム'
description: 'Astroポートフォリオに追加した、初めての自作ゲームについての解説です。'
pubDate: 'Mar 22 2026'
heroImage: '../../assets/blog-placeholder-1.jpg'
---

## 🎮 ゲームの概要
棒人間を使ったPKゲームです

### 🕹️ 今すぐ遊ぶ
[👉 ここをクリックしてゲームをプレイする](/my-game/index.html)

---

## 🚀 技術的なポイント
制作に使用した技術や、こだわった部分を紹介します。

- **言語:** JavaScript / HTML / CSS3
- **ライブラリ:** なし
- **工夫した点:** - 60fpsで滑らかに動くように調整しました。
  - スマホでも操作できるようにタッチイベントを実装しました。

## 💡 苦労したところ
プログラムの中で特に難しかった部分を、コードブロックを使って説明するとエンジニアらしくなります。

```javascript
// 例：当たり判定のロジック
function checkCollision(player, enemy) {
  return player.x < enemy.x + enemy.width &&
         player.x + player.width > enemy.x &&
         player.y < enemy.y + enemy.height &&
         player.y + player.height > enemy.y;
}