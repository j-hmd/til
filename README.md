# TIL

> Today I Learned

A collection of concise write-ups on small things I learn day to day across a
variety of languages and technologies.


_2 TILs and counting..._

---

### Categories

* [Cmake](#cmake)
* [Cpp](#cpp)
* [Git](#git)
* [Linux](#linux)
* [Vscode](#vscode)

---

### Cmake


### Cpp


### Git

- [How to find and see a commit diff](git\find-and-see-commit.md)
- [Rename Branch](git\rename-branch.md)

### Linux


### Vscode


## Usage

After creating a new entry, run `./createReadme.py > README.md` to regenerate
the readme with the new data.

If you are using git, you can install this script as a pre-commit git hook so
that it is autogenerated on each commit.  Use the following command:
    cd .git/hooks/ && ln -s ../../createReadme.py pre-commit && cd -


## About

I shamelessly stole this idea from
[jima80525/til](https://github.com/jima80525/til) who claims to have stolen
it from others.

## License

This repository is licensed under the MIT license. See `LICENSE` for
details.