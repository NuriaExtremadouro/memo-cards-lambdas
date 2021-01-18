# Introduction

This `memo-cards-lambdas` has been created using the Serverless CLI to practice both with Serverless and AWS (lambdas, DBs, S3 buckets, etc.).

# Deploy

You need to have [Serverless installed](https://www.serverless.com/framework/docs/getting-started/) and a AWS account to deploy. Once it's installed, you need to [configure a valid AWS](https://www.serverless.com/framework/docs/providers/aws/guide/credentials/) user that can connect programatically in the Serverless CLI. After that, run:

`serverless deploy`

# Usage

Once it's deployed, you can call the functions declared in `serverless.yml` with:

`serverless invoke -f hello`
