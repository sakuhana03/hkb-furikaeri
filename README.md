# 振り返りシート（広島北ボーイズ）

選手がスマホで振り返りワークシートに入力し、PDFにしてLINEで弘本トレーナーへ送るためのページです。

- 入力内容は端末にもサーバーにも保存しません。LINEで送ったPDFだけが残ります。
- PDFはブラウザの中で作ります（html2canvas + jsPDF）。
- 送信はスマホの共有メニュー（Web Share API）からLINEを選びます。LINEのトーク内ブラウザで開いた場合は、自動でSafari/Chromeに開き直します。

公開URL: https://sakuhana03.github.io/hkb-furikaeri/
