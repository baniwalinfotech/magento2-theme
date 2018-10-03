# Magento 2 Theme Frontend Structure

This theme is an extension of the default theme for Magento 2 "theme-frontend-luma".

## Compatibility
* This module was written based on Magento 2.2.0

## Extensibility
This module possesses specially prepared “less” files - “_extend-specific.less”, which allow the module to be extended.
If the theme “theme-frontend-structure” is used, the inheritance of themes is as follows:

**theme-frontend-luma < theme-frontend-structure < specific-theme**  

An example of the less file structure for a particular project based on "Divante / specific" using the theme “frontend-rapid” is as follows:

app/design/frontend/Baniwal/specific - Package/Theme  
app/design/frontend/Baniwal/specific/Magento_Theme - Specific module as an example  
app/design/frontend/Baniwal/specific/Magento_Theme/web/css/source/_extend.less - File to extend  
 
## Setup

#### Installation details

* `composer require baniwal/theme-frontend-structure`
* `php bin/magento setup:upgrade`

#### Admin configuration

* Go to admin panel under “Content > (Design) Configuration”
* Choose store and click “Edit” link in action column
* Under “Default Theme” tab set option “Basic Theme” for “Applied Theme”
    
## Standards & Code Quality
* This module respects all Magento2 code quality rules and our own PHPCS and PHPMD rulesets.

Visit our website [Baniwal Infotech](https://www.baniwalinfotech.com) for more information.
