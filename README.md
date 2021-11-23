# Php Data Object Generator plugin for IntelliJ and PhpStorm

[![Version](https://img.shields.io/jetbrains/plugin/v/17440.svg)](https://plugins.jetbrains.com/plugin/17440)
[![Downloads](https://img.shields.io/jetbrains/plugin/d/17440.svg)](https://plugins.jetbrains.com/plugin/17440)

<!-- Plugin description -->
## PHP Data Object Generator

### Description
Code generator plugin for PHP Data Objects (Value Object, DTO/Data Transfer Object, etc...) and Builder pattern objects for creating them.

### Cost
The basic code generator for Data Objects and Builders are **free** and require no license.  Just install the plugin.
Advanced in-place refactoring of previously generated classes to add/remove class properties require a nominal one time fee to use after
the 30-day trial.

### Features

#### Free
- Generate new Data Objects by defining class properties.
- Generate Builder classes for your Data Objects.
- Modify templates used in generation.

#### Paid
- Ability to in-place refactor the Data Object and their Builders to add and remove properties.

## Usage

### To generate a new Data Object:
- Select "Php Data Object" from the *New File* menu.
  - <kbd>Right Click</kbd> > <kbd>New</kbd> > <kbd>Php Data Object</kbd>
- Fill in the dialog supplying classname and property definitions.
- Optionally select to make the class immutable (no "setter" methods will be generated).
- Optionally enable generating a Builder for the class.

### To generate a Builder from an existing PHP class:
- Select "Builder..." from the _Generate_ menu
  - <kbd>Right Click in Editor view on PHP class</kbd> > <kbd>Generate</kbd> > <kbd>Builder...</kbd>
- Define Builder classname and select which properties to include in the Builder.

### Modify Templates used to Generate Code
- Open Project Preferences
  - <kbd>alt-.</kbd> or <kbd>command-.</kbd>
- Within Preferences: <kbd>Editor</kbd> > <kbd>File and Code Templates</kbd> > <kbd>"Other" tab</kbd> > <kbd>PHP Data Object Plugin</kbd>
- Select "PHP DataObject Plugin"
  - Edit templates as needed. 

### To In-Place Refactor existing Data Object:

- Select "Update Data Object" from the _Refactor_ menu
  - <kbd>Right Click in Editor view on PHP class</kbd> > <kbd>Refactor</kbd> > <kbd>Update Data Object</kbd>
- Unselect any properties you wish to **remove** from the _Existing Properties_ table.
- Define any properties you wish to **add** to the _New Properties_ table.

_Note: In-place refactoring will only function on data classes previously generated using this plugin._

_Note: Making **significant** modifications to the included templates may cause the automatic refactoring to fail or produce otherwise unsatisfactory results.  If you run into issues please submit a bug report with your template and example code._




Submit BugReports or Feature Requests: [https://github.com/SourceLabOrg/PhpDataObjectGeneratorPlugin/issues](https://github.com/SourceLabOrg/PhpDataObjectGeneratorPlugin/issues)


<!-- Plugin description end -->

---

## Installation

- Using IDE built-in plugin system:
  
  <kbd>Settings/Preferences</kbd> > <kbd>Plugins</kbd> > <kbd>Marketplace</kbd> > <kbd>Search for "Php Data Object Generator"</kbd> >
  <kbd>Install Plugin</kbd>
  
- JetBrains Market Place:

  Download the [latest release](https://plugins.jetbrains.com/plugin/17440-php-data-object-generator) and install it manually using
  <kbd>Settings/Preferences</kbd> > <kbd>Plugins</kbd> > <kbd>⚙️</kbd> > <kbd>Install plugin from disk...</kbd>

---
