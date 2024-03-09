# all
# 題名「共感的な応答を生成できる対話システム」

- emotion → 感情分類器について
  - data →「wrime:主観と客観の感情強度を付与した日本語データセット」
  - multi_label → pos_weightあり
  - single_label → pos_weightなし
  
- dialogueact→対話行為分類器について
  - 10class_no_weight →　10クラス分類でclass_weightなし
  - 10class_weight → 10クラス分類でclass_weightあり
  - 9class → 9クラス分類でclass_weightなし

- dialogueact_emotion→学習データに感情ラベルを付与
  - data → 「JAISTタグ付き自由対話コーパス」

- jpempathetic_dialogue→jpempatheticコーパスに対話行為ラベルを付与
  - data → dataset「Empathetic Dialogueコーパスの日本語版」
  
- dialogueact system→応答文生成モデル
  - data → 「JAISTタグ付き自由対話コーパス」に感情ラベルを付与したもの
  - output..10 → 各フィルタリングでの学習曲線
  - nasinasi → 学習フィルタリングなし，発話時フィルタリングなしの学習結果
  - arinasi → 学習フィルタリングあり，発話時フィルタリングなしの学習結果
  - nasiari → 学習フィルタリングなし，発話時フィルタリングありの学習結果
  - ariari → 学習フィルタリングあり，発話時フィルタリングありの学習結果
 
  - 主観評価 - 協力者2名による評価(kappa係数を出している)
  - 結果 - テストデータで応答文を生成した結果
  


