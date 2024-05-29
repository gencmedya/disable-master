=== Disable Master ===
  - Contributors: gencmedya
  - Tags: disable, functionalities, security, optimization, speed
  - Requires at least: 5.0
  - Tested up to: 6.5.3
  - Requires PHP: 7.4
  - Stable tag: 1.1.0
  - License: GPLv2 or later
  - License URI: https://www.gnu.org/licenses/gpl-2.0.html

A comprehensive plugin to disable various WordPress functionalities.

== Description ==

Disable Master is a comprehensive plugin that allows you to disable various WordPress functionalities to enhance security, performance, and user experience. Easily disable unused features to streamline your WordPress site.

**Features:**

- **Disable Gutenberg Editor**
  - Disabled: Gutenberg editor is used.
  - Enabled: Gutenberg editor is disabled, and the classic editor is used. Useful if you find it difficult to adapt to Gutenberg or prefer the classic editor.

- **Disable Comments**
  - Disabled: Comments remain enabled.
  - Enabled: Comments are disabled on all posts and pages. Useful if you do not want to receive comments or to prevent spam.

- **Disable Emojis**
  - Disabled: Emoji script added by WordPress is used.
  - Enabled: Emoji script is disabled. This can speed up the loading time of your site.

- **Disable XML-RPC & Pingbacks**
  - Disabled: XML-RPC and pingback functionality remain enabled.
  - Enabled: XML-RPC protocol and pingback functionality are disabled. This can prevent external services from communicating with your site via XML-RPC and enhance security.

- **Disable REST API**
  - Disabled: WordPress REST API remains enabled.
  - Enabled: WordPress REST API is disabled. This can enhance security and reduce issues related to external access.

- **Disable Author Pages**
  - Disabled: Author archive pages remain enabled.
  - Enabled: Author archive pages are disabled. Useful for reducing unnecessary pages and keeping your site organized.

- **Disable Feed**
  - Disabled: RSS feed functionality remains enabled.
  - Enabled: RSS feed functionality is disabled. Disable if you do not need feeds on your site.

- **Disable Post Formats**
  - Disabled: Post format support remains enabled.
  - Enabled: Post format support is disabled. Useful for keeping posts in a standard format.

- **Disable Revisions**
  - Disabled: Post revisions remain enabled.
  - Enabled: Post revisions are disabled. This can reduce database load and improve performance.

- **Disable Search**
  - Disabled: Search functionality remains enabled.
  - Enabled: Search functionality is disabled. Useful for simplifying user experience if you do not need search on your site.

- **Disable Self Pings**
  - Disabled: Self pings remain enabled.
  - Enabled: Self pings are disabled. This can reduce unnecessary server load.

- **Disable Sitemaps**
  - Disabled: Default WordPress sitemaps remain enabled.
  - Enabled: Default WordPress sitemaps are disabled. Useful if you are using an external sitemap.

- **Disable Tags**
  - Disabled: Tag functionality remains enabled.
  - Enabled: Tag functionality is disabled. Useful for simplifying content management.

- **Disable Widgets**
  - Disabled: All widgets and sidebars remain enabled.
  - Enabled: All widgets and sidebars are disabled. This can improve performance and remove unnecessary elements.

- **Disable Admin Bar**
  - Disabled: Admin bar remains enabled.
  - Enabled: Admin bar is disabled for all users. Useful for simplifying user experience.

- **Disable Autosave**
  - Disabled: Autosave feature remains enabled.
  - Enabled: Autosave feature is disabled. This can reduce database load and improve performance.

- **Disable Dashboard**
  - Disabled: WordPress dashboard remains enabled.
  - Enabled: WordPress dashboard is disabled. Useful if you do not use the dashboard or want to restrict access.

- **Disable Dashboard Widgets**
  - Disabled: Dashboard widgets remain enabled.
  - Enabled: Dashboard widgets are disabled. This simplifies the dashboard and improves performance.

- **Disable File Editor**
  - Disabled: Theme and plugin file editor remains enabled.
  - Enabled: Theme and plugin file editor is disabled. This can enhance security.

- **Disable Login Errors**
  - Disabled: Login error messages remain enabled.
  - Enabled: Login error messages are hidden. This can enhance security.

- **Disable User Registration**
  - Disabled: User registration form remains enabled.
  - Enabled: User registration form is disabled. Useful if you want to limit user registrations.

- **Disable Version Meta**
  - Disabled: WordPress version meta tag remains enabled.
  - Enabled: WordPress version meta tag is removed. This can enhance security.

- **Disable WP Generator**
  - Disabled: WordPress generator tag remains enabled.
  - Enabled: WordPress generator tag is removed. This can enhance security.

- **Disable Admin Notices**
  - Disabled: Admin notices remain enabled.
  - Enabled: Admin notices are disabled. This simplifies the admin panel.

- **Disable Plugin Updates**
  - Disabled: Plugin updates remain enabled.
  - Enabled: Plugin updates are disabled. Useful if you prefer to check for updates manually.

- **Disable Theme Updates**
  - Disabled: Theme updates remain enabled.
  - Enabled: Theme updates are disabled. Useful if you prefer to check for updates manually.

- **Disable Core Updates**
  - Disabled: WordPress core updates remain enabled.
  - Enabled: WordPress core updates are disabled. Useful if you prefer to check for updates manually.

- **Disable Media Sizes**
  - Disabled: Additional media sizes remain enabled.
  - Enabled: Additional media sizes are disabled. This can optimize disk space and performance.

- **Disable HTML Comments**
  - Disabled: HTML comments remain enabled.
  - Enabled: HTML comments are disabled. This can simplify HTML source code and enhance security.

- **Disable WooCommerce**
  - Disabled: WooCommerce functionality remains enabled.
  - Enabled: WooCommerce functionality is disabled. Useful if you want to temporarily disable WooCommerce.

- **Disable WP Notification**
  - Disabled: WordPress notifications remain enabled.
  - Enabled: WordPress notifications are disabled. This simplifies the admin panel.

- **Disable Heartbeat**
  - Disabled: WordPress heartbeat API remains enabled.
  - Limit: WordPress heartbeat API is limited to a 60-second interval to reduce server load.
  - Enabled: WordPress heartbeat API is disabled. This can conserve server resources and improve performance.

- **Disable admin-ajax.php on Front-End**
  - Disabled: admin-ajax.php remains enabled on the front-end.
  - Enabled: admin-ajax.php is disabled on the front-end to improve performance.

- **Remove Query Strings from Static Resources**
  - Disabled: Query strings remain enabled on static resources.
  - Enabled: Query strings are removed from static resources to improve caching and performance.
  
- **Disable API Request Logging**
  - Disabled: API request logging remains enabled.
  - Enabled: API request logging is disabled. This can reduce server load.

- **Disable WP-Cron and Use Real Cron Jobs**
  - Disabled: WP-Cron remains enabled.
  - Enabled: WP-Cron is disabled and real cron jobs are used. This can make scheduled tasks more efficient.

- **Disable Post Locking**
  - Disabled: Post locking remains enabled.
  - Enabled: Post locking is disabled. Useful for single-author or small team sites.

- **Disable Uploads**
  - Disabled: Upload functionality remains enabled.
  - Enabled: Disables the ability to upload media, themes, and plugins. Useful for preventing unauthorized uploads and enhancing security.

- **Disable Site Health**
  - Disabled: Site Health checks remain enabled.
  - Enabled: Site Health checks are disabled. This can be useful to prevent unnecessary load and simplify the admin interface.
  
== Installation ==

1. Upload the `disable-master` folder to the `/wp-content/plugins/` directory.
2. Activate the plugin through the 'Plugins' menu in WordPress.
3. Navigate to Settings > Disable Master to configure the plugin.

== Frequently Asked Questions ==

= How do I disable a functionality? =

Navigate to Settings > Disable Master, and check the box next to the functionality you want to disable. Click 'Save Changes' to apply your settings.

= Can I re-enable a functionality after disabling it? =

Yes, simply uncheck the box next to the functionality you want to re-enable and click 'Save Changes'.

= Will this plugin conflict with other plugins? =

Disable Master is designed to work seamlessly with other plugins. However, if you encounter any issues, please report them to our support team.

== Screenshots ==

1. **Settings Page** - Overview of the Disable Master settings page.
2. **Feature Selection** - Easily enable or disable various WordPress functionalities.
3. **Save Changes** - Save your settings to apply the changes.

== Changelog ==

= 1.1.0 =
* Added new feature: Disable Uploads - This feature prevents all file uploads (media, plugins, themes) to enhance security.
* Added new feature: Disable Site Health - This feature disables Site Health checks to reduce load and simplify the admin interface.
* Refactored the 'features' directory to organize functionalities into classes for better code management.
* Added an autoloading mechanism.
* Added new features:
  - Disable API Request Logging
  - Disable WP-Cron and Use Real Cron Jobs
  - Disable Post Locking
* Added 'System Check' page in the admin panel. This page allows you to check for potential conflicts with themes and other plugins.
* Added 'Buy Me a Coffee' button to the info popup in the admin panel.
* Various language file updates and bug fixes.
* Added options to disable API request logging, WP-Cron, post locking, and screen options/help tabs.
* Added option to disable `admin-ajax.php` on the front-end.
* Added option to remove query strings from static resources.
* Enhanced Heartbeat API control with options to disable or limit the interval.
* Improved UI/UX design and responsiveness.
* Added language support for Turkish.
* Enhanced security and performance.

= 1.0.0 =
* Initial release.

== Upgrade Notice ==

= 1.1.0 =
* Added new feature: Disable Uploads - This feature prevents all file uploads (media, plugins, themes) to enhance security.
* Added new feature: Disable Site Health - This feature disables Site Health checks to reduce load and simplify the admin interface.
* Refactored the 'features' directory to organize functionalities into classes for better code management.
* Added an autoloading mechanism.
* Added new features:
  - Disable API Request Logging
  - Disable WP-Cron and Use Real Cron Jobs
  - Disable Post Locking
* Added 'System Check' page in the admin panel. This page allows you to check for potential conflicts with themes and other plugins.
* Added 'Buy Me a Coffee' button to the info popup in the admin panel.
* Various language file updates and bug fixes.
* Added options to disable API request logging, WP-Cron, post locking, and screen options/help tabs.
* Added option to disable `admin-ajax.php` on the front-end.
* Added option to remove query strings from static resources.
* Enhanced Heartbeat API control with options to disable or limit the interval.
* Improved UI/UX design and responsiveness.
* Added language support for Turkish.
* Enhanced security and performance.

= 1.0.0 =
* Initial release.

== Arbitrary section ==

**Known Issues:**
- Currently, no known issues have been reported. If you encounter any bugs or have suggestions for improvement, please reach out to us.

**Future Plans:**
- We plan to add more advanced customization options in the upcoming versions.
- Integration with popular caching plugins to enhance performance.
- Detailed logging and analytics features to track the impact of disabled functionalities.
- More granular control over individual WordPress features to provide better customization.

**Contributors:**
- Halil Kaya - Lead Developer and Maintainer
- WordPress Turkey Team - Support, Suggestions and Development

We greatly appreciate feedback and contributions from the WordPress community. If you'd like to contribute, please contact us at halil@gencmedya.com or visit our website at https://gencmedya.com. Thank you for using Disable Master!
