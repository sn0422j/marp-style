---
marp: true
theme: customVer03.0-invert
size: 16:9
paginate: true
header: ヘッダー
footer: フッター
math: mathjax
style: |
    section {
        font-family: BIZ UDGothic, sans-serif !important;
    }
---

<!-- _class: title -->
<!-- _paginate: false -->

# タイトル！

---
# スライド1
## ふつうに書く

スライド1の内容です。
2行目
3行目
4行目
5行目
6行目
7行目
8行目
9行目
10行目
11行目
12行目

---
# スライド2
## 数式や箇条書きを入れる

スライド2の内容です。

$$
a = b
$$

- スライド2の箇条書きです。
- スライド2の箇条書きです。

1. スライド2の箇条書きです。
2. スライド2の箇条書きです。

> [1] 脚注です。

---
# スライド3
## 2列に分ける
<!-- _class: two-cols -->

スライド3の内容です。
2行目
3行目
4行目
5行目
6行目
7行目
8行目
9行目
10行目
11行目
12行目

スライド3の内容です。
2行目
3行目
4行目
5行目
6行目
7行目
8行目
9行目
10行目
11行目
12行目

---
# スライド4
## 2列目に画像
<!-- _class: two-cols -->

スライド4の内容です。
2行目
3行目
4行目
5行目
6行目
7行目
8行目
9行目
10行目
11行目
12行目

<div class="align-x-center align-y-center">

![height:400px](https://github.com/marp-team.png)</div>

---
# スライド5-1
## オートスケーリングは改行すればいけるかも？

<h3 is="marp-h3" data-auto-scaling>

2行目
3行目
4行目
5行目
6行目
7行目
8行目
9行目
10行目
11行目
12行目
13行目
14行目
15行目
16行目
17行目
18行目

<br><br></h3>

---
# スライド5-2
## オートスケーリングは改行すればいけるかも？

<h3 is="marp-h3" data-auto-scaling>

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod 
tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, 
quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. 
Duis aute irure dolor in reprehenderit in voluptate velit esse 
cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, 
sunt in culpa qui officia deserunt mollit anim id est laborum.

:smile:

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod 
tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, 
quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. 
Duis aute irure dolor in reprehenderit in voluptate velit esse 
cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, 
sunt in culpa qui officia deserunt mollit anim id est laborum.

<br><br></h3>

---
# スライド6
## ブロックを使う

<div class="block">

### 定義1
ここに定義を書く。
それは以下の式です。

$$
y = \frac{1}{N} \sum_{i=1}^N x_i
$$

すなわち、$y = \bar{x}$ といういうことです。

</div>

なるほど。なるほど。

> [1] 長い脚注です。こんにちは。こんにちは。こんにちは。こんにちは。こんにちは。こんにちは。こんにちは。こんにちは。こんにちは。こんにちは。こんにちは。こんにちは。こんにちは。こんにちは。こんにちは。

---
# スライド6
## TOCを使う
<!-- _class: toc -->

1. アイテム1
2. アイテム2
3. アイテム3
4. アイテム4
5. アイテム5
6. アイテム6

---
# スライド7
ポイントなしにもできる。

---
# スライド7
<!-- _class: two-cols -->

ポイントなしの二列にもできる。

ポイントなしの二列にもできる。

---
# スライド7
<!-- _class: two-cols -->

<div class="same-col">

<div class="block">

### 定義2
ここに定義を書く。
</div>

<div class="block">

### 定義3
ここに定義を書く。
</div>

ポイントなしの二列にもできる。

ポイントなしの二列にもできる。

</div>

ポイントなしの二列にもできる。

ポイントなしの二列にもできる。

---
# スライド8
<!-- _class: toc -->

1. ポイントなしのTOCもできる。
2. アイテム2
3. アイテム3
4. アイテム4
5. アイテム5
6. アイテム6

---
# スライド9
## 文字を小さくする

<div class="text-small"> 

これは小さい文字です。
2行目
3行目
4行目
5行目
6行目
7行目
8行目
9行目
10行目
11行目
12行目
13行目
14行目

</div>

---
# スライド10
## 文字をさらに小さくする

<div class="text-xsmall"> 

これは小さい文字です。
2行目
3行目
4行目
5行目
6行目
7行目
8行目
9行目
10行目
11行目
12行目
13行目
14行目
15行目
16行目

</div>

---
# スライド11
## 文字を大きくする

<div class="text-large"> 

これは大きい文字です。
2行目
3行目
4行目
5行目
6行目
7行目
8行目
9行目
10行目

</div>

---
# スライド12
## 文字をさらに大きくする

<div class="text-xlarge"> 

これは大きい文字です。
2行目
3行目
4行目
5行目
6行目
7行目
8行目

</div>

---
# スライド11
## 文字をとても小さくする

<div class="text-xxsmall"> 

これは小さい文字です。
2行目
3行目
4行目
5行目
6行目
7行目
8行目
9行目
10行目
11行目
12行目
13行目
14行目
15行目
16行目
17行目
18行目
19行目
20行目
21行目
22行目
23行目
24行目

</div>

---
# スライド12
## 文字をとても小さくする

<div class="text-xxxsmall"> 

これは小さい文字です。
2行目
3行目
4行目
5行目
6行目
7行目
8行目
9行目
10行目
11行目
12行目
13行目
14行目
15行目
16行目
17行目
18行目
19行目
20行目
21行目
22行目
23行目
24行目
25行目
26行目
27行目
28行目
29行目
30行目

</div>

---
# スライド13
## ブロックを使う

<div class="block block-green">

### 定義1
ここに定義を書く。
</div>

<div class="block block-red">

### 定義1
ここに定義を書く。
</div>

---
# スライド14
<!-- _class: appendix -->

---
# 浮動ボックスを試す

<style>
    .box {
        float: left;
        margin-right: 15px;
        border-radius: 5px;
        background-color: rgba(207, 232, 220, 0.5);
        padding: 0.5em;
    }
</style>

<div class="box">

![height:350px](https://github.com/marp-team.png)

Figure 1. example image.

</div>

これはなんでしょうか。

---
# 浮動ボックスを試す

<div style="float: left; margin-right: 20px;" class="block block-green">

### Figure 1. example image.

![height:350px](https://github.com/marp-team.png)

</div>

これはなんでしょうか。
・まず、〇〇する。
・次に、〇〇する。
・最後に、〇〇する。
