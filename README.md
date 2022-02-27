# MantisBT-Mattermost

Essentially a copy of a Slack plugin with a few modifications.

## General Information

This plugin is based on a [Slack plugin](https://github.com/infojunkie/MantisBT-Slack) with some modifications. This helps interact with Mattermost as it MM has Slack compatibilities. The following was changed from the original plugin:

* Text for various pieces
* Additional languages removed as it wasn't just a simple "change slack to mattermost" transition (translations are welcomed)
* Default message format for bug reports
* HTML simplification

The slack plugin was chosen for this purpose as the mattermost plugin was missing a lot of features and pieces that I had found useful. I could've just used that plugin too, but there are changes I'd like to make in the future that would make it incompatible with it for Slack.

## TODO

* Support Bot Accounts instead of simple push URL/Token
* Allow mapping to occur on the config page rather than in configuration workflow

## Compatibility

PHP: 7+

**Note**: PHP version 7.0 is the minimum because 5.x has been EOL for forever.

* If you are using Enterprise Linux 7, use Remi or IUS for a newer PHP
* If you are using Enterprise Linux 8, the default modules use PHP 7
* If you are using Enterprise Linux 6, **it is EOL**. Please backup and restore to a supported system.
