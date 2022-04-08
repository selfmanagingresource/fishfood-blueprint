# mysecondbp

## Description


## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] mysecondbp`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree mysecondbp`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init mysecondbp
kpt live apply mysecondbp --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
