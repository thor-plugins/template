# THOR Plugin Template

## Description

This repository contains a template for creating THOR plugins.

The template includes a basic structure for a plugin, as well as GitHub actions for validation.

For more information about THOR plugins and how to write and use them, see [the plugin documentation](https://github.com/NextronSystems/thor-plugin/).

## Usage

To create a new plugin based on this template, first select `thor-plugins/template` as the template repository when creating a new repository on GitHub.

Then, make sure to adjust the following files:

- `go.mod`: Update the module name to match your plugin's name.
- `README.md`: Update the description and usage instructions for your plugin.
- `metadata.yml`: Update the metadata for your plugin, including the name, version, and description.
- `plugin.go`: Update the plugin code to implement the desired functionality.
