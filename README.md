# 言語モデルの理論と実装

言語モデルについてまとめた資料。特に深層学習に着目し、言語モデルへの理解を深めていく。

> [!NOTE]
> 制作中。
> 4章までは整っている。5章以降はバージョンが古い（2年前）

## 1. [言語モデル](introduction.ipynb)

言語モデルの概要やそれを用いた文章生成について。

1. 言語モデル
2. 言語モデルを用いた文章生成
3. 学習済み言語モデルを体験する

## 2. [マルコフモデル](markov_model.ipynb)

まずはシンプルなモデルで言語モデルを学ぶ。

1. マルコフモデルを用いた言語モデル
2. マルコフモデルの学習
3. N階マルコフモデル

## 3. [コーパスの活用とトークナイザ](tokenizer.ipynb)

大きなデータセットとトークナイザの活用方法について。

1. コーパス
2. トークナイザ
3. コーパスを活用したマルコフモデルの学習
4. 深層学習に向けたデータセットの構築

## 4. [深層学習の導入](deep_learning.ipynb)

深層学習を用いてマルコフモデルを実装し、深層学習の活用方法を学ぶ。

1. 学習データの用意
2. モデル構築
3. パープレキシティ
4. 実践

## 5. [RNN](rnn.ipynb)

RNNを用いて文脈全体を考慮した言語モデルを実装する。

1. RNN
2. RNNを用いた言語モデル
3. 教師データの作成
4. BPTT
5. RNNにおけるミニバッチ学習
6. 実践

## 6. [ゲート付きRNN](gated_rnn.ipynb)

RNN層にゲートと呼ばれる機構を追加し、より長期的な文脈の情報を保持できるようにする。

1. 勾配消失
2. ゲート
3. GRU
4. LSTM
5. 実践

## 7. [Seq2Seq](seq2seq.ipynb)

あるシーケンスから別のシーケンスへの変換を行うSeq2Seqというモデルを学び、機械翻訳へ応用する。

1. 条件付き言語モデル
2. Seq2Seq
3. 教師データの作成
4. 双方向RNN
5. ビームサーチ
6. 実践

## 8. [Attention](attention.ipynb)

データの全体を見た上で重要な部分に着目するような仕組み。これを用いることでSeq2Seqの性能が向上する。

1. Attention機構
2. Attentionを用いたSeq2Seq
3. 実践
4. Attentionの可視化

## 9. [Transformer](transformer.ipynb)

現在の言語モデルの根幹を担うアーキテクチャであるTransformerについて学ぶ。

1. Transformerの概要
2. Positional Encoding
3. Self-Attention
4. Query-Key-Value Attention
5. Multi-Head Attention
6. Transformer Encoder
7. Transformer Decoder
8. Transformer
9. 実践
