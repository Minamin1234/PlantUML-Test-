# PlantUML(Test)
## 概要
PlantUMLを使ってクラス図を書いてみるリポジトリ

## 必要環境
- Java
- PlantUML(VSCodeの拡張機能でも可)
- Graphviz

## 導入方法
```powershell
> winget install Microsoft.OpenJDK.17
> winget install Graphviz.Graphviz
```

VSCodeの拡張機能から
```
PlantUML (publisher: "jebbs")
```
をインストール

## 使用方法
`.pu`のファイルを作成後、`Alt + D`でプレビューできる.

## サンプル
本リポジトリの`sample.pu`を配置している。武器と弾薬のクラス図を書いてみた。

矢印はそのクラスからの継承(汎化)、ダイヤマーク矢印は関係(集約/コンポジション)を表す。

![.\out\sample\sample.png](UML)