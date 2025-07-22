# KatcH

KatcH 是一個用於 LINE Login LIFF 的重定向頁面專案。  
本專案提供簡單的 HTML 頁面，協助開發者在 LINE 前端框架（LIFF）中進行登入後的頁面跳轉，適合用於驗證、權限授權或其他需要導向的應用場景。

## 功能特色

- 支援 LINE Login LIFF 登入後的自動重定向
- 結構簡單，易於二次開發與整合
- 適用於各類 LINE 應用或 Web App

## 專案結構

```
/
├── index.html                  # 入口頁面
├── diacopycat.html             # 其他自定義頁面
├── privacy-policy.html         # 隱私政策
├── terms-of-service.html       # 服務條款
├── quotation.html              # 報價頁面
├── quotation1.html             # 報價頁面2
├── zohoverify/verifyforzoho.html # Zoho 驗證頁
├── googlea3e14b0177df4fdd.html # Google 驗證頁
├── CNAME                       # GitHub Pages 網域設定
```

## 如何使用

1. Fork 或 Clone 此專案到你的 GitHub 帳號。
2. 修改 `index.html` 或其他頁面，根據你的需求調整重定向邏輯與 UI。
3. 部署至 GitHub Pages 或其他靜態網站服務。
4. 在 LINE LIFF 設定中填入你的 GitHub Pages 網址作為重定向 URI。

## 部署

本專案已支援 GitHub Pages，直接推送到 main 分支即可自動部署。

## 授權

MIT License
