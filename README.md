# CSharpFixFormat for Visual Studio Code
This extension helps to format C# code. When OmniSharp will support all features - will be deprecated.

## Features

  * Sort usings in alphabetical order at opened C# file.
Can be processed through commands menu or context menu in text editor with option "CSharp: Sort usings".
  * Fix indent size for all lines (omnisharp still cant do it for wrapped lines).
  * Cleanup empty lines with allowed limit in row.

## Extension Settings

* `csharpfixformat.sortUsingsSystemFirst`: Put System.xxx namespaces first at usings list.
* `csharpfixformat.indentEnabled`: Indent all lines with respect of parentheses / braces.
* `csharpfixformat.emptyLinesInRowLimit`: Amount of empty lines in row.