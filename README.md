<p align="center">
  <img src="https://dashboard.mrsignage.com/img/logo.png" width="105" height="128"/>
</p>
<h1 align="center">Magento2 product feed for MrSignage</h1>

This plugin provides a connection for the magento plugin in [MrSignage](https://mrsignage.com).

## Installation
You can install this package using composer:

```
Composer require Mrsignage/magento2

Php bin/magento module:enable MrSignage_Rss
Php bin/magento setup:upgrade
Php bin/magento cache:clean
```

## Usage
There are 2 options to show the products on your screen, the first option is to show all products form a certain category. The other option is to select each product.

To change the shown products navigate to MrSignage -> manage catalog. Here you can choose if you want to show a Category or Products.

### Categories
To show products from a category change the Datatype to Category. After changing the option to category you are able to select a category in the category field.

### Products
To show products change the Datatype to Products. After changing the option to product you are able to navigate to the product page in the sidebar. On this page you are able to select the products you want to show on your screen.

## FAQ and Troubleshooting  ##
If you have questions or experience problems while using [MrSignage](https://mrsignage.com), please see our [Documentation](http://docs.mrsignage.com/) or send an e-mail to [support@mrsignage.com](mailto:support@mrsignage.com).

## License

GNU Affero General Public License (AGPL-3.0). Please see [License File](LICENSE.md) for more information.
