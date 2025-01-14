=== EU/UK VAT Manager for WooCommerce ===
Contributors: omardabbas, kousikmukherjeeli
Tags: woocommerce, eu, uk, vat, eu vat, woo commerce
Requires at least: 4.4
Tested up to: 6.2
Stable tag: 2.9.8
License: GNU General Public License v3.0
License URI: http://www.gnu.org/licenses/gpl-3.0.html

Manage EU/ UK VAT in WooCommerce, validate VAT numbers, exempt or preserve VAT with various settings & cases.

== Description ==

**The All in One EU VAT Manager Plugin**

Because of the constant changes in VAT regulations, it became very time-consuming for online store owners to update their webshops to comply with EU VAT regulations.

With this plugin, we made adherence to EU VAT regulations much easier, with a few clicks, we made all settings you need possible to make your WooCommerce store fully compliant with EU VAT regulations in matter of a few clicks.

This EU/UK VAT Manager for WooCommerce plugin has all the settings you need to collect VAT numbers, validate them and keep or preserve charges based on validation results.


== Validation Features ==

**1. Collect VAT numbers without any validations:**

Not the default behavior for all stores, but if you need it, the plugin offers this.

**2. Validate VAT numbers with EU/UK VAT databases:**

The plugin checks instantly on checkout page with the VIES services (as well as those for UK) to verify validity of the entered VAT number, based on results, you can select the needed setting to be applied (preserve/keep VAT).

**3. Keep VAT charges in store base country:**

When you sell inside your store country, EU VAT regulations require you to keep/charge VAT on these goods.

**4. Preserve VAT in selected countries:**

If your regulations require you to keep VAT charges when you sell to specific countries (other than your store base country), you can do so by selecting which countries that should have VAT charges applied.

**5. Verify billing country:**

In most cases, you will need to verify that billing country is the same country registered for the entered EU VAT number.
With a single click, the plugin offers this functionality and act accordingly based on desired setting.

**6. Using VAT numbers with/without country codes:**

If your customers are used to provide their VAT numbers without preceding country code, you can tolerate this and treat both numbers the same with a seamless experience for your customers.

**7. Progress Messages:**

For a better UX on your checkout page, we provide different fields to show messages to your customers during the validation stages, you can set your messages based on these cases:
Valid, invalid, validating, company name mismatch, different shipping & billing countries.

== Frontend Interface options ==

**1. Field label settings:**

Customize field name, like using BTW in Belgium (which is more common than VAT), change the placeholder (text inside the field), and also add a description to the field if needed.

**2. Required/Optional Settings:**

We offer you almost all settings to match your needs, you can set the field to be required in these cases:

Always
In specific countries
In all countries except specific countries
If customer filled company field
And of course, make it completely optional

**3. Field placement:**

Easil control the location/placement of the EU VAT field on the checkout page, you can also insert it manually using the field_id when using a custom page builder for your checkout page.

== More Features ==

**1. Collect VAT on signup:**

You can add the EU VAT field to your WooCommerce signup form, entries will be automatically saved in customer data fields.

**2. Belgium Compatibility:**

Due to BE different VAT/BTW regulations, the plugin offers multiple extra features to fully comply with that, like allowing customers to select if they are business or individual, then handle VAT accordingly.

**3. PDF Invoice & Packing Slips:**

Without a doubt, this is one of the most used PDF invoicing plugins, without further customizations, the EU VAT number will be inserted to PDF invoices generated by PDF Invoices & Packing Slips for WooCommerce plugin.

**4. Tax Rates:**

With a matter of a click, you can insert all official VAT rates for EU countries, the tool is accessible from WordPress Tools >> EU Country VAT Rates

== Pro Version ==

We offered almost all the settings you need to make your store compliant with EU VAT regulations with the free version, but if you're interested in getting some extra benefits, you can also check the [Pro version](https://wpfactory.com/item/eu-vat-for-woocommerce/?utm_source=wporg&utm_medium=desc&utm_campaign=freeversion) of this plugin that includes:

**1. Verify company name:**
The plugin can also verify if entered VAT number is registered for the exact same company name filled in “Company” field in checkout, and it can even show a customized message if entered name is different from the registered one.

**2. Verify country by IP:**
As per EU VAT regulations, there should be a physical evidence that the customer is shopping from & shipping to the country of registered company for that VAT number.
The plugin will allow you to verify IP using GeoIP lookup databases.

**3. Show field in specific countries:**
By default, EU VAT field will appear in all EU countries, if you want to specifically hide/show it on some countries, you can select what those countries are using this option.

**4. Show field based on user role:**
This option will allow you to show the field for selected user roles only, while hiding it for all other user roles. 


= Demo Store =

If you want to try the plugin features and play around with its settings before installing it on your live website, feel free to do so on this demo store:
URL: https://wpwhale.com/demo/wp-admin/
User: demo
Password: G6_32e!r@


== Screenshots ==

1. Main Page - General
2. Validation & Progress
3. Admin settings & Advanced options

= Feedback =

* We are open to your suggestions and feedback. Thank you for using or trying out one of our plugins!
* [Visit plugin site](https://wpfactory.com/item/eu-vat-for-woocommerce/).

== Installation ==

1. Upload the entire plugin folder to the `/wp-content/plugins/` directory.
2. Activate the plugin through the "Plugins" menu in WordPress.
3. Start by visiting plugin settings at "WooCommerce > Settings > EU VAT".

== Changelog ==

= 2.9.9 - 09/06/2023 =
* Fixed cURL & Simple validation method by changing the VIES URL API.  

= 2.9.8 - 30/05/2023 =
* Update with extra character trim with EU VAT validator response.   
* WC tested up to 7.6

= 2.9.7 - 11/04/2023 =
* Update woocommerce_before_calculate_totals priority from MAX to 99, so users can run their own overwrite.  
* Compatibility with WordPress 6.2 verified

= 2.9.6 - 31/03/2023 =
* Move to WPFactory.
* Enhanced field validaiton on page load

= 2.9.5 - 18/03/2023 =
* PDF invoicing compatibility is part of the free version
* Fixed a bug in field starting validation on checkout page load
* Altered classname to allow more control on the field
* Verified compatibility with WooCommerce 7.5

= 2.9.4 - 08/03/2023 =
* Enhanced field border color for validation (before & after entering values)

= 2.9.3 - 21/02/2023 =
* Fixed a bug to make VAT field mandatory if a company field is not empty
* Enhanced checkout VAT recalculations once VAT number changed/removed
* Verified compatibility with WooCommerce 7.4
* More compatibility with PHP 8.2 introduced by addressing deprecated methods

= 2.9.2 - 06/02/2023 =
* Fixed a bug in free version regarding "Preserve VAT in selected countries"
* Enhanced handling for "Undefined_constant" errors

= 2.9.1 - 30/01/2023 =
* Fixed warning message for Taxes group
* Enhanced VAT handling when manually editing an order for a preserved country
* Error messages in PHP 8.2 (creation of dynamic property)
* Reverted options to select validation methods

= 2.9 - 14/01/2023 =
* Improved session handling
* Fixed a bug showing PHP warning (title not defined)
* Verified compatibility with WooComemrce 7.3

= 2.8.5 - 06/12/2022 =
* Removed cURL & Simple validation methods as they are no longer used on VIES
* Added new shortcodes to trasnlate EU VAT field in WPML & Polylang
* Enhancement to UK validation method

= 2.8.4 - 29/11/2022 =
* Enhanced seesion validation on checkout & cart pages, leading to better performance
* Added validation messages class names to tooltips

= 2.8.3 - 23/11/2022 =
* Enhanced validation checks when using PHP sessions, making more compatibility with stores using multisites plugins
* New option to completely remove the field from checkout so you can control it using field ID with checkout page builders
* Progress messages got class names, allowing customizing them using CSS

= 2.8.2 - 18/11/2022 =
* The plugin will automatically add VAT number to invoices in the popular plugin (PDF Invoices & Packing Slips)
* Bug fixes in cache handling

= 2.8.1 - 13/11/2022 =
* New feature: You can now show a custom message when VAT is valid but not matching company name (probably a minor typo)
* Fixed a bug in show/hide field for countries
* Enhancements on registrationg values passed to VAT validation
* Compatibility with WooCommerce 7.1 and WordPress 6.1 verified


= 2.8 - 20/09/2022 =
* Fixed a bug blocking checkout on valid numbers
* Allowed checking out if billing & shipping countries are different
* Enhanced VAT calculation when "Shipping to a different address" is unchecked without a refresh
* Compatibility with WooCommerce 6.9

= 2.7.4 - 02/09/2022 =
* Hotfix for a bug caused by SiteGround optimizer plugin and add related setting under Advanced tab

= 2.7.3 - 01/09/2022 =
* Fixed several bugs when field is required/optional
* Fixed bug allowing checkout on black VAT even field is required
* Fixed a bug on option "Show field in these countries"
* Enhanced caching mechanism on SiteGround hosting
* New feature: You can now verify if shipping country is same as billing country and preserve VAT if so

= 2.7.2 - 10/08/2022 =
* Added a new option to make field required in all countries except selected
* Compatibility with WooCommerce 6.8

= 2.7.1 - 04/07/2022 =
* Verified compatibility with WooCommerce 6.6

= 2.7 - 11/06/2022 =
* Update: Preserve VAT in shop base country/specific countries is now in FREE version
* Verified compatibility with WooCommerce 6.5 & WordPress 6.0

= 2.6.3 - 15/04/2022 =
* Fixed an issue in validating VAT on signup if field was empty
* Fixed a PHP Deprecated warning message & PHP Uncaught TypeError: explode()
* Verified compatibility with WooCommerce 6.4


= 2.6.2 - 26/03/2022 =
* Added depency to the wp_enqueue_script function related to Ajax handling
* Fixed an issue when EU VAT field is optional while creating new users using REST-API

= 2.6.1 - 19/03/2022 =
* Verified compatibily with WooCommerce 6.3
* Added a new option in the revamped "Required" section to make the VAT field required if company field is filled 

= 2.6 - 27/02/2022 =
* Added a new option to make the field required on selected countries only
* Enhanced how coupons tax should be handled on checkout
* Changed PHP_MAX_INT priority from server max. to 99 to allow more control for admins
* Fixed Uncaught Error: Call to undefined function message

= 2.5.4 - 18/02/2022 =
* Added an option to allow checkout even if VAT is not registered in VIES
* Added a new option to filter orders with VAT numbers in order admin page
* Verified compatibily with WooCommerce 6.2

= 2.5.3 - 28/01/2022 =
* Verified compatibily with WordPress 5.9 & WooCommerce 6.1
* Added an option to remove tax if customer is out of EU (Belgium regulations)
* Added an option to collect & validate VAT numbers in signup forms

= 2.5.2 - 11/12/2021 =
* Compatibilty issue with Wholesale plugin user roles

= 2.5.1 - 10/12/2021 =
* New feature added: Allow specific payment gateway if VAT is valid (i.e. for B2B to allow wire transfers)
* Verified compatibility with WooCommerce 5.9

= 2.5 - 06/11/2021 =
* Fixed a bug in showing EU VAT label if not filled.
* Verified compatibility with WooCommerce 5.8

= 2.4.5 - 10/10/2021 =
* Enhanced EU VAT appearance in billing section so it's easily identified
* UK VAT numbers are space-tolerated so plugin will read VAT numbers with/without spaces
* Verified compatibility with WooCommerce 5.7

= 2.4.4 - 20/09/2021 =
* NEW: The plugin now validates UK VAT numbers as well
* Verified compatibility with WooCommerce 5.6

= 2.4.3 - 06/08/2021 =
* Fixed a warning message regarding AJAX being broken

= 2.4.2 - 26/07/2021 =
* Added an option to hide validation messages in preserved countries
* Fixed a bug in removing VAT if shipping address is a forwarding address
* Verified compatibility with WordPress 5.8

= 2.4.1 - 13/07/2021 =
* Added an option to validate VAT based on final destination (if order is sent to a forwarding address)
* Fixed undefined index & order ID warning messages
* Verified compatibilty with WooCommerce 5.5 

= 2.4 - 24/06/2021 =
* Added a popup section to open official VIES website in orders backend (to verify VAT info on order)
* Verified compatibilty with WooCommerce 5.4 

= 2.3.3 - 16/05/2021 =
* Fixed a bug was showing "Undefined index" errors when connecting through SSH
* Verified compatibilty with WooCommerce 5.3

= 2.3.2 - 03/05/2021 =
* Fixed a bug in session not firing in store
* Added tolerance for dash (-) in case VAT number was entered with a dash

= 2.3.1 - 30/04/2021 =
* Enhanced session configuration
* Added a feature to preserve tax if valid VAT number holders are not exempted (useful in Belgium)
* Tested compatibility with WooCommerce 5.2

= 2.3 - 20/04/2021 =
* Added new option to allow user to select VAT option
* Added banners on the sidebar
* Added a filter to control changes updates
* Checked compatibility with WC 5.1 & WP 5.7

= 2.2.5 - 28/02/2021 =
* Tested compatibilty with WC 5.0

= 2.2.4 - 27/01/2020 =
* Tested compatibility with WC 4.9

= 2.2.3 - 30/12/2020 =
* Tested compatibility with WC 4.8 & WP 5.6
* Changed default session type to WooCommerce session

= 2.2.2 - 21/11/2020 =
* Tested compatibility with WC 4.7
* Plugin name updated

= 2.2.1 - 14/10/2020 =
* Fixed a warning message that was appearing the Site Health Check

= 2.2 - 02/10/2020 =
* Added more strings to be translatable using multi-language sites
* Tested compatibility with WC 4.5

= 2.1 - 20/08/2020 =
* Fixed a bug that wasn't exempting VAT on manual orders (WP backend)

= 2.0.1 - 15/08/2020 =
* Tested compatibility with WP 5.5
* Tested compatibility with WC 4.3

= 2.0 - 25/06/2020 =
* Fixed a bug that prevented showing the correct message (valid successful) for compatibility with some themes JS
* Enhanced the SOAP method via using better communication method with EU VAT servers

= 1.9 - 17/06/2020 =
* Stopped calling the main JS file on all pages and keep it only on checkout for better performance
* Removed the string from a deprecated argument to get list of countries
* Fixed a minor issue that was causing error (failed to load external entity ) in communicating with VIES servers in some cases

= 1.8.1 - 25/03/2020 =
* Checked all plugin features compatibility with WC 4

= 1.8.0 - 23/12/2019 =
* Dev - Plugin author updated.

= 1.7.2 - 12/12/2019 =
* Dev - General - Frontend Options - "Max length" option added.
* Dev - Validation - "Skip VAT validation for selected countries" option moved from to "Advanced" section.
* Dev - Code refactoring.

= 1.7.1 - 05/12/2019 =
* Fix - Validation - Check for matching billing country code - Fixed for Greece (`EL` is replaced with `GR` when comparing country codes).
* Dev - Admin & Advanced - "Force VAT recheck on checkout" option added.
* Dev - Debug - "Error: VAT is not valid" message added to the log.
* Dev - Code refactoring.
* Tested up to: 5.3.

= 1.7.0 - 08/11/2019 =
* Dev - Validation - "Always exempt VAT for selected user roles" and "Always not exempt VAT for selected user roles" options added.
* Dev - Admin & Advanced - Debug - "Country code does not match" message added to the log.
* Dev - Admin & Advanced - Session type - "WC session" option marked as "recommended".
* Dev - Code refactoring.
* WC tested up to: 3.8.

= 1.6.1 - 16/10/2019 =
* Dev - Validation - Check company name - Now converting all values to uppercase before comparing.
* Dev - JavaScript - Better event for company validation.

= 1.6.0 - 15/10/2019 =
* Dev - General - Frontend Options - "Show field for selected user roles only" option added.
* Dev - Validation - "Check company name" option added.
* Dev - Admin & Advanced - Advanced Options - "Debug" option added.
* Dev - Code refactoring.

= 1.5.0 - 13/08/2019 =
* Dev - Admin - Order List - "EU VAT" column added.
* Dev - Admin - Reports - Taxes - "EU VAT" report added.
* Dev - Admin - EU country VAT Rates Tool - Duplicates are no longer added for the country.
* Dev - Admin settings split into sections.
* Dev - Allow VAT number input without country code - Additional country fallback added.
* Dev - Functions - General - `alg_wc_eu_vat_session_start()` - Additional `headers_sent()` check added.
* WC tested up to: 3.7.
* Tested up to: 5.2.

= 1.4.1 - 04/05/2019 =
* Fix - Preserve VAT in selected countries - Bug (when "Allow VAT number input without country code" is enabled) fixed.
* Fix - Show field for selected countries only - Bug (when "Required" is enabled) fixed.
* Dev - Frontend Options - "Confirmation notice" options added.
* Dev - Code refactoring.
* Dev - "WC tested up to" updated.

= 1.4.0 - 06/03/2019 =
* Fix - "Preserve VAT in selected countries" fixed when "Allow VAT number input without country code" is enabled.
* Dev - Frontend Options - "Always show zero VAT" option added.
* Dev - `[alg_wc_eu_vat_translate]` shortcode added.
* Dev - Shortcodes are now also processed in field label, placeholder, description and validation message options.
* Dev - Validation - Preserve VAT in selected countries - "Comma separated list" option added.
* Dev - Frontend Options - "Show field for selected countries only" option added.

= 1.3.0 - 31/01/2019 =
* Fix - Default field value on the checkout fixed.
* Dev - Display Options - Display - Multiple positions are now allowed (i.e. multiselect).
* Dev - Display Options - Display - In billing address - Field is now editable ("My Account > Addresses").
* Dev - Frontend Options - "Label CSS class" option added.
* Dev - Code refactoring.

= 1.2.1 - 30/01/2019 =
* Dev - Advanced Options - "Session type" option added.
* Dev - Admin settings - "Your settings have been reset" notice added.

= 1.2.0 - 12/11/2018 =
* Fix - AJAX - Possible "undefined index" PHP notice fixed.
* Dev - General - "Priority (i.e. position)" option added.
* Dev - General - "Raw" input is now allowed in textarea admin settings.
* Dev - Code refactoring.
* Dev - Plugin URI updated.

= 1.1.0 - 07/06/2018 =
* Dev - General - "Check for matching billing country code" option added.
* Dev - General - "Allow VAT number input without country code" option added.

= 1.0.1 - 05/06/2018 =
* Dev - `%eu_vat_number%` replaced value added to "Message on not valid" option. "Message on not valid" now doesn't check for required (i.e. empty) field.

= 1.0.0 - 24/05/2018 =
* Initial Release.

== Upgrade Notice ==

= 1.0.0 =
This is the first release of the plugin.