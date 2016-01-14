---
description: na
keywords: na
title: Windows 10 custom policy settings in Microsoft Intune
search: na
ms.date: 2015-10-08
ms.service: microsoft-intune
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: 5756b025-6fe9-418d-a1c4-cae576d31b79
ms.author: dbdc710f437843008017318979c6adba
---
# Windows 10 custom policy settings in Microsoft Intune
Use the [!INCLUDE[wit_firstref](../Token/wit_firstref_md.md)]**custom configuration policy** for Windows 10 and Windows 10 Mobile to deploy OMA-URI (Open Mobile Alliance Uniform Resource Identifier) settings that can be used to control features on Windows 10 and Windows 10 Mobile devices. These are standard settings that many mobile device manufacturers use to control device features.

This capability is intended to allow you to deploy Windows 10 settings that are not configurable with an [!INCLUDE[wit_nextref](../Token/wit_nextref_md.md)] policy. For information about the settings you can configure with these policies, see [Manage settings and features on your devices with Microsoft Intune policies](../Topic/Manage_settings_and_features_on_your_devices_with_Microsoft_Intune_policies.md).

For a list of OMA-URI settings that you can configure on enrolled Windows 10 devices, see [Custom URI settings for Windows 10 devices](../Topic/Custom_URI_settings_for_Windows_10_devices.md).

## How to create a Windows 10 Custom Policy

1.  In the [Microsoft Intune administration console](https://manage.microsoft.com), click **Policy** &gt; **Add Policy**.

2.  Under **Windows**, configure a **Custom Configuration (Windows 10 Desktop and Mobile and later)** policy.

    For help creating and deploying policies, see the [Use policies to manage computers and mobile devices with Microsoft Intune](../Topic/Use_policies_to_manage_computers_and_mobile_devices_with_Microsoft_Intune.md).

    You can only create and deploy a custom policy. Recommended settings are not available.

3.  Use the following table to help you configure the general policy settings:

    |Setting name|More information|
    |----------------|--------------------|
    |**Name**|Enter a unique name for the policy to help you identify it in the [!INCLUDE[wit_nextref](../Token/wit_nextref_md.md)] console.|
    |**Description**|Provide a description that gives an overview of the policy and other relevant information that helps you to locate it.|

4.  In the **OMA-URI Settings** section, click **Add** to add a setting. You can also edit or delete an existing setting.

5.  In the **Add or Edit OMA-URI** Setting dialog box, specify the following information:

    |Item|More information|
    |--------|--------------------|
    |**Setting name**|Enter a unique name for the OMA-URI setting to help you identify it in the list of settings.|
    |**Setting description**|Provide a description that gives an overview of the setting and other relevant information to help you locate it.|
    |**Data type**|Select the date type in which you will specify this OMA-URI setting. Choose from:<br /><br />-   **String**<br />-   **String (XML)**<br />-   **Date and time**<br />-   **Integer**<br />-   **Floating point**<br />-   **Boolean**|
    |**OMA-URI (case sensitive)**|Specify the OMA-URI you want to supply a setting for.|
    |**Value**|Specify the value to associate with the OMA-URI you specified previously.|

6.  Click **OK** to save the setting and return to the **Create Policy** page.

7.  Continue to add as many settings as you require. When you are done, click **Save Policy**.

The new policy displays in the **Configuration Policies** node of the **Policy** workspace.

## Deploy a Windows 10 Custom policy

1.  Deploy the policy to one or more groups of users or devices in your organization.

For more information about how to deploy policies, see [Use policies to manage computers and mobile devices with Microsoft Intune](../Topic/Use_policies_to_manage_computers_and_mobile_devices_with_Microsoft_Intune.md).

A status summary and alerts on the **Overview** page of the **Policy** workspace identify issues with the policy that require your attention. Additionally, a status summary appears in the **Dashboard** workspace.

## See Also
[Use policies to manage computers and mobile devices with Microsoft Intune](../Topic/Use_policies_to_manage_computers_and_mobile_devices_with_Microsoft_Intune.md)

