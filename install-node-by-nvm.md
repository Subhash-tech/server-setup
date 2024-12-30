### Objective: Install NodeJS via NVM

[Github link for nvm](https://github.com/nvm-sh/nvm)
Visit the above link and check the latest version of nvm and update the version part in the download link

```bash
    curl --version
    # if curl is not present, install using following commands

    # apt install curl
    # Recheck the curl version to check the successful installation

    curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.1/install.sh | bash

    source ~/.bashrc

    nvm --version 

    nvm list

    # Replace the <version> with actual version number like 18, 20
    nvm install <version>

    node --version
```
