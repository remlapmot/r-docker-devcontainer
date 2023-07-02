# Test running r-docker in a devcontainer

To use

* Open this repo in VS Code
* When prompted with the following pop-up click "Reopen in Container"
  <img src="img/pop-up_reopen-in-container.png" width="85%">
* When VS Code reopens using the container, cancel or click "Don't Show Again" on the following pop-up about Git not being found
  <img src="img/pop-up_git-not-found.png" width="85%">
* To run R commands in r-docker write R scripts and then in the R session in the Terminal run them with commands such as
  ```r
  source("test.R")
  ```

To use the devcontainer in your own repo copy the *.devcontainer/devcontainer.json* file to the root of your repo (with the same directory structure).
