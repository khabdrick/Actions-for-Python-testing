# Actions for Python testing
This is a reusable workflow that is used to test (unit, lint) Python application.

## How to use Workflow
- Create a directory named _.github/workflows_, then create a YAML file with your preferred name in the directory you just created.
- Paste the following in the file you just created.
```yaml
on: [pull_request, push]
  
jobs:
  run_ubuntu:
    runs-on: ubuntu-latest
    steps: 
      - uses: actions/checkout@v2
  run_test:
      uses: khabdrick/Actions-for-Python-testing/.github/workflows/main.yml@main
```
Feel free to make contributions to improve it.
