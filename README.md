# Voice Math Game - Fixed & High Speed

視覚的な数式と音声による追加指示を組み合わせて解く、新感覚の計算トレーニングゲームです。
目で見ている情報に、耳から入る情報を瞬時に統合して計算する「マルチモーダル認知トレーニング」としての活用を想定しています。

## ✨ 特徴
* **ハイブリッド計算**: 画面上の数式（例：1+2）に対し、音声指示（例：「5を足して」）を加えて最終的な答えを導き出します。
* **完全ハンズフリー操作**: 音声認識（Web Speech API）により、開始からリスタートまで声だけで操作可能です。
* **デバイス最適化**: PC、iPad、スマートフォン（Android/iOS）の各画面サイズに対応したレスポンシブ設計です。
* **高レスポンス**: 音声合成の速度を速め、テンポよく次々に問題が出題されるハイスピード仕様になっています。
* **アクセシビリティ**: 画面タップが困難な状況や、リハビリテーション、知育などのトレーニングツールとしても適しています。

## 🛠 動作環境
ブラウザの **Web Speech API** および **Web Audio API** を使用しています。
* **推奨ブラウザ**: Google Chrome, Microsoft Edge, Safari (iOS/macOS)
* **必須条件**: マイクの使用許可が必要です。また、セキュリティ上の制約により、GitHub Pagesなどの **HTTPS環境** でのみ動作します。

## 🎮 遊び方
1.  **開始**: 「GAME START」ボタンをタップして開始します。
2.  **出題**: 画面に式が表示されますが、すぐには答えないでください。
3.  **音声指示**: コンピュータが「〇〇を足して（引いて）」と指示を出します。
4.  **回答**: 最終的な計算結果を声に出して答えてください。
5.  **終了**: 90秒が経過すると「終了」と表示され、スコアが読み上げられます。
6.  **リスタート**: 「スタート」または「もう一回」と話しかけることで、再度挑戦できます。

## 🔧 技術スタック
* **フロントエンド**: HTML5, CSS3, JavaScript (Vanilla JS)
* **音声認識**: [Web Speech API (SpeechRecognition)](https://developer.mozilla.org/ja/docs/Web/API/SpeechRecognition)
* **音声合成**: [Web Speech API (SpeechSynthesis)](https://developer.mozilla.org/ja/docs/Web/API/SpeechSynthesis)
* **効果音**: [Web Audio API](https://developer.mozilla.org/ja/docs/Web/API/Web_Audio_API)（正解時のビープ音を動的生成）

## 📄 ライセンス
このプロジェクトは **MITライセンス** の下で公開されています。詳細は [LICENSE](LICENSE) ファイルをご覧ください。
