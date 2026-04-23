---
title: Working with Reports
description: Working with Reports in [!DNL Adobe Experience Manager Guides]
exl-id: 755506a6-c416-4a8c-8359-8db7e63a90a4
TQID: https://experienceleague.adobe.com/k4uvmKzypx6Z29GkMbzV01G62BQp4A3aNDuQYjJDhUI
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
# Working with Reports

The Reports tab in the Map Dashboard allows you to identify and resolve broken links, content that is referenced and reused (conrefs), cross references, or other missing information. 

>[!VIDEO](https://video.tv.adobe.com/v/339039?quality=12&learn=on)

## Preparing for the exercise

You can download sample files for the exercise here.

[Exercise-Download](assets/exercises/working-with-reports.zip)

## Uploading Assets

1. In Repository View, select the Ellipsis icon on your main folder to open the Options menu.

    ![ellipses-9.png](images/ellipses-9.png)
 
1. Select **[!UICONTROL Upload Assets]**.

    ![upload-assets.png](images/upload-assets.png)
 
1. Select the files you would like to upload to the folder, and select **Upload**.
    
The DITA files open and you should review them for issues with missing content, conrefs, or cross references.

## Creating a map

1. Select the Ellipsis icon on your main folder to open the Options menu.

    ![ellipses-9.png](images/ellipses-9.png)
 
1. Select **Create > Map**.

    ![create-map.png](images/create-map.png)

    The Create New Map dialog displays.

1. In the Template field, select **Bookmap** (or **Map** based on the content type you are creating) from the drop-down menu and give your map a title.

1. Select **Create**.

Your map is created, and the left rail automatically changes from the Repository view to the Map view.

## Inserting map components

1. Select the pencil icon in the left rail.
This is the Edit icon, and allows you to open the map in the editor.

    ![edit-map.png](images/edit-map.png)

1. Switch back to Repository view by selecting the Repository icon.

    ![repository-button.png](images/repository-button.png)

1. Add a topic to the map by dragging and dropping it from the Repository into the map in the editor.
The line indicator will show you where your topic will be placed.

1. Continue to add topics as needed.

1. When finished, select **Save As New Version.**
 
    ![save-as-new-version.png](images/save-as-new-version.png)

1. In the *Comments for new Version* field, enter a descriptive comment.

1. Select **Save**. 

## Generating an AEM Site output

1. In the Repository, select the Ellipsis icon on your map to open the Options menu, and then **Open Map Dashboard.**

    ![open-map-dashboard.png](images/open-map-dashboard.png)

    The Map Dashboard opens in another tab.
1. In the Output Presets tab, select **AEM Site**.

    ![aem-site-checkbox](images/aem-site-checkbox.png)
 
1. Select **Generate**.

1. Navigate to the Outputs page to view the status of your generated outputs.
If there are errors the Outputs tab may display an orange circle under the Generation Setting column instead of green, indicating that generation is complete.

1. Select the link under the Generation Setting column to open the generated output.
Review your output for missing content.

## The Reports tab

The Reports tab displays a topic summary, and a table containing topic information and the issues within your map. 

Ideally you always check the Reports for a map after importing content.

![reports.png](images/reports.png)

The Missing Elements column indicates the number of missing images and broken conrefs. You can select the **Pencil** icon to open the topic in the editor.

## Resolving missing images

If images are missing from your files a common cause might be that content has been uploaded, but images have not. If so, resolve the missing image issues by uploading images to a specific folder matching the path and filenames expected by files.

1. In *Repository View*, select the Ellipsis icon on your images folder to open the Options menu.

    ![image-ellipsis.png](images/image-ellipsis.png)   
 
1. Select **[!UICONTROL Upload Assets]**, and select the missing images.

1. Select **Upload**.

The missing images have been uploaded. Now, a newly generated AEM Site output will display these images, and the Reports tab will no longer display any missing image errors.

## Resolving broken conrefs

If content that is referenced elsewhere (a conref) links to for a file within another folder (for example, one named "reuse.") and the content is not uploaded, an error must be resolved. For example, you must create a subfolder named "reuse," and upload the missing file into "reuse."

### Uploading an asset with the [!UICONTROL Assets] UI

In addition to the [!UICONTROL Upload Assets] option, you can upload assets by dragging and dropping into the Assets UI.

1. In Repository View, select the Ellipsis icon on your reuse folder to open the Options menu.

    ![reuse-ellipsis.png](images/reuse-ellipsis.png)
 
1. Select **View in Assets UI**. 

    ![assets_ui.png](images/assets_ui.png)
 
1. Drag and drop the file into the folder.
The file is uploaded, and the conref error is resolved.

All the errors have now been resolved. The Reports page will indicate that there are no more errors, and generating an AEM Site results in a complete output with no missing components.
