Herokuでのgem追加方法
========================

Gemfileにパッケージを記入する。

以下のコマンドでGemfile.lockを更新する。
bundler update

GemfileとGemfile.lockの両方をコミットしてpushする。
エラーがでなければok。

なおbundlerはgem install bundleでインストールできる。
