---
title: Creating and Publishing With Baselines
description: Creating and Publishing With Baselines in [!DNL Adobe Experience Manager Guides]
exl-id: 3c229c30-f2e0-4fb0-b60c-7bae60ef1a5b
TQID: https://experienceleague.adobe.com/P2NbWdOXSWFs40gpSWNrtDLR3VKofXymN5FlZSQRJ7Y
product_v2:
  - id: fae5e35a-80c9-4b94-9352-1a060a6aab1d
    internal-label: Experience Manager Guides
  - id: fd1f54a9-f50c-467d-8956-cebbaf4f3eb8
    internal-label: Experience Manager
feature_v2:
  - id: a3bd6397-2eb2-4908-a61c-226e26855dca
    internal-label: Publishing
  - id: d90290ec-3e61-4ebd-8649-bcafe0836803
    internal-label: Reports
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
---
# Creating and Publishing With Baselines

Using a baseline allows you to create a version of your map topics and related reference content. This can be based on a specific date or time, or labels. 

>[!VIDEO](https://video.tv.adobe.com/v/338993?quality=12&learn=on)

## Accessing the Baselines Tab in the Map Dashboard

You can access your baselines in the Map Dashboard.

1. Repository View, select the Ellipsis icon on your map to open the Options menu, and then **Open Map Dashboard.**

    ![ellipsis-map-dashboard.png](images/ellipsis-map-dashboard.png)
    The Map Dashboard opens in another tab.

1. Select **Baselines**.

    ![baseline-tab.png](images/baseline-tab.png) 

The Baselines tab displays.

## Creating a baseline based on labels

1. In the Baselines tab, select **Create**.

    ![create-baseline.png](images/create-baseline.png)

    The new baseline's information displays. Its default name is based on its creation date.

1. Give your baseline a new name, if needed.

1. Under the "Set the version based on" heading, select the circle for Label. 
    ![set-the-version.png](images/set-the-version.png) 

    >[!NOTE]
    >
    >NOTE: The *Use latest version if label is not present* checkbox is selected by default. If this is not selected, and topics or media files without the chosen label exist in your map, the Baseline creation process will fail.

1. Enter the label you would like to use.

1. Select **Save**.

Your baseline is created. A table of all of the topics and their associated information displays.

### Using the Browse All Topics feature 

The Browse All Topics feature allows you to view topic's information, including the version and label, as well as specify the version used. You can access it by selecting **Browse All Topics** when creating or editing your baseline.

![browse-all-topics.png](images/browse-all-topics.png)

## Creating a baseline based on date and time

You can also create baselines that are a snapshot in time. 

1. Ensure your Baselines tab is open, and select Create.

    ![create-baseline.png](images/create-baseline.png)
 
1. Under the "Set the version based on" heading, select the circle for "Version On."
    
    ![version-on.png](images/version-on.png)

1. Select the calendar icon and specify your desired date and time.

    ![calendar.png](images/calendar.png)

1. Give your baseline a new name if needed.

1. Select **Save**.

Your baseline is created. A table of all of the topics and their associated information displays.

### Adding labels to your baseline

You may want to assign a new label in bulk to all your map content.

1. Select the baseline for which you would like to add labels.

1. Select **Add Labels**.

    ![add-labels.png](images/add-labels.png) 

    The Add Label dialog displays.

1. Enter the label you want to assign, and select **Add**.

The label has been added to all topics.

## Generating an AEM Site output using a baseline

1. Navigate to the Output Presets tab in the Map Dashboard.

1. Select the AEM Site checkbox.

    ![aem-site-checkbox.png](images/aem-site-checkbox.png) 

1. Select **Edit**.

    ![edit-aem.png](images/edit-aem.png)
    
    A new page displays.

1. Select the Use Baseline checkbox, and choose the baseline you would like to use from the dropdown.

    ![baseline.png](images/baseline.png)

1. Select **Done**.

    ![done.png](images/done.png)

1. Select **Generate**.

    ![generate.png](images/generate.png)

    Your output has been generated with a baseline.

## Viewing the generated output

1. Navigate to the Outputs tab in the Map Dashboard.

1. Select the text in the Generation Setting column to open the output.
    ![aem-site-link.png](images/aem-site-link.png)

## Removing a baseline

1. In the Baselines tab, select the baseline you would like to remove.

1. Select **Remove**.

    ![remove-baseline.png](images/remove-baseline.png)

    The Remove Baseline dialog displays.

1. Select **Remove**.

The baseline is removed.

## Duplicating a baseline

1. In the Baselines tab, select the baseline you would like to duplicate.

1. Select **Duplicate**.

    ![duplicate.png](images/duplicate.png)

1. Select **Save**.

    ![save.png](images/save.png)
 
The duplicate baseline is created.

## Modifying a baseline

You can directly specify the version of a topic used in a baseline.

1. In the Baselines tab, select the baseline you would like to modify.
1. Select **Edit**.

    ![edit-aem.png](images/edit-aem.png)

1. Select **Browse All Topics**.

    ![browse-all-topics.png](images/browse-all-topics.png)

    A table of topics and their associated information displays.

1. For the topics you would like to modify, select the desired version from the dropdown under the Version column.

    ![version-dropdown.png](images/version-dropdown.png)
    
1. Select **Save**.
 
Your changes have been saved. Your baseline will now use the versions of the topic that you specified.

## Creating a customized AEM Site output preset

It is difficult to distinguish between default outputs of the same type in the Outputs tab. Using a customized output preset with a unique and user-friendly name allows you to address this issue.

In this case, we are creating an output preset based on a baseline.

1. Navigate to the Output Presets tab in the Map Dashboard.

1. Select **Create**.

    ![create-output-preset.png](images/create-output-preset.png)
    
    A new output preset page displays, called New Output.
1. In the Setting Name field, enter a user-friendly name.

1. Select the Use Baseline checkbox, and select the desired baseline from the dropdown menu.
    
    ![baseline.png](images/baseline.png) 

1. Select **Done**.
 
Your new output preset has been created, and displays on the output presets page.
