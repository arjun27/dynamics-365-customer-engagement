---
title: "Write plug-ins to extend business processes (Developer Guide for Dynamics 365 for Customer Engagement apps) | MicrosoftDocs"
description: "A plug-in is custom business logic that you can integrate with Dynamics 365 for Customer Engagement (online) Customer Engagement to modify or augment the standard behavior of the platform. Plug-ins are event handlers since they are registered to execute in response to a particular event being fired by the platform."
ms.custom: 
ms.date: 1/16/2019
ms.reviewer: 
ms.service: crm-online
ms.suite: 
ms.tgt_pltfrm: 
ms.topic: get-started-article
applies_to: 
  - Dynamics 365 for Customer Engagement (online)
f1_keywords: 
  - plugins
  - plugin
helpviewer_keywords: 
  - plug-in
ms.assetid: f5a0690c-1783-4b36-96cd-cd34ae41eb41
caps.latest.revision: 34
author: JimDaly
ms.author: jdaly
manager: amyla
search.audienceType: 
  - developer
search.app: 
  - D365CE
---
# Write plug-ins to extend business processes

[!INCLUDE[](../includes/cc_applies_to_update_9_0_0.md)]

Whenever possible, you should first consider applying one of the several declarative process options to define or apply business logic. More information: [Automate your business processes in Customer Engagement apps](automate-business-processes-customer-engagement.md).

When a declarative process doesn’t meet a requirement, as a developer you have several options. This topic will introduce common options to write code.

A plug-in is custom business logic that you can integrate with [!INCLUDE[pn_dynamics_crm_online](../includes/pn-dynamics-crm-online.md)] to modify or augment the standard behavior of the platform. Plug-ins are event handlers since they are registered to execute in response to a particular event being fired by the platform.
  
 The following topics describe how to add custom business logic to [!INCLUDE[pn_dynamics_crm](../includes/pn-dynamics-crm.md)] through the development and registration of plug-ins. For more information about the run-time execution of plug-ins and the plug-in development framework, see [Event Framework](/powerapps/developer/common-data-service/event-framework).  

> [!NOTE]
> In this documentation release, the plug-in documentation that is common to all [!INCLUDE[pn_dynamics_365](../includes/pn-dynamics-365.md)] deployment types has been moved to the [Common Data Service](/powerapps/developer/common-data-service/overview) documentation set. The sub-sections that follow contain only the information specifically related to developing plug-ins for an on-premises or Internet Facing Deployment (IFD). To learn about plug-in development, start by reading the plug-in [documentation](/powerapps/developer/common-data-service/apply-business-logic-with-code) under Common Data Service, and then if you are targeting an on-premises/IFD deployment, read the sub-topics that follow this topic.
  
## In This Section  
[Plug-in Development](plugin-development.md)
  
## Related Sections  
 [Developer Guide for Dynamics 365 for Customer Engagement apps](developer-guide.md)<br />     
 [Write Workflows to Automate Business Processes in Dynamics 365 for Customer Engagement apps](automate-business-processes-customer-engagement.md)<br />     
 [Package and Distribute Extensions with Dynamics 365 for Customer Engagement apps Solutions](package-distribute-extensions-use-solutions.md)<br /> 
