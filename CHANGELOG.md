# Changelog
All notable changes to this project will be documented in this file.

## 1.1.6
Release Date: September 18, 2020

* Added: An option on payment page to go back to select any mayment method. This can be disabled by a filter.
* Tweak: UPI Pay Button will be shown only on android devices.
* Tweak: Added some CSS Improvements.
* Optimize codes and stability.
* Tested with WooCommerce v4.5.

## 1.1.5
Release Date: August 14, 2020

* Fixed: Popup is not showing if QR is hidden on mobile devices.
* Tested with WordPress v5.5.

## 1.1.4
Release Date: June 29, 2020

* Fixed: Some JS issues.

## 1.1.3
Release Date: June 24, 2020

* Added: Option to get Transaction ID, which was previously removed on v1.1.2.
* Added: Option to change payment confirm message.
* Added: Some validations.
* Tweak: Sort UPI Handles alphabatically and introduced autocomplete.
* Fixed: UPI ID is not showing as WooCommerce transaction ID.
* Fixed: Some CSS & JS issues.
* Other Improvements.

## 1.1.2
Release Date: June 9, 2020

* Added: Dark Mode for popup.
* Tweak: Plugin will now show UPI ID field on checkout page as it will boost customer experience on checkout instead of getting the UPI ID after the payment. It can be disable from plugin settings.
* Tweak: Transaction ID is completely removed to simplify the customer checkout experience.
* Tweak: Added some styles on order payment page to enhance the checkout experience.
* Tweak: Cancel button will redirect customers to checkout page.
* Tweak: Cart will be automatically cleared if payment is actually completed.
* Fixed: 404 not found issue and other permaalinks issues.
* WC Compatibity upto v4.2.

## 1.1.1
Release Date: June 1, 2020

* Tweak: Added some css classes to use custom styling for mobile button.
* Fixed: A bug where 404 error is thrown if WordPress does not use pretty permalinks.
* Fixed: A bug where popup becomes unresponsive in mobile devices if QR Code is hidden on mobile device.
* Fixed: Some CSS & JS issues.


## 1.1.0
Release Date: May 24, 2020

* Tweak: Can disable Payment details collection from plugin settings.
* Fixed: A bug where popup becomes unresponsive in mobile devices.
* Fixed: Some CSS & JS issues.
* Fixed: Custom button text is not working.

## 1.0.9
Release Date: May 20, 2020

* Tweak: Payment Dialog will automatically apprear after page load.
* Fixed: The `upiwc_order_total_amount` filter is not working.

## 1.0.8
Release Date: May 18, 2020

* Fixed: A PHP error.
* Fixed: Wrong tooltips.
* Updated the Payment gateway logo.

## 1.0.7
Release Date: May 18, 2020

* NEW: Added option to enable or disable UPI Handle field.
* NEW: Added option to enable or disable UPI Transaction field.
* NEW: Added option to make UPI Transaction field required at the time of checkout.
* NEW: Added option to hide QR Code on mobile devices.
* NEW: Added a cancel button to go back to the actual order pay page if customer wants to change payment method.
* Improved: Payment verification process to prevent false order payment.
* Improved: Added some mobile only CSS to make it easy for customers.
* Tweak: Make some settings JS based to make the checkout process smooth.
* Tweak: It is now possible to use any other payment method to make payment when payment initialized at first through the UPI QR Code method.
* Fixed: Undefined variable issue which shows warning at the time of processing payment.
* Fixed: Some CSS & JS issues.
* Fixed: Untraslated strings.
* Cleanup: Removed unnecessary codes.
* Compatibity with WooCommerce v4.1.

## 1.0.6
Release Date: April 28, 2020

* Added: A filter to disable UPI Handle field.
* Fixed: Some CSS issues.
* Fixed: Untraslated strings.

## 1.0.5
Release Date: April 26, 2020

* Added: Client Side validation for UPI ID and Transaction ID.
* Tweak: Applied QR Auto corrction and resizes it to 150x150 px.
* Fixed: QR Code is not displaying if there is some unexpected charecters.
* Fixed: Some typos.
* Fixed: Untraslated strings.

## 1.0.4
Release Date: April 15, 2020

* Improved: Order Confirm mechanism.
* Fixed: Dialog Box issue on Mobile devices.

## 1.0.3
Release Date: April 13, 2020

* NEW: Major UI Changes in Payment Confirm Process.
* Fixed: A bug where payment can't be done using BHIM App.

## 1.0.2
Release Date: March 20, 2020

* Fixed: A bug where plugin shows a false 403 error.

## 1.0.1
Release Date: March 14, 2020

* Added: JS Validation to verify the UPI Transaction ID.
* Added: A filter `upiwc_capture_payment_redirect_notice` to customize the payment success message.
* Improved: Now this plugin treats all unpaid orders as pending. After successful UPI Validation order status will be changed into "On Hold". It can be customized from plugin settings.
* Improved: This plugin now uses On Hold Order Email template to send payment pending email to customers.
* Fixed: Some CSS Errors.
* Fixed: Some typo.
* Tested upto WordPress v5.4 and WooCommerce v4.0.

## 1.0.0
Release Date: January 30, 2020

* Initial release.