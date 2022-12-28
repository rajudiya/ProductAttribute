# Custom ProductAttribute

Creates custom CMS block with content along with product attribute `Condensing` 

`Custom product attribute which shows static block 'condensing'at product page`

## Composer install

- `composer config repositories.ProductAttribute vcs https://github.com/rajudiya/ProductAttribute`

- `composer require custom/product-attribute:dev-main`

## Composer uninstall

- `composer remove custom/product-attribute`

## Settings

- Module Enable Path `Store >> Configuration >> Custom Product Attribute >> Enable`

## Known issues

- **Issues will be here**
  Compartible with magento 2.4.5

## Developer informations
- Developer Name - Rohan Ajudiya
- Inkdin url     - https://www.linkedin.com/in/ajudiya-rohan-9a9ab81b3/
- Contect us     - +91 6353856107

### Install module

1. Run `php bin/magento setup:upgrade`
2. Run `php bin/magento setup:di:compile`
3. Run `php bin/magento s:s:d`
4. Run `php bin/magento c:c`
6. Run `php bin/magento indexer:reindex`
7. run `php bin/magento setup:static-content:deploy -f`

### Uninstall module
1. Run `php bin/magento setup:di:compile`
2. Run `php bin/magento s:s:d`
3. Run `php bin/magento c:c`
4. Run `php bin/magento indexer:reindex`
5. run `php bin/magento setup:static-content:deploy -f`

### Additional developer notes
Reference URL `References will be added.`
