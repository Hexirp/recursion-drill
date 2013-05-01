# 再帰ドリル

再帰を学ぶためのドリル。使用するプログラミング言語は Haskell。[Haskell Platform](http://www.haskell.org/platform/) の利用を推奨します。

1. [自然数に対する素朴な再帰](1.md) ([演習1](1.hs))
2. [自然数に対する末尾再帰](2.md) ([演習2](2.hs))
3. [いろいろな終わり方](3.md) ([演習3](3.hs))
4. [再帰的な自然数](4.md) ([演習4](4.hs))
5. [自然数に対する少し複雑な再帰](5.md) ([演習5](5.hs))
6. [再帰のこころ](6.md) ([演習6](6.hs))
7. [メモ化](7.md) ([演習7](7.hs))
8. [リストに対する素朴な再帰](8.md) ([演習8](8.hs))
9. リストを生成する再帰
10. ループを超えた再帰
11. 木に対する再帰

演習では、用意された Haskell コードの undefined を変更し、テストして動作を確認して下さい。テストに利用している hspec ライブラリは、以下のようにしてインストールして下さい。

    % cabal update
    % cabal install hspec
