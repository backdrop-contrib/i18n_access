# Translation Access

This module provides per-language access control for creating and updating nodes
by adding a list of checkboxes for each available language to the user add/edit
form (only visible to users with 'administer users' permission). These language
permissions are combined with the normal user permissions to give more
fine-grained access control.


## Installation

 - Install this module using the [official Backdrop CMS instructions](https://backdropcms.org/guide/modules).

## Configuration and Usage

 - When creating new content, the language select box will only contain those
   languages that a user has permissions for.
 - The translation tab on nodes will only show Add Translation, or Edit for
   those languages that a user has permissions for.
 - The edit tab will not show for if a user does not have access to the language
   of that node. The node edit page will also return an access denied in this
   case.
 - Language Neutral is supported, so unless a user has access to Language
   Neutral, they will be forced to select a language for every translatable
   node.
 - No effect on nodes that are not translatable.
 - Users with "Administer nodes" permission still have access to all languages.

More details may be found (or added) in the [Wiki](https://github.com/backdrop-contrib/i18n_access/wiki)

## Issues

Bugs and Feature requests should be reported in the [Issue Queue](https://github.com/backdrop-contrib/i18n_access/issues)

## Current Maintainers

 - [Laryn Kragt Bakker](https://github.com/laryn), [CEDC.org](https://CEDC.org)
 - Collaboration and co-maintainers are welcome.

## Credits

- Ported to Backdrop by [Laryn Kragt Bakker](https://github.com/laryn), [CEDC.org](https://CEDC.org).
- Maintained for Drupal by [yang_yi_cn](https://www.drupal.org/u/yang_yi_cn),
  [zroger](https://www.drupal.org/u/zroger), 
  and [toemaz](https://www.drupal.org/u/toemaz).

## License

This project is GPL v2 software. See the LICENSE.txt file in this directory for
complete text.
