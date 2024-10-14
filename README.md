# ByteDev.Resharper.Templates

Collection of Resharper Templates (Live Templates and File Templates) to help when writing (mainly C#) code.

## Installation

To import a `.DotSettings` templates file into Resharper:

- Open Visual Studio
- Select drop down menu: **Extensions** -> **Resharper** -> **Tools** -> **Templates Explorer**
- In the Templates Explorer select the **Live Templates** or **File Templates** tab depending on what kind of template you want to import
- Select the C# scope (on the left) 
- Click on the "Import" toolbox button and select the `.DotSettings` file

## Live Templates

C# Live Templates for unit testing include:

- NUnit (shortcuts start with `nunit`)
- MSTest (shortcuts start with `mstest`)
- xUnit (shortcuts start with `xunit`)

Other C# Live Templates include:

- Specflow (shortcuts start with `specflow`)
- Builder (shortcuts start with `builder`)
- Simple Factory (shortcuts start with `factory`)
- log4net (shortcuts start with `log4net`)
- Override (shortcuts start with `override`)
- ToString

Other templates include:

- Markdown (accessible only in `*.md` files)
- Cake (accessible only in `*.cake` files)
- .NET XML documentation (shortcuts start with `xmldoc`)

### Usage

To insert a live template simply start typing its shortcut in your C# file (or press `Ctrl+J` or `Ctrl+E, L` to bring up the inline menu).


## File Templates

C# file templates include:

- Assembly info file
- Builder class
- Exception class
- NUnit class
- Simple Factory class
- xUnit class

Other file templates include:

- JSON file
- Markdown file
- Nuspec file
- Text file
- XML file

### Usage

To choose from the list of file templates press `Ctrl+Alt+Insert`.

To place a new file from a file template in a particular place in Solution Explorer:

- Select in Solution Explorer where you want the file to be placed
- Press `Alt+Insert`
- Select the file template from the inline menu

