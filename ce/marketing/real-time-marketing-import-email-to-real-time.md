---
title: "Import outbound emails, templates, and content blocks to real-time marketing (Dynamics 365 Marketing) | Microsoft Docs"
description: "Learn how to import outbound emails, templates, and content blocks to real-time marketing in Dynamics 365 Marketing."
ms.date: 06/30/2023
ms.custom: 
  - dyn365-marketing
ms.topic: article
author: alfergus
ms.author: alfergus
search.audienceType: 
  - admin
  - customizer
  - enduser
---

# Import outbound emails, templates, and content blocks to real-time marketing

Save time and resources, reuse and adapt your existing outbound assets to create engaging and relevant real-time marketing experiences. Easily import your outbound marketing emails, templates, and content blocks into real-time marketing to plug them into your real-time journeys.

## Import emails from outbound marketing

To start the email import process, go to Channels > Emails and click on the Import emails button 
on the top ribbon. The import wizard will appear. Follow the next steps:

1. **Select up to 50 emails** to copy from outbound to real-time marketing. You can use sorting and filtering to easily locate the emails.
   > [!div class="mx-imgBorder"]
   > ![Screenshot of selecting 50 emails in one go](media/real-time-marketing-select-emails-in-one-go.png "Screenshot of selecting 50 emails in one go")
1. In the **Settings** step you can specify if you also want to import the **content blocks** used and associated with these emails. You can skip this and the emails will be imported properly but the association between the imported emails and content blocks will be lost.
   > [!div class="mx-imgBorder"]
   > ![Screenshot of configuring your settings](media/real-time-marketing-settings-configuration.png "Screenshot of configuring your settings")

> [!NOTE]
> Emails including A/B tests cannot be imported at the moment and are skipped completely in the import process. These emails, along with any others that fail to be imported are gathered in a downloadable file, displayed when the import is completed.

## Import email templates from outbound marketing

Templates are imported in a similar fashion to emails. To start the template import process, go to **Assets > Templates** and click on the **Import templates** button on the top ribbon. The import wizard will appear and the steps you need to follow are identical to those needed for emails:

1. **Select up to 50 templates** to copy from outbound to real-time marketing. You can use sorting and filtering to easily locate the templates.
   > [!div class="mx-imgBorder"]
   > ![Screenshot of selecting 50 templates in one go](media/real-time-marketing-select-templates-in-one-go.png "Screenshot of selecting 50 templates in one go")
1. In the **Settings** step you can specify if you also want to import the **content blocks** used and associated with these templates. You can skip this and the templates will be imported properly but the association between the imported templates and content blocks will be lost.
   > [!div class="mx-imgBorder"]
   > ![Screenshot of configuring your template settings](media/real-time-marketing-template-settings-configuration.png "Screenshot of configuring your template settings")

## Import content blocks from outbound marketing

To import content blocks from outbound marketing, go to **Assets > Content blocks** and click on the **Import content blocks** button on the top ribbon. The import wizard will appear and all you need to do is to select the content blocks you’d like to copy to real-time marketing.

   > [!div class="mx-imgBorder"]
   > ![Screenshot of importing content blocks](media/real-time-marketing-import-content-blocks.png "Screenshot of importing content blocks")

## Using imported assets in real-time marketing

Imported emails, templates and content blocks are distinguished through the **[Outbound]** word tag they include in their title. There is also a new view, “**Imported from outbound marketing**” that can be used to filter assets down to the ones imported only.

All assets are imported in a **Draft** state and can therefore be reviewed before getting marked as ready to use. The conversion process during the import is accurate, but it is recommended to review all assets to make sure the content and settings are optimal for each one.
