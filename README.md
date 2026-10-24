# Materials for "Machine Vision Inspection with Raspberry Pi and Python"

**English readers:** these are the exercise files for *Machine Vision Inspection with Raspberry Pi and Python: OpenCV, Camera Setup, OK/NG Decisions, Evidence Records, and Shop-Floor Operation* by Ryo Nishikido (the English edition of the Japanese book below).

**[Download the materials ZIP (about 16 KB)](https://github.com/sunnishi/raspberrypi-inspection-book-materials/releases/download/v1.3.0/raspberrypi_inspection_code.zip)**

- Latest materials: v1.3.0 (October 24, 2026), file `raspberrypi_inspection_code.zip`. No GitHub account is needed.
- On the release page, choose `raspberrypi_inspection_code.zip` under "Assets". "Source code (zip)" and "Source code (tar.gz)" do not contain the exercise code.
- Extract the ZIP to get a `code` folder, open `README_EN.md` inside it, and start with the quick start in the Preface or with Chapter 3.
- Tested on macOS with Python 3.10, OpenCV 5.0.0, and NumPy 2.2.6 using synthetic images. A real Raspberry Pi, cameras, PLCs, and continuous operation were not verified.
- Report errors or problems on [Issues](https://github.com/sunnishi/raspberrypi-inspection-book-materials/issues). Please include your OS (and Raspberry Pi model), Python version, the command you ran, and the full message. Do not post product images or confidential information.
- License: MIT (see LICENSE in the ZIP).

---

# 『ラズパイとPythonでつくる 製造業の画像検査』の教材

西城戸 亮 著『ラズパイとPythonでつくる 製造業の画像検査：OpenCV・カメラ接続からOK／NG判定、記録・運用まで』の実習用ファイルです。

## 教材ZIPをダウンロードする

**[教材ZIPをダウンロード（約16 KB）](https://github.com/sunnishi/raspberrypi-inspection-book-materials/releases/download/v1.3.0/raspberrypi_inspection_code.zip)**

- 最新の教材：v1.3.0（2026年10月24日。英語版の案内`README_EN.md`を追加。コードはv1.2.0と同じ）
- ファイル名：`raspberrypi_inspection_code.zip`
- [この版の配布ページ](https://github.com/sunnishi/raspberrypi-inspection-book-materials/releases/tag/v1.3.0)

ダウンロードにGitHubアカウントは不要です。配布ページの「Assets」から取得する場合は、`raspberrypi_inspection_code.zip`を選んでください。自動表示される「Source code (zip)」「Source code (tar.gz)」には、実習用のコードは入っていません。

ZIPを展開すると`code`フォルダーができます。書籍の「はじめに」のクイックスタート、または第3章の手順で始めてください。

## 収録内容

| 学ぶ内容 | 教材内の場所 |
| --- | --- |
| 一枚の画像の検査と記録（第5・8〜11章） | `inspection.py` |
| 合成画像10枚と三つの検査設定を作る（第5章） | `generate_samples.py` |
| 27項目の一括確認（第5章） | `verify.py` |
| ラズパイのカメラで一枚撮る（第6章、実機用） | `capture_once.py`、`station_once.py` |
| 記入用の帳票（付録B） | `templates` |

## 実行環境と検証範囲

制作時の環境はmacOS、Python 3.10、OpenCV 5.0.0、NumPy 2.2.6です。合成画像による検査部分は、この環境で動作を確認しています。ラズパイ実機、カメラ、PLC、連続運転は未検証です。カメラ用のコードは、公式のAPIに沿って用意したもので、実機での受入確認が必要です。

## 正誤表

現時点で、報告された誤りはありません。

## 質問・不具合の報告

本文の誤りや、教材が動かない場合は、[Issues](https://github.com/sunnishi/raspberrypi-inspection-book-materials/issues)から報告してください。OS（ラズパイの場合は機種とOSの版）、Pythonの版、実行したコマンド、表示されたメッセージを添えると状況を確認しやすくなります。製品の画像や社内の情報は書き込まないでください。

## 利用条件

収録コードと合成画像は、自分の検査に合わせて改変・利用できます（LICENSEを参照）。依存ライブラリやカメラなどの利用条件は、それぞれの提供元に従います。

## ダウンロードしたファイルを確認する

[SHA256SUMS.txt](SHA256SUMS.txt)の値と照合できます。
