# aws-codepipeline-examples

What is [AWS CodePipeline](https://aws.amazon.com/codepipeline/)?

This repo is a submodule of: [aws-cdk-examples](https://github.com/d-w-arnold/aws-cdk-examples)

Each CodePipeline pipeline uses [CodeConnections](https://docs.aws.amazon.com/codeconnections/latest/APIReference/Welcome.html) (formerly CodeStar Connections), to connect to [Bitbucket](https://www.atlassian.com/software/bitbucket/) in order to source changes for a given: `repo:branch`

Each CodePipeline pipeline uses a build project (defined in [CodeBuild](https://aws.amazon.com/codebuild/)) for the build steps of the pipeline.
