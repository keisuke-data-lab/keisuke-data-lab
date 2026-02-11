# Keisuke Data Lab
**Strategic Data Science & Decision Support Systems (DSS)**

[![Portfolio Status](https://img.shields.io/badge/Status-Active_Seeker-success)](https://github.com/keisuke-data-lab)
[![Role](https://img.shields.io/badge/Role-Data_Scientist_%7C_Tech_Lead-blue)](https://github.com/keisuke-data-lab)

> **"Bridging the Gap between Engineering and Business Strategy"**
> ビジネスの不確実性を、数理モデルとシミュレーション技術によって「計算可能なリスク」へと変換する。

---

## 🚨 Business Value / Concept
### 「経験と勘」の経営から、「構造と論理」の意思決定へ
現代の組織課題（目標設定の歪み、採用バイアス、組織崩壊）の多くは、静的なデータ分析だけでは解決できません。
本ラボでは、**システム思考（System Dynamics）** と **データサイエンス** を融合させ、内生的な実績データに外生マクロ変数を組み合わせた **意思決定支援システム (DSS)** を構築しています。

私のソリューションは、以下の3点においてビジネスインパクトを創出します：
1.  **構造的欠陥の検定 (Structural Audit):** 慣習やバイアスに基づく意思決定を数理モデルで検定し、リスクを定量化。
2.  **動的な将来予測 (Simulation):** 過去の分析だけでなく、「パラメータ変化に伴う臨界点（Tipping Point）」を提示。
3.  **合意形成の加速 (Consensus Building):** 複雑な数理アルゴリズムをインタラクティブなUIに落とし込み、意思決定をサポート。

---

## 🏆 Featured Solutions (Hero Projects)
経営層・テックリードが抱える不透明な課題を、数理モデルでハックするシミュレーション群です。

### 1. [Gender Bias ROI Simulator](https://github.com/keisuke-data-lab/gender-bias-simulation)
**採用バイアスによる「組織生産性毀損」の定量化**
[![Open App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://gender-bias-simulation-efntmryjj8pth6vr86vpwn.streamlit.app/)
* **Target:** CHRO、採用責任者、テックリード
* **Issue:** 応募者母集団の属性比率を無視した、選考基準（バイアス）のブラックボックス化。
* **Solution:** 応募者比率と採用基準を変数とした数理モデルにより、バイアスが組織の平均生産性をどれだけ毀損するかを算出。
* **Tech Stack:** `Python` `SciPy` `Streamlit` (切断正規分布モデル, 逆ミルズ比による推計)

### 2. [Market Capacity Audit Algorithm](https://github.com/keisuke-data-lab/market-based-target-simulator)
**外生マクロ指標に基づく目標妥当性の統計的検定**
[![Open App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://market-based-target-simulator-zwqtvkegecarptxsefwrrk.streamlit.app/)
* **Target:** 経営企画、事業開発、データサイエンティスト
* **Issue:** 組織内の実績（内生変数）のみに依存した目標設定と、市場容量（外生変数）との構造的ミスマッチ。
* **Solution:** e-Stat（人口推計）やマクロ経済指標から**市場容量指数 (MCI)** を算出。目標乖離度を正規化シグモイド関数で評価し、リソースの**損失コスト (Wasted Cost)** を試算。
* **Tech Stack:** `Python` `Streamlit` `Altair` (MCIアルゴリズム, 非線形リスク評価モデル)

### 3. [Strategic Org Resilience Simulator](https://github.com/keisuke-data-lab/strategic-org-resilience)
**「離職の連鎖」と組織崩壊の臨界点検知**
[![Open App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://strategic-org-resilience-9ejs4h2kqqpx5zdwuygri9.streamlit.app/)
* **Target:** 人事部長、組織開発マネージャー
* **Issue:** ハイパフォーマーの離職に伴う負荷集中が引き起こす、ドミノ倒し的な連鎖離職（デススパイラル）。
* **Solution:** 業務負荷とストレス耐性を変数としたエージェントベース・シミュレーション。上記「MCI検定」の結果（目標乖離）を業務負荷パラメータとして接続し、組織崩壊のデッドラインを特定。
* **Tech Stack:** `Python` `Streamlit` `NetworkX` (複雑系ネットワーク分析)

---

## 🔬 Advanced Analytics & Research
Jupyter Notebookを用いた、より詳細な統計解析・因果推論の成果物です。

| Project Name | Domain | Description |
| :--- | :--- | :--- |
| **[HR Attrition Causal Analysis](https://github.com/keisuke-data-lab/hr-attrition-causal-analysis)** | HR Tech | 離職要因の因果構造分析（相関ではなく因果関係の特定） |
| **[Human Capital ROI Analysis](https://github.com/keisuke-data-lab/human-capital-roi-analysis)** | Finance | 人的資本投資のリターン（ROI）計測モデルの構築 |
| **[Student Retention Analysis](https://github.com/keisuke-data-lab/student-retention-analysis)** | Education | マクロ経済要因が退学率に与える影響の計量経済学的分析 |

---

## 💻 Causal Connectivity & Technology
単一のダッシュボード提供に留まらず、各プロジェクトの出力を次の分析の入力とする**因果パラメータ接続（Causal Connectivity）**を重視しています。

1. **[Target Audit]** で算出された構造的な目標乖離率（Overload）を算出。
2. その値を **[Org Resilience]** の業務負荷増分パラメータとして入力し、離職の連鎖シミュレーションを実行。
3. **[Gender Bias Simulator]** で、離職に伴う欠員補充時の採用バイアスによる組織IQ（生産性）損失リスクを評価。

### Technology Stack & Philosophy
* **Python (Core Logic):** プロダクションレベルの確率統計処理（SciPy）や行列演算（NumPy）を、堅牢なロジックで実装。
* **Streamlit (Decision Interface):** 現場の意思決定者がパラメータを操作し、リアルタイムで感度分析（"What-if"分析）を行うためのUI。
* **Non-linear Modeling:** シグモイド関数（ロジスティック曲線）等を用い、線形分析では捉えきれない**臨界点（Tipping Point）**をモデル化。

---

## 👤 Author / Contact
**Keisuke Nakamura**
*Data Scientist / Tech Lead / Strategic Consultant*

ビジネス課題の構造化から、数理アルゴリズムの実装、そして実証的な意思決定支援までを一気通貫で担当します。

* **GitHub:** [https://github.com/keisuke-data-lab](https://github.com/keisuke-data-lab)
