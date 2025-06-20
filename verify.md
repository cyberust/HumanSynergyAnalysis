実行完了後、生成されたグラフを確認したい場合は、新しいセルで以下のように入力して個別に表示させてください。
これにより、Colabのフリーズ問題を回避しつつ、好きなグラフを安全に確認できます。

グラフの個別表示（例）
Python

# シナジーヒートマップを表示する場合
results['figures']['synergy_heatmap'].show()

# 成長軌道を表示する場合
results['figures']['growth_trajectory'].show()

# シャプレー値を表示する場合
results['figures']['shapley_values'].show()
