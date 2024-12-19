# Terraform構成管理

## 概要
このディレクトリには、GCPリソースのInfrastructure as Code (IaC)が含まれています。

## ディレクトリ構造
- `environments/`: 環境別（dev/stg/prod）の設定
- `modules/`: 再利用可能なTerraformモジュール

## 使用方法
```bash
# 初期化
terraform init

# 計画の確認
terraform plan

# 適用
terraform apply
