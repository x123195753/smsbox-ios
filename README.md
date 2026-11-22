# smsbox-ios

短信盒子 iOS WebView 壳（未签名 IPA，GitHub Actions 自动构建）。

- App 内容来自线上 `https://box.1000.yun/`（App.swift 里可改 START_URL）→ **服务器网页更新 = App 内容热更新**，无需重新打包
- 权限已在 Info.plist 预声明：麦克风（语音通话）、摄像头；ATS 允许自建域名
- Actions 产物为**未签名 IPA**，需自行签名后安装：
  - 免费：Sideloadly / AltStore + Apple ID（7 天有效，可无限重签）
  - 付费：个人/公司开发者证书，用 ESign、爱思助手等签后可长期使用
