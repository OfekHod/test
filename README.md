# ScalaTemplate
## Description
Project template for scala integrated with: gralde, scalatest, scalacheck, log4j and settings taken from application.conf.
Very simple calculator is used for putting all the components together.
## Usage
Open cmd at repository's folder and run the following commands:
### Build
`gradlew build`
(It actually builds and runs scalatest)
### Run
`gradlew test`
### Intellij Idea
`gradlew idea`
## Extras
### Change Project Name (via Intellij Idea)
In order to safely change project's name:
1. Change settings.gradle rootProject.name to new name
2. Exit Intellij Idea
3. `gradlew clean cleanIdea`
4. Exit every opened context of project's folder (including current cmd)
5. Change main folder name to new name
6. `gradle idea`
7. `gradle build`
