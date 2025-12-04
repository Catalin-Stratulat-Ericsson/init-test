# test-draft-package

## Description
Test package for deletion

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] test-draft-package`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree test-draft-package`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init test-draft-package
kpt live apply test-draft-package --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
