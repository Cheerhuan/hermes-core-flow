---
name: hermes-core-flow
description: 將 Hermes Agent 進化體核心 (CaMeL 安全邊界與雲端部署) 標準化至本地開發流程。
tags: [devops, security, deployment, hermes-agent]
---

# Hermes-Core-Flow

這是一個將 "Hermes Agent" 進化體（如安全性、雲端化）核心標準內化至本地開發流程的標準化 Skill。

## 核心價值
1. **CaMeL 信任邊界 (Security)**：在執行任何寫入或遠端操作前，進行風險評估。
2. **標準化雲部署 (Deployment)**：強制使用統一的 Dockerfile 與部署範本。

## 使用方式
當您準備好開發新功能或部署時，調用本 Skill。

## 操作步驟
1. **執行前確認**：確認專案是否包含必要的配置檔案。
2. **風險邊界評估**：針對指令進行風險評估。
3. **部署封裝**：產生 Cloud-ready 結構設定。
