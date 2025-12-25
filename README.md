# WorldBoxNMLPack
A simple NML mod packer.

```terminaloutput
Usage: nmlpack.exe [OPTIONS]

Options:
      --assets <ASSETS>    Asset directories to be included in the package [default: assets]
      --build <BUILD>      The command used to build the project [default: "dotnet build"]
      --compile            Whether to run the build command before packing
      --include <INCLUDE>  Additional files or directories to include [default: Locals LICENSE default_config.json icon.png mod.json]
  -o, --output <OUTPUT>    The final output path of the packed zip file
      --sources <SOURCES>  Source code directories [default: Code code src]
  -h, --help               Print help
  -V, --version            Print version
```
