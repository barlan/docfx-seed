# docfx-seed
## Description
This is a sample docfx documentation project. It contains .NET source code and markdown files.
`docfx.json` is the configuration file for running `docfx`.
`docfx` will generate a static website as similar to http://docascode.github.io/docfx-seed/index.html

## How to run
### Under Windows
* Download and unzip [docfx.zip](https://github.com/dotnet/docfx/releases/latest) to run `docfx.exe` directly!
* Run `docfx` under current repo! Website will be generated under `_site` folder.
* Run any web hosting tool to host `_site` folder, e.g. `docfx serve _site`.

### Cross platform and use `dnx`
As a prerequisite, you will need to install [DNVM](http://docs.asp.net/en/latest/getting-started/installing-on-windows.html#install-the-net-version-manager-dnvm) and [DNX](http://docs.asp.net/en/latest/getting-started/installing-on-windows.html#install-the-net-execution-environment-dnx).
###Quick Start
* `dnvm upgrade` to get the latest dnvm.
* Add feed https://www.myget.org/F/aspnetrelease/api/v2/ to Nuget.config
  > For Windows, the nuget config file is  **%AppData%\NuGet\NuGet.config**.

  > For Linux/OSX, the nuget config file is **~/.config/NuGet/NuGet.config**.

* `dnu commands install docfx` to install `docfx` as a command
* Run `docfx` under current repo! Website will be generated under `_site` folder.
* Run any web hosting tool to host `_site` folder, e.g. `docfx serve _site`.

## Further information about `docfx`
`docfx` is a tool to generate documentation towards .NET source code and markdown files. Please refer to [docfx](http://dotnet.github.io/docfx/tutorial/docfx_getting_started.html) to get start. The `docfx` website itself is generated by `docfx`!
