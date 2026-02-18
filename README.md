# JPG_ARW_Auto_Classification

## 🇯🇵 日本語

### 概要
一眼カメラで撮影したJPGとARW（RAW）ファイルを自動的に分類するWindows用デスクトップアプリケーションです。SDカードの日付フォルダをドラッグ＆ドロップするだけで、PC上の指定フォルダにJPG/ARWを振り分けてコピーします。

### 主な機能
- **ドラッグ＆ドロップ対応**: フォルダをドロップするだけで即座に処理開始（複数フォルダ対応）
- **自動分類**: JPGとARWファイルを別々のサブフォルダに整理
- **システムテーマ対応**: Windows 11のライト/ダークモードに自動追従するFluent Design UI
- **パス記憶機能**: 前回使用した保存先フォルダを自動的に記憶
- **安全なコピー**: 元ファイルを削除せずコピーするため、データ消失のリスクがありません

### 使用技術
- Python 3.12
- CustomTkinter (Fluent Design UI)
- TkinterDnD2 (ドラッグ＆ドロップ)
- PyInstaller (exe化)

### インストール方法
最新版のインストーラは Releases からダウンロードできます。
詳細な手順は以下を参照してください。

📄 **[DISTRIBUTION_GUIDE.md](./DISTRIBUTION_GUIDE.md)**

### 動作環境
- Windows 10 / 11（64bit）

---

## 🇺🇸 English

### Overview
A Windows desktop application that automatically classifies JPG and ARW (RAW) files taken with digital cameras. Simply drag and drop date folders from your SD card, and it will copy and sort JPG/ARW files into specified folders on your PC.

### Features
- **Drag & Drop Support**: Start processing instantly by dropping folders (supports multiple folders)
- **Auto Classification**: Organizes JPG and ARW files into separate subfolders
- **System Theme Support**: Fluent Design UI that automatically adapts to Windows 11 Light/Dark modes
- **Path Memory**: Automatically remembers the last used destination folder
- **Safe Copy**: Copies files without deleting originals, ensuring data safety

### Tech Stack
- Python 3.12
- CustomTkinter (Fluent Design UI)
- TkinterDnD2 (Drag & Drop)
- PyInstaller (Executable creation)

### Installation
You can download the latest installer from Releases.
For detailed instructions, please refer to:

📄 **[DISTRIBUTION_GUIDE.md](./DISTRIBUTION_GUIDE.md)**

### System Requirements
- Windows 10 / 11 (64-bit)
