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
* webpack.mix.jsなくね？
* 違う、バージョン6以降は作られなくなったから、自分で作らないといけないんだ。
* [こっち](https://push.tokyo/laravel-mix/#toc4)のがわかりやすいや
* ビルド前のサンプルファイルは自分で作成しないといけないの！？わかりやした・・・
* なんでや、うまくうごかへんぞ。。。
* てか、Laravel9だとlaravel-mixからviteに置き換わってるらしい。なんやて？

## やるべきはlaravel-mixじゃなくてviteだった！？
* [参考URL](https://qiita.com/monji586/items/4338db30d62f765f7829)
* [ここも参考に](https://zakkuri.life/laravel-vite/)

## sailのshellへの入り方わからん・・・
* [参考URL](https://omkz.net/laravel-sail/)

## ていうかMacのデスクトップの順番が勝手に入れ替わるのなんやねん！しばき回すぞ！
* [解決方法](https://lovemac.jp/3384#:~:text=%E3%81%AE%E3%81%84%E3%81%BE%E3%81%97%E3%81%9F%E2%80%A6%E3%80%82-,%E3%83%87%E3%82%B9%E3%82%AF%E3%83%88%E3%83%83%E3%83%97%E3%81%AE%E4%B8%A6%E3%81%B3%E9%A0%86%E3%81%8C%E5%8B%9D%E6%89%8B%E3%81%AB%E5%A4%89%E3%82%8F%E3%82%89%E3%81%AA%E3%81%84%E3%82%88%E3%81%86,%E4%BB%A5%E4%B8%8A%E3%80%82)ありました。
