==========================
openExplorer_LvPlugin
==========================

# 概要
  現在、アクティブになっているVIが保存されているフォルダをエクスプローラ
で表示する機能を LabVIEW のツールメニューに追加するプラグインVI。
LabVIEW 2009 で作成しています。Windows用です。

  VIを編集中に、編集中のVIが保存されているフォルダを表示したいことが多々
あります。
  例えば、リリース用とデバッグ用などに複数のソースファイルで作業している
場合に現在編集しているのがどちらのものなのか確認したい時。
  また、subversionやgitなどのツールを使ってバージョン管理している時に、
TortoiseSVN/Git や git bash などメニューを呼び出すために、エクスプローラで
保存されているフォルダを開きたい時など。
  lvprojプロジェクトからエクスプローラを呼び出す、という方法もありますが、
そもそもそれなりの規模のプロジェクトなら、サブVIがたくさんあるので、
その中から、編集中のサブVIを探すのがそもそも手間。

# インストール

## 対応する環境
  LabVIEW 2009 で作成しています。Windows用です。

## インストール方法
  openExplorer_LvPlugin ファイルを LabVIEW インストールフォルダの所定の
場所にコピーするだけです。
			
## インストールする場所
LabVIEW 32bit版の場合、以下の場所にファイルをコピーします。


    Windows 32bit:
      C:\Program Files\National Instruments\LabVIEW 20xx\project

    Windows 64bit:
      C:\Program Files(x86)\National Instruments\LabVIEW 20xx\project

  "20xx" の部分には使用しているLabVIEW のバージョン(2009,2010,2011,2012,...)
が入ります。複数バージョンがインストールされている場合は、それぞれの
バージョンのprojectフォルダにコピーしてください。

  ファイルをコピーした後、LabVIEWを再起動すると、ツールメニューに
"open explorer..."が表示されます。

## 使い方
  LabVIEWで適当なVIを開いて、開いた状態でツールメニューから"open explorer..."
を選択するとエクスプローラでVIが保存されているフォルダを開きます。

