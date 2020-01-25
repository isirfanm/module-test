# module-test
Simple project with go module

## Useful go module command

- go mod init -> creates a new module and create the go.mod file that describes it
- go list -m all -> prints all the current module’s dependencies
- go get -> adds a new dependency or changes the required version of a dependency
- go mod tidy -> removes unused dependencies

Create new module.

```
go mod init github.com/isirfanm/module-test
```

Add dependency to module.

```
go get github.com/elliotforbes/test-package
```

Change version of adependency.

```
go get github.com/elliotforbes/test-package@v1.0.0
```

Remove unused dependencies.

```
go mod tidy
```
