# Free Port finder Jenkins Global Library

This project is meant to be used in Jenkins pipeline as a global groovy library to find a free port on the machine the build is running. It encapsulates a groovy one-liner to achieve this goal,
but calling PortFinder.getFreePort() is a lot more readable in my opinion than copy-pasting the one-liner function.

The source for the one-liner: https://stackoverflow.com/questions/46883466/find-unused-port-in-jenkins-pipeline-library

## Authors

AvaLanCS