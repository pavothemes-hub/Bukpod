# Forms

Elementor-styled wrappers around form plugins - all actual field configuration happens in the plugin itself, not in Elementor.

## Bukpod Contact Form

Only registered when **Contact Form 7** is active. See [Set up Contact Form](../set-up-contact-form.md) for the full walkthrough.

* **Select contact form** - dropdown of your published Contact Form 7 forms (shows a notice if none exist yet).
* **Form name** - used as the form's accessible title attribute.
* No other Content-tab controls - add/edit the actual fields inside Contact Form 7 itself.
* **Style tab**: Input (padding, background/text/placeholder color, border, radius), Label (padding, typography, color), Button (alignment, padding, margin, typography, icon size/gap, Normal/Hover background/text/border/icon colors).

## MailChimp Sign-Up Form

Only registered when **MC4WP (Mailchimp for WP)** is active. See [Set up MailChimp](../set-up-mailchimp.md) for the full walkthrough.

* No Content-tab controls at all - the widget renders your configured MC4WP form directly. This is entirely a Style-tab widget.
* **Style tab**: Form Group (alignment, Normal/Hover background/border/radius/padding), Input (Normal/Focus color/placeholder/background, border, radius, margin, padding - targets the email field), Button (Normal/Hover background/text/icon colors, border, radius, margin, padding).

{% hint style="info" %}
To change the actual form fields, labels, or sign-up behavior, edit the form inside **MC4WP > Forms** (or **Contact** for Contact Form 7) - not in Elementor.
{% endhint %}
