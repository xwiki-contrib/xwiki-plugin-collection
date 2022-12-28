# Collection Plugin

This plugin allows to perform multipage exports in several formats, with a refactoring of header block levels. Beware it is an old plugin which uses deprecated XWiki APIs. More recent APIs and applications allow to perform similar operations, such as the [Multipage Export Application](https://extensions.xwiki.org/xwiki/bin/view/Extension/Multipage%20PDF%20Export) or the [Filter XAR Module](https://extensions.xwiki.org/xwiki/bin/view/Extension/Filter%20XAR%20module). The 2.0 release of this plugin was performed only for keeping the legacy export features available in XWiki 14.x. The old `CollectionActivityStream` which was present in older releases has been dropped since it was too complex to upgrade.

## Usage

* Install plugin via the Extension Manager
* Add `com.xpn.xwiki.plugin.collection.CollectionPlugin` to the list of plugins in `xwiki.cfg`
* Restart XWiki