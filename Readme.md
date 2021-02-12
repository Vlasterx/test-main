# Submodules
https://git-scm.com/book/en/v2/Git-Tools-Submodules

Adding submodules with

```bash
git submodule add git@github.com:Vlasterx/test-submodule-1.git submodule-1
git submodule add git@github.com:Vlasterx/test-submodule-2.git submodule-2
```

Cloning with all submodules initialised

```bash
git clone git@github.com:Vlasterx/test-main.git --recurse-submodules
```

To also initialize, fetch and checkout any nested submodules, you can use the foolproof

```bash
git submodule update --init --recursive
```