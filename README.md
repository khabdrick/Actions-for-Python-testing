# Actions for Python testing
This is a reusable workflow that is used to test(unit, lint) Python application.

## How to use Workflow
- Create a directory named _.github/workflows_, then create a YAML file with your preferred name in the directory you just created.
- Paste the following in the file you just created.
```yaml
jobs:
  build:
  uses:
    khabdrick/Actions-for-Python-testing/.github/workflows/name_of_file.yml@1
```
