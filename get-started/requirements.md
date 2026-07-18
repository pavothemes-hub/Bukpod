# Requirements

In most cases, installing WordPress is a very simple process that takes less than five minutes. Most web hosts now offer tools to automatically install WordPress for you.

## **1) WordPress Requirements**  <a href="#id-1-requirements-for-wordpress" id="id-1-requirements-for-wordpress"></a>

Make sure your web host meets the [minimum requirements to run WordPress](http://wordpress.org/about/requirements/).

You can download the latest WordPress release from [WordPress.org](http://wordpress.org/).

## **2) Requirements for the Bukpod Theme** <a href="#id-2-requirements-for-shome-wp" id="id-2-requirements-for-shome-wp"></a>

To run the Bukpod theme, make sure your hosting meets the following requirements:

{% hint style="info" %}
WordPress 5.8+ (tested up to 6.7)
{% endhint %}

{% hint style="info" %}
PHP 7.4+
{% endhint %}

{% hint style="info" %}
MySQL 5.6+
{% endhint %}

{% hint style="info" %}
Bukpod requires three plugins to run correctly: **Pavo Core**, **Elementor**, and **WooCommerce**. These are marked required in the Theme Setup wizard and will be flagged for installation automatically.
{% endhint %}

{% hint style="info" %}
To let customers upload and preview their own artwork on a product (the core print-on-demand feature), also install the recommended **WC Designer Pro** (listed as "WooCommerce Designer Pro" once activated) and **Opal Woo Custom Product Variation** plugins - both are bundled with your purchase and installable from the Theme Setup wizard. See [Set up Product Designer](../content-management/set-up-product-designer.md).
{% endhint %}

## **3) Recommended PHP Configuration Limits** <a href="#id-3-recommended-php-configuration-limits" id="id-3-recommended-php-configuration-limits"></a>

{% hint style="success" %}
Max\_execution\_time 600
{% endhint %}

{% hint style="success" %}
Memory\_limit 512M
{% endhint %}

{% hint style="success" %}
Upload\_max\_filesize 40M
{% endhint %}

{% hint style="success" %}
Post\_max\_size 48M
{% endhint %}

{% hint style="success" %}
PHP Imagick extension (recommended for CMYK color conversion in Product Designer print exports)
{% endhint %}

## **4) Recommended Setting for the Bukpod Theme**

{% hint style="danger" %}
**For threads to work, change permalinks to the post name format. This is required and should be done immediately after activating the theme**
{% endhint %}

<figure><img src="../.gitbook/assets/image (155).png" alt=""><figcaption></figcaption></figure>
