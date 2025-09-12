Let's see the tools that we will be installing.

# Tools We need 
1. Brew (for installing tools)
2. Oracle VM VirtualBox,
2. Git Bash
3. Vagrant
4. Chocolatey (Windows system) or Brew (macOS).
5. JDK8
6. Maven
7. IntelliJ (IDE) or Visual Studio or sublime.
8. AWS CLI

## Sign up
1. Github
2. Domain Purchase (GoDaddy). **optional** 
2. Dockerhub
3. Sonarcloud

## AWS
1. Free tier account
2. Iam with MFA
3. Billing alarm
4. Certificate setup **optional**

```bash 
brew install --cask virtualbox 
brew install --cask vagrant
brew install --cask vagrant-manager
brew install git
brew install openjdk@17
sudo ln -sfn $HOMEBREW_PREFIX/opt/openjdk@17/libexec/openjdk.jdk /Library/Java/JavaVirtualMachines/openjdk.jdk
exec zsh -l
brew install maven
brew install --cask visual-studio-code
brew install --cask intellij-idea
brew install --cask intellij-idea-ce
brew install --cask sublime-text
brew install awscli

```

