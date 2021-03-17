Supported Magento versions

- Magento v2.0.x
- Magento v2.1.x
- Magento v2.2.x
- Magento v2.3.x

Install from Terminal use in root folder

```
php bin/magento maintenance:enable
-----------------------------------
#copy i18n folder to /app
-----------------------------------
php bin/magento indexer:reindex
php bin/magento cache:clean
php bin/magento cache:flush
php bin/magento maintenance:disable

```

Active Spanish MX Language

In your Magento 2 store:
- Stores > Configuration > General > Locale Options > Locale > Español (MX)
