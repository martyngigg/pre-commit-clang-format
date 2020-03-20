# ClangFormat hook for pre-commit

[ClangFormat](http://clang.llvm.org/docs/ClangFormat.html) package for [pre-commit](http://pre-commit.com).

## Using clang-format with pre-commit

```yaml
-   repo: git://github.com/martyngigg/pre-commit-clang-format
    rev: master
    hooks:
    -   id: clang-format
```

The hook requires Python to be on the PATH.