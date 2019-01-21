WooCommerce PayOp Payment Gateway
=====================

## Brief Description

Add the ability to accept payments in WooCommerce via Payop.com.

## Requirements

-  WooCommerce 3.0+


## Installation
 1. Download latest [release](https://github.com/Payop/woocommerce-plugin/releases)
 2. Log in to your WordPress dashboard, navigate to the Plugins menu and click "Add New" button
 3. Click "Upload Plugin" button and choose release archive
 4. Click "Install Now". 
 5. After plugin installed, activate the plugin in your WordPress admin area.
 6. Open the settings page for WooCommerce and click the "Payments" tab
 7. Click on the sub-item for PayOp.
 8. Configure and save your settings accordingly.

You can issue  **Public key** and **Secret key** after register as merchant on PayOp.com.  

Use below parameters to configure your PayOp project:
* **Callback/IPN URL**: https://{replace-with-your-domain}/?wc-api=wc_payop&payop=result

## Support

* [Open an issue](https://github.com/Payop/woocommerce-plugin/issues) if you are having issues with this plugin.
* [PayOp Documentation](https://payop.com/en/documentation/common/)
* [Contact PayOp support](https://payop.com/en/contact-us/)
  
**TIP**: When contacting support it will help us is you provide:

* WordPress and WooCommerce Version
* Other plugins you have installed
  * Some plugins do not play nice
* Configuration settings for the plugin (Most merchants take screen grabs)
* Any log files that will help
  * Web server error logs
* Screen grabs of error message if applicable.

## Contribute

Would you like to help with this project?  Great!  You don't have to be a developer, either.
If you've found a bug or have an idea for an improvement, please open an
[issue](https://github.com/Payop/woocommerce-plugin/issues) and tell us about it.

If you *are* a developer wanting contribute an enhancement, bugfix or other patch to this project,
please fork this repository and submit a pull request detailing your changes.  We review all PRs!

This open source project is released under the [MIT license](http://opensource.org/licenses/MIT)
which means if you would like to use this project's code in your own project you are free to do so.


## License

Please refer to the 
[LICENSE](https://github.com/Payop/woocommerce-plugin/blob/master/LICENSE)
file that came with this project.
