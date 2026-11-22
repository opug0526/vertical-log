# Vertical Log v0.2 (experimental)

Safari向け縦動画カメラ。v0.1と同じIndexedDB `vertical-log-v1` を利用します。

- 既存の撮影・コメント・途中保存
- 連続プレビュー（時刻とコメントを中央表示）
- Canvas + MediaRecorder による実験的な無音動画書き出し

注意：iOS Safariでは canvas.captureStream や MediaRecorder の組み合わせが使えず書き出せない場合があります。iPhone実機で未検証。あんずもじは未収録（代替フォント）。ブラウザデータを消すと保存動画が失われる可能性があります。既存クリップを残すため同じGitHub Pages URLで更新してください。
