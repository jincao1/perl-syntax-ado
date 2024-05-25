# Perl Syntax Highlighting for Azure DevOps

This is a bare bone extension providing syntax highlighting to Perl modules (`.pm`) and Perl test (`.t`) files.
It was created because Azure DevOps currently only has `.pl` extensions registered to have syntax highlighting in the Monaco editor.

At the time of writing, Microsoft and Azure DevOps for some reason is not associating other common Perl files with their corresponding extensions resulting in them rendered as plain text.
This aims to address that.

# Building Extension

To build the extension run `npx tfx-cli extension create`. It wil produce a `.vsix` that can be added to the market place.

# Syntax Highlighting

This a direct port from the Microsoft Monaco Editor source language definition for Perl which could be found here: https://github.com/microsoft/monaco-editor/blob/main/src/basic-languages/perl/perl.ts

All credit goes to Microsoft for providing the syntax rules.

# Author

@jincao1 - Jin Cao