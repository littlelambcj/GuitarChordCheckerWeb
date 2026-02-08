# Guitar Chord Checker

A simple web tool to check guitar chord fingerings.
Created with AI-assistance for quick utility.

## Features
- Instant chord visualization.
- Built for efficiency over complexity.

## Known Bugs / Features

Note on File Naming: Since this app was refactored from my original Ukulele tool, some internal UI elements still carry the "Ukulele" prefix. Please be assured that the logic and data are fully optimized for Guitar.

## License
MIT (Feel free to use/mod)

ボタンを押してギターのコードをチェックできる簡素なアプリです。
AIと一緒に作りました。

自作のウクレレアプリを元にギター用にしたので"ukulele"って名前が入ったファイル名がありますがギター用のものです。

MITライセンス。改造など自由ですが、自己責任でどうぞ。

## About Chord Naming / 音楽理論上の名称について

Chords with identical pitch classes may be displayed as different names depending on the root note interpretation. This is not a bug, but a reflection of musical theory (e.g., D6 vs. Bm7).

音楽理論の性質上、構成音が同じでも、どの音をルート（主音）とみなすかによってコードの名称が変わることがあります。
例えば、D6（D, F#, A, B）と Bm7（B, D, F#, A）は同じ音で構成されています。

本アプリでは以下のパターンなどで名称が重複して表示されることがありますが、これは理論上の性質であり、不具合とは異なります：
D#6 が Cm7と表示される
D#m6 が Cdim 系統の名称になる
D#dimが Cdim と表示される
