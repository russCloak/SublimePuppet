SublimePuppetSnippetsAndHighlights
==================================

[Puppet](puppetlabs.com) highlighting, snippets and completion for Sublime Text 2 & 3.  Now with windows parsing support.

### Plugin installation

#### Manual

Use `git` to clone into your Sublime Text Packages directory:

**Without Git:** Download the latest source from [here](https://github.com/petems/SublimePuppetSnippetsAndHighlights/archive/master.zip) and copy the `SublimePuppetSnippetsAndHighlights` folder to your Sublime Text "Packages" directory.

**With Git:** Clone the repository in your Sublime Text "Packages" directory:

    git clone https://github.com/SublimeLinter/SublimeLinter.git


The "Packages" directory is located at:

* OS X:

        ~/Library/Application Support/Sublime Text 2/Packages/

* Linux:

        ~/.config/sublime-text-2/Packages/

* Windows:

        %APPDATA%/Sublime Text 2/Packages/

#### Package Manager

When [this](https://github.com/wbond/package_control_channel/pull/3523) gets merged, you'll be able to install the package with Package Control plugin, instructions here: http://wbond.net/sublime_packages/package_control.

Once you install Package Control, restart ST2 and bring up the Command Palette (`Command+Shift+P` on OS X, `Control+Shift+P` on Linux/Windows). Select "Package Control: Install Package", wait while Package Control fetches the latest package list, then select SublimeLinter when the list appears. The advantage of using this method is that Package Control will automatically keep PuppetSnippetsAndHighlights up to date with the latest version.

### Puppet installation
Before using this plugin, you must ensure that `puppet` is installed on your system. To install `puppet`, do the following:

1. Install [Ruby](http://ruby-lang.org).

1. Install `puppet` by typing the following in a terminal:
   ```
   gem install puppet
   ```

1. If you are using `rvm` or `rbenv`, ensure that they are loaded in your shell’s correct startup file. See [here](http://sublimelinter.readthedocs.org/en/latest/troubleshooting.html#shell-startup-files) for more information.

## Contributing
If you would like to contribute enhancements or fixes, please do the following:

1. Fork the plugin repository.
1. Hack on a separate topic branch created from the latest `master`.
1. Commit and push the topic branch.
1. Make a pull request.
1. Be patient.  ;-)

Please note that modifications should follow these coding guidelines:

- Indent is 4 spaces.
- Code should pass flake8 and pep257 linters.
- Vertical whitespace helps readability, don’t be afraid to use it.
- Please use descriptive variable names, no abbreviations unless they are very well known.

[pc]: https://sublime.wbond.net/installation
[locating-executables]: http://sublimelinter.readthedocs.org/en/latest/usage.html#how-linter-executables-are-located
[cmd]: http://docs.sublimetext.info/en/sublime-text-3/extensibility/command_palette.html
