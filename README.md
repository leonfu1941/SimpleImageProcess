# OpenCV
simple image process based on OpenCV and MFC frame

## ソフト機能
### バージョン: 1.0beta
- 静止的な処理
  -  画像ファイルの読み込みと保存
  -  画面輝度調整
  -  コントラスト調整
  -  ヒストグラム平坦化
  -  露出補正
  -  Gamma
  -  画面を強める
  -  Laplace
  -  ホワイトバランス調整
  -  シャープ
- 動的な処理
  -  カメラからの映像を撮った
  -  カメラのパラメターの読み込みと保存
  -  露出補正
  -  ゲイン
  -  フォーカス調整
      - 自動調整
  -  飽和度調整
  -  自動ホワイトバランス調整

### バージョン: 1.1 追加の機能:
- 動的な処理
  - 複数のカメラが連携しての場合、特定のカメラを指定する
  - 動画捕捉(.avi)
  - datamatrixを読み込む

### バージョン: 2.0 追加の機能:
- 静止的な処理
  - モルフォロジー
  - 二値化処理
  - Canny
  - フィルター
    - filter2D
    - 平均値フィルター
    - gaussian
    - sobel
    - 膨張・収縮
    - 直線を検出する
    - ...
- システム
  - 画像フェイル/コントロールフェイルをロードする方式
    - フォルダからファイルをソフトにドラッグ＆ドロップ
  - パラメータの調整パネル

### バージョン: 2.1 追加の機能:
- システム
  - 同じ処理方法とパラメータで違う画像に対する可能です
  - 処理順番中にある処理パラメータを修正する可能です
  - 個別で画像を出力する可能です

### バージョン: 2.2 ~ 2.3
- システム
  - ソフトの安定性改善
