# gcr-io

## Description

sample description

## Usage

### Fetch the package

`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] googleapis`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content

`kpt pkg tree googleapis`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package

```
kpt live init googleapis
kpt live apply googleapis --reconcile-timeout=2m --output=table
```

Details: https://kpt.dev/reference/cli/live/
