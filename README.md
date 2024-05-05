# README
## これは何？
- カスタムローマ字配列の説明をする際の前提として、AZIKのローマ字テーブルを作る必要があったので作成したリポジトリです。
- AZIKをGoogle日本語入力で実装するためのローマ字テーブルファイルが含まれています。
- AZIKについては [AZIK総合解説書](https://hp.vector.co.jp/authors/VA002116/azik/azikinfo.htm) を参照してください。

## 設定方法
JIS配列キーボード + Google日本語入力IME向けです

1. このリポジトリにある azik_romantable.txt の [Rawファイル](https://raw.githubusercontent.com/toriwasa/azik-roman-table/main/azik_romantable.txt) を開き、名前を付けて保存する
2. Google日本語入力のプロパティを開き、 一般タブ -> キー設定 -> ローマ字テーブル -> 編集 -> 編集 -> インポート... を選択する
3. さきほどダウンロードした azik_romantable.txt を選択する

なお、元に戻す場合は上記手順の「インポート...」を選択したメニューで「インポート...」ではなく「初期値に戻す」を選択すればリセットできます

## ファイル内容
1. 通常のローマ字テーブル(清音 → 濁音)
2. 通常の拗音ローマ字 + 互換キー拗音
3. 通常の小文字ローマ字
4. 促音(っ)、撥音(ん)、長音(ー)
5. 記号系
6. 撥音拡張(an, in, un, en, on系の清音 → 濁音 → 拗音)
7. 二重母音拡張(ai, uu, ei, ou系の清音 → 濁音 → 拗音)
8. ザ行拡張
9. 特殊拡張(短縮入力系)

上記の順序でローマ字テーブルが記載されています。
カスタマイズしたいときに参考にしてください。
