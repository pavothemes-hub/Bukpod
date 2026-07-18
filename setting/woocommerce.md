# WooCommerce

Bukpod adds its own controls into the **WooCommerce** Customizer panel to control how the Shop archive and the Single Product page look, on top of what WooCommerce itself provides.

**Step 1 -** From your admin Dashboard navigate to **Appearance** > **Customize** > **WooCommerce**.

**Step 2 -** You'll see the extra **Archive** and **Singular** sections added by the theme, alongside WooCommerce's own **Product Catalog**, **Product Images**, **Store Notice** and **Checkout** sections.

## 1. Archive

Open the **Archive** section to configure the Shop and product category/tag listing pages.

* **Product Layout** - `Default` (grid) or `List`.
* **Content Width** - `Default` or `Wide`.
* **Filter Style** - controls how the product filter sidebar/widgets are presented:
  * **No Sidebar** - hides the sidebar completely, archive runs full width.
  * **Sidebar** - classic fixed sidebar next to the product grid.
  * **Menu Filter** - filters open from a horizontal menu bar above the grid.
  * **Drawing Filter** - filters slide out as an overlay drawer.
  * **Canvas Filter** - filters open in an off-canvas panel.
  * **Dropdown Filter** - filters are shown as a dropdown panel.
* **Sidebar Position** - `Left` or `Right`. Only applies when **Filter Style** is set to **Sidebar**.
* **Products pagination** - `Pagination` (numbered pages), `Load More` (button), or `Infinit Scroll` (auto-load on scroll).

{% hint style="info" %}
**Sidebar Position** and the sidebar itself only render when **Filter Style** is set to **Sidebar** - the other filter styles (Menu/Drawing/Canvas/Dropdown) render their own widget area instead of a sidebar.
{% endhint %}

### Banner ads

Still inside the **Archive** section, you can insert promotional banner images between the products on the Shop page.

**Step 1 -** Set **Enable Banner Item** to **Yes**.

**Step 2 -** Set **Number of Banners** - how many banners you want (0 to 10).

**Step 3 -** For each banner that appears (**Banner #1**, **Banner #2**, ...), set:

* **Banner # Image** - the banner image itself.
* **Banner # Position** - the product grid position (1-based) after which the banner is inserted. For example, position `4` inserts the banner right after the 4th product.

{% hint style="info" %}
Only as many "Banner #N" controls show up as the **Number of Banners** you set - increase that number first if you don't see the banner slot you need.
{% endhint %}

## 2. Singular (Single Product page)

Open the **Singular** section to configure the single product page.

* **Product Gallery Style** - `Horizontal`, `Vertical`, `Gallery`, `Sticky`, or `Without Thumb`.
* **Product Tabs Style** - `Tabs`, `Full content`, `Accordion`, or `Sticky`. Only available when **Product Gallery Style** is `Horizontal`, `Vertical`, or `Gallery`.
* **Trust seal image** - upload an image (e.g. payment/security badges) shown on the single product page.

## 3. Product Catalog (products per row)

WooCommerce's own **Product Catalog** section (also under the **WooCommerce** panel) contains the theme's grid density controls:

* **Products per row Laptop**
* **Products per row tablet**
* **Products per row mobile extra**
* **Products per row mobile**

Set how many products display per row at each breakpoint, then click **Publish** to save.
