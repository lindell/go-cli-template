<h1 align="center">
  go-cli-template
</h1>

go-cli-template description.

Clone it, and replace `lindell/go-cli-template` with `USERNAME/new-cli-name`,
replace `go-cli-template` with `new-cli-name`,
and update all TODOs.

You also need to:
* Set Write access in "Workflow permissions" for Actions.
* Enable Code scanning

## Install

### Homebrew
If you are using Mac or Linux, [Homebrew](https://brew.sh/) is an easy way of installing go-cli-template.
```bash
brew install lindell/go-cli-template/go-cli-template
```

### Manual binary install
Find the binary for your operating system from the [release page](https://github.com/lindell/go-cli-template/releases) and download it.

### From source
You can also install from source with `go install`, this is not recommended for most cases.
```bash
go install github.com/lindell/go-cli-template@latest
```

## Config file

All configuration can be done through command line flags, configuration files or a mix of both. If you want to use a configuration file, simply use the `--config=./path/to/config.yaml`. The file `~/.go-cli-template/config` be used for configuration. The priority of configs are first flags, then defined config file and lastly the static config file.




## Usage

* [version](#-usage-of-version) Get the version of go-cli-template.


### Usage of `version`
Get the version of go-cli-template.
```
Usage:
  go-cli-template version
```


