# Learning Magento2 Extension
To Add text message, Drop Down, Radio Button, Multi Select and Text Area in store configuration

# How to install

Add the module in app/code/ folder in magento root like as app/code/Abhay/GroupProductOptions
and run the command 
```php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento setup:static-content:deploy -f
php bin/magento indexer:reindex
php bin/magento cache:clean
php bin/magento cache:flush
```
