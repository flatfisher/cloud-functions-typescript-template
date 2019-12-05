## cloud-functions-typescript-template
cloud-functions-typescript-template is a base project of Google Cloud Functions using TypeScript. This project contains tools and configuration files that are likely to be used frequently (eg Test tool and Lint) from the beginning. Please feel free to submit Pull Request or Issue if there are recommended tools and configuration files.

### Prerequisites
npm, tsc, gcloud commands installed

## (alpha) Installation

```
$ npm install google-cloud-functions-typescript

$ npx create-project your-directory
```

## Edit config in package.json

```
"config": {
  "function_name": "Your function name, it must match the name of export function in index.ts.",
  "region": "europe-west1 or us-east1 or us-central1 or asia-northeast1",
  "gcp_project": "Your GCP project name"
  "runtime": "nodejs8"
}
```

## Lint

```
$ npm run lint
```

## Build
It makes a Node.js project into `functions/src/`

```
$ npm run build
```

## Test

```
$ npm run test
```

## Deploy

```
$ npm run deploy --prefix functions/src/
```

## Contribution
Feel free to create a pull request:) Recommended settings, bug fixes, descriptions and more!
