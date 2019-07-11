# angular-awscodebild
An example buildspec that will build an angular-cli project and deploy to s3

# How to use
This needs 2 Environment Variables that are to be passed in from the codebuild environment
*S3_BUCKET - the name of the bucket to deploy
*BUILD_ENV - the build configuration to use for the angular cli build
