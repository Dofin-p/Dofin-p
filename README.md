<div align="center">

# Backend & Signal Processing Engineer 🚀
**筑波技術大学 情報科学コース 2年 | 音響知覚研究 × 業務効率化ツール開発**

日常の煩雑な作業を自動化するツール、Webサービスの開発や、空間音響・音響知覚向上の研究に取り組んでいます。

---

### 🛠 Tech Stack & Tools
**⚙️ Backend & Logic**

<img src="https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
<img src="https://img.shields.io/badge/springboot-%236DB33F.svg?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot" />
<img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" alt="Python" />

**🗄️ Database**

<img src="https://img.shields.io/badge/postgresql-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />

**🌐 Frontend**

<img src="https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E" alt="JavaScript" />
<img src="https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
<img src="https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />

**🔧 DevOps & Tools**

<img src="https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white" alt="Git" />

---
</div>

### 🚀 Featured Projects (代表作)
私が課題解決のために設計・開発したプロダクトです。詳しくはそれぞれのリポジトリのREADME.mdをご参照ください。

| プロジェクト名 | 概要・解決した課題 | 技術スタック |
| :--- | :--- | :--- |
| **[Sound Training Site](https://github.com/Dofin-p/Sound-trainnningSite)** | 補聴器ユーザーの「音の前後感」知覚課題に着目し、Webブラウザ上で空間音響トレーニングと研究データ収集ができるシステムを構築。単純なパンニングでなくEQ調整を組み合わせた独自アルゴリズムで前後感を強調。 | Vanilla JS (Vite), Web Audio API (HRTF), Three.js |
| **[Visual Sort Suite](https://github.com/Dofin-p/Visualsort-suite)** | 「データ量・アルゴリズムの違いが処理時間にどう影響するか」を視覚的に検証するシミュレータ。Promise等の非同期処理でUIをフリーズさせずに5種のソートアニメーションを描画。 | Vanilla JS, HTML/CSS |

---

### 🔬 Academic Research
**テーマ：補聴器ユーザーの音響知覚・空間音響**

* **背景:** 補聴器ユーザーが日常生活で「音の方向（特に前後感）」を知覚しづらいという課題を発見し、研究・システム開発の両面からアプローチ。
* **実装アプローチ:** `Web Audio APIのPannerNode`（HRTFベース）に加えて、EQ調整で耳の錯覚を利用した前後感の強調アルゴリズム（`FrontBackTestManager.js`）も実装した。
* **設計の工夫:** 音声処理ロジック（`AudioManager.js`）とUI・ゲームロジックを完全分離し、保守性と将来的なテスト拡張を考慮したモジュール設計を採用。


