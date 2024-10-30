# bachelor
研究室の新 B4 向けの配属情報をまとめた Web ページのリポジトリです。

研究室の全体説明会と、各チームの個別説明会の案内、研究紹介などをまとめています。
毎年更新すべき箇所は、説明会のスケジュールと、研究内容の紹介、集合写真です。

## MDWiki
この Web ページは MDWiki で構成されています。
MDWiki とは、Markdown を自動的に Web ページとして変換してレンダリングしてくれるソフトウェアです。
MDWiki の本体は index.html にあります。このページは Single Page Application として動作し、Markdown のファイルの取得と描画を行います。

## Git による管理
remote は /home/git/repositories に Git bare リポジトリがおいてあります。
このリポジトリは以下のように初期化されていて、研究室の人なら誰でも Write 権限を持ちます。
```
git init --bare --shared=group /home/git/repositories/bachelor.git
git clone /home/git/repositories/bachelor.git .
```

リモートに push するときは以下のコマンドで行います。
master の部分はローカルのブランチ名です。
```
git push origin master
```

リモートから pull するときは以下のコマンドで行います。
master の部分はリモートのブランチ名です。
```
git pull origin master
```
