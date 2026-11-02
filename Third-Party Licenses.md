# 第三者ソフトウェアのライセンス / Third-Party Licenses

FileManagerExplorer(以下「本ソフトウェア」)は、次の第三者ソフトウェアを利用しています。
これらの部分には、本ソフトウェアのライセンス([LICENSE.md](LICENSE.md))ではなく、それぞれのライセンスが適用されます(LICENSE.md 第8条)。

FileManagerExplorer uses the third-party software listed below.
Each component is governed by its own license, which takes precedence over LICENSE.md for that component.

> 各ライブラリの著作権表示とライセンス全文は、配布物に同梱するか、各プロジェクトのリポジトリ(下表の URL)で確認してください。
> 配布するバージョンに合わせて、バージョン番号とライセンス全文を追記してください。

## 一覧

### 実行に使うライブラリ(任意。なくても起動し、その機能だけ無効になります)

| 名称 | 用途 | ライセンス | 入手先 |
|---|---|---|---|
| tkinterdnd2 | ドラッグ&ドロップ | MIT License(同梱の tkdnd は BSD 系ライセンス) | https://github.com/Eliav2/tkinterdnd2 |
| Send2Trash | ゴミ箱へ移動 | BSD-3-Clause | https://github.com/arsenetar/send2trash |
| Pillow | 画像のプレビュー・サムネイル・EXIF | MIT-CMU(HPND) | https://github.com/python-pillow/Pillow |
| mutagen | 音声ファイルの情報 | **GPL-2.0-or-later** | https://github.com/quodlibet/mutagen |
| cryptography | 暗号化フォルダー | Apache-2.0 または BSD-3-Clause(どちらか選択) | https://github.com/pyca/cryptography |
| pypdf | PDF のメタデータ削除 | BSD-3-Clause | https://github.com/py-pdf/pypdf |
| PyMuPDF(MuPDF を含む) | PDF のプレビュー | **AGPL-3.0**(Artifex の商用ライセンスも選択可) | https://github.com/pymupdf/PyMuPDF |

### 実行環境・ビルドに使うソフトウェア

| 名称 | 用途 | ライセンス | 入手先 |
|---|---|---|---|
| Python(tkinter を含む) | 実行環境 | PSF License | https://www.python.org/ |
| Tcl/Tk | tkinter の GUI | Tcl/Tk License(BSD 系) | https://www.tcl.tk/ |
| PyInstaller | exe の作成 | GPL-2.0-or-later(ブートローダー例外あり。作成した exe には適用されません) | https://github.com/pyinstaller/pyinstaller |
| Inno Setup | インストーラーの作成 | Inno Setup License | https://jrsoftware.org/isinfo.php |

## 注意事項(GPL / AGPL のライブラリについて)

次の 2 つは、GPL 系のライセンスです。

- **mutagen**: GPL-2.0-or-later
- **PyMuPDF / MuPDF**: AGPL-3.0

これらを同梱した状態で本ソフトウェアを配布する場合、それぞれのライセンスの条件(ソースコードの提供、同じライセンスでの配布など)が、本ソフトウェアの配布に及ぶかどうかを確認する必要があります。
本ソフトウェアのライセンス(LICENSE.md)は、これらのライブラリのライセンスを変更・上書きするものではありません。

配布物にこれらを含めるかどうかは、作者が配布前に判断します。含めない場合、該当する機能(音声ファイルの情報の表示 / PDF のプレビュー)は無効になります。

## ライセンス全文

配布物には、上の各ライブラリのライセンス全文(著作権表示を含む)を同梱してください。
全文は、インストールしたパッケージの中(`site-packages\<パッケージ名>-<バージョン>.dist-info\` 内の `LICENSE` など)か、各リポジトリで確認できます。

以下に、ライセンスごとに、全文の入手先を示します。

| ライセンス | 全文の入手先 |
|---|---|
| MIT License | https://opensource.org/license/mit |
| BSD-3-Clause | https://opensource.org/license/bsd-3-clause |
| MIT-CMU(HPND) | https://github.com/python-pillow/Pillow/blob/main/LICENSE |
| Apache-2.0 | https://www.apache.org/licenses/LICENSE-2.0 |
| GPL-2.0 | https://www.gnu.org/licenses/old-licenses/gpl-2.0.html |
| AGPL-3.0 | https://www.gnu.org/licenses/agpl-3.0.html |
| PSF License | https://docs.python.org/3/license.html |
| Tcl/Tk License | https://www.tcl.tk/software/tcltk/license.html |

---

本ソフトウェアの著作権: Copyright (c) 2026 Unknown777hello (aka Unknown777)
