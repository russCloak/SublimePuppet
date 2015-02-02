SublimePuppet
==================================

[Puppet](puppetlabs.com) highlighting, snippets and completion for Sublime Text 2 & 3.  Now with windows parsing support.

### Plugin installation

#### Package Manager

First, install the Package Control plugin, instructions here: http://wbond.net/sublime_packages/package_control.

Once you install Package Control, restart ST2 and bring up the Command Palette (`Command+Shift+P` on OS X, `Control+Shift+P` on Linux/Windows). Select "Package Control: Install Package", wait while Package Control fetches the latest package list, then select SublimeLinter when the list appears. The advantage of using this method is that Package Control will automatically keep SublimePuppet up to date with the latest version.

#### Manual

Sublime Puppet can be manually installed to your Sublime Text "Packages" directory. You can find and open the "Packages" directory from the Sublime Text menu at:

_Preferences_ | _Browse Packages..._

Then download the code into place from the Git version control repository or by directly downloading a snapshot of the latest code: 

**With Git:** 

1. Change your working directory to the Sublime Text "Packages" directory
1. Clone the repository into your Sublime Text "Packages" directory:

        git clone https://github.com/russCloak/SublimePuppet.git

**Without Git:** 

1. Download the [latest SublimePuppet source code](https://github.com/russCloak/SublimePuppet/archive/master.zip) archive.
1. Unpack the downloaded archive to a local folder somewhere.
1. Rename the unpacked folder `SublimePuppet-master` to the new name `SublimePuppet`.
1. Move the `SublimePuppet` folder into your Sublime Text "Packages" directory.


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
