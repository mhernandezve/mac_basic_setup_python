# Basic Mac Setup for Python


### This is an **bash** script to setup a basic Python development environment


#### First, check if there are installed the xcode command line tools running the following command:

```xcode-select -p```

If the xcode command line tools are installed you should get something like that: 

```/Applications/Xcode.app/Contents/Developer```

If you get anything else, then run the following command:

```xcode-select --install```


#### Second, install Homebrew with the following command:

```/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"```


#### Third, run the Brewfile 

```curl -fsSL 'https://raw.githubusercontent.com/mhernandezve/mac_basic_setup_python/master/Brewfile' | brew bundle --file=-```

