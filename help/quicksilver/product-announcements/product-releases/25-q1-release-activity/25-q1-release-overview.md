---
title: First Quarter 2025 release overview
description: This page provides information about functionality that is included in the First Quarter 2025 release. These enhancements are planned to become available in the Production environment throughout the quarter.
author: Nolan
feature: Product Announcements
recommendations: noDisplay, noCatalog
exl-id: 5bb898fa-d74e-4174-bc93-d8ffb8937680
---
# First Quarter 2025 release overview

This page provides information about functionality that is included in the First Quarter 2025 release. These enhancements are planned to become available in the Production environment throughout the quarter.

<span class="preview">Off-cycle features (those releasing to Production prior to the First Quarter 2025 release date) are highlighted in yellow.</span>

>[!IMPORTANT]
>
>The 23.3 release included the option to move your organization to monthly releases. Therefore, Workfront has changed the numbering scheme of releases to account for both monthly and quarterly release tracks. The first number designates the year, and the second number signifies the month of the release. Example: The release for April, 2025 reads as 25.4.
>
>Monthly and quarterly releases are planned to be available on the Thursday of the second full week of the month, unless otherwise specified.
>
>|Monthly release|Quarterly release|
>|----|----|
>|<ul><li>24.11 (November 14, 2024)</li><li>24.12 (December 12, 2024)</li><li>25.1 (January 15, 2025)</li></ul>| <ul><li>25.1 (January 16, 2025)</li></ul>|
>
>Note that for the final release of each quarter (25.1 this quarter), users on the fast release schedule will receive the release one day early.
>
>For more information on the fast release process, see [Enable or disable the fast release process](/help/quicksilver/administration-and-setup/set-up-workfront/configure-system-defaults/enable-fast-release-process.md). 

## Adobe Workfront enhancements

* [Administrator enhancements](#administrator-enhancements)<!--* [Boards enhancements](#boards-enhancements)-->
* [Document management enhancements](#document-management-enhancements)
* [Home enhancements](#home-enhancements)
* [Proofing enhancements](#proofing-enhancements)
* [Report and Dashboard enhancements](#report-and-dashboard-enhancements)
* [Other enhancements](#other-enhancements)

### Administrator enhancements

<table>
<col style="width: 50%;" />
<col style="width: 50%;" />
<tbody>
    <tr>
        <td>
            <p><span class="bold">Feature</span></p>
        </td>
        <td>
            <p><span class="bold">Release dates</span></p>
        </td>
    </tr>
    <tr>
        <td>
            <p><a href="/help/quicksilver/product-announcements/product-releases/25-q1-release-activity/25-q1-administrator-enhancements.md" class="MCXref xref" xrefformat="{para}">
            Preference to use project or user schedule for single-assignment tasks</a></p>
            [!BADGE New in Preview ]{type=Negative}
            <p>As a system or group administrator, you now have a new preference to indicate whether Workfront should use the project's or the user's schedule to calculate the timeline of the project when you assign one user to a task and both the project and the user are associated with a schedule.</p>
        </td>
        <td>
            <p><b>Available on these dates:</b></p>
            <ul>
                <li>Preview release: November 21, 2024</li>
                <li>Production for fast release: With the 24.12 release (December 2024)</li>
                <li>Production release for all customers: With the 25.1 release (January 2025)</li>
            </ul>
        </td>
    </tr>     
    <tr>
        <td>
            <p><a href="/help/quicksilver/product-announcements/product-releases/25-q1-release-activity/25-q1-administrator-enhancements.md" class="MCXref xref" xrefformat="{para}">
            Business rules now support hyperlinks</a></p>
            [!BADGE New in Preview ]{type=Negative}
            <p>You can now include hyperlinks in the custom error message of a business rule, to guide the user on how to modify their action within the constraint of the rule. The static URL could link to documentation or other pages that would be helpful to the user.</p>
        </td>
        <td>
            <p><b>Available on these dates:</b></p>
            <ul>
                <li>Preview release: November 21, 2024</li>
                <li>Production for fast release: With the 24.12 release (December 2024)</li>
                <li>Production release for all customers: With the 25.1 release (January 2025)</li>
            </ul>
        </td>
    </tr>    
    <tr>
        <td>
            <p><a href="/help/quicksilver/product-announcements/product-releases/25-q1-release-activity/25-q1-administrator-enhancements.md" class="MCXref xref" xrefformat="{para}">
            Filtering on native typeahead fields is now available</a></p>
            [!BADGE New in Preview ]{type=Negative}
            <p>When you add a native field reference to a custom form and it references a typeahead field (such as Portfolio, Company, or Owner), a filter option is now available. The filter allows you to limit the objects users can choose when they are using the field. This custom filter works the same as a filter on a custom typeahead field, using Text Mode to define the filter.</p>
        </td>
        <td>
            <p><b>Available on these dates:</b></p>
            <ul>
                <li>Preview release: November 21, 2024</li>
                <li>Production for fast release: With the 24.12 release (December 2024)</li>
                <li>Production release for all customers: With the 25.1 release (January 2025)</li>
            </ul>
        </td>
    </tr>
    <tr>
        <td>
            <p><a href="/help/quicksilver/product-announcements/product-releases/25-q1-release-activity/25-q1-administrator-enhancements.md" class="MCXref xref" xrefformat="{para}">
            "Move to" icon added to custom fields</a></p>
            [!BADGE In production for Fast Release ]{type=Positive}
            <p>When a custom form contains multiple sections with many fields, it can be difficult to move a field from one section to another by dragging and dropping. A "move to" icon has been added to each field, allowing you to select the section that the field is placed in.</p>
        </td>
        <td>
            <p><b>Available on these dates:</b></p>
            <ul>
                <li>Preview release: October 29, 2024</li>
                <li>Production for fast release: With the 24.11 release (November 14, 2024)</li>
                <li>Production release for all customers: With the 25.1 release (January 2025)</li>
            </ul>
        </td>
    </tr>
</tbody>
</table> 

<!--### Boards enhancements

<table>
<col style="width: 50%;" />
<col style="width: 50%;" />
<tbody>
    <tr>
        <td>
            <p><span class="bold">Feature</span></p>
        </td>
        <td>
            <p><span class="bold">Release dates</span></p>
        </td>
    </tr>
    <tr>
        <td>
            <p><a href="/help/quicksilver/product-announcements/product-releases/25-q1-release-activity/25-q1-boards-enhancements.md" class="MCXref xref" xrefformat="{para}">
            Change the owner of a board</a></p>
            <p>The creator of a board is the owner by default. The board owner is the only person who can delete that board or update its filters in the Configure panel. Functionality has been added to allow Workfront system administrators to change the owner of a board. The current owner of a board can also change the owner of that specific board.</p>
        </td>
        <td>
            <p><b>Available on these dates:</b></p>
            <ul>
                <li>Preview release: October 31, 2024</li>
                <li>Production for fast release: With the 24.11 release (November 14, 2024)</li>
                <li>Production release for all customers: With the 25.1 release (January 2025)</li>
            </ul>
        </td>
    </tr>
</tbody>
</table>--> 

### Document management enhancements

<table>
<col style="width: 50%;" />
<col style="width: 50%;" />
<tbody>
    <tr>
        <td>
            <p><span class="bold">Feature</span></p>
        </td>
        <td>
            <p><span class="bold">Release dates</span></p>
        </td>
    </tr>
    <tr>
        <td>
            <p><a href="/help/quicksilver/product-announcements/product-releases/25-q1-release-activity/25-q1-document-mgmt-enhancements.md" class="MCXref xref" xrefformat="{para}">
            Edit multiple documents at once</a></p>
            [!BADGE New in Preview ]{type=Negative}
            <p>You can now edit multiple documents at once. You can edit the descriptions and update custom forms.</p>
        </td>
        <td>
            <p><b>Available on these dates:</b></p>
            <ul>
                <li>Preview release: November 21, 2024</li>
                <li>Production for fast release: With the 24.12 release (December 2024)</li>
                <li>Production release for all customers: With the 25.1 release (January 2025)</li>
            </ul>
        </td>
    </tr>    
    <tr>
        <td>
            <p><a href="/help/quicksilver/product-announcements/product-releases/25-q1-release-activity/25-q1-document-mgmt-enhancements.md" class="MCXref xref" xrefformat="{para}">
            New Withdrawn status available for document version approvals</a></p>
            [!BADGE In production for Fast Release ]{type=Positive}
            <p>When a new version is added to a document with pending approvals, the approval for the previous version will now display as "Withdrawn," indicating that the prior approval process has closed due to the new version being added.</p>
        </td>
        <td>
            <p><b>Available on these dates:</b></p>
            <ul>
                <li>Preview release: November 7, 2024</li>
                <li>Production for fast release: With the 24.11 release (November 14, 2024)</li>
                <li>Production release for all customers: With the 25.1 release (January 2025)</li>
            </ul>
            <p><i>This feature is part of a phased release and only available for specific customers.</i></p>
        </td>
    </tr>
</tbody>
</table> 

### Home enhancements

<table>
<col style="width: 50%;" />
<col style="width: 50%;" />
<tbody>
    <tr>
        <td>
            <p><span class="bold">Feature</span></p>
        </td>
        <td>
            <p><span class="bold">Release dates</span></p>
        </td>
    </tr>
    <tr>
        <td>
            <p><a href="/help/quicksilver/product-announcements/product-releases/25-q1-release-activity/25-q1-home-enhancements.md" class="MCXref xref" xrefformat="{para}">
            Updated options in the My Focus column in Priorities</a></p>
            [!BADGE In production ]{type=Informative}
            <p>We have updated the options in the My Focus column to help you prioritize and sort your work in a more intuitive way. The new labels include</p>
            <ul>
                <li>Urgent</li>
                <li>High</li>
                <li>Normal</li>
                <li>Low</li>
            </ul>
        </td>
        <td>
            <p><b>Available on these dates:</b></p>
            <ul>
                <li>Preview release: November 14, 2024</li>
                <li><span class="preview">Production release for all customers: November 14, 2024</span></li>
            </ul>
        </td>
    </tr>
    <tr>
        <td>
            <p><a href="/help/quicksilver/product-announcements/product-releases/25-q1-release-activity/25-q1-home-enhancements.md" class="MCXref xref" xrefformat="{para}">
            View project details in Priorities</a></p>
            [!BADGE In production for Fast Release ]{type=Positive}
            <p>You can now view project details and comments from the worklist in Priorities.</p>
        </td>
        <td>
            <p><b>Available on these dates:</b></p>
            <ul>
                <li>Preview release: November 6, 2024</li>
                <li>Production for fast release: With the 24.11 release (November 14, 2024)</li>
                <li>Production release for all customers: With the 25.1 release (January 2025)</li>
            </ul>
        </td>
    </tr>
</tbody>
</table>

## Proofing enhancements

<table>
<col style="width: 50%;" />
<col style="width: 50%;" />
<tbody>
    <tr>
        <td>
            <p><span class="bold">Feature</span></p>
        </td>
        <td>
            <p><span class="bold">Release dates</span></p>
        </td>
    </tr>
    <tr>
        <td>
            <p><a href="/help/quicksilver/product-announcements/product-releases/25-q1-release-activity/25-q1-proofing-enhancements.md" class="MCXref xref" xrefformat="{para}">
            New browser extension for interactive review available in beta</a></p>
            [!BADGE In production ]{type=Informative}
            <p>We are introducing a new browser extension, the Adobe Workfront review tool, to replace the legacy browser extension for reviewing interactive ZIP content. The new Adobe Workfront review tool supports reviewing ZIP content across all common browsers.</p>
            <p>The legacy browser extension will be removed on February 28, 2025.</p>
        </td>
        <td>
            <p><b>Available on these dates:</b></p>
            <ul>
                <li>Preview release: November 7, 2024</li>
                <li><span class="preview">Production release for all customers: November 7, 2024</span></li>
            </ul>
        </td>
    </tr>
</tbody>
</table>

## Report and Dashboard enhancements

<table>
<col style="width: 50%;" />
<col style="width: 50%;" />
<tbody>
    <tr>
        <td>
            <p><span class="bold">Feature</span></p>
        </td>
        <td>
            <p><span class="bold">Release dates</span></p>
        </td>
    </tr>
    <tr>
        <td>
            <p><a href="/help/quicksilver/product-announcements/product-releases/25-q1-release-activity/25-q1-report-and-dashboard-enhancements.md" class="MCXref xref" xrefformat="{para}">
            First time reader account creation button for Data Connect</a></p>
            <p>Administrators accessing Data Connect for the first time are now presented with the option to create a new Snowflake reader account by clicking on a single button. The process takes a few minutes to complete, but requires no further action.</p>
        </td>
        <td>
            <p><b>Available on these dates:</b></p>
            <ul>
                <li>Preview release: November 14, 2024</li>
                <li><span class="preview">Production release for all customers: November 14, 2024</span></li>
            </ul>
        </td>
    </tr>
</tbody>
</table>

### Other enhancements

<table>
<col style="width: 50%;" />
<col style="width: 50%;" />
<tbody>
    <tr>
        <td>
            <p><a href="/help/quicksilver/product-announcements/product-releases/25-q1-release-activity/25-q1-other-enhancements.md" class="MCXref xref" xrefformat="{para}">
            Update on how moved or deleted assets in linked folders are managed</a></p>
            [!BADGE New in Preview ]{type=Negative}
            <p>We've changed the way moved and deleted assets are handled when using the Adobe Workfront integration with Experience Manager Assets and Assets Essentials:</p>
            <ul>
                <li>Deleted assets: When an asset is deleted inside of a linked folder in Assets or Assets Essentials, the deleted asset will be retained in the Project Documents area.</li>
                <li>Moved assets: When an asset is moved outside of a linked folder in Assets or Assets essentials, the moved asset will be retained in the Projects Documents area.</li>
            </ul>
        </td>
        <td>
            <p><b>Available on these dates:</b></p>
            <ul>
                <li>Preview release: November 21, 2024</li>
                <li><span class="preview">Production release for all customers: December 5, 2024</span></li>
            </ul>
        </td>
    </tr>
    <tr>
        <td>
            <p><a href="/help/quicksilver/product-announcements/product-releases/25-q1-release-activity/25-q1-other-enhancements.md" class="MCXref xref" xrefformat="{para}">
            Sections within a custom form are now collapsible and expandable</a></p>
            <p>When a custom form with multiple sections is attached to an object, you can now collapse and expand all sections except the default section at the top of the form. The administrator can also see this functionality when previewing the form in the form designer.</p>
        </td>
        <td>
            <p><b>Available on these dates:</b></p>
            <ul>
                <li>Preview release: November 11, 2024</li>
                <li>Production for fast release: With the 24.12 release (December 2024)</li>
                <li>Production release for all customers: With the 25.1 release (January 2025)</li>
            </ul>
        </td>
    </tr>
    <tr>
        <td>
            <p><a href="/help/quicksilver/product-announcements/product-releases/25-q1-release-activity/25-q1-other-enhancements.md" class="MCXref xref" xrefformat="{para}">
            AI Assistant can now work with projects, tasks, and issues</a></p>
            [!BADGE In production for Fast Release ]{type=Positive}
            <p>To make it easier to manage your work items in Workfront, we've updated AI Assistant to work with projects, tasks, and issues. Now, AI Assistant can locate  projects, tasks, and issues based on criteria you specify.</p>
        </td>
        <td>
            <p><b>Available on these dates:</b></p>
            <ul>
                <li>Preview release: October 31, 2024</li>
                <li>Production for fast release: With the 24.11 release (November 14, 2024)</li>
                <li>Production release for all customers: With the 25.1 release (January 2025)</li>
            </ul>
        </td>
    </tr>
    <tr>
        <td>
            <p><a href="/help/quicksilver/product-announcements/product-releases/25-q1-release-activity/25-q1-look-and-feel-updates.md" class="MCXref xref" xrefformat="{para}">
            Look-and-feel updates during the First Quarter 2025 timeframe</a></p>
            <p>Minor updates to the look and feel of various areas of the Adobe Workfront application are being made within the First Quarter 2025 timeframe. Review the individual release notes for specific release dates.</p>
        </td>
        <td>
            <p><b>Available on these dates:</b></p>
            <ul>
                <li>Preview release: Throughout the First Quarter 2025 release timeframe</li>
                <li><span class="preview">Production release: Review the release notes for specific dates</span></li>
            </ul>
        </td>
    </tr>                            
</tbody>
</table>   

<!--
### Functionality soon to be removed from Workfront

The following functionality is soon to be removed from Workfront:
-->

## Announcements

### Workfront Fusion enhancements

New features in Workfront Fusion are available in Production at a cadence outside of the First Quarter 2025 release schedule. For more information about the latest features, see [Adobe Workfront Fusion release activity](/help/quicksilver/product-announcements/product-releases/fusion-release-activity/fusion-release-activity.md).

### Workfront Planning enhancements

New features in Workfront Planning are available in Production. For more information about the latest features, see [Adobe Workfront Planning First Quarter 2025 release activity](/help/quicksilver/product-announcements/product-releases/planning-release-activity/planning-release-activity-25-q1.md).

### Workfront Scenario Planner enhancements

There are no Scenario Planner updates at this point in the release. This area will be updated when updates are available.

### Workfront Proof enhancements

There are no Workfront Proof updates at this point in the release. This area will be updated when updates are available.

### Workfront Goals enhancements

There are no Workfront Goals updates at this point in the release. This area will be updated when updates are available.

### API version 19

For API version 19, we've modified some resources and endpoints. Some of the changes support new functionality, and others make it easier for you to use the information available through the API.

For information on what's new and updated, see [What's new in API version 19](/help/quicksilver/wf-api/api/new-api-version-19.md).

For information on API versions, see [API versioning and support schedule](/help/quicksilver/wf-api/api/api-version-support-schedule.md).

### Workfront Maintenance Updates

For information about the maintenance updates made during the First Quarter 2025 release, see [Workfront Maintenance Updates](https://experienceleague.adobe.com/docs/workfront-known-issues/releases/current-updates.html).

### Training updates

Explore the latest updates made to learning programs, learning paths, videos, and guides for each Adobe Workfront product release. For more information, see the "What's New" section of the [Workfront Tutorials page](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/home.html).
