# tonejs-tone-editor

## 状況
- 未着手
- いつ着手する？
  - 気が向いたら
    - 機が熟したら

## いろいろ

- 位置付け
  - 音色づくりを手軽に楽しめる用
    - 例、SuperSaw
  - tonejs-mml-to-json に類似
- input
  - GUI
  - instrumentをプルダウンで選んで、それぞれのパラメータを手軽に変更
  - portamentoはon/offできる。instrument付属なので
  - effectもプルダウンで選ぶ。直列だけMML記述ができるので、ひとまずそれでやる
  - ディレイビブラートはon/offできる
- output
  - MML
    - その場でpreview演奏
  - 設定JSONを、
    - local storageに保存できる
    - jsonファイルにexportできる
      - 作者としても、手早く作った音色のjsonをデフォのプルダウンに入れてexample充実はメリットがある
- 要点
  - JSONで保存できて、再利用性が高いこと
    - これまでの課題
      - Tone.jsは音色を作るために都度、JavaScriptのコードを書く必要があった
      - このエディタを使えば、プログラミング不要で、ノーコードで、音色づくりを手軽に楽しめる
