# Changelog

This changelog tracks changes starting from first public release.

## `master` branch - Not released yet

## v0.1.2

- Provide parser output command

- Support for symbols and parser error on multiple documents

## v0.1.1

- Added `firstLine` element in extension definition so VSCode can recognise API Blueprint documents.

- Clear all related annotations when a document is closed. See [https://code.visualstudio.com/updates#_extension-authoring](VSCode updates) for more details.

- Renamed all references from `APIBlueprint` to `API Blueprint`. Same from `APIElements` to `API Elements`

- Grab the Refract output even when an exception is thrown

- Handle the case when the source map is actually on a new line symbol
