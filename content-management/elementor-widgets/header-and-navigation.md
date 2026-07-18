# Header & Navigation

Widgets used to build the Header, Footer, and mobile navigation templates in Theme Builder.

## Site Logo

* **Custom Image** - `No` uses your Customizer [logo](../../setting/logo.md) automatically; `Yes` reveals an **Add Image** picker so this instance can use a different image (e.g. a light-colored logo for a transparent header).
* **Image Size**, **Alignment** (Left/Center/Right, responsive).
* **Caption** - `No`/`Yes` → reveals a **Custom Caption** text field.
* **Link** - `Default` (home URL) / `None` / `Media File` / `Custom URL` → Custom URL reveals a URL field; **Lightbox** (Default/Yes/No) only appears when Link = Media File.
* **Style tab**: Width, Max Width (%), background, border (style/width/color/radius), box shadow, Opacity and CSS Filters (Normal/Hover tabs), Hover Animation, plus its own Caption style section (only shown when a caption is set).

## Bukpod Nav Menu

Renders any WordPress menu - used for the main and footer navigation.

* **Menu** - select which WordPress menu (from **Appearance > Menus**) to render; shows a warning if no menus exist yet.
* **Hover Right** - flips which direction dropdown submenus open.
* **Style tab**: alignment, typography for top-level and submenu items, per-item padding/margin/border-radius, "Hidden Icon Children" (hides the dropdown-arrow icon), "Submenu Width" (reveals Dropdown Width and Spacing), and separate Normal/Hover/**Active** color tabs (background, text, submenu text, dropdown background, border, arrow color) - the Active tab styles the current page's menu item/ancestors.

## Bukpod Menu Canvas

The mobile hamburger toggle button that opens the off-canvas menu panel.

* No Content-tab controls - it's a pure Style-tab widget: Icon Padding, Width, Height of the hamburger bars, and Normal/Hover background (color or gradient) for the bars.

## Bukpod Breadcrumbs

See [Breadcrumb](../../setting/breadcrumb.md) for the full walkthrough. Quick control reference:

* **Display Title** / **Display Nav** (switchers, independent of each other).
* **Separator** (icon, shown when Display Nav = Yes), **Home Page** / **Search** / **404 Page** text overrides.
* **HTML Tag Title** - H1-H6/div/span/p (shown when Display Title = Yes).
* **Alignment** (Left/Center/Right, responsive).
* **Style tab**: separate Title section (color, typography, text-stroke/shadow, position Above/Below the nav, margin) and Breadcrumb Items section (padding, radius, backdrop blur, border, background, text/link/link-hover color, typography, separator size/spacing/color).

## Language Switcher

WPML language switcher, styled to match the theme. The language list itself comes from your WPML setup - there's nothing to pick here, only a single **Layout** section (all on the Content tab, no separate Style tab):

* Typography, Normal/Hover tabs for Label Color, Title Color, Icon Color.
* **Hover Right** switcher - flips the dropdown's opening direction, same as Nav Menu.
