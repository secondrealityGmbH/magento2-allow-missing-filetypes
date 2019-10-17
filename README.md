# Magento 2 Module to allow missing filetypes

    ``secondrealitygmbh/magento2-allowmissingfiletypes``

 - [Main Functionalities](#markdown-header-main-functionalities)
 - [Installation](#markdown-header-installation)
 

## Main Functionalities
Enable the upload of missing Filetypes like videos and PDFs.  
Currently enables:
- pdf
- mp4
- m4v
- webm

## Installation
\* = in production please use the `--keep-generated` option

### Type 1: Zip file

 - Unzip the zip file in `app/code/SecondrealityGmbH`
 - Enable the module by running `php bin/magento module:enable SecondrealityGmbH_AllowMissingFileTypes`
 - Apply database updates by running `php bin/magento setup:upgrade`\*
 - Flush the cache by running `php bin/magento cache:flush`

### Type 2: Composer

 - Install the module composer by running `composer require secondrealitygmbh/magento2-allowmissingfiletypes`
 - enable the module by running `php bin/magento module:enable SecondrealityGmbH_AllowMissingFileTypes`
 - apply database updates by running `php bin/magento setup:upgrade`\*
 - Flush the cache by running `php bin/magento cache:flush`




