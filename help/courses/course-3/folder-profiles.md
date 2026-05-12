---
title: Folder Profiles
description: Creations and Use of Folder Profiles for AEM Guides
exl-id: 5a0daa68-51ae-42d0-8320-6e8bdb1fe545
TQID: https://experienceleague.adobe.com/ztMvUcFQ-GJTOEU3ikB-2WFgj--ttbY7JoSyGW6Poa8
product_v2:
  - id: fae5e35a-80c9-4b94-9352-1a060a6aab1d
    internal-label: Experience Manager Guides
  - id: fd1f54a9-f50c-467d-8956-cebbaf4f3eb8
    internal-label: Experience Manager
feature_v2:
  - id: ab01a588-7dea-43f2-a699-0b3f128465d6
    internal-label: Authoring
  - id: cb8c6a2a-3c38-4e40-867c-756f8c36bb0e
    internal-label: Configuration
subfeature_v2:
  - id: ad602516-aca3-4247-9ae8-f393d958efa9
    internal-label: Editor
  - id: b0521e56-a0b2-40b6-bf47-ebc98751f9ba
    internal-label: Web Editor configuration
  - id: b1ef4d86-3917-4b76-a0bc-4a4771f9b3b0
    internal-label: Profiles
  - id: f89f75b0-cf2e-4e96-aec8-fe8c39cbd0ef
    internal-label: Web Editor
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
---
# Folder Profiles

AEM provides quick access to configuration tools. By customizing Folder Profiles, different departments or products can have unique templates, authoring environments, conditional attribute profiles, Snippets, or even Web Editor configurations. 

Sample files that you may opt to use for this lesson are provided in the file [folderprofiles.zip](assets/folderprofiles.zip).

>[!VIDEO](https://video.tv.adobe.com/v/342758?quality=12&learn=on)

## Access Folder Profiles

Configurations are managed through the Folder Profiles icon.

1. From the Navigation screen, click the [!UICONTROL **Tools**] icon.

    ![Tools Icon](images/reuse/tools-icon.png)

1. Select **Guides** on the left panel.

1. Click the [!UICONTROL **Folder Profiles**] tile.

    ![Folder Profiles](images/reuse/folder-profiles-tile.png)

1. Select the desired profile. For example, choose **Global Profile**, which is the default profile.

    ![Global Profile](images/lesson-3/global-profile-tile.png)
 
## Edit Conditional Attributes in the Global Profile

Once you have accessed the Global Profile you can edit its configuration. The Global Profile settings are applied to all users unless otherwise specified.

1. In the Global Profile, select the **Conditional Attributes** tab.

1. Click [!UICONTROL **Edit**] in the top left corner of the screen.

    ![Conditional Attributes](images/lesson-3/edit-conditional-attributes.png)

1. Click [!UICONTROL **Add**].

1. Populate the **Name**, **Value**, and **Label** fields for the new condition.

    ![new Condition](images/lesson-3/new-condition.png)

1. Click [!UICONTROL **Save**] at the top left corner of the screen.
The new condition is now available to all users. You can select it in the Content Properties panel and apply it to content as required. 

## Build a new Folder Profile

In addition to the default Global Profile, you can create your own custom profiles.

1. From the Navigation screen, click the [!UICONTROL **Tools**] icon.

    ![Tools Icon](images/reuse/tools-icon.png)

1. Select **Guides** on the left panel.

1. Click the [!UICONTROL **Folder Profiles**] tile.

    ![Folder Profiles](images/reuse/folder-profiles-tile.png)
 
1. Click [!UICONTROL **Create**].

1. In the Create Folder Profile dialog.

    a. Name the profile.

    b. Specify a path.

    c. Click [!UICONTROL **Create**].

    ![Create Folder Profile](images/lesson-3/create-folder-profile.png)
 
A tile with the new profile name appears on the Folder Profiles page.

## Add administrative users from the General tab

Administrative users have rights to update the Conditional Attributes, Authoring Template, and Output Presets for the Folder Profile. 

1. Click on the tile to open the desired Folder Profile.

    ![Edit Folder Profile](images/lesson-3/edit-folder-profile.png)

1. Select the **General** tab.

1. Click [!UICONTROL **Edit**] at the top left of the screen.

1. Under Admin Users, either select a user from the dropdown or type a user's name.

1. Click [!UICONTROL **Add**].

    You can add multiple Admin Users if required. 

    ![Add Admin](images/lesson-3/add-admin.png)

1. Click [!UICONTROL **Save**] in the top right corner of the screen when all users have been added.

Administrative users are now assigned to this profile.

## Add a new audience from the Conditional Attributes tab

Once you have accessed the Global Profile you can edit its configuration. The Global Profile settings are applied to all users unless otherwise specified.

1. From within the desired Folder Profile, select the **Conditional Attributes** tab.

1. Click [!UICONTROL **Edit**] in the top left corner of the screen.

    ![Edit Conditional Attributes 2](images/lesson-3/edit-conditional-attributes-2.png)

1. Click [!UICONTROL **Add**].

1. Populate the **Name**, **Value**, and **Label** fields for the new condition.

    Clicking the [!UICONTROL **Plus**] sign allows you to add additional Value and Label pairs for the named attribute.

    ![Add Conditions](images/lesson-3/add-conditions.png)

1. Click [!UICONTROL **Save**] at the top left corner of the screen.

The new Conditional Attributes have been added to this profile.

## Choose a template and map from the Authoring Templates tab

AEM Guides comes with out-of-the-box authoring templates and maps. You can restrict them to specific authors. By default, the templates are stored in the Assets location within a DITA templates folder.

1. From within the desired Folder Profile, select the Authoring Templates tab.

1. Click Edit in the top left corner of the screen.

1. Add a Map Template.

    a. From the **Map Templates** dropdown, select an option from the available maps.

    b. Click [!UICONTROL **Add**].

    ![Map Templates](images/lesson-3/map-templates.png)

1. Add a Topic Template.

    a. From the **Topic Templates** dropdown, select an option from the available templates.

    ![Topic Templates](images/lesson-3/topic-templates.png)

1. Click [!UICONTROL **Add**].

1. Add additional Topic Templates as required.

1. When finished, click [!UICONTROL **Save**] at the top left of the screen.

The new Authoring Templates have been added to this profile.

## Delete nonessential presets from the Output Presets tab

You can configure each Output Preset based on the Folder Profile. Output Presets that are not needed should be removed.

1. From within the desired Folder Profile, select the **Output Presets** tab.

1. On the left panel, select the checkboxes of any presets that are not required.

    ![Delete Presets](images/lesson-3/delete-presets.png)

1. Click [!UICONTROL **Delete Preset**] in the top left corner of the screen.

1. In the Delete Preset dialog, click [!UICONTROL **Delete**].

    ![Delete](images/lesson-3/delete.png)
 
Now the only Output Presets showing are the ones that will be used.

## Upload a Snippet from the XML Editor Configuration tab

1. From within the desired Folder Profile, select the **XML Editor Configuration** tab.

1. Under XML Editor Snippets, click [!UICONTROL **Upload**].

    ![Upload Snippet](images/lesson-3/upload-snippet.png)

1. Navigate to a previously created Snippet. 

1. Click [!UICONTROL **Open**].

1. Click [!UICONTROL **Save**] at the top left of the screen.

You have successfully modified the Editor Configuration to include Snippets.

## Specify the Folder Profile in the Repository

In the Editor, you can see the results of the modifications you made to the Folder Profiles.

1. Navigate to **Repository View**.

1. Click on the folder for the content you want to work with.

1. Click the [!UICONTROL **User Preferences**] icon on the top toolbar.

    ![User Preferences](images/lesson-3/hr-user-prefs.png)

1. In the User Preferences dialog, select the desired Folder Profile from the dropdown.

    ![Select User Preferences](images/lesson-3/select-user-pref.png)

1. Click [!UICONTROL **Save**].

You have applied the Folder Profile to your content. Now, when you create a new DITA topic, you will see a restricted list of topic types based on the Folder Profil. The Audience Condition contains the Global settings as well as those specific to the Folder Profile. The Snippets file you uploaded created a set of default Snippets to choose from. The Map Dashboard displays the restricted Output Presets.
