---
layout: fluid/docs_base
category: cli
id: cli-serve
command_name: serve
title: Ionic CLI Documentation - serve
header_sub_title: Ionic CLI
---

# `$ ionic serve`

Start a local dev server for app dev/testing
## Synopsis

```bash
$ ionic serve 
```
  
## Details

Easily spin up a development server which launches in your browser. It watches for changes in your source files and automatically reloads with the updated build.

Try the `--lab` option to see multiple platforms at once.

By default, `ionic serve` will only bind to your local address. You can share your app with an external IP by using the `--address=0.0.0.0` option.





Option | Description
------ | ----------
`--consolelogs`, `-c` | Print app console logs to Ionic CLI
`--serverlogs`, `-s` | Print dev server logs to Ionic CLI
`--port`, `-p` | Dev server HTTP port
`--livereload-port`, `-r` | Live Reload port
`--nobrowser`, `-b` | Disable launching a browser
`--nolivereload`, `-d` | Do not start live reload
`--noproxy`, `-x` | Do not add proxies
`--address` | Network address for server
`--browser`, `-w` | Specifies the browser to use (`safari`, `firefox`, `chrome`)
`--browseroption`, `-o` | Specifies a path to open to (/#/tab/dash)
`--lab`, `-l` | Test your apps on multiple platform types in the browser
`--platform`, `-t` | Start serve with a specific platform (ios/android)

## Examples

```bash
$ ionic serve -lcs
$ ionic serve --lab -lcs
```
