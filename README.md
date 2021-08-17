# Php Data Object Generator plugin for IntelliJ and PhpStorm

[![Version](https://img.shields.io/jetbrains/plugin/v/17440.svg)](https://plugins.jetbrains.com/plugin/17440)
[![Downloads](https://img.shields.io/jetbrains/plugin/d/17440.svg)](https://plugins.jetbrains.com/plugin/17440)

<!-- Plugin description -->
Code generator plugin for PHP Data Objects (POJO, POPO, DTO, etc...) and Builder pattern objects.

To generate a new Data Object:
- <kbd>Right Click</kbd> > <kbd>New</kbd> > <kbd>Php Data Object</kbd>
- Fill in the form supplying name and property definitions.
- Optionally make the class immutable (has no setter methods).
- Optionally enable generating a Builder for the class.

To generate a Builder from an existing PHP class:
- <kbd>Right Click in Editor view on PHP class</kbd> > <kbd>Generate</kbd> > <kbd>Builder...</kbd>

Classes are generated from templates that can be customized as needed.  To edit the templates: 
- <kbd>Settings/Preferences</kbd> > <kbd>Editor</kbd> > <kbd>File and Code Templates</kbd> > <kbd>"Other" tab</kbd> > <kbd>PHP Data Object Plugin</kbd> 

<!-- Plugin description end -->

---

## Installation

- Using IDE built-in plugin system:
  
  <kbd>Settings/Preferences</kbd> > <kbd>Plugins</kbd> > <kbd>Marketplace</kbd> > <kbd>Search for "Php Data Object Generator"</kbd> >
  <kbd>Install Plugin</kbd>
  
- Manually:

  Download the [latest release](https://github.com/sourcelaborg/PhpDataObjectGeneratorPlugin/releases/latest) and install it manually using
  <kbd>Settings/Preferences</kbd> > <kbd>Plugins</kbd> > <kbd>⚙️</kbd> > <kbd>Install plugin from disk...</kbd>

---
