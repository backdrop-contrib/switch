# Switch

This module provides a form element and widget for a visual on/off switch.

## Installation

 - Install this module and its dependencies using the official
  [Backdrop CMS instructions](https://backdropcms.org/guide/modules)

## Configuration and Usage

There are two ways to use the widget:

1. **Field UI**
A widget is provided for checkbox (boolean) fields. When creating a boolean
field, select `switch` as the widget.

2. **Form API**
The module defines a new form element type `switch` - use as you would a
checkbox.

```
$form['example'] = array(
	'#type' => 'switch',
	'#title' => t('Example'),
);
```

## Issues

Bugs and Feature requests should be reported in the [Issue Queue](https://github.com/backdrop-contrib/switch/issues)

## Current Maintainers

 - [Laryn Kragt Bakker](https://github.com/laryn)

## Credits

- Ported to Backdrop CMS by [Laryn Kragt Bakker](https://github.com/laryn) for
  [Aten Design Group](https://atendesigngroup.com/).
- Current maintainer for the Drupal module: [Ben Scott](https://github.com/benscott).

## License

This project is GPL v2 software. See the [LICENSE.txt](https://github.com/backdrop-contrib/switch/blob/1.x-1.x/LICENSE.txt)
file in this directory for complete text.
