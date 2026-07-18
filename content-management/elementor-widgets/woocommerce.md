# WooCommerce

Product-showcase widgets - only registered in the Elementor panel when WooCommerce is active.

## Bukpod Products

* **Content** - Style (`Default`/`List`, responsive), Columns (1-10 or Default, responsive), Rows, **Enable Carousel**, **Pagination** (hidden when Source is Related/Upsells/Cross-sells, or when carousel is on) → reveals **Allow Order** (front-end sort dropdown - doesn't work if this widget is on the front page) and **Show Result Count**.
* **Query** - Source: `Manual Selection` (pick specific products) / `Current Query` / **Related Products** / **Upsells** / **Cross-sells**, plus the usual Include/Exclude by category/tag/author, order, offset, items per page.
* **Title** section (only shown when Source = Related Products/Upsells/Cross-sells) - Title switcher, per-type heading text override (defaults to "Related Products" / "You may also like…" / "You may be interested in…"), Title Alignment.
* Uses the shared **Carousel Options** when Enable Carousel is on (see [Content & Blog](content-and-blog.md) for what that includes).
* **Style tab**: normal product-card design controls, plus a dedicated Title style section for the Related/Upsell/Cross-sell heading.

## Bukpod Category Product

* **Config** - **Items** repeater: Include Category (pick a product category, indented by hierarchy), Title override, Choose Image (overrides the category's thumbnail), Link to (overrides the term's own link).
* **Image Size**.
* **Layout** - `Style 1` / `Style 2` / `Style 3` (adds a corner arrow-button overlay and repositions the product count).
* **Count** (switcher) - shows the product count per category (`(12)` for Style 1/2, `12 Items` for Style 3).
* **Enable Carousel** toggles between Column Options and Carousel Options.
* **Style tab**: Item container (background/border/radius/padding), Image (height, radius+overflow), Title (pill padding/margin/radius, typography, Normal/Hover color+background), Count typography/color, Button/Icon (Layout 2/3 only - Normal/Hover background+icon color, size, padding, radius).
