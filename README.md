# C3 Admin #
Administrative tools and instructions for C3 challenge.

## Tool Setup ##
For this challenge, you will need to install the following tools:
* Tortoise GIT: https://tortoisegit.org/download/
* IntelliJ: https://www.jetbrains.com/idea/download/#section=windows
* JDK 8: http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html

## Code MR Dashboard Plugin ##
Once you have IntelliJ installed, you will need to download and install the Code MR plugin.
1. From this repository, clone the codemr-ij-v2018.2.1.zip file.
2. Within IntelliJ, go to File -> Settings.
3. Click on "Plugins" on the left-hand side.
4. Click the "Install Plugin from Disk" button at the bottom right-hand side.
5. Select the zip file you just cloned.
6. Click the "Apply" button in the bottom right-hand side.
7. Click the "Restart IntelliJ" button to apply the changes and install the plugin.

## Running Code Analysis Reports ##
Each team in the challenge should commit their code to a different branch of the hello-world-c3 repository:
https://github.com/merciersj/hello-world-C3

1. Clone that project, and switch to the branch for the team you want to run the report on.
2. In IntelliJ, create a project for the hello-world-c3 code.
3. Once the code is fully imported, click on the parent application folder (hello-world-C3) in the "Project" panel on the left-hand side.
4. Click on the "CodeMR" option at the top of your IntelliJ.
5. Select "Extract Model for Java"
6. In the popup that comes up, name the report after the team (example: "helloworld team 3").
7. Leave all options checked and click extract model.
8. The report will come up in your browser after IntelliJ has completed its calculations.
