# 第三者ソフトウェアのライセンス / Third-Party Licenses

FileManagerExplorer（以下「本ソフトウェア」）は、次の第三者ソフトウェアを利用しています。  
これらの部分には、本ソフトウェアのライセンス（[LICENSE.md](LICENSE.md)）ではなく、それぞれのライセンスが適用されます（LICENSE.md 第8条）。

FileManagerExplorer uses the third-party software listed below.  
Each component is governed by its own license, which takes precedence over LICENSE.md for that component.

各ライブラリの著作権表示とライセンス全文は、配布物に同梱しています。各プロジェクトのリポジトリでも確認できます。

## 一覧

### アプリケーションが利用する外部ライブラリ

| 名称 | バージョン | 用途 | ライセンス | 入手先 |
|---|---:|---|---|---|
| tkinterdnd2 | 0.6.4 | ドラッグ＆ドロップ | MIT License（同梱のtkdndは別途ライセンスを確認） | https://github.com/Eliav2/tkinterdnd2 |
| Send2Trash | 2.1.0 | ゴミ箱へ移動 | BSD-3-Clause | https://github.com/arsenetar/send2trash |
| Pillow | 13.0.0 | 画像のプレビュー・サムネイル・EXIF | MIT-CMU（HPND） | https://github.com/python-pillow/Pillow |
| cryptography | 50.0.2 | 暗号化フォルダー | Apache-2.0 または BSD-3-Clause | https://github.com/pyca/cryptography |
| pypdf | 6.21.4 | PDFのメタデータ削除 | BSD-3-Clause | https://github.com/py-pdf/pypdf |

### 実行環境・ビルドに使うソフトウェア

| 名称 | 用途 | ライセンス | 入手先 |
|---|---|---|---|
| Python（tkinterを含む） | 実行環境 | PSF License | https://www.python.org/ |
| Tcl/Tk | tkinterのGUI | Tcl/Tk License | https://www.tcl.tk/ |
| PyInstaller | EXEの作成 | GPL-2.0-or-later（ブートローダー例外あり） | https://github.com/pyinstaller/pyinstaller |
| Inno Setup | インストーラーの作成 | Inno Setup License | https://jrsoftware.org/isinfo.php |

## ライセンスに関する注意事項

各ライブラリおよびソフトウェアのライセンスは、それぞれの条件に従います。

本ソフトウェアのライセンス（LICENSE.md）は、第三者ソフトウェアのライセンスを変更・上書きするものではありません。

また、EXEにはビルド環境や設定に応じて、上記以外のソフトウェアが同梱される場合があります。同梱されるコンポーネントについても、それぞれのライセンス条件を確認してください。

## ライセンス全文

配布物には、使用している第三者ソフトウェアのライセンス全文および必要な著作権表示を同梱してください。

ライセンス全文は、インストールしたパッケージ内の `site-packages` 以下にある `LICENSE` などのファイル、または各プロジェクトのリポジトリで確認できます。

| ライセンス | 全文の入手先 |
|---|---|
| MIT License | https://opensource.org/license/mit |
| BSD-3-Clause | https://opensource.org/license/bsd-3-clause |
| MIT-CMU（HPND） | https://github.com/python-pillow/Pillow/blob/main/LICENSE |
| Apache-2.0 | https://www.apache.org/licenses/LICENSE-2.0 |
| PSF License | https://docs.python.org/3/license.html |
| Tcl/Tk License | https://www.tcl.tk/software/tcltk/license.html |

---

本ソフトウェアの著作権: Copyright (c) 2026 Unknown777hello (aka Unknown777)