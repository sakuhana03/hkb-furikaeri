# 振り返りシート（広島北ボーイズ）

選手がスマホで振り返りワークシートに入力し、PDFにしてLINEで弘本トレーナーへ送るためのページです。

- 入力内容はその端末のブラウザにだけ保存されます。サーバーには送信しません。
- PDFはブラウザの中で作ります（html2canvas + jsPDF）。
- 送信はスマホの共有メニュー（Web Share API）からLINEを選びます。共有に対応していない端末では、PDFを保存してLINEのファイル添付で送ります。

公開URL: https://sakuhana03.github.io/hkb-furikaeri/
