# Perl Syntax Highlighting for Azure DevOps

This is a bare bone extension providing syntax highlighting to Perl file extensions that does not have language associations in Azure DevOps.

At the time of writing, Microsoft and Azure DevOps for some reason is only associating `.pl` files with Perl. All other common Perl extensions were not included. This aims to address that.

# Overview

See [Overview](overview.md) for full details on what extensions this is enabled on.

# Building Extension

To build the extension run `npx tfx-cli extension create`. It wil produce a `.vsix` that can be added to the market place.

# Syntax Highlighting

This a direct port from the Microsoft Monaco Editor source language definition for Perl which could be found here: https://github.com/microsoft/monaco-editor/blob/main/src/basic-languages/perl/perl.ts

All credit goes to Microsoft for providing the syntax rules.

# Author

@jincao1 - Jin Cao