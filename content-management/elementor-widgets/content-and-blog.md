# Content & Blog

Widgets for blog listings, feature blocks, Service, and Team content.

## Posts Grid

* **Style** - `Style 1` (grid) or `Style 2` (list).
* **Enable Carousel** (switcher) - when off you get **Column Options** (columns/spacing) and a **Pagination** section (None/Numbers/Previous-Next/both, page limit, custom Previous/Next labels); when on you get the shared **Carousel Options** (see hint below).
* **Image Size**.
* **Query** section - Source (`Manual Selection` by search, or `Current Query`), Include/Exclude by Term or Author, order, order direction, offset, posts per page.
* **Style tab**: Wrapper (padding/margin/background/border/radius), Image radius (+ Width/Height for list style), Content (background, vertical alignment for list style, Title and Description typography/color - Description only shows for Style 2).

## Bukpod Archive Post

Same visual system as Posts Grid, but automatically pulls the current archive/blog query - only shows content on actual archive pages.

* **Style** - Grid/List. No manual Query section (it follows whatever archive page it's placed on).
* **Column Options** always available (no carousel option on this widget).
* **Style tab**: same Wrapper/Image/Content sections as Posts Grid, plus a Pagination style section (spacing, alignment).

## Bukpod Icon Box

* **Icon** picker → once set, reveals **View** (Default/Stacked/Stacked Bukpod/Framed) and **Effect** (Default/Rotate/Zoom hover effect); **Shape** (Circle/Square) only shows when View ≠ Default.
* **Title**, **Description Top**, **Description Bottom** (textareas), **Link** (wraps the icon+title in a link), **Title HTML Tag** (H1-H6/div/span/p).
* **Style tab**: box background (Normal/Hover), Icon Position (Left/Top/Right), vertical alignment, box padding/border/radius/shadow; Icon section has Normal/Hover Primary/Secondary Color + Hover Animation; Title/Description Top/Description Bottom each get their own style section, shown only if that field has content.

## Bukpod Steps

* **Items** repeater - Title, Content, **Step Number** (free text, e.g. "Step 01" - also renders an arrow-button link when **Link to** is set), Image, Link to.
* **Style** - `Style 1` / `Style 2`; **Enable Carousel** only available on Style 2 (with the shared Column Options / Carousel Options toggling accordingly).
* **Style tab**: item height (per style, responsive), items gap, radius, content padding, overlay color (Normal/Active), Title/Content typography+color (Normal/Active), Number & Meta typography/color (Normal/Active) + divider color, button padding/color/background (Normal/Hover).

## Bukpod Pricing

A single pricing card per widget instance (not a repeater at the top level).

* **Header** - Title, Description.
* **Pricing** - Currency Symbol (None/Dollar/Euro/Pound/Custom → Custom reveals a text field), Price, Sale price (shown struck-through when set), Period (e.g. "month").
* **Button** - Button Text, Icon, Link.
* **Features** - Features Title, then a **Features** repeater (Icon, Text, **Enabled** switcher - disabled items render with a struck-through/disabled style).
* **Popular** - "Most Popular" switcher → reveals Popular Title + Popular Icon and adds a ribbon/badge style.
* **Style tab**: Popular badge, Wrapper, Info Box, Title, Description, Price (Currency Position Before/After, price/old-price/period color+typography), Button (Normal/Hover), Features Title, Features List (enabled vs. disabled colors set separately).

## Bukpod Service

Displays a grid/list of your [Service](../service/README.md) posts. See [Bukpod Service Widget](../service/pavo-service.md) for the walkthrough. Control reference:

* **Style** - Style 1/Style 2; **Hidden Image** and **Sticky** (sticky-scroll items) switchers, Style 1 only.
* **Services** repeater - **Include Service** (search your Service posts), then optional overrides: Choose Image, Title, Description, Link, Background Color - any left blank falls back to that service post's own title/excerpt/permalink/featured image.
* **Style tab**: Layout (items gap, padding, sticky offset), Item (background/border/radius/divider), Title/Excerpt (typography, color, max-width), Icon and Image sizing, Button (Normal/Hover, Style 1 only).

## Bukpod Service Meta

Placed inside a single Service template - pulls straight from the current service post's meta, no manual fields.

* **Show Icon** (switcher) - shows the service's Image field.
* **Show Features List** (switcher) - shows the service's Features list.
* **Style tab**: icon size, features typography/color/item-gap.

## Bukpod Archive Services

The archive-page version of Bukpod Service - automatically shows the current Service archive/category query, same rendering as Bukpod Service. See [Archive & Category Page](../service/archive-and-category-page.md).

* **Style** - Style 1/Style 2, **Image Size**. No repeater - only shows content on Service archive/search/home context.
* **Style tab**: same sections as Bukpod Service, plus a Pagination style section (spacing, alignment).

## Bukpod Team Box

See [Bukpod Team Box Widget](../teams/pavo-team.md) for the walkthrough. Control reference:

* **Team Members** repeater - Image, Name, Job, Link to, and a nested **Socials** repeater (Title, Icon, Link - up to 5 per member).
* **Image Size**, **Column Options**.
* **Style tab**: Media Box (background/border/radius/padding), Image (radius + hover Scale/Top Offset/Border Radius), Socials (gap, icon size/color/background/border, hover states), Name & Job typography/color.

{% hint style="info" %}
**Enable Carousel**, when available on a widget, reveals a shared **Carousel Options** block: Slides to Show/Scroll, Space Between, Navigation (Arrows/Dots/Both/None), Autoplay (+ Pause on Hover/Interaction, speed), Infinite Loop, Effect (Slide/Fade - only when Slides to Show = 1), Animation Speed, Direction, and full arrow/dot styling in the Style tab.
{% endhint %}
