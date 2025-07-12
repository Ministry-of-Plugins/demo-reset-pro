=== Demo Reset Pro ===
Contributors: anjanahema
Tags: demo, theme demos, reset, wordpress-reset, restore
Requires at least: 5.6
Tested up to: 6.8
Requires PHP: 7.4
Stable tag: 1.0.0
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/old-licenses/gpl-2.0.html

Reset any WordPress website manually or automatically to a predefined Reset Point, perfect for sales demos, training, and presentations.

== Description ==

> **Build it → Freeze it → Let them play with it → Let it to Auto Reset via Server Cron.**

A lightweight plugin built to deliver robust Auto Reset functionality while upholding the simplicity of the WordPress core.

### Philosophy

Whether you are a Freelance Developer or a Development Team, we understand how challenging it can be to showcase your Skills, Creativity, or Products to your customers.

By letting customers to explore your Website, Theme, or Plugin through a Demo, you will save countless words while ensuring their trust and satisfaction.

At Ministry of Plugins we believe, it is our duty to develop WordPress technologies to close the gap between you and your customer.

### Concept

Simply install the Demo Reset free plugin or Demo Reset Pro plugin on your WordPress website and create a Reset Point to put the site in the Frozen State (Demo Mode). This allows you to let your customers to interact with the website without any risk of permanent changes. With each automatic or manual reset, all customer changes will be removed, restoring the website to its original state. In short; Now your website is ready for Demo purposes.

![Demo Reset Concept Diagram](https://ministryofplugins.com/wp-content/uploads/2025/03/demo-reset-concept-diagram.png)

### Use Cases of Demo Reset plugin

#### Demo for sales purposes:

Having a Demo Website as part of your sales funnel can significantly boost customer conversions for website developers, theme developers, and plugin developers. It allows potential customers to experience the product firsthand and increasing their confidence of making a purchase. With each manual or automatic reset cycle, the Demo Reset plugin will keep the WordPress website in its original state by removing all temporary changes made by customers.

#### Demo for presentation purposes:

For website developers, converting a newly developed WordPress website into a Demo Site is an excellent strategy for presenting its features and functions to stakeholders. After the presentation, the developer can easily reset the website to its original state, erasing any temporary changes. This ensures that the website remains clean and professional. The Demo Reset plugin can be turned off once the presentation is complete.

#### Demo for training purposes:

Training the staff and stakeholders on a newly developed WordPress website is more effective when using the website in Demo state. This approach allows trainees to interact with the website and explore its features without the risk of making permanent changes. After the training session, the developer can reset the website to its original state, removing any temporary modifications. This method ensures the site remains pristine and always ready for future use. The Demo Reset plugin can be turned off as needed.

![Demo Reset Use Cases Chart](https://ministryofplugins.com/wp-content/uploads/2025/03/use-cases-process-chart.png)

### Demo Reset Free Plugin

#### Interfaces of Demo Reset Free Plugin

https://youtu.be/JnDlcWehfqI?si=wT-p4R0-89JdODUT

#### Features of Free Plugin:

*   Able to create multiple Reset Points.
*   Manual Demo Reset execution capability.
*   Demo Reset Cycle automation via a regular URL.
*   Demo Reset Cycle automation via a RESTful URL.
*   The entire Database will reset to the chosen Reset Point.
*   All logged-in users will be logged out during the Reset process.
*   Displays the Demo Reset Status (THAWED state or FROZEN state) on the WP Admin Bar.
*   Media files uploading and deleting is restricted in the FROZEN state. (Images, PDFs etc.)
*   Plugins, Themes are WP Core auto updates are restricted, but can update manually in the THAWED state.
*   Capable of deploying Demo Websites only for Non-admin users. Because all admins can deactivate the Demo Reset plugin or delete Reset Points.

#### THAWED state of Free Plugin:

*   Changes made by admins or other users will remain on the website.
*   Permalink Settings page is accessible.
*   All the auto-updates are suspended.
*   Admins can install WP Core, Plugin & Theme updates.
*   Admins can install or delete Plugins & Themes.
*   Admins and users can upload new images or files.
*   Admins and users can delete/trash existing uploaded images or files.
*   Only admins can access the Demo Reset Admin Menu.
*   Only admins can change Demo Reset settings.
*   Admins must add at least one Reset Point to activate the FROZEN state (Demo Mode).

#### FROZEN state of Free Plugin:

*   Changes made by admins or other users will be reset in every Reset Cycle.
*   Permalink Settings page is restricted.
*   All the auto-updates are suspended.
*   Installation of WP Core, Plugin & Theme updates is suspended.
*   Installation, activation, deactivation or deletion of Plugins & Themes are suspended.
*   New images or files uploading is suspended.
*   Deletion of already existing uploaded images or files is suspended.
*   Logged-in users will automatically be logged out during the reset process.
*   Only admins can access the Demo Reset Admin Menu.
*   Only admins can change Demo Reset settings.
*   Admins can add multiple Reset Points.
*   Admins should delete all Reset Points to get back to the THAWED state.

#### Setting a WordPress website to FROZEN state (Valid for Free & Pro)

https://youtu.be/Q-ES0ey_0kg?si=bP2tWv1m_OCVa654

#### Setting an Active Reset Point for Auto Reset (Valid for Free & Pro)

https://youtu.be/rbw3ffD7jOM?si=V8se27ZzqLPqqfk5

#### Setting Reset Runner URL to run Auto Reset (Valid for Free & Pro)

https://youtu.be/S4qRo6vgyAY?si=QNq6TKHmyjYn54Kk

#### Setting Reset Runner REST URL to run Auto Reset (Valid for Free & Pro)

https://youtu.be/GIJi1zxjGMU?si=5cdp3el-QTREWKrK

#### Setting a WordPress website back to THAWED state (Valid for Free & Pro)

https://youtu.be/tq7wX74X2-s?si=yjEEqCpqG-Sm9xQG

Demo Reset Documentation: [https://ministryofplugins.com/demo-reset-docs](https://ministryofplugins.com/demo-reset-docs)

### Demo Reset Pro Plugin

#### Interfaces of Demo Reset Pro Plugin

https://youtu.be/GswUX7dRuE0?si=NV-cFyu2kfWrvrTU

### Features of Pro Plugin:

*   Able to create multiple Reset Points.
*   Manual Demo Reset execution capability.
*   Demo Reset Cycle automation via a regular URL.
*   Demo Reset Cycle automation via a RESTful URL.
*   Demo Reset Cycle automation via server Cron Jobs directly.
*   The entire Database and Media Library can be reset to the selected Reset Point.
*   Offers options to avoid forceful log out on logged-in users during the Reset process.
*   Displays the Demo Reset Status (THAWED state or FROZEN state) on the WP Admin Bar.
*   THAWED State Website Isolation capability to prevent unnecessary changes to the website.
*   Capable of allowing users to upload new media files and trash already uploaded files in the FROZEN state. (Images, PDFs etc.)
*   There will be no accumulation of abandoned files in the uploads directory because the Media Library will reset with every reset run.
*   Plugins, Themes are WP Core auto updates are restricted, but can update manually in the THAWED state.
*   Able to deploy Demo Websites for both Admin and Non-admin users. Only Admin who activate the Demo Reset plugin can access its setup features.
*   Displays the Demo Reset Countdown Timer showing the time remaining for the next Reset.
*   Shows the customizable Promo Bar at the top of the Demo Website on both admin and public sides.
*   Options to display the Promo Bar on the admin side, public side, both, or hide it entirely.
*   Features your Logo and Brand Name on the Promo Bar, linking your Business Website to the Demo site.
*   Highlights your Special Offers or Promotions on the Promo Bar, linking your Landing Page to the Demo site.
*   Capable of providing your Phone Number and Email Address for Demo users as Promo Bar Tools.
*   Includes your Help Articles for Demo users as a Promo Bar tool.
*   Able to add Extra Links for Demo users as a Promo Bar tool.
*   Capable of sending an email notification at the end of each Reset Cycle.

Demo Reset Documentation: [https://ministryofplugins.com/demo-reset-docs](https://ministryofplugins.com/demo-reset-docs)

== Installation ==

### Requirements

*   PHP version 7.4.0 or greater.
*   WordPress 5.6.0 or greater.
*   The website should not be a WordPress multisite.
*   If both the Demo Reset Free and Pro plugins are installed on the same website, neither will activate until one is uninstalled.

### Installation

*   Method 1: Install and activate the Demo Reset plugin via the WordPress Plugin Installer.
*   Method 2: Download the Demo Reset plugin zip, extract it, and upload its contents to the wp-content/plugins/ directory. Then, activate the plugin from the Plugins page in the WordPress Admin area.

### Notes

*   For the purpose of a Demo Website, it is crucial that all permanent changes to the Website are made intentionally and consciously. Therefore, auto-updates will be paused by the Demo Reset plugin. In THAWED state (Non-Demo mode), you can manually update Plugins, Themes, and WordPress Core.

== FAQ ==

#### How to set a WordPress website to FROZEN state? (Valid for both Free & Pro plugins)

*   To put the website into FROZEN state (Demo Mode), please add at least one Reset Point.
*   **Important:** We highly recommend backing up your website files and database before switching your website to the FROZEN state (Demo Mode).
*   **Important:** If you plan to use the Reset Runner REST URL or Reset Runner URL to trigger the Reset, please ensure the website Permalink Structure is set to anything other than "Plain" before adding first Reset Point.

#### How to set an Active Reset Point for Auto Reset? (Valid for both Free & Pro plugins)

*   On the Demo Reset Settings page, under Auto Reset Settings, select a Reset Point as the Active Reset Point from the dropdown and save your changes.
*   **Note:** This is the Reset Point to which the website will reset via Reset Runners.

#### How to set the Reset Runner URL to run Auto Reset? (Valid for both Free & Pro plugins)

*   Before generating Reset Runners for Reset execution, please ensure the Active Reset Point is set. The Active Reset Point is the Reset Point to which the website will be reset.
*   Ensure the Permalink Structure under WordPress Permalink Settings is set to something other than Plain. This must be done when the website is in the THAWED state.
*   Navigate to the Reset Runners page under the Demo Reset admin menu. Check the Generate Reset Runner URL checkbox, fill in the Action Confirmation field, and click the Generate URL button. The Reset Runner URL will be generated.
*   Test the Reset Runner URL by entering it into your browser. Upon success, the page will display the success message. Also, check the Demo Reset Dashboard page on the website for the Reset entry.
*   The Reset Runner URL can be triggered using a Unix Cron Scheduler, Zapier Automation (Zap), web browser, or any compatible client to reset the website.
*   **Note:** The Reset Runner URL should always be kept secret.
*   **Note:** Security plugins, firewall plugins, custom codes, server-side firewalls, and CDN services like Cloudflare may block Reset Runner URL calls; ensure they are properly bypassed.
*   **Note:** The Reset will log out all users from the website if successful, unless the Pro plugin is used.
*   **Important:** Triggering the Reset Runner URL with Unix Cron through cPanel is the best trigger option with consistent trigger intervals. Watch the complete video tutorial on YouTube. <a href="https://youtu.be/S4qRo6vgyAY?si=QNq6TKHmyjYn54Kk" target="_blank">https://youtu.be/S4qRo6vgyAY?si=QNq6TKHmyjYn54Kk</a>


#### How to set the Reset Runner REST URL to run Auto Reset? (Valid for both Free & Pro plugins)

*   Before generating Reset Runners for Reset execution, please ensure the Active Reset Point is set. The Active Reset Point is the Reset Point to which the website will be reset.
*   Ensure the Permalink Structure under WordPress Permalink Settings is set to something other than Plain. This must be done when the website is in the THAWED state.
*   Navigate to the Reset Runners page under the Demo Reset admin menu. Check the Generate Reset Runner REST URL checkbox, fill in the Action Confirmation field, and click the Generate URL button. The Reset Runner REST URL will be generated.
*   Test the Reset Runner REST URL by entering it into your browser. Upon success, you will receive message: "ok" JSON response. Also, check the Demo Reset Dashboard page on the website for the Reset entry.
*   The Reset Runner REST URL can be triggered using any external RESTful source, such as Cron-job.org, Zapier, or any compatible client, to reset the website.
*   **Note:** The Reset Runner REST URL should always be kept secret.
*   **Note:** Security plugins, firewall plugins, custom codes, server-side firewalls, and CDN services like Cloudflare may block Reset Runner REST URL calls; ensure they are properly bypassed.
*   **Note:** The Reset will log out all users from the website if successful, unless the Pro plugin is used.
*   **Important:** Using Cron-job.org to trigger the Reset Runner REST URL is a good option for monitoring but not for consistent trigger intervals. Watch the complete video tutorial on YouTube. <a href="https://youtu.be/GIJi1zxjGMU?si=5cdp3el-QTREWKrK" target="_blank">https://youtu.be/GIJi1zxjGMU?si=5cdp3el-QTREWKrK</a>

#### How to set a WordPress website back to THAWED state? (Valid for both Free & Pro plugins)

*   To put the website back into THAWED state (Exit the Demo Mode), please remove all Reset Points.

#### Why is it always advised to try the Demo Reset Free version before having the Pro version?

*   Both URL-based Reset Runner systems are available in the Free Plugin version and Pro version. Therefore, we strongly advise you to use the Free version to determine which Reset Runner system and external trigger source works best for your WordPress website. Different websites have different internal and external setups, firewalls, and CDNs (Content Delivery Networks) that may block external triggers.

#### What makes WordPress Cron unsuitable for triggering a website reset?

*   WordPress cron is a pseudo-cron system that only triggers whenever a page is loaded. Therefore, it is impossible to trigger the Website Reset Process with WordPress cron in consistent time intervals. The trigger must be outside of the WordPress system.

#### Are Reset Runners safe? 

*   Yes, they are generated with a unique randomly generated 15-character token, making them highly secure. Once generated, a Reset Runner should always be kept confidential.

== Screenshots ==

1. Demo Reset Dashboard - THAWED state (Non-Demo mode)
2. Add New Reset Point
3. Reset Points - THAWED state (Non-Demo mode)
4. Reset Runners
5. Settings - THAWED state (Non-Demo mode)
6. Demo Reset Dashboard - FROZEN state (Demo Mode)
7. Reset Points - FROZEN state (Demo Mode)
8. Edit Reset Point - FROZEN state (Demo Mode)
9. Delete Reset Point - FROZEN state (Demo Mode)
10. Reset to a Reset Point - FROZEN state (Demo Mode)
11. Settings - FROZEN state (Demo Mode)
12. Philosophy and Concept
13. Use Cases of Demo Reset plugin
14. Pro Plugin vs Free Plugin
15. THAWED state vs FROZEN state
16. Help Resources
17. WP Dashboard - THAWED state (Non-Demo mode)
18. WP Dashboard - FROZEN state (Demo Mode)
19. Demo Reset Pro Dashboard - FROZEN state (Demo Mode)

== Changelog ==

##### 1.0.0

Initial release.