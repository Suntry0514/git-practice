# git-practice
このリポジトリはGit動画講座用です．
更新
pull rebase用


# マークダウンについて紹介

## こんな感じの主砲で文章をかく

### #の数＝ヘッダータグの数　＃＝h1  ##=h2

- リストの表示
- 点の表示方法
  - ネスト１行目
    - ネストのネスト１行目

1. リストの表示
2. 数字のリスト
   1. ネストの１行目
   2. ネストの２行目
3. 連番の数字と実際の見た目の数字は異なる

- 番号と点のリスト
    1. ネストの番号  

## リンク

[yahoo](https://yahoo.co.jp)

<!-- リンクを変数のように使う方法 -->
[google]:https://google.co.jp

[グーグル][google]

## 改行と段落
<!-- 文末に２個スペースをいれる -->
１行目  
２行目

段落は改行２回押すことで

実現することができます。

## 引用と多重引用

> 引用っぽく表示する  
>２行目の引用です。  
>>多重引用です。

## インランコードとブロックコード
<!-- `はバッククオートという shift + @ -->
これは`インランコード`です。

```javascript
function double(){
  return "コードもかけるよ"
}
```

## 画像の挿入

![ダミー画像](https://placehold.jp/150*150.png)

## 文字の装飾

*斜体*のテキスト

**太字**のテキスト

~~訂正線~~です。

****斜体と太字***のテキスト

## 水平線

上

---

下

## テーブルの書き方

名前 | 年齢
----|-----
aさん｜20  
bさん| 30
