# AzureMachineLearning-AutoML-Image-Detection

## Overview
このリポジトリは[Azure Machine Learning サンプル](https://github.com/Azure/azureml-examples/blob/main/sdk/python/jobs/automl-standalone-jobs/automl-image-object-detection-task-fridge-items/automl-image-object-detection-task-fridge-items.ipynb) をもとに AutoML でのオブジェクト検知ジョブの設定と実行方法するハンズオン用のノートブックを提供します。
ノートブックでは、小さなデータセットを使って AutoML によりモデルを学習し、モデルの性能を最適化するためにモデルのハイパーパラメータを調整する方法を示し、推論シナリオで使用するモデルをデプロイします。

## Requirements
**前提条件** - このハンズオンを進めるにあたり、以下が前提条件となります:
- Machine Learning の基礎知識
- 利用可能な Azure subscription. [Create an account for free](https://azure.microsoft.com/free/?WT.mc_id=A261C142F)
- Azure ML workspace [Check this notebook for creating a workspace](../../../resources/workspace/workspace.ipynb) 
- Compute Cluster [Check this notebook to create a compute cluster](../../../resources/compute/compute.ipynb)
- Python 実行環境
- Azure Machine Learning Python SDK v2 - [install instructions](../../../README.md)

## Objective
**学習のゴール** - このハンズオンを完了すると、以下を学習できます:
- Python SDK から AML workspacce への接続方法
- 'image_object_detection()' 関数を使って `AutoML Image Object Detection Training Job` を実行する方法
- Azure Machine Learning のコンピュートで AutoML 機能を使ってモデルを構築する方法
- 学習済みモデルと推論スコアの取得

## Usage
- Azure Machine Learning Workspace 、またはローカル開発環境で
 [automl-image-object-detection-task-fridge-items.ipynb](./automl-image-object-detection-task-fridge-items/automl-image-object-detection-task-fridge-items.ipynb) を実行する。