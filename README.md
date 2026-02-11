# Keisuke Data Lab
**Strategic Data Science & Decision Support Systems (DSS)**

[![Portfolio Status](https://img.shields.io/badge/Status-Active_Seeker-success)](https://github.com/keisuke-data-lab)
[![Role](https://img.shields.io/badge/Role-Data_Scientist_%7C_Tech_Lead-blue)](https://github.com/keisuke-data-lab)

> **"Bridging the Gap between Engineering and Business Strategy"**
> ビジネスの不確実性を、数理モデルとシミュレーション技術によって「計算可能なリスク」へと変換する。

---

## 🚨 Business Value / Concept
### 「経験と勘」の経営から、「データと論理」の意思決定へ
現代の組織課題（DXプロジェクトの炎上、採用バイアス、組織崩壊）の多くは、静的なデータ分析だけでは解決できません。
本ラボでは、**システム思考（System Dynamics）** と **データサイエンス** を融合させた **意思決定支援システム (DSS)** を構築しています。

私のソリューションは、以下の3点においてビジネスインパクトを創出します：
1.  **リスクの金額換算 (Financial Impact):** 技術的負債やバイアスを「損失額（PLインパクト）」として可視化し、投資判断を支援。
2.  **動的な将来予測 (Simulation):** 過去の分析だけでなく、「もしこうしたら？」という未来のシナリオ分岐を提示。
3.  **合意形成の加速 (Consensus Building):** 複雑な数理モデルを直感的なWeb UIに落とし込み、非エンジニアの意思決定をサポート。

---

## 🏆 Featured Solutions (Hero Projects)
経営層・PM・人事責任者が抱える課題を解決するための、即戦力となるシミュレーション・アプリケーション群です。

### 1. [Gender Bias ROI Simulator](https://github.com/keisuke-data-lab/gender-bias-simulation)
**採用バイアスによる「組織IQ損失」の定量化**
[![Open App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://gender-bias-simulation-efntmryjj8pth6vr86vpwn.streamlit.app/)
* **Target:** CHRO、採用責任者、経営企画
* **Business Issue:** 「女性の応募が少ない」というパイプライン問題を言い訳にした、男性偏重採用の常態化。
* **Solution:** 応募者比率と採用基準（バイアス）を変数とした数理モデルにより、無理な比率調整が組織の平均生産性をどれだけ毀損するかを算出。
* **Tech Stack:** `Python` `SciPy` `Streamlit` (切断正規分布モデル, 逆ミルズ比)

### 2. [Strategic Org Resilience Simulator](https://github.com/keisuke-data-lab/strategic-org-resilience)
**「離職の連鎖」と組織崩壊の予兆検知**
[![Open App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://strategic-org-resilience-9ejs4h2kqqpx5zdwuygri9.streamlit.app/)
* **Target:** 人事部長、組織開発担当
* **Business Issue:** ハイパフォーマーの離職が引き起こす、残存メンバーへの業務負荷集中と連鎖離職（デススパイラル）。
* **Solution:** 業務負荷とストレス耐性を変数としたエージェントベース・シミュレーションにより、組織が崩壊する「ティッピング・ポイント（臨界点）」を特定。
* **Tech Stack:** `Python` `Streamlit` `NetworkX` (複雑系ネットワーク分析)

### 3. [DX Project Budget Simulator](https://github.com/keisuke-data-lab/dx-project-failure-structure)
**技術的負債の財務インパクト可視化**
[![Open App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://dx-project-failure-structure-nl4ewadvnnug5haxtsfa2u.streamlit.app/)
* **Target:** CIO、DX推進本部長、PMO
* **Business Issue:** 「あと数人追加すれば間に合う」という安易な判断による、プロジェクト赤字の拡大（ブルックスの法則）。
* **Solution:** 工数遅延をリアルタイムで「累積赤字額（円）」に換算。手戻りコストと品質コストを分解し、損益分岐点をシミュレート。
* **Tech Stack:** `Python` `Plotly` `Pandas` (システムダイナミクス)

### 4. [DX Risk Diagnostic (Project Omen)](https://github.com/keisuke-data-lab/dx-risk-diagnostic)
**過去の炎上判例に基づくガバナンス診断**
[![Open App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://dx-risk-diagnostic-etshqp5dvhv6pwbvzacarb.streamlit.app/)
* **Target:** 内部監査室、法務、リスク管理担当
* **Business Issue:** プロジェクト開始前の構造的欠陥（丸投げ、要件未決）の見落とし。
* **Solution:** (事例ベース推論 / CBR)

---

## 🔬 Advanced Analytics & Research
Jupyter Notebookを用いた、より詳細な統計解析・因果推論の成果物です。

| Project Name | Domain | Description |
| :--- | :--- | :--- |
| **[HR Attrition Causal Analysis](https://github.com/keisuke-data-lab/hr-attrition-causal-analysis)** | HR Tech | 離職要因の因果構造分析（相関関係ではなく因果関係の特定） |
| **[Human Capital ROI Analysis](https://github.com/keisuke-data-lab/human-capital-roi-analysis)** | Finance | 人的資本投資のリターン（ROI）計測モデルの構築 |
| **[Student Retention Analysis](https://github.com/keisuke-data-lab/student-retention-analysis)** | Education | マクロ経済要因が学生の退学率に与える影響の計量経済学的分析 |

---

## 💻 Technology Stack & Philosophy

私が技術を選定する基準は、「最新であるか」ではなく**「ビジネスの意思決定に最速で貢献できるか」**です。

* **Python (Core Logic):**
    * 複雑な確率統計処理（SciPy）や行列演算（NumPy）を、プロダクションレベルの堅牢性で実装するため。
* **Streamlit (UI/UX):**
    * 経営層がパラメータを操作し、リアルタイムで結果を確認できる「Interactive Dashboard」を、最短工数で構築するため（React/Vue等のOver-engineeringを避ける）。
* **Plotly / Seaborn (Visualization):**
    * 単なるグラフではなく、意思決定に必要な「閾値」や「リスク領域」を明示し、インサイトを即座に伝達するため。
* **System Dynamics / Agent-Based Model:**
    * 静的な相関分析では見えない、時間経過に伴う「非線形なリスク（急激な崩壊など）」をモデル化するため。

---

## 👤 Author / Contact
**Keisuke Nakamura**
*Data Scientist / Full-Stack Engineer / Strategic Consultant*

ビジネス課題の構造化から、数理モデルの実装、そして経営層へのプレゼンテーションまでを一気通貫で担当します。

* **GitHub:** [https://github.com/keisuke-data-lab](https://github.com/keisuke-data-lab)
