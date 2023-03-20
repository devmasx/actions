# Github Action reusing workflows

Store reusable workflow.

More info:
https://docs.github.com/en/actions/using-workflows/reusing-workflows

Nodejs build and test

```yml

jobs:
  build-and-test:
    uses: devmasx/actions/.github/workflows/nodejs-build-test.yml@main
    with:
      node-version: 16
```
