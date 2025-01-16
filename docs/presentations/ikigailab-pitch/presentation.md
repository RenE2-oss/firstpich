---
marp: true
theme: default
paginate: true
style: |
  section {
    background-color: #F5F5F5;
    font-family: 'Helvetica Neue', 'Hiragino Kaku Gothic ProN', 'ヒラギノ角ゴ ProN W3', 'Hiragino Kaku Gothic Pro', 'ヒラギノ角ゴ Pro W3', 'メイリオ', Arial, sans-serif;
    padding: 40px;
  }
  h1:not(.title h1) {
    color: #333333;
    font-size: 36px;
  }
  .title h1 {
    font-size: 48px;
    border-bottom: 2px solid #333333;
  }
  h2 {
    color: #4A4A4A;
    font-size: 36px;
  }
  p, li {
    color: #4A4A4A;
    font-size: 32px;
    line-height: 1.6;
  }
  strong {
    color: #333333;
    font-weight: bold;
  }
  .gray {
    color: #888888;
  }
  .flow {
    font-size: 36px;
    line-height: 1.8;
    margin: 40px 0;
  }
  blockquote {
    font-size: 36px;
    line-height: 1.8;
    margin: 40px 0;
  }
  table {
    width: 100%;
    border-collapse: collapse;
    margin: 20px 0;
  }
  th, td {
    border: 1px solid #4A4A4A;
    padding: 12px;
    font-size: 28px;
  }
  th {
    background-color: #4A4A4A;
    color: #ffffff;
  }
  td {
    background-color: rgba(255, 255, 255, 0.9);
  }
  img.center {
    display: block;
    margin: 20px auto;
    max-width: 80%;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
  }
  video {
    max-width: 80%;
    margin: 20px auto;
    display: block;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
  }
---

<!-- _class: title -->
# AIエージェントオーケストレーション
## 神威/KAMUIの可能性

---

> 流れ:
> **1. 導入**
> <span class="gray">2. 現状の課題</span>
> <span class="gray">3. 解決策</span>
> <span class="gray">4. 具体例</span>
> <span class="gray">5. 締めくくり</span>

---

## 1.1 問題提起
- **生成AI利用の課題**
  - ツールの切り替え大変では？

![center](../../assets/images/manytool.png)

---

- で次は？

![center](../../assets/images/boltdemo.png){: style="margin-bottom: -20px;"}

---

> 流れ:
> <span class="gray">1. 導入</span>
> **2. 現状の課題**
> <span class="gray">3. 解決策</span>
> <span class="gray">4. 具体例</span>
> <span class="gray">5. 締めくくり</span>

---

## 2.1 直列型AIエージェントの限界
- タスクごとに生成AIツールの切り替え大変
- 全体感が掴めない
- 大規模生成は難しい

![center](../../assets/images/promptchain.png)

---

> 流れ:
> <span class="gray">1. 導入</span>
> <span class="gray">2. 現状の課題</span>
> **3. 解決策**
> <span class="gray">4. 具体例</span>
> <span class="gray">5. 締めくくり</span>

---

## 3.1 AIエージェントオーケストレーション
- **基本的な仕組み**
  - オーケストレーターが指示出し
  - 計画書をもとに複数のエージェントが並列実行

![center](../../assets/images/orchestrator.png)

---

<video controls width="100%" loop preload="auto">
  <source src="../../assets/videos/lotofmarpx4.mp4" type="video/mp4">
  お使いのブラウザは動画タグをサポートしていません。
</video>

---

<video controls width="100%" loop preload="auto">
  <source src="../../assets/videos/lotofmarpoutx2.mp4" type="video/mp4">
  お使いのブラウザは動画タグをサポートしていません。
</video>

---

# 3.2 解決できる課題

- **効率的な実行**
  - 全体最適化されたタスク実行
  - 計画的なエージェント配置
- **並列処理の実現**
  - 同時実行による大量生成

---

> 流れ:
> <span class="gray">1. 導入</span>
> <span class="gray">2. 現状の課題</span>
> <span class="gray">3. 解決策</span>
> **4. 具体例**
> <span class="gray">5. 締めくくり</span>

---

## 4.1 都市計画への活用
- **統一的なコンテンツ生成**
  - 資料、画像、動画の一括生成
  - 時間とコストの大幅削減

![center](../../assets/images/xlink.png)

---

# 4.2 業務マニュアル・研修資料の作成

- **一括生成による効率化**
  - 手順書、マニュアル、研修スライド生成
  - 全体感の掴みやすさ

---

<video controls width="100%" loop preload="auto">
  <source src="../../assets/videos/shinjin.mp4" type="video/mp4">
  お使いのブラウザは動画タグをサポートしていません。
</video>

---

> 流れ:
> <span class="gray">1. 導入</span>
> <span class="gray">2. 現状の課題</span>
> <span class="gray">3. 解決策</span>
> <span class="gray">4. 具体例</span>
> **5. 締めくくり**

---

## さあ、AIエージェントオーケストレーションを始めましょう！