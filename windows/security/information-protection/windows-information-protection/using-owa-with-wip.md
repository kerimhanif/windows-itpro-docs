---
title: Using Outlook on the web with Windows Information Protection (WIP) (Windows 10)
description: Options for using Outlook on the web with Windows Information Protection (WIP).
keywords: WIP, Windows Information Protection, EDP, Enterprise Data Protection, WIP and OWA configuration, OWA, Outlook Web access
ms.prod: w10
ms.mktglfcycl: explore
ms.sitesec: library
ms.pagetype: security
author: eross-msft
ms.localizationpriority: medium
ms.date: 09/11/2017
---

# Using Outlook on the web with Windows Information Protection (WIP)
**Applies to:**

- Windows 10, version 1607 and later
- Windows 10 Mobile, version 1607 and later

>Learn more about what features and functionality are supported in each Windows edition at [Compare Windows 10 Editions](https://www.microsoft.com/en-us/WindowsForBusiness/Compare).

Because Outlook on the web can be used both personally and as part of your organization, you have the following options to configure it with Windows Information Protection (WIP):

|Option |Outlook on the web behavior |
|-------|-------------|
|Disable Outlook on the web. Employees can only use Microsoft Outlook 2016 or the Mail for Windows 10 app. | Disabled. |
|Don't configure outlook.office.com in any of your networking settings. |All mailboxes are automatically marked as personal. This means employees attempting to copy work content into Outlook on the web receive prompts and that files downloaded from Outlook on the web aren't automatically protected as corporate data. |
|Add outlook.office.com to the Cloud resources network element in your WIP policy. |All mailboxes are automatically marked as corporate. This means any personal inboxes hosted on Office 365 are also automatically marked as corporate data. |

>[!NOTE]
>These limitations don’t apply to Outlook 2016, the Mail for Windows 10 app, or the Calendar for Windows 10 app. These apps will work properly, marking an employee’s mailbox as corporate data, regardless of how you’ve configured outlook.office.com in your network settings. 




