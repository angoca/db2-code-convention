# 1. File Names

## 1.1. File suffixes

The files that contain SQL only or SQL PL should have the `.sql` extension.
This extension is used for different RDBMs and it is an standard.

Other extension should not be used.

*Correct:*

    installation.sql 

*Incorrect:*

    installation.db2 << Invalid extension
    installation.sqlpl << Invalid extension
    installation << No extension

## 1.2. File name

These are the rules for the names of the files:

 * The name of the file should describe the content of the file.
 * It cannot contains blankspaces. All characters should be together.
 * The valid characters inside a file name are: `a-zA-z0-9.-_`.
 * Words can be separated by using: CamelCase, underscore `_` or dash `-.

Examples:

*Correct:*

    Installation.sql
    Patch-4123.sql
    01-FirstStep.sql

*Incorrect*

    First step.sql << Blankspace as word separator.
    Instalación.sql << Special character.
    1.sql << Does not describe the content
