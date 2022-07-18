# Sentry plugin issue
This sample app showcases the problem which arises when you add version `3.1.x` of the Sentry Gradle plugin to an app which uses Google's OSS-Licenses plugin:

The gradle task `releaseOssLicensesTask` fails with a `StackOverflowError`

Start the gradle build with the build variant set to `release` to see for yourself.