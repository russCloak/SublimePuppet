SublimePuppet
=============

[Puppet][] highlighting, snippets and completion for Sublime Text 2 & 3.  

Now with Windows parsing support.

### Plugin installation

#### Package Manager

First, install the Package Control plugin, instructions here: https://packagecontrol.io/installation

Once you install Package Control, restart ST2 and bring up the Command Palette (`Command+Shift+P` on OS X, `Control+Shift+P` on Linux/Windows). 

Select "Package Control: Install Package", wait while Package Control fetches the latest package list, then select SublimePuppet when the list appears. The advantage of using this method is that Package Control will automatically keep SublimePuppet up to date with the latest version.

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

This SublimePuppet package requires Puppet be intalled on your system in order to run syntax check commands. Follow the steps outlined in the [Puppet Labs guide to Installing Puppet](https://docs.puppet.com/puppet/latest/install_pre.html). 

## Contributing

If you would like to contribute enhancements or fixes, please do the following:

1. Fork the [SublimePuppet package Github repository](https://github.com/russCloak/SublimePuppet).
1. Hack on a separate topic branch created from the latest `master` branch.
1. Commit and push your topic branch to your forked remote repository.
1. Make a pull request on Github with a 
    1. short descriptive title.
    1. description outlining the purpose of your changes.
1. Be patient.  ;-)

Please note that modifications should follow these coding guidelines:

- Indent is 4 spaces. 
- Indent using spaces only.
- Code should pass flake8 and pep257 linters.
- Vertical whitespace helps readability, don’t be afraid to use it.
- Please use descriptive variable names, no abbreviations unless they are very well known.

[Puppet]: https://puppet.com/
