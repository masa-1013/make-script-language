# 内容
2週間でできる！スクリプト言語の作り方のまとめ

# まとめ
## 1日目
- インタプリタとコンパイラ
  - インタプリタ・・ソースコードや中間表現を実行するソフトウェアのこと。内部でコンパイラを使用するものもある。
  - コンパイラ・・ソースコードを機械語ないし、機械語以外のプログラムに変換するソフトウェアのこと

- 言語処理系内部の処理の流れ
  - 字句解析・・ソースコードを意味のある単位で分割して、トークンを作成する
  - 構文解析・・トークンを抽象構文木に変換する
  - コード生成 or 実行・・抽象構文木をもとに別のコードを生成するのがコンパイラ。実行するのがインタプリタ