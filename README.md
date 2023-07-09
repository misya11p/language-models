# 言語モデル

言語モデルについてまとめた資料。  
本リポジトリでは、特に深層学習に着目し、言語モデルへの理解を深めていく。

> **Warning**  
> 現在製作途中

## 言語モデルとは

単語の並びに確率を割り当てるモデル。

基本的には文章生成に使われるので、文章生成モデルとみてもいいかもしれない。文章生成では、与えられた文脈と語彙の下で次に続く単語を予測し、その単語を文脈に含めた上でまた次の単語を予測する。これを繰り返すことで文章を生成する。

## 目次

1. マルコフモデル
2. 深層学習を用いた言語モデル
3. RNN
4. RNNLM
5. ゲート付きRNN
6. 言語モデルの評価
7. seq2seq
8. Attention
9. Transformer

## おまけ

1. 形態素解析
2. word2vec
