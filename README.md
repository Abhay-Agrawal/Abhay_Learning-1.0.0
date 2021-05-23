
![](https://komarev.com/ghpvc/?username=Abhay-Agrawal&color=green)
[![Github All Releases](https://img.shields.io/github/downloads/Abhay-Agrawal/Abhay_Learning-1.0.0/total.svg)]()

# Learning Magento2 Extension
**To Add text message, Drop Down, Radio Button, Multi Select and Text Area in store configuration**
___
# How to install

Add the module in app/code/ folder in magento root like as app/code/Abhay/Learning
and run the command 
```php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento setup:static-content:deploy -f
php bin/magento indexer:reindex
php bin/magento cache:clean
php bin/magento cache:flush
```

This Module is used to add 
1. Radio Button
2. Drop Down
3. Multi Select
4. Text Area in the system configuration
after adding these field in the admin configuration then our admin pannel looking like as below image 

![learning_backend](https://user-images.githubusercontent.com/55655451/91631748-87a3aa00-e9f9-11ea-97d4-9f8c08c2da77.png)

After saving the value of admin configuration then we can get these value in our custom layout like as given image 

![learning_front](https://user-images.githubusercontent.com/55655451/91631762-a6a23c00-e9f9-11ea-8062-afeb6768ffd9.png)

___

# My Magento Module

| S.No.| Module Name | Description |
| --- | --- | --- |
| 1.| [Learning Module](https://github.com/Abhay-Agrawal/Abhay_Learning-1.0.0) | To Add text message, Drop Down, Radio Button, Multi Select and Text Area in store configuration |
| 2.| [Custom Module](https://github.com/Abhay-Agrawal/CustomModule)| To Fetch the system configuration value and Product Information using GraphQl |
| 3.| [Custom Shipping](https://github.com/Abhay-Agrawal/Abhay_CustomShipping-1.0.0) | This module is used to add the Custom Shipping in the Website|
| 4.| [LatestNews](https://github.com/Abhay-Agrawal/Abhay_LatestNews-1.0.0) | Add Latest News Related to product offer with content in your website |
| 5.| [GroupProductOptions](https://github.com/Abhay-Agrawal/Abhay_GroupProductOptions-1.0.0) | To show the group product options like as child product available quantity, SKU and custom message |


