# The Elder Scrolls Online UI Schema Definitions

XML Schema definitions for validating The Elder Scrolls Online (ESO) user interface addon files. This repository provides XSD files for both GuiXml and Bindings validation.

## Usage

### GuiXml Validation

Add the following namespace declaration to your GuiXml files:

```xml
<GuiXml xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
    xsi:noNamespaceSchemaLocation="https://raw.githubusercontent.com/DakJaniels/esoui_gui_xsd/main/esoui_gui_xml.xsd">
</GuiXml>
```

### Bindings Validation

Add the following namespace declaration to your Bindings files:

```xml
<Bindings xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
    xsi:noNamespaceSchemaLocation="https://raw.githubusercontent.com/DakJaniels/esoui_gui_xsd/main/esobindings.xsd">
</Bindings>
```

## Schema Files

- `esoui_gui_xml.xsd` - Schema for UI layout and controls
- `esobindings.xsd` - Schema for keybinding definitions

## Alternative Resources

For additional ESO UI schema resources and validation tools:

- Visit [sirinsidiator's documentation](https://sir.insidi.at/or/2018/07/10/schema-definition-for-esoui-xml/)
- Alternative schema URLs:
  - ESOUI Schema: [http://sir.insidi.at/or/schema/esoui.xsd](http://sir.insidi.at/or/schema/esoui.xsd)
  - ESOBindings Schema: [http://sir.insidi.at/or/schema/esobindings.xsd](http://sir.insidi.at/or/schema/esobindings.xsd)

**Note:** The GuiXml schema at sirinsidiator's website may be outdated (last verified: February 2023).

## Contributing

For issues, suggestions, or contributions, please open an issue or pull request in this repository.
