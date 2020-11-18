# Odoo Code Snippets

This extension contains useful predefined code snippets for [Odoo](https://www.odoo.com/) developers.

All snippets are for Odoo versions `10.0` and above, and follow the last [Odoo Guidelines](https://www.odoo.com/documentation/13.0/reference/guidelines.html).

## Installation

1. Launch **Quick Open**

    * [Linux](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-linux.pdf) `Ctrl+P`
    * [MacOS](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-macos.pdf) `⌘+P`
    * [Windows](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf) `Ctrl+P`

2. Paste the following command and press `Enter`:

    ```shell
    ext install lgallo.odoo-snippets
    ```

## Usage

Snippets are available for the following languages:

* Python (`.py`)
* XML (`.xml`)

### Python Snippets

| Snippet               | Description             |
| --------------------- | ----------------------- |
| `omanifest`           | Manifest file           |
| `oimport`             | Imports                 |
| `omodel_new`          | Model                   |
| `omodel_inherit`      | Inherited model         |
| `omodel_test`         | Test class              |
| `ofield_binary`       | Binary field            |
| `ofield_boolean`      | Boolean field           |
| `ofield_char`         | Char field              |
| `ofield_date`         | Date field              |
| `ofield_datetime`     | Datetime field          |
| `ofield_float`        | Float field             |
| `ofield_html`         | Html field              |
| `ofield_integer`      | Integer field           |
| `ofield_text`         | Text field              |
| `ofield_selection`    | Selection field         |
| `ofield_m2o`          | Many2one field          |
| `ofield_m2m`          | Many2many field         |
| `ofield_o2m`          | One2many field          |
| `omethod_create`      | create() method         |
| `omethod_write`       | write() method          |
| `omethod_unlink`      | unlink() method         |
| `omethod_compute`     | Compute method          |
| `omethod_compute_ext` | Extended Compute method |
| `omethod_constrains`  | Constraint method       |
| `omethod_onchange`    | Onchange method         |

### XML Snippets

| Snippet                | Description                            |
| ---------------------- | -------------------------------------- |
| `<odoo>`               | Odoo namespace                         |
| `<data>`               | Data file                              |
| `<menuitem>`           | Root menu                              |
| `<menuitem>`           | Submenu                                |
| `<form>`               | Form view                              |
| `<tree>`               | List view                              |
| `<kanban>`             | Kanban view                            |
| `<search>`             | Search view                            |
| `<calendar>`           | Calendar view                          |
| `<cohort>`             | Cohort view (Enterprise Edition)       |
| `<dashboard>`          | Dashboard view (Enterprise Edition)    |
| `<gantt>`              | Gantt view (Enterprise Edition)        |
| `<graph>`              | Graph view                             |
| `<pivot>`              | Pivot view                             |
| `<activity>`           | Activity view                          |
| `<qweb>`               | QWeb view                              |
| `<inherit_view>`       | Inherited view                         |
| `<field>`              | Field                                  |
| `<field_self_closing>` | Self-closing field                     |
| `<notebook>`           | Notebook                               |
| `<page>`               | Notebook Page                          |
| `<status>`             | Status bar                             |
| `<button>`             | Button                                 |
| `<button>`             | Stat button                            |
| `<button>`             | Button box                             |
| `<chatter>`            | Chatter                                |
| `<window_action>`      | Window action (versions prior to 13.0) |
| `<window_action>`      | Window action (version 13.0)           |
| `<server_action>`      | Server action                          |
| `<client_action>`      | Client action                          |
| `<url_action>`         | URL action                             |
| `<automated_action>`   | Automated action                       |
| `<report_action>`      | Report action                          |
| `<report_template>`    | Report template                        |
| `<record>`             | Record                                 |
| `<function>`           | Function                               |
| `<template>`           | Template                               |
| `<inherit_template>`   | Inherited template                     |
| `<xpath>`              | XPath                                  |
| `<xpath_attr>`         | XPath to attributes                    |
| `<attribute>`          | Attribute tag for XPath                |
| `<t-if>`               | QWeb if condition                      |
| `<t-if>`               | QWeb if-else condition                 |
| `<t-foreach>`          | QWeb loop                              |
| `<t-set>`              | QWeb variable                          |
| `<t-att>`              | QWeb attribute                         |
| `<t-att>`              | QWeb attribute with format value       |
| `<t-att>`              | QWeb attribute with format value       |
| `<t-esc>`              | QWeb evaluate expression               |
| `<t-raw>`              | QWeb evaluate HTML content             |
| `<t-call>`             | QWeb call template                     |
| `<t-debug>`            | QWeb invoke debugger                   |
| `<t-log>`              | QWeb log expression result             |

## Contributing

If you'd like to report an issue or help contribute to this extension, please visit the repository on Github.

* [Repository](https://github.com/lisandrogallo/vscode-odoo-snippets/)
* [Issues](https://github.com/lisandrogallo/vscode-odoo-snippets/issues)

See the contributing guidelines [here](https://github.com/lisandrogallo/vscode-odoo-snippets/blob/master/CONTRIBUTING.md).

## Release Notes

Detailed release notes are available [here](https://github.com/lisandrogallo/vscode-odoo-snippets/blob/master/CHANGELOG.md).

## Credits

This extension includes some snippets based on two other different Visual Studio Code extension projects:

* [VscOdooSnippets](https://github.com/Droggol/VscOdooSnippets)
* [vscode-odoo-snippets](https://github.com/mstuttgart/vscode-odoo-snippets)

Snippets order and structure, prefix names and coding style are based on my daily use and some criteria of my preference, following the last [Odoo Guidelines](https://www.odoo.com/documentation/13.0/reference/guidelines.html).
