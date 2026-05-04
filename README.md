# uB-filter-by-kdroidwin


uBlacklist＆uBlock Origin用のフィルター　
- 主に、詐欺サイトや偽サイト、悪質なアフィリエイトサイトを除外することが目的です。
- 誤検知やブロックすべきサイトがあれば教えてください。Github,Codebergアカウントを持っていない人でも[Twitter](https://x.com/Kdroidwin1)もしくは[アンケートフォーム](https://tally.so/r/wA5brD)からお願いします。
- [Codebergリポジトリ ミラー](https://codeberg.org/Kdroidwin/uB-filter-by-kdroidwin)

# Changelog(変更履歴)

[完全な変更履歴](https://github.com/Kdroidwin/uBlacklist-filter-by-kdroidwin/commits/main/)
<br>
<br>

# uBlacklist用フィルター購読方法

 1. [uBlacklist](https://iorate.github.io/ublacklist/ja/docs)をインストールしてください。
 2. 下の購読を押してください。

※uBlock Origin用のフィルターはuBlacklistには使えません。


# uBlacklist用 フィルターの種類
- １つ目のは基本的なフィルターです。
- 2つ目の購読の方は多少の誤ブロックが許せる方向けです。本来ブロックするべきではないサイトもブロックされる恐れがあります。実験的です。1つ目のフィルターに加えて併用してください。
- 3つ目の除外用は購読必須です。1つめと2つめのフィルターの誤爆を減らすためのものです。



<br>
<br>
chrome(chromiumの派生)ユーザー向け

[購読](https://iorate.github.io/ublacklist/subscribe?name=uBlacklist-filter-by-kdroidwin&url=https://raw.githubusercontent.com/Kdroidwin/uBlacklist-filter-by-kdroidwin/main/uBlacklist.txt)

[購読2](https://iorate.github.io/ublacklist/subscribe?name=uBlacklist-filter-by-kdroidwin2&url=https%3A%2F%2Fraw.githubusercontent.com/Kdroidwin/uBlacklist-filter-by-kdroidwin/main/uBlacklist2.txt)

[除外用の購読](https://iorate.github.io/ublacklist/subscribe?name=uBlacklist-filter-by-kdroidwin_exclusion&url=https%3A%2F%2Fraw.githubusercontent.com/Kdroidwin/uBlacklist-filter-by-kdroidwin/refs/heads/main/uBlacklist-Exclusion.txt)

<br>

Firefox及びそのフォークユーザー向け

[購読](https://ublacklist.github.io/rulesets/subscribe?url=https%3A%2F%2Fraw.githubusercontent.com%2FKdroidwin%2FuBlacklist-filter-by-kdroidwin%2Fmain%2FuBlacklist.txt)

[購読2](https://ublacklist.github.io/rulesets/subscribe?url=https%3A%2F%2Fraw.githubusercontent.com%2FKdroidwin%2FuBlacklist-filter-by-kdroidwin%2Fmain%2FuBlacklist2.txt)

[除外用の購読](https://ublacklist.github.io/rulesets/subscribe?url=https%3A%2F%2Fraw.githubusercontent.com%2FKdroidwin%2FuBlacklist-filter-by-kdroidwin%2Fmain%2FuBlacklist-Exclusion.txt)

下記は上の購読リンクで購読できなかった人向けのURLです。
uBlacklistのオプション＞購読＞購読を追加する からコピーボタンを押してコピーしたURLと適当な名前を入力してください。SafariユーザーはURLをコピーボタンを押してコピーしてください。
<br>

- uBlacklist-filter-by-kdroidwin 1 URL
```
https://raw.githubusercontent.com/Kdroidwin/uBlacklist-filter-by-kdroidwin/main/uBlacklist.txt
```

- uBlacklist-filter-by-kdroidwin expt URL(実験的)
```
https://raw.githubusercontent.com/Kdroidwin/uBlacklist-filter-by-kdroidwin/main/uBlacklist2.txt
```

- uBlacklist exclusionフィルター(除外用) by Kdroidwin URL
```
https://raw.githubusercontent.com/Kdroidwin/uBlacklist-filter-by-kdroidwin/refs/heads/main/uBlacklist-Exclusion.txt
```

<br>
<br>



# uBlock Origin 用フィルターの種類


-購読を押してください。
- 検索結果には表示されますがアクセスを防ぐことができます。ただし、強力であるため、関係のないサイトまでブロックされることがあります。


<br>
<br>

- Block malicious websites by Kdroidwin
[購読](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/Kdroidwin/uB-filter-by-kdroidwin/refs/heads/main/uBlockorigin.txt&title=Block%20malicious%20websites%20by%20Kdroidwin)

```
https://raw.githubusercontent.com/Kdroidwin/uBlacklist-filter-by-kdroidwin/refs/heads/main/uBlockorigin.txt
```
<br>
<br>


- Block specific note by Kdroidwin
[購読](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/Kdroidwin/uBlacklist-filter-by-kdroidwin/refs/heads/main/uBlacklist_converted-foruBo.txt&title=Block%20specific%20note%20by%20Kdroidwin)
```
https://raw.githubusercontent.com/Kdroidwin/uBlacklist-filter-by-kdroidwin/refs/heads/main/uBlacklist_converted-foruBo.txt
```
一部の中身のないnote記事をnote内のおすすめやnote内の検索結果から非表示にします。（実験的）

<br>
<br>

# 対象サイト

- いかがでしたか系（デマ・芸能ゴシップ）
  - 根拠なしのセンセーショナル見出し

- 悪質アフィリエイトサイト（報酬優先ランキング）
  - 商品比較が曖昧
  - 「報酬が高い順」など不透明なランキング

- 悪質アフィリエイト記事（自社製品・ステマ）
  - 批判や欠点が書かれていない
  - CTA（購入誘導）が過剰

- 偽レビューサイト（R18漫画・ガジェット等、AI生成含む）
  - 同じ文言のコピペが多い
  - 実体験の裏付けが弱い

- 詐欺サイト

- サポート詐欺／不正リダイレクト

- SEOスパム
  - 評価基準がアフィリエイトや報酬重視
  - 役に立たないランキングサイトなど
  - 「〇〇 おすすめ」「〇〇 比較」

- フィッシングサイト（偽サイト）

- 誤情報サイト

- 危険なソフト配布サイト（マルウェア）
  - 前科ありのサイトも含む

- 悪質なまとめサイト（デマ拡散）
  - 出典不明の情報を寄せ集め
  - 拡散目的の誇張見出し

- AIハルシネーション多発サイト
  - 事実誤認が頻繁
  - 訂正履歴や更新履歴がない

- 偽ダウンロードボタン／広告トリック
  - 広告ボタンをダウンロードと誤認させる配置
  - 複数の紛らわしいボタン

- クリックベイトサイト
  - 見出しと本文の乖離が大きい
  - 中身が広告・アフィリエイト中心

- 注意すべきTLD（悪用率が比較的高い）
  - `.best` `.click` `.top` `.cfd` `.cyou` `.sbs` `.cm` `.cf` `.my`
  - 登録の敷居が低く、悪用事例が多い傾向あり

- 注意すべきドメインパターン
  - `za.com` `sa.com` `ru.com`　悪質なサイトによく使われる。

<br>
<br>

# 貢献

URLの追加やミスの削除に協力していだける方は、レポジトリをForkして編集していただき、pull requestを送ってください。
issueでも構いません。並び替えはbotがやるので不要です。

Githubアカウントを持っていない方はTwitterもしくは[こちら](https://tally.so/r/wA5brD)からお願いします。

# Credits

Contains parts from Dandelion Sprout's Anti-Malware List  
by Dandelion Sprout  
https://github.com/DandelionSprout/adfilt  

License: Dandelicence v1.4  
https://github.com/DandelionSprout/Dandelicence

This project is based on FMHYFilterlist (https://github.com/fmhy/FMHYFilterlist
).
It has been significantly extended with additional filters and modifications.
This project is licensed under the GNU GPL-3.0.
