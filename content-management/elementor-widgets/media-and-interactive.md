# Media & Interactive

Sliders, marquees, toggles, and other interactive display widgets.

## Bukpod Testimonials

* **Testimonials** repeater - Rating (select 0-5, 0 = hidden), Logo, Quote Icon, Content, Name, Job, avatar Image, Link to.
* **Style** - `Style 1` (logo+rating in the header, avatar+quote icon in the footer) or `Style 2` (quote icon at top).
* **Enable Carousel** toggles between **Column Options** and the shared **Carousel Options** (see the note at the bottom of [Content & Blog](content-and-blog.md) for what Carousel Options includes).
* **Style tab**: Card (background/border/radius/padding), Header, Logo size, Rating (icon size, empty vs. filled color - renders as a CSS-width bar, not discrete stars), Content typography/color, Footer & Avatar sizing, Name & Job typography/color, Quote Icon size/color.

## Bukpod Brands

* **Items** repeater - Brand Name, **Display Type** (Image/Icon → reveals the matching picker), Link to.
* **Alignment Info** (Left/Center/Right) for content inside each brand slot.
* **Effects Brand** (switcher) - turns on an infinite auto-scrolling marquee.
* **Style tab**: Direction (RTL/LTR), Animation Duration (only when Effects Brand = Yes), padding/margin, border+radius, backdrop blur, item spacing, Normal/Hover (SVG color, background, opacity), SVG/image width & height.

## Bukpod Slides

A nested-container carousel - each slide holds its own Elementor containers rather than simple text fields.

* **Slides** - a nested repeater where each slide only has a Title label; you build the actual slide content by dropping containers/widgets inside each slide in the canvas.
* **Enable Carousel** is locked on. Reuses the shared Carousel Options (Slides to Show/Scroll and Dots Position are forced by the widget).
* **Effect** (only when Slides to Show = 1) - `Slide` / `Fade` / `Coverflow` / `Cards` / `Marquee` / `Flip` / `Cube` / `Creative`.

## Bukpod Toggle

A nested accordion/FAQ widget - each toggle body is a full Elementor container, not a plain text field.

* **Toggles** (nested repeater) - Title, Text (a small badge next to the title, e.g. "Sale").
* **Style tab**: row alignment, header padding/margin/radius/gaps/border; Title section (padding, radius, typography, Normal/Hover/Active color + active background highlight); Text/badge section (padding, typography, Normal/Hover/Active background+color).

{% hint style="info" %}
After editing the nested containers inside a toggle, click **Reload Preview** in the Elementor panel to see the change reflected.
{% endhint %}

## Bukpod Slider Scrolling

An infinite marquee of text/icon items (for logo strips, announcement bars, etc.).

* **Items** repeater - Icon, Title, Link to.
* **Effects Scrolling** (switcher) toggles the marquee animation.
* **Style tab**: wrapper padding/margin, overlay background, Title color/hover/typography/margin, Time scroll (animation duration in seconds), Direction (RTL/LTR), Icon color/size.

## Bukpod Scroll Image

Same infinite marquee as Slider Scrolling, but for images only (no title/link per item).

* **Items** repeater - Choose Image only.
* **Effects Scrolling** (switcher).
* **Style tab**: wrapper padding/margin, overlay background, Image Width/Height, image margin/radius, Time scroll, Direction (RTL/LTR).

## Bukpod Image Hotspots

Clickable pins over an image, each opening a tooltip - supports linking a pin straight to a WooCommerce product.

* **Image** + Image Size.
* **Hotspots** repeater (one per pin) - Title (tooltip heading), Horizontal/Vertical Position (% or px, positions the pin over the image), **Content to Show**:
  * **Text Editor** - a plain textarea.
  * **Elementor Template** - pick a saved template (must be named with a "Hotspots" prefix to show up in the list).
  * **Product** - reveals a searchable WooCommerce product picker; the tooltip then renders that product's image, title+link, star rating, and price automatically. Requires WooCommerce active.
  * **Link** (switcher) - adds a URL for the whole pin, but it only becomes a clickable wrapper when Trigger Type = Hover (see Tooltips below).
* **Hidden Radar Animation** (switcher) - hides the pulsing radar/ping effect on every pin.
* **Tooltips** section - Trigger (Click/Hover), Show Arrow, Position (multi-select, order = fallback priority), Spacing, Min/Max Width, Height, Animation (Fade/Grow/Swing/Slide/Fall), Animation Duration, Delay, Close Delay (Hover only), "Hide on Mobiles".
* **Style tab**: Image (border/radius/padding/alignment), Tooltips (color, typography, shadow, background, border, radius), Container (background, border, radius, shadow, spacing).

## Bukpod Video Popup

A button/thumbnail that opens a YouTube/Vimeo video in a lightbox popup.

* **Link to** - the video URL.
* **Title**, **Description**, **Alignment** (responsive).
* **Icon** (the play-button icon) → once set, reveals **Icon Position** (Before/After the text) and **Position Vertical** (stacks icon above the text instead of inline).
* **Style tab**: Wrapper (width/height once an icon is set, Normal/Hover background+border, radius, padding, backdrop blur), Icon (size, "Effects" pulsing/ripple animation toggle, Normal/Hover color+background+shadow), Title and Description typography/color (+ hover color).

## Bukpod Quick Action

The header's utility icon row - Home / Store / Search / Account / Wishlist / Cart.

* **Config** - a **Show** switcher per item; Wishlist and Cart only render if WooCommerce is active.
* For each enabled item: Icon, Icon Size, Spacing, Title, and **Order** (a number controlling render order, independent of the panel's section order). Extra per-item options:
  * **Account** - "User Name" (show the logged-in display name instead of a static label), "Dropdown" (adds an account dropdown panel).
  * **Wishlist** - "Count" (needs YITH or WPC Smart Wishlist installed).
  * **Cart** - "Count" (live WooCommerce cart item count).
* **Style tab**: Item (Icon Position, padding/margin/radius/border, "Separator" toggle+color, spacing, Normal/Hover background+text color), Title typography, Count badge (Normal/Hover background+color, typography).

{% hint style="info" %}
Bukpod also extends the native **Accordion**, **Button**, **Image Box**, and **Tabs** widgets with extra style controls - see [Native widget extensions](README.md#native-widget-extensions) in the widgets index.
{% endhint %}
