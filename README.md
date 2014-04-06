XcodeThemes
===========

Custom Fonts &amp; Colors palette for Xcode's editor.

Installation
------------

The preferred installation method for this Color Schemes is done using the Package (Plug-ins) Manager [Alcatraz](https://github.com/supermarin/Alcatraz).
Custom Color Schemes for Xcode are stored in the `~/Library/Developer/Xcode/UserData/FontAndColorThemes/` folder.

### Installation using Alcatraz

All themes in this repository will be available on [Alcatraz](https://github.com/supermarin/Alcatraz).
Once you have Alcatraz installed, installing the theme is done in Xcode's menu `Window -> Package Manager` simply by clicking on the Color Scheme you want to add to Xcode. You may need to restart Xcode to see the new themes.

*Right now the only theme in this repository, Anubis, is pending insertion into Alcatraz.*

### Manual Installation

Simply paste this into a new Terminal window :)

    git clone https://github.com/gtranchedone/XcodeThemes.git
    cd XcodeThemes/
    mkdir -p ~/Library/Developer/Xcode/UserData/FontAndColorThemes/
    cp *.dvtcolortheme ~/Library/Developer/Xcode/UserData/FontAndColorThemes/
    cd ..
    rm -rf XcodeThemes/
    
    
Anubis
----

![Interface Sample](https://raw.github.com/gtranchedone/XcodeThemes/master/Anubis%20Class%20Interface%20Sample.png)

![Implementation Sample](https://raw.github.com/gtranchedone/XcodeThemes/master/Anubis%20Class%20Implementation%20Sample.png)
