---
title: Bot Builder Overview | Microsoft Docs
description: Description of the various means of creating a bot.
services: Bot Framework
documentationcenter: BotFramework-Docs
author: kbrandl
manager: rstand

ms.service: Bot Framework
ms.topic: article
ms.workload: Cognitive Services
ms.date: 02/03/2017
ms.author: v-kibran@microsoft.com

---
# About Bot Builder

Bot Builder enables you to build and connect intelligent bots to interact with your users naturally wherever they are — from your website or app to text/SMS, Skype, Slack, Facebook Messenger, Office 365 mail, Teams and other popular services. 
A majority of developers create bots via one of the following means:

- [Bot Builder SDK for .NET](#dotnet) 
- [Bot Builder SDK for Node.js](#node)
- [Azure Bot Service](#azure)

## <a id="dotnet"></a>Bot Builder SDK for .NET
The Bot Builder SDK for .NET is a powerful framework for constructing bots that can handle both freeform interactions and more guided ones where the possibilities are explicitly shown to the user. It is easy to use and leverages C# to provide a familiar way for .NET developers to write bots. 

For a detailed walkthough of creating a bot using the Bot Builder SDK for .NET, see <a href="bot-framework-dotnet-getstarted.md">Using .NET</a>.

## <a id="node"></a>Bot Builder SDK for Node.js
The Bot Builder SDK for Node.js is a powerful framework for constructing bots that can handle both freeform interactions and more guided ones where the possibilities are explicitly shown to the user. It is easy to use and models frameworks like Express & Restify to provide a familiar way for JavaScript developers to write bots. 

For a detailed walkthough of creating a bot using the Bot Builder SDK for Node.js, see <a href="bot-framework-nodejs-getstarted.md">Using Node.js</a>.

## <a id="azure"></a>Azure Bot Service
The Azure Bot Service provides an integrated environment that is purpose-built for bot development, 
enabling you to build, connect, test, deploy and manage intelligent bots, all from one place. 
You can write your bot in C# or Node.js directly in the browser using the Azure editor, without any need for a tool chain (local editor and source control). 

For a detailed walkthough of creating a bot using Azure Bot Service, see <a href="bot-framework-azure-getstarted.md">Using Azure Bot Service</a>.

## Other Options (REST)
As an alternative to using the Bot Builder SDK for .NET, the Bot Builder SDK for .NET, or the Azure Bot Service, 
you can create a bot with any programming language by using the Bot Framework REST API.
- The Bot Connector REST API enables your bot to send and receive messages to channels configured in the [Bot Framework Developer Portal](https://dev.botframework.com/). 
- The Bot State REST API enables your bot to store and retrieve state associated with the conversations that are conducted through the Bot Connector REST API. 

For details about the Bot Connector REST API and the Bot State REST API, see [TBD-topic-in-Develop-section].

To connect your own application (i.e., client application, web chat control, mobile app, etc.) directly to a single bot, 
you can use the Direct Line REST API. 
For details about the Direct Line REST API, see [TBD-topic-in-Develop-section].