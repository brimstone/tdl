## Intro

![](https://img.shields.io/github/go-mod/go-version/iyear/tdl?style=flat-square)
![](https://img.shields.io/github/license/iyear/tdl?style=flat-square)
![](https://img.shields.io/github/workflow/status/iyear/tdl/master%20builder?style=flat-square)
![](https://img.shields.io/github/v/release/iyear/tdl?color=red&style=flat-square)
![](https://img.shields.io/github/last-commit/iyear/tdl?style=flat-square)

🧷 Telegram Downloader, but more than a downloader 🚀

> ⚠ Note: Command compatibility is not guaranteed in the early stages of development

## Features

- Single file start-up
- Cross-platform support
- Low resource usage
- Faster than official clients
- Downloading files from protected chats

## Usage

```shell
# check the version
tdl version

# use proxy
tdl --proxy socks5://127.0.0.1:1080

# login your account
tdl login -n iyear

# download files in url mode, url is the message link
tdl dl -n iyear -u https://t.me/tdl/1 -u https://t.me/tdl/2 -m url

# full examples in url mode
tdl dl -n iyear --proxy socks5://127.0.0.1:1080 -u https://t.me/tdl/1 -u https://t.me/tdl/2 -m url -s 262144 -t 16 -l 3
```

## Data

Your account information will be stored in the `~/.tdl` directory.

## Commands

Go to [command documentation](docs/command/tdl.md) for full command docs.

## LICENSE

AGPL-3.0 License