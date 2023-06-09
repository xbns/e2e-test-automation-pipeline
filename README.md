### About this project

Project forked from [e2e-automation-pipeline](https://github.com/BushnevYuri/e2e-automation-pipeline)

The article [QA Automation Pipeline](https://www.blazemeter.com/blog/qa-automation-pipeline-learn-how-to-build-your-own)

Have only converted it to a spring boot gradle project.

### How to run the tests
- $ ./gradlew clean test -Ptags='type:Smoke'
- $ ./gradlew clean test -Ptags='type:API'
- $ ./gradlew clean test -Ptags='type:UI'

