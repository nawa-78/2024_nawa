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

