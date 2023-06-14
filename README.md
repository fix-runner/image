# image

This action works around bugs in github runner images

## Installation

```yml
    steps:
    - uses: fix-runner/image@main
```

## Bugs

* [macOS runners ship broken go & python brew installations](https://github.com/actions/runner-images/pull/7710)
