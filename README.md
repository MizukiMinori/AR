QRコードに埋め込むURL（完成形）
  https://＜GitHubユーザー名＞.github.io/ar/index.html?img=https://pbs.twimg.com/media/XXXXXXXX.jpg&marker=event01

  img
  → 表示したい画像のURL（Twitter / X上の画像直リンク）

  marker
  → 使用する marker.patt のファイル名（拡張子なし）

GitHub Pages に配置するファイル構成

  /ar
  　├ index.html
  　└ markers/
  　　　└ event01.patt

④ 動作の流れ（確認）

ユーザーが QRコードをiPhoneで読み取る

Safariで index.html が開く

URLパラメータを解析

img → 表示画像

marker → marker.patt

カメラ起動

マーカーを認識

Twitter画像がARで1枚表示

⑤ 実務上の注意点（重要）
Twitter画像URLについて

右クリック → 画像アドレスをコピー

pbs.twimg.com/media/....jpg 形式であること

認証が必要なURLは不可

マーカー印刷

余白を十分取る（最低でも周囲20%）

QRコードとマーカーは 兼用しない

マーカーは単独で大きく印刷
