# GhTrend

<p align="center">
<img src="https://github.com/cybershang/ghtrend/blob/a6460104b013274c96bd3f58de705ff2cb002bda/docs/media/GhTrend.gif" width="360"/>
</p>

<p align="center">
<a href="https://pypi.org/project/ghtrend/"><img alt="PyPI - Version" src="https://img.shields.io/pypi/v/ghtrend"></a>
<a href="https://pypistats.org/packages/ghtrend"><img alt="PyPI - Downloads" src="https://img.shields.io/pypi/dw/ghtrend"></a>
<a href="https://opensource.org/licenses/MIT"><img src="https://img.shields.io/badge/License-MIT-yellow.svg"></a>
</p>


Request and parse Github trending page.

**Usage**:

```console
$ get-trend [OPTIONS] [DATE_RANGE] [OUT_FILE]
```

**Arguments**:

* `[DATE_RANGE]`: Choose from: daily, weekly, monthly
* `[OUT_FILE]`: Enter the filepath csv to be stored at

**Options**:

* `--quiet / --no-quiet`: [default: no-quiet]
* `--version / --no-version`
* `--install-completion`: Install completion for the current shell.
* `--show-completion`: Show completion for the current shell, to copy it or customize the installation.
* `--help`: Show this message and exit.

**Dependency:**

- requests
- BeautifulSoup4
- typer

