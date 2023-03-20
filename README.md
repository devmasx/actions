# actions-reusing-workflows
Store reusable workflow.


More info:
https://docs.github.com/en/actions/using-workflows/reusing-workflows


```yml

jobs:
  build-and-test:
    uses: devmasx/actions-reusing-workflows/nodejs/build-and-test.yml
    with:
      node-version: 16
```
