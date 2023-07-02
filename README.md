# Test running r-docker in a devcontainer

To use

* Open this repo in VS Code
* When prompted click "Reopen in Container"
* When VS Code reopens using the container, ignore the pop-up about Git not being found
* To run R commands in r-docker write R scripts and then in the R session in the Terminal run them with commands such as
  ```r
  source("test.R")
  ```

To use the devcontainer in your own repo copy the *.devcontainer/devcontainer.json* file to the root of your repo (with the same directory structure).
