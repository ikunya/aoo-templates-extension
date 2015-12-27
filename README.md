# Apache OpenOfficeのImpressテンプレート拡張

## これは何？
これはApache OpenOffice (AOO) 4.0以降にデフォルトで含まれているImpress用テンプレートをLibreOfficeで使用するための拡張機能です。

AOO 4.0以降には含まれていますが、日本語版では使用できないため、日本語で使用するAOOユーザーにも有益かと思います。

ただしAOOでの動作確認は行っておりません。

元のテンプレートファイルは[AOOのsvnリポジトリ](http://svn.apache.org/viewvc/openoffice/trunk/main/extras/source/templates/layout/lang/en-US/)から取得できます。

## ビルド方法
次のコマンドを実行してください。

```
zip aoo-template-extension.oxt * impress-templates/* impress-templates/aoo-templates/* META-INF/manifest.xml
```

## 使用方法
LibreOfficeの拡張機能としてインストールしてください。
