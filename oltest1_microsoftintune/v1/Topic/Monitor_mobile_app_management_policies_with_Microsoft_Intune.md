---
description: na
keywords: na
title: Monitor mobile app management policies with Microsoft Intune
search: na
ms.date: 2015-11-17
ms.service: microsoft-intune
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: d3aa6c74-6b5d-4b50-aa66-a040ec44393e
ms.author: fb8a7802-3b27-41b8-82f3-31bfdcf49ff2
---
# Monitor mobile app management policies with Microsoft Intune
Use the information in this topic to help you monitor your mobile application management policies in the Azure preview portal.

### Monitoring mobile application management policy compliance
The **User status** tile in the **Intune mobile application management** blade displays the compliance status of your app policies as described below:

![](../Image/AppManagement/AzurePortal_MAM_MonitorUsers.png)

-   **Users**- The total number of users in your company who are using work apps on their devices.

-   **POLICY**-This is the number of users who have used at least one of the apps associated with the policy.

-   **NO POLICY**- The number of users actively using work apps but not protected by the mobile application management policy.

    The **Flagged users** tile gives you the aggregated information on how many users are experiencing issues. Currently only users with jailbroken devices are marked as flagged.

    ![](../Image/AppManagement/AzurePortal_MAM_FlaggedUserDetails.png)

-   The **Wipe requests** tile shows you the summary report of the status of the wipe requests you made. Clicking on this tile will open a new blade that has more detailed information. For a detailed description of the wipe request information that is displayed in this blade, read the [Wipe managed company app data with Microsoft Intune](../Topic/Wipe_managed_company_app_data_with_Microsoft_Intune.md) topic.

    ![](../Image/AppManagement/AzurePortal_MAM_WipeRequestsSummary.png)

## See Also
[Create and deploy mobile app management policies with Microsoft Intune](../Topic/Create_and_deploy_mobile_app_management_policies_with_Microsoft_Intune.md)
[Configure data loss prevention app policies with Microsoft Intune](../Topic/Configure_data_loss_prevention_app_policies_with_Microsoft_Intune.md)

