# oxid-cookie-compliance

# OXID cookie compliance modul

Free OXID eShop 4/5/6 module for GDRP compliance.

## Installation
- Get module by composer `composer require aggrosoft/oxid-cookie-compliance` (oxid 6)
- Copy module to modules folder (oxid 4/5)

## Configuration
- See module settings
- Activate "Lern-Modus" and make an test order, after this deacticate "Lern-Modus"
- Change cookie settings in general shop data --> cookie
- add `[{include file="widget/cookieinfos.tpl"}]` to `oxsecurityinfo` cms-page
