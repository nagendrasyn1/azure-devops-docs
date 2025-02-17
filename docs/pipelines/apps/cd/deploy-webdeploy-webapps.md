---
title: Deploy a web app to App Services
description: Set up CD of an ASP.NET or Node.js web deploy package to Azure App Services with Azure Pipelines
ms.assetid: 449254BF-EAC1-466E-B10C-85C2DE086F30
ms.topic: conceptual
ms.custom: seodec18
ms.author: ronai
author: RoopeshNair
ms.date: 09/07/2021
monikerRange: '>= tfs-2015'
---

# Deploy a web app to Azure App Services

**Azure Pipelines | TFS 2018 | TFS 2017.2**

We'll show you how to set up continuous deployment of your ASP.NET or Node.js app to an Azure Web App using
Azure Pipelines. You can use the steps in this quickstart
as long as your continuous integration pipeline publishes a Web Deploy package.

## Prerequisites

Before you begin, you'll need a CI build that publishes your Web Deploy package. To set up CI for your specific type of app, see:

* [Build your ASP.NET 4 app](../aspnet/build-aspnet-4.md)

* [Build your ASP.NET Core app](../../ecosystems/dotnet-core.md)

* [Build your Node.js app with gulp](../../ecosystems/javascript.md)

You'll also need an Azure Web App where you will deploy the app.

[!INCLUDE [create-release](../includes/create-release.md)]

## Next step

* [Customize web app deployment](../../targets/webapp.md)
