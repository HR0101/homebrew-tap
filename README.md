# HR0101/homebrew-tap

[AttendanceSystem](https://github.com/HR0101/AttendanceSystem) を Homebrew で導入するための tap です．

## インストール

```sh
brew install HR0101/tap/attendance
```

仮想環境・Python 依存ライブラリ・Playwright（Chromium）・`att` コマンドがまとめて導入されます．設定ファイル・予定・ログは既定で `~/AttendanceSystem`（環境変数 `ATTENDANCE_HOME` で変更可能）に保存されます．

## アップデート

```sh
brew update
brew upgrade attendance
```

## 収録 Formula

| Formula | 説明 |
| --- | --- |
| `attendance` | 大学の出席確認・登録を行う macOS 向け CLI/TUI |

## メンテナンス

`Formula/attendance.rb` は AttendanceSystem のリリースワークフロー（`.github/workflows/release.yml`）が生成するファイルです．手動で編集せず，新しいタグのリリースに添付された `attendance.rb` で置き換えてください．
