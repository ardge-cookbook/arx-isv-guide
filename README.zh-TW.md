# arx-isv-guide — ARX OS App 移植參考套件

[English](README.md) | **繁體中文** | [日本語](README.ja.md)

給 ISV（獨立軟體開發商）開發、移植 ARX OS app 用的參考套件：可執行的範例 app、移植說明文件，以及給 AI agent 使用的 skills。

> 本 repo 只放說明文件。套件請從 [Releases](https://github.com/ardge-cookbook/arx-isv-guide/releases) 下載。

## 下載

| 版本 | 檔案 |
|---|---|
| 最新版 | [Releases › Latest](https://github.com/ardge-cookbook/arx-isv-guide/releases/latest) |
| v0.6.7 | [arx-isv-guide-v0.6.7.zip](https://github.com/ardge-cookbook/arx-isv-guide/releases/download/v0.6.7/arx-isv-guide-v0.6.7.zip) |

下載後可用同一個 release 附的 `SHA256SUMS.txt` 確認檔案完整：

```bash
sha256sum -c SHA256SUMS.txt
```

## 套件內容

| 路徑 | 用途 |
|---|---|
| `apps/` | 可執行的最小範例、reference app 與第三方 app 移植範例 |
| `docs/` | 平台能力、移植方式與 template 欄位參考 |
| `.claude/skills/` | 建置、驗證與操作 ARX OS app 的 AI agent skills |

解壓縮後，先讀套件根目錄的 `README.md`，再依 app 的現況選擇上手路徑（從零開始、從 docker-compose 移植、移植第三方 app）。

## 使用說明

- [ARX OS 開發指南](https://developer.ardge.com/zh-tw/guide/overview)：版本化教學的正式入口，請以開發指南為準
- [ARX ISV Cookbook](https://arx-isv-cookbook.pages.dev/zh-tw/)：實務範例與操作經驗

## 版本

各版差異見 [CHANGELOG](CHANGELOG.md)。開發指南提供的 v0.6.4（`arx-isv-skills-v0.6.4.zip`）只含 skills；本 repo 從 v0.6.7 起提供完整套件。

## 問題與回饋

本 repo 不開放 Issues。問題與回饋請洽 ARDGE 窗口。

## 授權

Copyright © 2026 ARDGE. All rights reserved. 使用範圍見 [LICENSE](LICENSE)。
