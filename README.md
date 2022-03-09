# Github を置き場に。

ローカルの MarkDown に自作の画像を載せたいけど、その画像の管理とか大変になるじゃなぁ～い？

そこで、専用の publicリポジトリを作ってそこに画像を置いて、直リンクしちゃえば良いと思ったんですよ。

## １．リポジトリ作成
あれなので置き場にするブランチを切る。
```bash
git checkout -b okiba
git add .
git commit -m "first commit"
git push --set-upstream origin okiba
```
で、そこに画像ファイルを置いて管理する。

<br>

## ２．直リンク
URLの構成は以下のようになる。

```bash
https://github.com/アカウント/リポジトリ名/blob/ブランチ名/ファイル.jpg?raw=true
```


```markdown
![](https://github.com/b3stcr3ation/mono/blob/okiba/img/5.jpg?raw=true)
```
![](https://github.com/b3stcr3ation/mono/blob/okiba/img/5.jpg?raw=true)
出た～！やった～
以上です。

かしこ

