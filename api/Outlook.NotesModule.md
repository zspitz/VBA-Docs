---
title: NotesModule Object (Outlook)
keywords: vbaol11.chm3198
f1_keywords:
- vbaol11.chm3198
ms.prod: outlook
api_name:
- Outlook.NotesModule
ms.assetid: cdbdde08-0773-a78d-3809-a3811975bcc1
ms.date: 06/08/2017
---


# NotesModule Object (Outlook)

Represents the  **Notes** navigation module in the Navigation Pane of an explorer.


## Remarks

The  **NotesModule** object, derived from the **[NavigationModule](Outlook.NavigationModule.md)** object, provides access to the navigation groups contained in the **Notes** navigation module of the Navigation Pane for an explorer. Use the **[GetNavigationModule](Outlook.NavigationModules.GetNavigationModule.md)** method or the **[Item](Outlook.NavigationModules.Item.md)** method of the **[NavigationModules](Outlook.NavigationModules.md)** collection for the parent **[NavigationPane](Outlook.NavigationPane.md)** object to retrieve a **NavigationModule** object, then use the **[NavigationModuleType](Outlook.NavigationModule.NavigationModuleType.md)** property of the **NavigationModule** object to retrieve the navigation module type. If the **NavigationModuleType** property is set to **olModuleNotes**, you can then cast the **Module** object reference as a **NotesModule** object to access the **[NavigationGroups](Outlook.NotesModule.NavigationGroups.md)** property for that navigation module.

You can use the  **[Visible](Outlook.NotesModule.Visible.md)** property to determine if the navigation module is visible and the **[Position](Outlook.NotesModule.Position.md)** property to return or set the display position of the navigation module within the Navigation Pane. You can use the **[Name](Outlook.NotesModule.Name.md)** property to return the display name of the **Notes** navigation module within the Navigation Pane.


## Properties



|**Name**|
|:-----|
|[Application](Outlook.NotesModule.Application.md)|
|[Class](Outlook.NotesModule.Class.md)|
|[Name](Outlook.NotesModule.Name.md)|
|[NavigationGroups](Outlook.NotesModule.NavigationGroups.md)|
|[NavigationModuleType](Outlook.NotesModule.NavigationModuleType.md)|
|[Parent](notesmodule-parent-property-outlook.md)|
|[Position](Outlook.NotesModule.Position.md)|
|[Session](notesmodule-session-property-outlook.md)|
|[Visible](Outlook.NotesModule.Visible.md)|

## See also


[Outlook Object Model Reference](http://msdn.microsoft.com/library/73221b13-d8d8-99b8-3394-b95dbbfd5ddc%28Office.15%29.aspx)