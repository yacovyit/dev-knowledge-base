## Tools
### [Homebrew](https://brew.sh/)
The Missing Package Manager for macOS (or Linux)

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
post installation
```bash 
echo >> /Users/{your-user!!!}/.zprofile
echo 'eval "$(/usr/local/bin/brew shellenv)"' >> /Users/{your-user!!!}/.zprofile
eval "$(/usr/local/bin/brew shellenv)"
```