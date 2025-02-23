---
filename: group-cards-on-board
content-type: reference
navigation-topic: boards
title: Use Groups on a Board
description: You can group cards on a board by assignee or by tag. When you select an option to group by, the cards appear in a swimlane format.
author: Lisa
feature: Agile
exl-id: 6f57a20e-0e47-4457-8605-9bce55c013ec
---
# Use groups on a board

You can group cards on a board by assignee or by tag. When you select an option to group by, the cards appear in a swimlane format. Unassigned cards or cards without tags appear in their own swimlane.

>[!NOTE]
>
>Any cards in the intake column are not included in a group, and the intake column is hidden when a group is applied. For information on the intake column, see [Add an intake column to a board](/help/quicksilver/agile/use-boards-agile-planning-tools/add-intake-column-to-board.md).

## Access requirements

+++ Expand to view access requirements for the functionality in this article.

You must have the following access to perform the steps in this article:

<table style="table-layout:auto"> 
 <col> 
 <col> 
 <tbody> 
  <tr> 
   <td role="rowheader">[!DNL Adobe Workfront]</td> 
   <td> <p>Any</p> </td> 
  </tr> 
  <tr> 
   <td role="rowheader">[!DNL Adobe Workfront] license</td> 
   <td> 
   <p>New: [!UICONTROL Contributor] or higher</p> 
   <p>or</p>
   <p>Current: [!UICONTROL Request] or higher</p>
   </td> 
  </tr> 
 </tbody> 
</table>

For more detail about the information in this table, see [Access requirements in Workfront documentation](/help/quicksilver/administration-and-setup/add-users/access-levels-and-object-permissions/access-level-requirements-in-documentation.md).

+++

## Group cards on a board

{{step1-to-boards}}

1. Access a board. For information, see [Create or edit a board](../../agile/get-started-with-boards/create-edit-board.md).
1. Click **[!UICONTROL Group]** to open the group panel on the left of the board.

   >[!NOTE]
   >
   >The default setting to group by is **[!UICONTROL None]**. You can select this option at any time to remove a group and show only the columns on the board.

1. To group the cards, select **[!UICONTROL Assignees]** or **[!UICONTROL Tags]**.

   The cards are grouped automatically. Click the arrow next to the group name to collapse and expand the group.

   ![Grouped cards on a board](assets/group-by-assignee.png)

1. Select what happens when a card is moved to another group.

   * **[!UICONTROL Add on assignees] / [!UICONTROL Add on tags]:** The assignees or tags in the new group are added to the existing list of assignees or tags on the card.
   * **[!UICONTROL Override assignees] / [!UICONTROL Override tags]:** The assignees or tags in the new group override all other assignees or tags, and become the only assignees or tags on the card.

   ![[!UICONTROL Group by options]](assets/group-by-rail.png)

1. Click **[!UICONTROL Hide groups]** to hide the group panel and display the full board.
