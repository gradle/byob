# byob

Script Downloads:

Gradle
curl -s -L -O https://github.com/gradle/gradle-enterprise-build-validation-scripts/releases/download/v2.3.2/gradle-enterprise-gradle-build-validation-2.3.2.zip && unzip -q -o gradle-enterprise-gradle-build-validation-2.3.2.zip

Maven
curl -s -L -O https://github.com/gradle/gradle-enterprise-build-validation-scripts/releases/download/v2.3.2/gradle-enterprise-maven-build-validation-2.3.2.zip && unzip -q -o gradle-enterprise-maven-build-validation-2.3.2.zip


How to invoke scripts:

Gradle
./03-validate-local-build-caching-different-locations.sh -r https://github.com/mockito/mockito -t build -e -s https://byob-devnexus-1.gradle-enterprise.cloud

Maven
./02-validate-local-build-caching-different-locations.sh -r https://github.com/FasterXML/jackson-core -g install -e -s https://byob-devnexus-1.gradle-enterprise.cloud 

