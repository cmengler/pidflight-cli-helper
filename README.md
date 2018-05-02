# PIDflight CLI Helper
The aim of this project is to help organise and maintain the CLI commands that is utilised by the CLI Helper function in the PIDflight app.

# File formats
There are two files per translation --

| File | Description | Columns |
| ---- | ----------- | ------- |
| \<firmware>\_cli\_\<locale>.csv | CLI command details | Category, Command, Title, Description |
| \<firmware>\_category\_\<locale>.csv | Category names | Category |

# Firmware

* __Betaflight__ also encapsulates Cleanflight and ButterFlight commands.
* __FlightOne__ (formerly RaceFlight One) is currently a work-in-progress, place holder CSV files have been added for convenience.

# How to contribute

### New category
Any new additions to the CLI categories must be added to the English CSV file first.

### New CLI command
Any new additions to the CLI commands must be added to the English CSV file first.

Things to note:
1. CLI commands don't necessarily require a description, a title may suffice in most cases -- especially if the title is self explanatory.
2. Be mindful to keep descriptions as short as possible.

### New translations
New translations __must__ be based off the English files. Please use \<firmware>_cli_en.csv and \<firmware>_category_en.csv as the base file for the new translation.

# Locales

See [LOCALE.md](https://github.com/cmengler/pidflight-cli-helper/blob/master/LOCALE.md) for a list of available languages.