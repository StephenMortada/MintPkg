# The Mint Package System

This is the page for the Mint Package System.
For the package list, go to https://www.github.com/StephenMortada/MintPkg.

___

## Building

See the steps in [the Mint home page](https://stephenmortada.github.io/Mint/).

___

## Usage

**General Syntax:** `mintpkg [option] [name]`

### Options

- `install [name]`: Install package of name `[name]`.
- `remove [name]`: Uninstall package of name `[name]`.
- `upload [name]`: Submit an extension. Go to the section titled under _'Contributing'_ for details on the structure of the extension.

___

## Contributing

You can submit an extension to help with things.
There are two types of extensions:

- **Display extensions:** Change the way the editor looks, etc...
- **Command extensions:** Extra commands for use in the input handler.

The file should be provided in `.zip` format _only_.

The directory structure should be something like this:

```txt
pkg_name/
├── info.txt
├── meta.txt
└── main.lua
```

- `info.txt` should contain information about the package, and its creator.
- The first line of `meta.txt` is the package version. the second line is the extension type, `disp` for display extensions and `cmd` for command extensions.
- `main.lua` should look something like this:

  ```lua
  function main()
      -- Still not completed, please wait.
  end
  
  return main
  ```

___

[Go back to home page](https://stephenmortada.github.io/Mint/)
