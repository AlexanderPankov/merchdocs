---
ee_only: true
title: Rules Workspace
group: marketing
---

The rules workspace lists the current selection of rules and their status, and provides access to tools you need to create and manage rules. From the workspace you can:

- Search for rules
- View rule details
- Activate/deactivate rules
- Delete rules
- Access the rule editor

  ![Rules workspace]({% link live-search/assets/rules-workspace.png %}){: .zoom}
  _Rules workspace_

## Set the scope

If your Magento installation includes multiple stores or store views, set **Scope** to the [store view]({% link configuration/scope.md %}) where your rules apply.

## Show/hide columns

1. In the upper-right corner, click **Show/hide** ( ![Show/hide columns button]{% link live-search/assets/btn-show-hide-columns.png %})) columns.

   The visible columns have a blue check mark in the options menu. The rule name is the only column that cannot be hidden.

   ![Rules workspace]({% link live-search/assets/rules-workspace-show-hide-columns.png %}){: .zoom}
   _Show/hide columns_

1. In the menu, do either of the following:

   - To show a hidden column, click any column name without a check mark.

   - To hide a visible column, click any column name with a check mark.

   ![Rules workspace]({% link live-search/assets/rules-workspace-all-columns.png %}){: .zoom}
   _Rules workspace with all columns visible_

## Filter rules by status

If your store has many rules, you can filter the rules by status to shorten the list. By default, the Rules list displays all rules.

  ![Rules - filter by status]({% link live-search/assets/rules-workspace-filter-status.png %}){: .zoom}
  _Filter rules by status_

To list only rules with a specific status setting, set **Status** to one of the following:

- All
- Active
- Inactive
- Scheduled

  ![Rules - filter by status]({% link live-search/assets/rules-workspace-filter-status-active.png %}){: .zoom}
  _Rules filtered by "Active" status_

## Search rules by name

Begin typing the name of the rule, or any word in the rule name.

Search finds the matching rule(s) as you type. The string of matching characters are highlighted in the name of each rule found.

  ![Rules - search by name]({% link live-search/assets/rules-workspace-search-name.png %}){: .zoom}
  _Search by name_

{: #view-details}
## View details

The details panel shows the rule name, status, conditions and events, start and end date, description, and date last edited. Rules can be enabled, edited, and deleted from the details panel.

1.	On the _Rules_ tab, find the rule in the grid that you want to view and click **More** (…).

1.	Click **View details**.

     You can do any of the following from the View details panel:

      - Edit Rule
      - Delete Rule
      - Enable/Disable Rule

1. To close the _View details_ panel, click **Close** (X) in the upper-right corner.

  ![Rule - details]({% link live-search/assets/rules-workspace-details.png %}){: .zoom}
  _Rule details_

## Column Descriptions

{: .fields-table }
|Column |Description |
|--- |--- |
|Name |The name of the rule. |
|Last Updated |The date that the rule was last updated. |
|Start date |The start date of a scheduled rule. |
|End date |The end date of a scheduled rule. |
|Status |The color-coded status indicates the current state of the rule. Use the Status control above the grid to filter rules by status. Values: All status <br />Active (blue)<br />Scheduled (Orange)<br />Inactive (gray)|
|(...)|Displays more actions that can be applied to the selected rule. Options: Edit, View details, Delete |

## Controls

{: .fields-table }
|Control |Description |
|--- |--- |
|<span class="btn">Add rule</span> | Opens the [rule]({% link live-search/rules-add.md %} editor.|
|Status |Filters the list of rules by status. Options: All, Active, Inactive, Scheduled |
|![Column selector]({% link live-search/assets/btn-show-hide-columns.png %})|Specifies the columns that visible in the grid. Options: Last updated, Start date, End date, Status |
|Search |Searches for a rule by full name or partial match. |

## Rule Details

{: .fields-table }
|Field |Description |
|--- |--- |
| Status | The current status of the rule.|
| Conditions | The search query that describes the condition(s) associated with the rule.|
| Start Date | The date the rule goes into effect, if scheduled.|
| End Date | The date the rule expires, if scheduled.|
| Description | A brief description of the rule.|
| Last updated | The date and time the rule was last updated.|
| Enabled | A control that changes the status of the rule. Options: Enabled / Disabled.|

<style>
.fields-table td:first-of-type {
width: 270px;
}
</style>