---
layout: page
title: 設定 VPN，突破地區限制 (Mac用戶)
---

### 目錄:
1. 下載 ShadowsocksX-NG
2. 安裝 ShadowsocksX-NG
3. 設定 VPN Server
4. 設定 External PAC URL
5. 選擇 Auto Mode by External PAC
6. 使用時 Turn Shadowsocks On
7. 使用後 Turn Shadowsocks Off

### 1. 下載 ShadowsocksX-NG

按此下載 [ShadowsocksX-NG.dmg (v1.10.0)](https://github.com/shadowsocks/ShadowsocksX-NG/releases/download/v1.10.0/ShadowsocksX-NG.dmg)

### 2. 安裝 ShadowsocksX-NG

雙點 ShadowsocksX-NG.dmg 打開以下畫面，並拖曳 ShadowsocksX-NG 到 Applications 目錄。

![](/public/images/mac-vpn-01.png)

完成後，打開應用程式。

![](/public/images/mac-vpn-02.png)

以下視窗按 "Cancel"。

![](/public/images/mac-vpn-03.png)

然後到 System Settings / System Preferences > Privacy and Security > 按下 "Open Anyway"。

![](/public/images/mac-vpn-04.png)

以下視窗按 "Open"。

![](/public/images/mac-vpn-05.png)

### 3. 設定 VPN Server

右上角打開 ShadowsocksX-NG 選單 > Import Server URLs
![](/public/images/mac-vpn-06.png)

貼上 `ss://` 開頭的連結，按Import。

右上角打開 ShadowsocksX-NG 選單 > Servers，選擇 "ChatGPT Only"。

![](/public/images/mac-vpn-07.png)

### 4. 設定 External PAC URL

右上角打開 ShadowsocksX-NG 選單 > Preferences。

![](/public/images/mac-vpn-08.png)

跳到 "Advanced" > 在 External PAC URL 填上以下連結，**並按下"Enter"儲存**。

```
https://chatgpt-helpers.github.io/public/config/mac/mac-ss-ng-pac.js
```

![](/public/images/mac-vpn-09.png)


### 5. 選擇 Auto Mode by External PAC

![](/public/images/mac-vpn-10.png)

### 6. 使用時 Turn Shadowsocks On

![](/public/images/mac-vpn-11.png)

### 7. 使用後 Turn Shadowsocks Off

![](/public/images/mac-vpn-12.png)
