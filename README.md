# 生成AIパスポート Udemy 問題集 解説画像

Udemy講座「生成AIパスポート 問題集」シリーズの解説欄に挿入する画像を配信するためのリポジトリです。

## フォルダ構成

| フォルダ | 用途 | 元CSV |
|---|---|---|
| `anki/` | 暗記用問題集（200問） | `anki_all_chapters.csv` |
| `mock1/` | 模擬試験1（予定） | `mock_exam_1.csv` |
| `mock2/` | 模擬試験2（予定） | `mock_exam_2.csv` |
| `mock3/` | 模擬試験3（予定） | `mock_exam_3.csv` |

## URL 形式

```
https://keitassy96-coder.github.io/seiseiai-pass-udemy-quiz-images/{set}/qNN.png
```

例:
- `anki/q01.png` → https://keitassy96-coder.github.io/seiseiai-pass-udemy-quiz-images/anki/q01.png
- `anki/q200.png` → https://keitassy96-coder.github.io/seiseiai-pass-udemy-quiz-images/anki/q200.png

## ファイル仕様

- 解像度: 600×448 px
- 形式: PNG
- 生成方法: 4問ずつまとめて Gemini 3.1 Flash Image Preview で生成 → 4分割
