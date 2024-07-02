# Pants Cross Platform Go Build Issue

This repo is a minimal example highlighting https://github.com/pantsbuild/pants/issues/21113

To reproduce the issue, clone the repository on a ARM64 darwin machine and run 

```
GOOS=linux pants package ::
```

or 

```
GOARCH=amd64 pants package ::
```
