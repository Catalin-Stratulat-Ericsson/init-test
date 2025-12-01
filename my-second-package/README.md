# my-second-package

## Description
My second Porch package

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] my-second-package`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree my-second-package`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init my-second-package
kpt live apply my-second-package --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
