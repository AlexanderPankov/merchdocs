---
ee_only: true
title: Faceting Workspace
group: marketing
---

The workspace lists all facets that are currently available. The facets that are pinned to the top of the Facets list appear first, followed by dynamic facets. The list can be filtered to show all, pinned, or dynamic facets.

![Faceting workspace]({% link live-search/assets/faceting-workspace.png %}){: .zoom}
_Faceting Workspace_

## Set the scope

If your Magento installation includes multiple stores or store views, set **Scope** to the [store view]({% link configuration/scope.md %}) where your facet settings apply.

## Filter the list

1. Click the **Filter by** control.
1. Choose one of the following options:

  - All filters
  - Pinned
  - Dynamic

![Faceting workspace]({% link live-search/assets/facets-filter-by.png %}){: .zoom}
_Filter by_

## Add a facet

1. Click **Add facets**.

1. See [Add Facets]({% link live-search/facets-add.md %}) for instructions.

## Column Descriptions

|Column |Description |
|--- |--- |
|Name |The label of the facet that is visible in the storefront. |
|Select type | The selection method that is used to choose a facet value from the storefront. Options: Multi-select (and), Multi-select (or) Single-select |
|Sort type |The sorting order of facet values. Options: Alphabetical, Count |
|Max value |The number of facet values that are available in the storefront as filters, with a maximum of 10. |

## Controls

|Add facets | Opens the [Add Facets]({% link live-search/facets-add.md %}) page.|
|Filter by |Determines the type of facets that appear in the list. Options: All, Pinned, Dynamic |
|![Move selector]({% link live-search/assets/btn-move.png %})|Changes the order of pinned facets at the top of the Filters list. |
|![Pin selector]({% link live-search/assets/btn-pin-blue.png %}) |Pins or unpins a facet to the top of the filters list. The pin is blue for a pinned facet and gray for an unpinned facet. Options: Blue (pinned), gray (unpinned)|
|(...)|Displays more actions that can be applied to the selected facet. Options: Edit, Delete |
