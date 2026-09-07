=== Ocasio Clean Image Filenames ===
Contributors: ocas
Tags: image filenames, clean filenames, seo images, sanitize filenames, media upload
Requires at least: 6.0
Tested up to: 6.7
Stable tag: 1.0.0
Requires PHP: 7.4
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Automatically sanitizes uploaded media file names, converting spaces to hyphens and removing special characters for better SEO.

== Description ==

When you upload images from cameras, phones, or design software, they often come with messy filenames like `IMG_0042 (1) Copy!.PNG` or `Screen Shot 2026-08-31 at 12.30.45 PM.jpg`. These messy names create ugly URLs, cause encoding errors on some servers, and hurt your search rankings.

Ocasio Clean Image Filenames fixes this automatically the moment you upload any file to your WordPress media library. It converts spaces and underscores into clean hyphens, removes special characters, strips accents, and forces lowercase letters.

You get clean, SEO-friendly media URLs every time with zero extra clicks.

= Features =

* **Automatic Cleanup on Upload:** Cleans filenames the exact second they enter your media library.
* **SEO-Friendly Hyphens:** Converts spaces and odd characters into clean hyphens (`-`), matching Google search best practices.
* **Accents & Special Character Removal:** Strips symbols, emojis, and accents that break image links.
* **Zero Front-End Assets:** Pure PHP execution with 0 bytes of extra CSS or JavaScript on your public pages.
* **Instant Dashboard Switch:** Turn the feature on or off in one click directly from the Ocasio Plugins dashboard.

== Installation ==

1. Upload the `ocasio-clean-image-filenames` folder to your `/wp-content/plugins/` directory, or install it directly through the WordPress plugins screen.
2. Activate the plugin through the 'Plugins' screen in WordPress.
3. Go to **Ocasio Plugins -> Dashboard** in your sidebar to toggle your settings.

== Frequently Asked Questions ==

= Does this modify my existing images in the media library? =
No. The plugin only sanitizes new files as you upload them. It doesn't alter files that are already inside your media library.

= Will this slow down my website? =
No. The plugin runs only during the upload process in your WordPress dashboard and adds zero scripts to your public pages.

== Changelog ==

= 1.0.0 =
* Initial public release.
