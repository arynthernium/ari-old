# ari

A tool to create package.json files used by [npm](https://www.npmjs.com/) following the [npm documentation](https://docs.npmjs.com/cli/v8/configuring-npm/package-json).

Usage:
```cmd
./ari.exe [filename]
```
`[optional]`

## inputs

The program will walk you through the steps needed for creating the file and will provide a default for most steps.

Some inputs will be validated and will not let you enter them if they are invalid. These include but are not limited to package names and versions.

For names (e.g. package name or author name) you can simply use a space (" ") to leave that field out of the file. There's not much reason to do this, but if you don't want the field in the file, that's how.

When selecting a license, you may type to search the list of SPDX identifiers, or select UNLICENSED. Up and down arrows will move the selection on the current page, and left and right will go to the previous or next page respectively. Press enter to select the highlighted entry.

## output

The file will output to `package.json` in the current working directory, or you can provide a file name as the first argument.