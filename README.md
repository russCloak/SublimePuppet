SublimePuppetSnippetsAndHighlights
==================================

[Puppet](puppetlabs.com) highlighting, snippets and completion for Sublime Text 2 & 3.  Now with windows parsing support.

### Plugin installation
Please use [Package Control][pc] to install this plugin. This will ensure that the plugin will be updated when new versions are available. If you want to install from source so you can modify the source code, you probably know what you are doing so we won’t cover that here.

To install via Package Control, do the following:

1. Within Sublime Text, bring up the [Command Palette][cmd] and type `install`. Among the commands you should see `Package Control: Install Package`. If that command is not highlighted, use the keyboard or mouse to select it. There will be a pause of a few seconds while Package Control fetches the list of available plugins.

1. When the plugin list appears, type `puppet`. Among the entries you should see `SublimePuppet`. If that entry is not highlighted, use the keyboard or mouse to select it.

### Puppet installation
Before using this plugin, you must ensure that `puppet` is installed on your system. To install `puppet`, do the following:

1. Install [Ruby](http://ruby-lang.org).

1. Install `puppet` by typing the following in a terminal:
   ```
   [sudo] gem  install puppet
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
