# Create JIMPLE From APK

## Setup
- Requires Java 8
- Setup ANDROID_HOME env var by running `export ANDROID_HOME=~/Library/Android/sdk/platforms` for mac.
- To build the project and create the jar file, run `./gradlew clean jar`
- Gradle version, preferably less than 4.8

## Example command to create JIMPLE
```shell
java -jar build/libs/android-instrumentor-1.0-SNAPSHOT.jar -apk "/path/to/apk/app.apk" -output "/output/folder/in/your/computer/output" -b 
```