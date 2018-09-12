CONTENTS OF THIS FILE
---------------------

 * Introduction
 * Requirements
 * Installation
 * Configuration
 * Maintainers


INTRODUCTION
------------

This module is temporary solution, before issue [#2999018][Issue #2999018] will be solved.

It allows you to change oEmbed Providers URL other than default via UI. For example, in Russia this URL is blocked and oEmbed not working, this why this module exists.

For example, you can use providers.json uploaded on [GitHub Gist][providers.json]. For this you upload actual file contents to Gist, and get link to [**Raw**][providers.json raw] value of file and set it in settings.

For security reasons use only URL's you absolutely trust.

Features:

 * Adds editable field for settings `media.settings.oembed_providers_url`.
 * Restore default value on uninstall.

REQUIREMENTS
------------

This module requires Media module from Drupal core, and core Drupal 8.6+ in which oEmbed was added.

 * Drupal core >= 8.6.0
 * Media from core.


INSTALLATION
------------

It's recommended to install module via composer, but not necessary.

 * Install the oEmbed Providers URL UI module as you would normally install a contributed
   Drupal module. Visit https://www.drupal.org/node/1897420 for further
   information.


CONFIGURATION
-------------

 1. Navigate to Administration > Extend and enable the module.
 2. To configure oEmbed Providers URL navigate to Administration > Configuration > Media > Media settings. Or use Configuration link from module list.


MAINTAINERS
-----------

 * Nikita Malyshev (Niklan) - https://www.drupal.org/u/niklan

[Issue #2999018]: https://www.drupal.org/project/drupal/issues/2999018
[providers.json]: https://gist.github.com/Niklan/56cf7d3d72fe906a6458cf5ad296762d
[providers.json raw]: https://gist.githubusercontent.com/Niklan/56cf7d3d72fe906a6458cf5ad296762d/raw/f44a606535b9e5afa4ba3d52c652681e152bf4ff/providers.json