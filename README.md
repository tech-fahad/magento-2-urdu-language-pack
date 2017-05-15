## Magento 2 Urdu Language Pack

How to install **Magento 2 Urdu Language Pack** on Magento 2 store? The best explanation will be pointed out in this topic with the same topic that is built by Mageplaza team. The post allows replacing the default language (English) by the native one (Urdu). That is great idea when your business is growing in Parkistan. Thanks to that, you will gain the expectable results in the conversion.

In this guide, not only the installation guide, you are also directed how to get the translation file through clicking on "Download .zip" button. All requirements to apply the Urdu on the entire store are referred fully and apparently. Take a look at the post now!

Read more [Magento 2 Urdu Language Pack](https://www.mageplaza.com/magento-2-urdu-language-pack.html)


## Overview

- Download & Contribute
- Install Urdu Language Pack
- How to Install Urdu Language Pack

## Download & Contribute to Urdu Language Pack

Below are two active buttons which are required operations before installing the language package. Let's hit them to download and contribute Magento 2 Urdu Language Pack immediately!

**Download packages**:

- [Download .zip](https://github.com/mageplaza/magento-2-urdu-language-pack/archive/master.zip)
- [Download .tar.gz](https://github.com/mageplaza/magento-2-urdu-language-pack/tarball/master)


Find other [language packs here]({https://www.mageplaza.com/kb/magento-2-language-pack/)

## How to Install Urdu Language Pack

There are 3 different methods to install this language pack.

### #1. Composer method
Install the Urdu language pack via composer is never easier.

**Install Urdu pack**:

```
composer require mageplaza/magento-2-urdu-language-pack:dev-master
php bin/magento cache:clean
php bin/magento setup:static-content:deploy ur_PK
php bin/magento indexer:reindex
php bin/magento cache:clean
php bin/magento cache:flush

```


**Update  Urdu pack**:

```
composer update mageplaza/magento-2-urdu-language-pack:dev-master
php bin/magento cache:clean
php bin/magento setup:static-content:deploy ur_PK
php bin/magento indexer:reindex
php bin/magento cache:clean
php bin/magento cache:flush

```

#### Authentication required (Optional)

![Authentication required](https://i.imgur.com/dmryiPk.png)

If you have not added this authentication, you can follow [this guide](http://devdocs.magento.com/guides/v2.0/install-gde/prereq/connect-auth.html)


### #2. Copy & Paste method

This method suitable for non-technical people such as merchants. Just download the package then flush cache.

**Overview**

- Step 1: Download the Urdu language pack
- Step 2: Unzip Urdu pack
- Step 3: Flush Magento 2 Cache

#### Step 1 : Download the Urdu language pack

You can download the language pack from above link

#### Step 2: Unzip Urdu pack

Unzip the Urdu language pack to Magento 2 root folder. In this guide, we extract to `/var/www/html/`
Your Magento 2 root folder can be: `/home/account_name/yourstore.com/public_html/`

```
unzip fr.zip /var/www/html/
```

You also can unzip locally and upload them to Magento 2 root folder.

#### Step 3: Flush Magento 2 Cache

Follow this guide to [Flush Cache on your Magento 2 store](https://www.mageplaza.com/kb/how-flush-enable-disable-cache.html)


### #3. Download and install manually

To download and install Urdu pack manually, you have to access to your server via FTP or SFTP.

#### Step 1: Download the package

- [Download .zip](https://github.com/mageplaza/magento-2-urdu-language-pack/archive/master.zip)
- [Download .tar.gz](https://github.com/mageplaza/magento-2-urdu-language-pack/tarball/master)

#### Step 1: Unzip and upload

Unzip the compressed file and upload file `ur_PK.zip` into `app/i18n/mageplaza/ur_PK/ur_PK.csv`

#### Step 2: Flush cache

Follow this guide to [Flush Cache on your Magento 2 store](https://www.mageplaza.com/kb/how-flush-enable-disable-cache.html)


## How to active language pack

Now time to active the language pack for your Magento 2 store. From Magento 2 admin panel, navigate to `Stores > Configuration > General > Locale Options`
![{{Magento 2 Urdu language pack}}](https://i.imgur.com/aPSUA0l.png)


<!-- ## Translation process of Urdu Language Pack
![process](http://progressed.io/bar/80) -->

Contribute to this language at https://crowdin.com/project/magento-2/ur_PK

## Supported Magento versions

- Magento v2.0.0
- Magento v2.0.1
- Magento v2.0.2
- Magento v2.0.3
- Magento v2.0.4
- Magento v2.0.5
- Magento v2.0.6
- Magento v2.0.7
- Magento v2.0.8
- Magento v2.0.9
- Magento v2.0.10
- Magento v2.0.11
- Magento v2.0.12
- Magento v2.0.13
- Magento v2.1.0
- Magento v2.1.1
- Magento v2.1.2
- Magento v2.1.3
- Magento v2.1.4
- Magento v2.1.5
- Magento v2.1.6



## Language package authors

- [Magento official translations project for Magento 2](https://crowdin.com/project/magento-2)
- Language packages built by [Mageplaza team](https://www.mageplaza.com/)


## References:

- https://www.mageplaza.com/magento-2-urdu-language-pack.html
- https://www.mageplaza.com/kb/magento-2-language-pack/
- https://crowdin.com/project/magento-2