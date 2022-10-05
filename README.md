# Shogi686MicroSPM

https://github.com/select766/shogi686micro-xcframework で生成されたxcframeworkをSwift Package Manager (SPM)形式にラップする。

# ビルド
このソースツリー自体にビルドすべきものはない。

xcframeworkをビルドして、Frameworks内にその出力である`libshogi686micro.xcframework`をコピーする。

gitにコミットし、タグを付与する(例: `0.0.1`)。

SPMの利用側ではgitのタグをキーに内容を特定するためバイナリのコミットおよびタグ付与が必須。
