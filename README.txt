R448A CoolProp 8.0.0 スマホ計算ページ

必要ファイル（同じフォルダに置く）
- index.html（このパッケージ）
- coolprop.js（CoolProp 8.0.0 公式 JavaScript binary）
- coolprop.wasm（CoolProp 8.0.0 公式 JavaScript binary）

公式配布:
https://sourceforge.net/projects/coolprop/files/CoolProp/8.0.0/Javascript/

使い方:
1. CoolProp公式から coolprop.js と coolprop.wasm をダウンロード。
2. index.html と同じフォルダに置く。
3. GitHub Pages等のHTTPS Webサーバーに3ファイルを配置。
4. スマホで index.html を開く。
5. 「-40～+50℃ 19点を計算」を押す。
6. 25℃ Honeywell照合を確認。
7. 「CSVを保存」で結果を出力。

注意:
- file:// で直接開くのではなくHTTPSサーバーで配信してください。
- .wasm は application/wasm MIME typeで配信される必要があります。
- Excelへ採用する前に25℃既知値と照合してください。
