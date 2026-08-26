# AWS Lambda example

This is an example usage of `onerpc` deployed as a AWS Lambda function using AWS CDK.

## Usage

```sh
npx cdk deploy
curl -fsS https://<cf-output-domain>.cloudfront.net
```

## Bundling

AWS CDK bundles Lambda functions in a directory where a lock file exists, which is the repository root. Thus, `esbuild` is a development dependency of the root package rather than this example.
