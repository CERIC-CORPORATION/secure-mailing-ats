# プロジェクト概要

## プロジェクト名
secure-mailing-ats

## プロジェクトの背景
PPAP方式（Password付きZIP、Password別送）の廃止が政府・企業で進む中、セキュアな情報伝達システムの構築が急務となっている。同時に、AI技術を活用した開発フローの効率化も求められている。

## 二重の目的

### システム側
- **必ず実現**: PPAP方式に代わるセキュアな情報伝達を可能とするシステムを構築する
- **できれば実現**: ロボシリーズのアドオンとしても使える形でシステムを構築し、商用化の下地を作る

### AI側
- **必ず実現**: AIを使用したチーム開発フローのプロトタイプを構築する
- **できれば実現**: AIを使用した開発で有用だった思考法や手法をドキュメント化する

## 現在のステータス
- プロジェクト初期化完了
- 要件定義書作成完了
- メモリーバンク基盤構築完了

## 主要成果物
- docs/requirements_definition.md - 包括的要件定義書
- memory-bank/ - プロジェクト記憶領域

## 技術スタック（候補）
- フロントエンド: React/Vue.js
- バックエンド: Node.js/Python/Go
- データベース: PostgreSQL/MongoDB
- クラウド: AWS/Azure/GCP
- AI/ML: TensorFlow/PyTorch
- コンテナ: Docker/Kubernetes

## プロジェクト構造
- memory-bank/ - プロジェクト記憶領域
- docs/ - ドキュメント格納
  - requirements_definition.md - 要件定義書
