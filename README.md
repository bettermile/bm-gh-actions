# bm-gh-actions
Github Actions Shared Workflows

You can use these shared github workflows but calling them from your project's workflow action like so: 

...

jobs:
  test:
    uses: gls-ecl/bm-gh-actions/.github/workflows/test.yaml@main
