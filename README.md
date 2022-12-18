# 学んだことのあれやこれ
## laravelの環境構築
* MacとWindowsで環境行き来してるので、できればDockerを使いたい！
* sailっていう便利なやつがある。
* [sailを使った環境構築URL](https://qiita.com/hinako_n/items/45a7232b0b0ed16bffc8)

## sailで環境構築した後、sorcetreeをつかってremoteにpushしたいのにできない;;
* 初回push時は色々確認されるらしい
* コマンドラインからやろう。
* `git push --set-upstream origin master`
* 'origin' does not appear to be a git repositoryって怒られるかも。
* `git remote add origin gitのURL`でoriginを追加してやろう。
* git pushのときに、origin以外を指定すればうまくいくかもね
* [ここ](https://mugendennou.net/development/git/sourcetreepush/#Sourcetree)が参考になったよ
* 2回目以降はうまくいくのか試してない。

## laravel-mixしたいね〜
* [参考URL](https://reffect.co.jp/laravel/first-laravel-mix#Laravel_Mix-2)
