---
title: Configuring Layered Navigation
group: marketing
---

{:.bs-callout-info}
[Live Search]({% link live-search/overview.md %}) is an advanced search service that is available for Magento Commerce. This topic describes standard Magento price navigation. If your installation of Magento Commerce has Live Search installed, see the Live Search [Quick Tour]({% link live-search/quick-tour.md %}) and [Faceting]({% link live-search/facets.md %}).

The layered navigation configuration determines if a product count appears in parentheses after each attribute, and the size of the step calculation that is used in price navigation.

1. On the _Admin_ sidebar, go to **Stores** > _Settings_ > **Configuration**.

1. In the left panel, expand the _Catalog_ section and choose **Catalog** underneath.

1. Expand the _Layered Navigation_ section and do the following:

    ![]({% link images/images/config-catalog-catalog-layered-navigation.png %}){: .zoom}
    [_Layered Navigation_]({% link configuration/catalog/catalog.md %})

    {:.bs-callout-info}
    If necessary, first deselect the **Use system value** checkbox to change these settings.

    - To display the number of products found for each attribute, set **Display Product Count** to `Yes`.

    - Set **Price Navigation Step Calculation** to `Automatic (equalize price ranges)`.

1. When complete, click <span class="btn">Save Config</span>.
