Clone this repo and then add hook path to your global git config.

```bash
cd githooks
make
```

Which actually runs this:
```bash
git config --global core.hooksPath $PWD
```

Edit ```~/.gitconfig``` to remove it. Inspired by [githook-clang-format](https://github.com/andrewseidl/githook-clang-format).

Skip pre-commit stage with no verify flag.
```bash
git commit --no-verify
```
