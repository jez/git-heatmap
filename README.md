# git-heatmap

> Display a heatmap for oft-edited files

![screenshot of git heatmap](screenshot.png)

## Install

### Dependencies

You must have the `bars` command on your system first:

```
npm install -g https://github.com/jez/bars.git
```

### Installation

Download `git-heatmap` and put it on your path.

```bash
# Homebrew:
brew install jez/formulae/git-heatmap
```

## Usage

```
❯ git heatmap -h
Heatmap of oft-edited files.

Usage:
  git heatmap [options] [<path>...]

Options:
  -n <top>                      Limit to top <n> files. [default: 30]
  --width <n>                   Limit histogram to <n> chars.
  -b <branch>, --base <branch>  Compare relative to <branch>. If on <branch>,
                                show heatmap for entire repo. [default: master]
  -h                            Show this message.
```

## License

[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)](https://jez.io/MIT-LICENSE.txt)
