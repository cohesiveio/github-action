## Cohesive `github-action`

Cohesive GitHub deploy action.

___

## Usage

###

```yaml
name: deploy

on:
  push:
    branches: main

jobs:
  deploy:
    name: Deploy
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - name: Deploy
        uses: cohesiveio/action@main

```
