# Human Synergy Analysis System

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cyberust/HumanSynergyAnalysis/blob/main/HumanSynergyAnalysis_jp.ipynb)

## 概要

このリポジトリは、特定の人物たちのプロフィール情報（経歴、スキル、専門分野など）を基に、チームを組んだ際の相乗効果（シナジー）を多角的に分析・予測・可視化するためのシステムです。

分析は以下の要素を含みます：
- スキル、経験、ネットワークのプロフィール分析
- スキル補完性、経験、ネットワーク効果、文化的多様性に基づくシナジー計算
- チームの将来的な成長を予測する動的システムモデリング
- 価値貢献度を測るゲーム理論分析（シャプレー値）
- ビジネス指標（ROI、NPVなど）の財務予測
- モンテカルロシミュレーションによる不確実性評価

## 使い方

1.  上記の "Open in Colab" バッジをクリックして、Google Colabでノートブックを開きます。
2.  **（推奨）** ご自身のGoogleドライブの「マイドライブ」直下に、分析対象者のプロフィールを記述した以下のテキストファイルをご準備ください。
    - `arale_cohen_profile.txt`
    - `yanay_geva_profile.txt`
    - `yasuyuki_sakane_profile.txt`
    
    ※ ファイルが存在しない場合でも、コード内に記述されたサンプルデータを用いて分析は実行されます。
3.  Google Colabのメニューから「ランタイム」>「すべてのセルを実行」を選択します。
4.  Googleドライブへのアクセス許可を求めるポップアップが表示されたら、許可してください。
5.  分析が実行され、結果のグラフがノートブック上に出力されます。
6.  最終的な分析レポート（.mdファイル）が、ご自身のGoogleドライブの「マイドライブ」直下に保存されます。

## ライセンス

このプロジェクトはMITライセンスの下で公開されています。
