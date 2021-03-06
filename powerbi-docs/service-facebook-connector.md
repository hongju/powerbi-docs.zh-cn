---
title: 第三方服务：适用于 Power BI Desktop 的 Facebook 连接器
description: 第三方服务：适用于 Power BI Desktop 的 Facebook 连接器
author: davidiseminger
manager: kfile
ms.reviewer: ''
ms.service: powerbi
ms.subservice: powerbi-desktop
ms.topic: conceptual
ms.date: 05/08/2019
ms.author: davidi
LocalizationGroup: Connect to data
ms.openlocfilehash: 6b02717c49a1207dfec39ebb1529e7e9b222fa62
ms.sourcegitcommit: 60dad5aa0d85db790553e537bf8ac34ee3289ba3
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 05/29/2019
ms.locfileid: "65512862"
---
# <a name="facebook-connector-for-power-bi-desktop"></a>适用于 Power BI Desktop 的 Facebook 连接器
**Power BI Desktop** 中的 Facebook 连接器依赖于 Facebook Graph API。 同样，功能和可用性可能会随着时间推移有所不同。

你可以查看 [Power BI Desktop 的 Facebook 连接器的相关教程](desktop-tutorial-facebook-analytics.md)。

Facebook 已于 2015 年 4 月 30 到期 Graph API 的 v1.0。 Power BI 在后台对 Facebook 连接器使用 Graph API，从而允许你连接到你的数据并对其进行分析。

在 2015 年 4 月 30 之前生成的查询可能不再起作用或返回较少的数据。 2015 年 4 月 30 subsequent to Power BI 使用 v2.8 中所有对 Facebook API 调用。 如果你的查询在 2015 年 4 月 30 日之前生成，并且从那以后再也没有使用，你可能需要重新进行验证，以批准我们将要求的新权限集。

尽管我们尝试依照任何更改发布更新，API 可能会以影响我们生成的查询的结果的方式进行更改。 在某些情况下，某些查询可能不再受支持。 使用此连接器时，由于此依赖关系，我们无法保证你的查询的结果。

可在[此处](https://developers.facebook.com/docs/apps/changelog#v2_0)了解有关 Facebook API 中更改的详细信息。

