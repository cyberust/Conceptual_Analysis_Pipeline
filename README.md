# 坂根構造コーパス：概念分析パイプライン (Conceptual Analysis Pipeline for Sakane Structural Corpus)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cyberust/Conceptual_Analysis_Pipeline/blob/main/Conceptual_Analysis_Pipeline_Example.ipynb)

## 概要

本リポジトリは、「坂根構造コーパス：エントロピーの時代における「人間的構造」の再設計と未来共創」の思想に基づき、関連するテキストデータ（CV、ジャーナル、バズワードリストなど）から構造的な知見を抽出・分析するためのPythonベースのパイプラインです。

このパイプラインは、自然言語処理（NLP）技術、トピックモデリング、キーワード抽出、ネットワーク分析などを組み合わせ、バズワードが示す構造信号や、それらが織りなす意味の座標軸を可視化し、考察することを目的としています。

## 特徴

* PDF、Markdown、CSV、Excelなど複数のデータソースに対応
* spaCyを用いた高度なテキスト前処理（レンマ化、品詞フィルタリング、固有表現抽出、N-gram生成など）
* BERTopicによるトピックモデリング
* TF-IDFおよびKeyBERTによるキーワード抽出
* Sentence-BERTによる文書埋め込み生成
* NetworkXを用いたキーワード共起ネットワーク分析と可視化
* ユーザー定義の「注目ワードリスト」に基づいた分析機能

## セットアップ

### 1. リポジトリのクローンまたはダウンロード
```bash
git clone [https://github.com/](https://github.com/cyberust/Conceptual_Analysis_Pipeline.git
cd Conceptual_Analysis_Pipeline
