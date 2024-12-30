[Github link for nvm](https://github.com/nvm-sh/nvm)
1. Visit the above link and check the latest version of nvm and update the version part in the download link

```bash
    curl --version
    # if curl is not present, install using following commands
    # apt install curl
    # Recheck the curl version to check the successful installation

    curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.1/install.sh | bash

    source ~/.bashrc

    nvm --version 
  ```