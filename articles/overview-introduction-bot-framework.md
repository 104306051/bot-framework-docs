---
title: About the Bot Framework | Microsoft Docs
description: Learn about the Microsoft Bot Framework, a comprehensive framework of tools and services to build and deploy high quality bots.
author: RobStand
ms.author: rstand
manager: rstand
ms.topic: article
ms.prod: bot-framework
ms.date: 05/31/2017
---

# 關於 Bot Framework

Bot Framework 是一個可以建置、連結、測試和部署非常強大且智能的機器人平台。Bot Framework 支援 .NET、Node.js 和 REST。您可以[取得 Bot Builder SDK](resources-tools-downloads.md) 並用 Bot Famework 快速[開始建置您的 Bot](bot-builder-overview-getstarted.md)。 

## 什麼是 Bot ?
想像 Bot 是個可以和使用者有對話互動的應用軟體。Bots 可以和文字訊息、字卡或文章進行交談。 一個 Bot 可以只有基本的回應功能，也可以對現在的企業有一個複雜的人工智慧技術、具有複雜的溝通和追蹤功能。

這個 Bot 框架讓您建置一個可以支援多種和使用者有互動功能的機器人。 您可以在機器人裡設計各種自由形式的對話。 您的機器人也可以提供使用者選擇是否要有更多的互動及引導。對話方式可以使用基本的文字字串，或者使用包含文字、圖片和操作按鈕的卡片功能。 您也可以透過增添自然語言的方式，讓您的使用者和機器人有一個更自然、更容易表達的互動體驗。



讓我們來看一個用機器人預約沙龍的例子。 機器人了解使用者的意圖之後，用操作按鈕呈現預約時間的選項，使用者按下選取的預約時間後，機器人會送回使用者選取的時間，並發送一個包含預約細節的簡略圖卡進行確認。 

<p>
<div style="text-align: center" markdown="1">
![salon bot example](~/media/salon_bot_example.png)
</div>  

機器人現在正成為數位體驗一個缺一不可的部分。它們變得像網站和行動 App 一樣，成為讓使用者可以有互動的一個平台和應用程式。


## 為什麼要用 Bot Framework?
開發者在編寫機器人時，都會遇到一樣的問題：機器人需要基本的 I/O，它們必須擁有語言和對話的技術，它們也必須根據使用者選擇的語言和聊天經驗和使用者聯繫。
此 Bot 框架提供一個強大的工具和功能來解決這些問題。 

### Bot Builder
為了幫您建置您的機器人，此 Bot 框架包含 [Bot Builder](bot-builder-overview-getstarted.md)，它為 .NET 和 Node.js 平台提供了豐富且完整功能的 SDK。 SDK提供功能讓使用者和機器人之間的互動更簡單。 Bot Builder 也包括了調整您機器人的模擬器，還有很多機器人的使用範例讓您可以使用。

### Bot Framework 入門
用 Bot Framework 入門來管理您的機器人非常簡單。 Bot Framework 入門提供您一個方便的地方去註冊、連結和管理您的機器人。它同時也提供診斷工具和可以在網頁上嵌入您機器人的網頁聊天控制器。

![Configure a bot in the developer portal](~/media/portal-configure-bot.png)

### 頻道
此 Bot 框架支援許多常用的頻道讓您的機器人和更多的人們有所連結。使用者可以和您的機器人在任何您已確認的頻道中開始對話，這些頻道包括了電子郵件、Facebook、Skype、Slack 和 SMS 等等。 您可以使用 [Channel Inspector](portal-channel-inspector.md) 在您選擇的標頻道上去預覽您想要使用的功能。

![List of channels on the portal](~/media/portal-channels-list.png)

## 建構您的智能機器人
您可以從微軟提供的智能服務系統中獲得許多好處，像是增添語意的理解能力、圖像辨識、語音等等的智慧功能。
[了解更多](~/cognitive-services-bot-intelligence-overview.md) 讓您的機器人增添智慧功能。

## 下一步
去深入了解更多 Bot Framework的 [功能](overview-how-bot-framework-works.md) 。
開始  [建置您的第一個機器人](bot-builder-overview-getstarted.md) 並了解更多關於如何 [設計完美的機器人](~/bot-design-principles.md)。

[NodeGetStarted]:~/nodejs/bot-builder-nodejs-quickstart.md
[DotNETGetStarted]:~/dotnet/bot-builder-dotnet-quickstart
