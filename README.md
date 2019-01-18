# LCC|Pay

A Litecoincash payment method for the Magento 2 ecommerce app using Litecoin Cash RPC API.

## Install with Composer as you go

1. Go to Magento 2 root folder

2. Enter following commands to install module:

    composer require kasbrahan/module-litecoincash
    ```
   Wait while dependencies are updated.

3. Enter following commands to enable module:

	php bin/magento setup:upgrade
	php bin/magento setup:static-content:deploy
