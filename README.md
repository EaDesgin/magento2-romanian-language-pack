# EaDesign Magento 2 Romanian Language Pack (ro_RO)
The Romanian language pack maintained and supported by EaDesign

# Configure backend for Magento 2

* Activate language (backend): Account > Settings > Account information > Interface Locale
* Activate language (frontend): Stores > Settings > Configuration > [storeview] > Locale options > Locale

# Installation (manual) by cloning or copy of the files

* Clone repository to app/i18n/eadesigndev/ro_ro/
* Upgrade installation using $ php bin/magento setup:upgrade
* Clear cache using $ php bin/magento cache:clean
* Deploy static content $ php bin/magento setup:static-content:deploy ro_RO

# Installation using Composer

* Require via Composer CLI $ composer require eadesignro/ro_ro
* Upgrade installation using $ php bin/magento setup:upgrade
* Clear cache using $ php bin/magento cache:clean
* Deploy static content $ php bin/magento setup:static-content:deploy ro_RO

# What next?

* The translation is incomplete. 
* Fix some areas that are no sounding ok.
