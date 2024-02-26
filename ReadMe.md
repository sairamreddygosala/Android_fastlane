## DOCKER IMAGE BUILD INSTRUCTIONS

* Setup Fastlane in your Android Project. Follow the instructions here [fastlane](https://docs.fastlane.tools/getting-started/android/setup/) (this will create a gem file).
* Run docker build command.
* Use Docker run command to run the container.

## APPLICATION BUILD INSTRUCTIONS

* CLone the project. Enter into root directory.
* Run export GRADLE_USER_HOME=$(pwd)/.gradle
* chmod +x ./gradlew
* Run fastlane commands based the lanes you have created.
