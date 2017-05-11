# AWSLambdaSample
ASP.NET Core Lambda sample project. Created using AWS Toolkit for VS 2017


### Setup

in `aws-lambda-tools-defaults.json`

* Set `profile` to an aws-profile on your local machine. In case you dont't want to use a default one.
* Set `s3-bucket` to an existing s3 backet.


### Deploy

`dotnet restore`
`dotnet lambda deploy-serverless`
