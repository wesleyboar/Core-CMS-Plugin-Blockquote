## Texas Advanced Computing Center
# Django CMS Plugin: "Blockquote"

This plugin renders a `<blockquote>` with semantic internal markup.

- __`__plugin_name__`__: `taccsite_blockquote`
- __`__PluginName__`__: `TaccsiteBlockquote`
- __"Plugin Name"__: "Blockquote"

## Quick Start

1. Follow https://github.com/tacc-wbomar/Core-CMS-Plugin/wiki/Core-CMS-Plugin-Usage-Quick-Start.

## Usage

1. Add instance of plugin to a page.
1. Configure the plugin instance.
1. See plugin render content that matches configuration.

## Features

1. Render a `<blockquote>` with content in semantic markup.
2. Support (optional) complex citation: author/speaker, source text, source URL.
3. Uses supported, integrated plugin instances to incorporate extra features.
    <details>

    | feature | supported by |
    | :- | :- |
    | offset blockquote from surrounding content | [`taccsite_offset`][tacc-offset] |

    </details>.

## Caveats

- Requires [`taccsite_offset`][tacc-offset].\*

> \* Support is mandatory, but should become optional in a future release.

[tacc-offset]: https://github.com/tacc-wbomar/Core-CMS-Plugin-Offset/
