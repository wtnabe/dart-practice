## requirements

* `brew tap dart-lang/dart`
* `brew install dart@2`
   * no --with-dartium and --with-content-shell
* `brew link --force dart@2`
* `pub global activate webdev`
* modify shell rc file and re-source
* prepare pubspec.yaml
* `pub get`
* `webdev serve web:8000 --hot-reload`

note) these files in web/ diretory are generated from stagehand command and shaved by me.

## references

* [Flutterだけじゃない！ Dart × Webフロントエンドの現状と未来](https://aloerina01.github.io/blog/2018-08-01-1)
* https://webdev.dartlang.org/dart-2
* https://pub.dartlang.org/
* https://www.dartlang.org/tools/pub/pubspec
* https://www.dartlang.org/tools/pub/package-layout
* https://www.dartlang.org/guides/language/language-tour
