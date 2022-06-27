# kpt-recursion-bug

## Description

This package shows an [kpt fn render bug](https://github.com/GoogleContainerTools/kpt/issues/3330) with recursive rendering.

To reproduce this bug using the following commands:

```bash
kpt fn render googleapis --truncate-output=false
kpt fn render gcr-io --truncate-output=false
git add .; git commit -m "Commit diff"
kpt fn render . --truncate-output=false
git diff
```

## Usage

### Fetch the package

`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] kpt-recursion-bug`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content

`kpt pkg tree kpt-recursion-bug`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package

```bash
kpt fn render googleapis --truncate-output=false
```
