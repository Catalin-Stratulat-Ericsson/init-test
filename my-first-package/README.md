# my-first-package

## Description
My first Porch package

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] my-first-package`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree my-first-package`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init my-first-package
kpt live apply my-first-package --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
