# FixStoreInformationScope

Magento 2 module for fix 'Store Information' scope (see https://github.com/magento/magento2/issues/38498). 

**This is a temporary solution.** Created a pull request https://github.com/magento/magento2/pull/38542.

***

## INSTALLATION

### manual

1. Download ZIP file and extract to **app/code/Noon/FixStoreInformationScope**. If this path not exists, please create under Magento2 root directory.
2. Run the command in Magento2 root directory:

```bash
php bin/magento setup:upgrade
```

### composer

1. Run the command in Magento2 root directory:

```bash
composer require noon/module-fix-store-information-scope
php bin/magento setup:upgrade
```

***

<a href="https://www.buymeacoffee.com/alex79" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a>
