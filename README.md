# Knowledge Bases for Amazon Bedrock を利用した RAG のベースライン

## TL;DR

## 目次

## 背景

## 目的

自学のため，本実装では LangChain を利用せず boto3 のみを利用して実装している．

## オリジナリティ

- LangChain を利用せず，boto のみを利用して実装している．
  - 本番環境においては，バージョンアップデートによる影響が大きい LangChain を利用することはリスクが高いため，boto のみを利用して実装している．
- 利用する LLM について，Bedrock で利用可能なモデルに容易に切り替えられるようにしている．
  - 本実装では，Claude3 と Command R+に切り替えられるように実装している．今後のモデルの追加にも対応できるようにしている．

## 前提

## 手順

## 手順の各ステップの詳細

## TODO

- 引用部分の提示
- Knowlwdge base の IaC 化
  - CDK or CloudFormation
