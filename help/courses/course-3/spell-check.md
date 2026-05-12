---
title: Spell check and find/replace
description: Using spell check and find/replace in AEM Guides
exl-id: 5f39618d-a919-4d3c-a4de-2896f2d1bf20
TQID: https://experienceleague.adobe.com/cSdhulSc30KrwsGh1ldB2yn-8eSLccHBpyD-0S1x1M0
product_v2:
  - id: fae5e35a-80c9-4b94-9352-1a060a6aab1d
    internal-label: Experience Manager Guides
  - id: fd1f54a9-f50c-467d-8956-cebbaf4f3eb8
    internal-label: Experience Manager
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
---
# Spell Check and Find/Replace

The AEM Guides Editor has powerful spell check and Find and Replace capabilities.

>[!VIDEO](https://video.tv.adobe.com/v/342768?quality=12&learn=on)

Correct a spelling error

1. Locate an error in an open topic, shown with a red underline.

1. Press and hold Ctrl + click the secondary mouse button within the word.

1. Choose the correct spelling from the suggestions.

If the correct spelling is not suggested, you can always manually edit the word. 

## Switch to AEM Spell Check

You may want to use a spell check tool other than the browser's default dictionary.

1. Navigate to **Editor Settings**.

1. Select the **General** settings tab. 

    ![Spell Check Config](images/lesson-11/configure-dictionary.png)

1. There are two options:

    - **Browser Spell Check** — the default setting where spell check uses the browser's built-in dictionary.

    - **AEM Spell Check** — use this to build a custom word list using AEM's custom dictionary. 

1. Choose **AEM Spell Check**.

1. Click [!UICONTROL **Save**].

Configure a custom dictionary

The Administrator can change the settings so that the AEM dictionary recognizes custom words such as company names.

1. Navigate to the **Tools** pane.

1. Log in to **CRXDE Lite**.

    ![AEM UI CRXDE Lite Icon](images/lesson-11/crxde-lite.png)

1. Navigate to the **_/apps/fmdita/config node_**.

    ![CRXDE Lite Config Node](images/lesson-11/config-node.png)

1. Create a new file.

    a. Right-click on the config folder.

    b. Choose **Create > Create File**.

    ![New Dictionary File Creation](images/lesson-11/new-dictionary-file.png)

    c. Name the file _**user_dictionary.txt**_.

    ![User Dictionary text](images/lesson-11/user-dictionary.png)

    d. Click [!UICONTROL **OK**].

1. Open the file.

1. Add a list of words you want to include in your custom dictionary.

1. Click [!UICONTROL **Save All**].

1. Close the file.

Authors may need to restart their Web Editor session to get the updated custom word list in the AEM Dictionary. 

## Find and Replace in a single file

1. Click the Find and Replace icon on the top toolbar.

    ![Find Replace Icon](images/lesson-11/find-replace-icon.png)

1. In the bottom toolbar, type a word or phrase.

1. Click [!UICONTROL **Find**].

1. If required, type a word to replace the found word.

1. Click [!UICONTROL **Replace**].

## Find and Replace across the Repository

1. Navigate to the **Repository**.

1. Click the [!UICONTROL **Find and Replace**] icon at the bottom left of the screen.

1. Click the [!UICONTROL **Show Settings**] icon.

1. Choose either

    - **Checkout file before replace** — if enabled by an Administrator, the file will be checked out automatically before replacing search terms.

    - **Whole word only** — restricts the search to return only the exact word or phrase entered.

    ![Find Replace in Repository](images/lesson-11/repository-find-replace.png)

1. Click the [!UICONTROL **Apply Filter**] icon to select the path in the Repository where you want to perform the search.

1. Enter the terms to Find and Replace.

1. If required, select **Create new version after replace**.

1. Click [!UICONTROL **Find**].

1. Open the desired file and use the arrows to navigate from one found result to the next.

    ![Find Replace Navigation UI](images/lesson-11/find-replace-navigation.png)
