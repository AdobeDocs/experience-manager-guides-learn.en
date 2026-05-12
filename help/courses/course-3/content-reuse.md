---
title: Content Reuse
description: Recurring use of features in AEM Guides
exl-id: 453c5a09-0bcf-4760-87fc-df3ea4a3a30a
TQID: https://experienceleague.adobe.com/MJKB2oOi8SQbB6L8059wvMpFkwQ3M9iH2Jpxo3g9R0U
product_v2:
  - id: fae5e35a-80c9-4b94-9352-1a060a6aab1d
    internal-label: Experience Manager Guides
  - id: fd1f54a9-f50c-467d-8956-cebbaf4f3eb8
    internal-label: Experience Manager
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
topic_v2:
  - id: f5c2a4bb-71ca-4d7e-8efd-442250e6ba48
    internal-label: Content reuse
  - id: fc314d1d-7cb9-4a38-8dbd-8f9b6478f40d
    internal-label: Content strategy
---
# Content Reuse

One of the main features of DITA is the ability to reuse content. It allows reuse of  content from small phrases up to entire topics or maps.  However, for content to be effectively reused, it must be well managed. Ensure that you have an effective Content Strategy when working with reusable information.

>[!VIDEO](https://video.tv.adobe.com/v/342757?quality=12&learn=on)

## Create a reusable topic

When a change is made to a reusable source topic, the information will update everywhere the content is used. 

1. Navigate to the **Repository**.

1. Click the **contextual menu** next to the reuse folder.

1. Choose **Create > Dita Topic**.

1. Populate the fields in the Create New Topic dialog. For example:

    ![Confirmation](images/lesson-8/new-topic-dialog.png)

1. Click [!UICONTROL **Create**].

1. Add content to the topic as required.

## Add a new reusable element to a topic

There are several methods for adding reusable elements. Here, the first workflow is best when adding only one component. The second workflow is better for adding multiple reusable components.

### Workflow 1

1. Click in the topic at a valid location.

1. Select the **Insert Reusable Content** icon on the top toolbar.

    ![Confirmation](images/lesson-8/insert-reuse-icon.png)

1. In the Reuse Content dialog, click the [!UICONTROL **Folder**] icon.

1. Navigate to the required folder.

1. Choose a topic with reusable components.
For example:

    ![Confirmation](images/lesson-8/reusable-topic.png)

1. Click [!UICONTROL **Select**].

1. Choose a specific component to reuse.

1. Click [!UICONTROL **Select**].

The reusable element has now been inserted into the topic.

### Workflow 2

1. Navigate to **Reusable Contents** on the left panel.

1. Click the [!UICONTROL **Add**] icon on the Reusable Contents panel.

    ![Confirmation](images/lesson-8/reuse-contents-icon.png)

1. Navigate to a folder.

1. Select a specific topic or topics.

1. Click [!UICONTROL **Add**].

1. From the Reusable Contents panel, expand **Element Overview**.

1. Drag and drop an element into the topic at a valid location.

The reusable element has now been inserted into the topic.

## Assign an ID and value to an element

The dlentry you just created is a reusable element. Therefore, it requires an ID and a value.

1. Click inside the dlentry. 

1. In the Content Properties panel, click the dropdown under Attribute.

1. Select **ID**.

1. Type a logical name for the Value.

1. Save or version the topic so the change reflects in the Repository.

The ID and value have been assigned to the element.
