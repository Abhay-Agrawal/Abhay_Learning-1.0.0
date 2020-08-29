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

![learning_backend](https://user-images.githubusercontent.com/55655451/91631748-87a3aa00-e9f9-11ea-97d4-9f8c08c2da77.png)

![learning_front](https://user-images.githubusercontent.com/55655451/91631762-a6a23c00-e9f9-11ea-8062-afeb6768ffd9.png)
