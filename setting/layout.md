# Layout

This is Elementor's own **Layout** tab inside **Site Settings** - it controls the site-wide content width, spacing, page title, and responsive breakpoints that every Elementor page/widget follows.

**Step 1** - You can go to any elementor edit page.

<figure><img src="../.gitbook/assets/image (224).png" alt=""><figcaption></figcaption></figure>

**Step 2** - Site Settings >> Layout >>

<figure><img src="../.gitbook/assets/Screenshot 2024-07-15 at 14.16.22.png" alt=""><figcaption></figcaption></figure>

**Step 3** - Set the following:

* **Content Width** - the max width (px) of the content area for normal (boxed) sections/containers.
* **Space Between Widgets** - the default vertical/horizontal gap between widgets inside a section or container.
* **Page Title Selector** - the CSS selector Elementor uses when you toggle "Hide Title" on a page (default `h1.entry-title`).
* **Breakpoints** - Bukpod ships with these active custom breakpoints:
  * **Mobile** and **Mobile Extra** - phones.
  * **Tablet** - up to `768px`.
  * **Tablet Extra** - up to `1025px`.
  * **Laptop** - up to `1440px`.

**Step 4** - Click **Update** to save.

{% hint style="info" %}
These breakpoints are what drive the **Products per row Laptop/Tablet/Mobile Extra/Mobile** controls in [WooCommerce](woocommerce.md) settings, and every widget's responsive (desktop/tablet/mobile) style controls in Elementor. Changing a breakpoint here shifts where those responsive styles kick in.
{% endhint %}
