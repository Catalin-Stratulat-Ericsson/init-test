# test-reject-delete

## Description
Test package for rejection

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] test-reject-delete`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree test-reject-delete`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init test-reject-delete
kpt live apply test-reject-delete --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
