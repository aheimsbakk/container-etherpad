# Etherpad with plugins

Based on [Etherpad](https://hub.docker.com/r/etherpad/etherpad) `latest`, see Github repository [etherpad-lite](https://github.com/ether/etherpad-lite/) for more information.

Only addition is extra plugins:

* `ep_adminpads2` --- Etherpad plugin to list and delete pads in /admin.
* `ep_author_hover` --- Adds author names to span titles (shows on hover), works as authors change their name. Hover includes author color and fast switching between author spans. Hat tip to Martyn York for the initial work on this.
* `ep_font_color` --- Apply colors to fonts.
* `ep_headings2` --- Adds heading support to Etherpad Lite. Includes improved suppot for export, i18n etc.
* `ep_prompt_for_name` --- Prompt an author for their name 5 seconds after they type.
* `ep_spellcheck` --- Add support to do 'Spell checking', with a toggle on/off option in Settings.

## Tags

* [`latest`](https://github.com/aheimsbakk/container-etherpad/blob/master/Dockerfile)

# Usage

See original documentation [docker.md](https://github.com/ether/etherpad-lite/blob/develop/doc/docker.md).

<!---
# vim: set spell spelllang=en:
-->
