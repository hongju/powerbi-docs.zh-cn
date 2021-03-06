---
title: 优化用于手机的 Power BI 的仪表板
description: 了解如何在 Power BI 服务中创建专供在移动电话上查看的仪表板自定义视图。
author: maggiesMSFT
manager: kfile
ms.reviewer: ''
ms.service: powerbi
ms.subservice: powerbi-service
ms.topic: conceptual
ms.date: 04/18/2019
ms.author: maggies
LocalizationGroup: Dashboards
ms.openlocfilehash: f2b8c2c4be343dc135fe1b133bfcb956c1549de4
ms.sourcegitcommit: 60dad5aa0d85db790553e537bf8ac34ee3289ba3
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 05/29/2019
ms.locfileid: "61158154"
---
# <a name="optimize-a-dashboard-for-mobile-phones---power-bi"></a>优化用于手机的 Power BI 的仪表板 
在手机上纵向模式下查看仪表板，请您注意到仪表板磁贴的布局方式逐个传递所有相同大小。 在 Power BI 服务中，可以创建自定义仪表板中，专用于在手机上纵向模式视图。 即使您创建电话视图，当侧向打开手机时，您会看到仪表板，因为它在服务中的布局方式。

正在寻找有关移动设备上查看仪表板的信息？ 请尝试本快速入门教程[浏览仪表板和报表在 Power BI 移动应用中的](consumer/mobile/mobile-apps-quickstart-view-dashboard-report.md)相反。

> [!NOTE]
> 在手机上查看仪表板的任何人都可以实时看到你在编辑电话视图时所做的更改。 例如，如果你取消固定仪表板电话视图上的所有磁贴，手机仪表板上的磁贴会突然消失。 
> 
> 

## <a name="create-a-phone-view-of-a-dashboard"></a>创建仪表板电话视图
1. 在 Power BI 服务中打开仪表板。
2. 依次选择右上角“Web 视图”  旁边的箭头和“电话视图”  。

    ![](media/service-create-dashboard-mobile-phone-view/power-bi-service-phone-view-dashboard.png)

    如果不是仪表板的所有者，将看不到此选项。

    ![](media/service-create-dashboard-mobile-phone-view/power-bi-mobile-edit-phone-view-canvas.png)

    此时将打开电话仪表板编辑视图。 你可以在该视图中取消固定、调整大小以及重排磁贴以适应电话视图。 仪表板的 web 版本不会更改。


1. 选择一个磁贴进行拖放、调整大小或取消固定操作。 你将发现，拖动某个磁贴时，其他磁铁也会移开。
   
    ![](media/service-create-dashboard-mobile-phone-view/power-bi-unpin-tile-phone-dashboard.png)
   
    未固定的磁贴会进入“未固定的磁贴”窗格中，除非重新添加回原处，否则它们将继续留在此窗格中。
   
    ![](media/service-create-dashboard-mobile-phone-view/power-bi-mobile-edit-phone-view-post-edit.png)
2. 如果改变主意，请选择“重置磁贴”  ，按之前的大小和顺序将它们放回原处。
   
    ![](media/service-create-dashboard-mobile-phone-view/power-bi-service-phone-view-reset-tiles.png)
   
    在 Power BI 服务中直接打开“电话编辑”视图会稍稍改变手机上磁贴的大小和形状。 因此，若要将仪表板完全恢复到在“电话编辑”视图中打开之前的状态，请选择“重置磁贴”  。
3. 若对手机仪表板布局感到满意，请依次选择右上角“电话视图”  旁边的箭头和“Web 视图”  。
   
    此时，Power BI 会自动保存手机布局。

## <a name="next-steps"></a>后续步骤
* [创建针对 Power BI 手机应用的优化报表](desktop-create-phone-report.md)
* [创建优化为适应任意大小的响应式视觉对象](visuals/desktop-create-responsive-visuals.md)
* 更多问题？ [尝试咨询 Power BI 社区](http://community.powerbi.com/)

