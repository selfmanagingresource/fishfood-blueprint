# myfirstbp

## Description


## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] myfirstbp`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree myfirstbp`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init myfirstbp
kpt live apply myfirstbp --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
