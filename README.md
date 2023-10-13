# XCode
I just use the Apple store to install XCode.  Open XCode to agree to the license.

# Visual Studio Code
Hopefully this URL still works the future
`https://code.visualstudio.com/docs?dv=osx`

# Node main page currently supports 18.18.1
`https://nodejs.org/en`

Check node is installed via terminal

`node --version`


# Java
OpenJDK all the way.
`https://aws.amazon.com/corretto/?filtered-posts.sort-by=item.additionalFields.createdDate&filtered-posts.sort-order=desc`

Opting for Java 21

Mac M1 is considered as macOS aarch64

```zsh
vi ~/.zshenvor
# edit in
# pathing my vary, run /usr/libexec/java_home to find correct pathing
export JAVA_HOME=/Library/Java/JavaVirtualMachines/amazon-corretto-21.jdk/Contents/Home
export PATH=%JAVA_HOME/bin:$PATH
```

# Brew
`https://brew.sh/`

Run the following in terminal
```zsh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
(echo; echo 'eval "$(/opt/homebrew/bin/brew shellenv)"') >> /Users/John/.zprofile
60  eval "$(/opt/homebrew/bin/brew shellenv)"\n
```

Some useful apps from brew
```zsh
brew install links youtube-dl speedtest-cli tree tmux midnight-commander htop wifi-password gnu-typist

```

# Gradle
`https://docs.gradle.org/current/userguide/installation.html#ex-installing-with-a-package-manager`

```zsh
brew install gradle
```

# Wget
```zsh
brew install wget
```