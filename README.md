# downloader

A Trivy plugin for databases downloading.

## Install
```shell
trivy plugin install github.com/afdesk/downloader
```

## Usage
```shell
trivy downloader -h

Usage: trivy downloader [-h,--help] path
    A Trivy plugin that download databases.

Options:
    -h, --help    Show usage.

Examples:
    # Donwload databases to a specific directory
    trivy downloader ~/home/trivy-db

    # Download databases into the default trivy cache dir
    trivy downloader
```

## Uninstall
```shell
trivy plugin uninstall downloader
```
